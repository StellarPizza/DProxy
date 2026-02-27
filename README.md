# DProxy
(HTTP or SOCKS5) for TCP connections

Automatic Installation For an easier setup, use the included installer dproxy.exe. Run the program and fill in the proxy settings, then click Install to automatically place the necessary files in the correct folder.

In some regions where some apps and games works but voice chat is blocked, you can use Direct mode to bypass voice chat restrictions without a proxy.

To uninstall the program and remove all associated files, run dproxy.exe again and click Uninstall.

Manual Installation If you prefer manual installation, copy the version.dll and dproxy.ini files into the folder containing the targeted app. The proxy is specified in the dproxy.ini file under the proxy parameter.

Example
dproxy.ini Configuration: [dproxy] ; Proxy can use http or socks5 protocols proxy = http://127.0.0.1:1080

;use-nekobox-proxy = 1 ;nekobox-proxy = http://127.0.0.1:2080


Features
Forces apps to use a specified proxy for TCP connections.
Slight interference with UDP traffic for bypassing voice chat restrictions.
In Direct mode, no proxy is used, only UDP manipulation is performed.
Supports HTTP proxies with authentication (login and password).
No drivers or system-level modifications are required.
Works locally at the process level, offering an alternative to global VPN solutions.


EDIT : Deleted
Removed the latest release/update

Packages archived 
