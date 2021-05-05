# status.hitco.at
hitco.at Status-Page

* This repo provides the content for a "Cloudflare Page" which hosts the WebSite https://status-hitco-at.pages.dev 
* This "Cloudflare Page" is configured with Custom Domain:  https://status.hitco.at/ 
* DNS CNAME Record needed: status.hitco.at -> status-hitco-at.pages.dev 
* DNS CAA Record needs to be unconfigured or has to allow Cloudflare (digicert.com / Digicert Baltimore CyberTrust Root) to issue a SSL/TLS certificate.
* Basically it is just an iframe displaying UptimeRobot Status: https://stats.uptimerobot.com/NG0DCJo
* In addition a Status-Text for the Users can be set in the Headline
