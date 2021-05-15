# Azure Front Door vs Traffic Manager

Comparison of Azure Front Door vs Azure Traffic Manager

## Features

Feature | Azure Front Door | Azure Traffic Manager
--- | --- | ----
Application acceleration | Yes | No
Web Application Firewall | Yes | No
TLS Termination | Yes | No
Routing | Reverse proxy | DNS lookup
Protocols | HTTP(s) | Any (TCP, HTTP, UDP, etc.)
URL Rewrite | Yes | No
URL Redirect | Yes | No
URL-path based routing | Yes | No
Custom Domain | Yes | Yes (but not to root domain)
Health Probe | Yes (Get,Head) | Yes (Get)
Cookie-based affinity | Yes | No
Host multiple applications | Yes | No
Requires internet facing service (Public IP) | Yes | Yes

## Front Door Important concepts

### Front Door Probes

-	https://marcelzehner.ch/2021/02/27/azure-front-door-health-probes/
-	https://brettmckenzie.net/2019/05/03/beware-the-non-obvious-costs-of-azure-front-door/
