#  👨‍💻 Advance-Recon-Dorks  #
⚡ **This Dork List Provides Dorks for files,vulnerabilities , cloud services & many more**




open redirect Dork |
------------------ | 
```
site:domain.com inurl:redir | inurl:url | inurl:redirect | inurl:return | inurl:src=http | inurl:r=http
```

Install / Setup Files Dork  |
--------------------------  |

```
site:domain.com inurl:redir | inurl:url | inurl:redirect | inurl:return | inurl:src=http | inurl:r=http
```
Finding BackDoor Dork |
--------------------- |
```
site:domain.com  inurl:shell | inurl:backdoor | inurl:wso | inurl:cmd | shadow | passwd | boot.ini | inurl:backdoor
```

Apache STRUTS RCE  |
-----------------  |
```
site:domain.com ext:action | ext:struts | ext:do
```

3RD Party exposure |
------------------ |
```
site:http://ideone.com | site:http://codebeautify.org | site:http://codeshare.io | site:http://codepen.io | site:http://repl.it | site:http://justpaste.it | site:http://pastebin.com | site:http://jsfiddle.net | site:http://trello.com | site:*.atlassian.net | site:bitbucket.org "domain.com"
```

Robots.txt |
---------- |
```
domain.com/robots.txt
```
Domain/Host investigation tool |
------------------------------ |
**website :**  | 
 https://domaineye.com/

LinkedIn Employee Dork |
---------------------- |
```
site:linkedin.com employees domain.com
```

.htaccess & Sensitive Files |
--------------------------- |
```
site:domain.com inurl:"/phpinfo.php" | inurl:".htaccess"
```

Find Subdomains |
--------------- |
```
site:*.domain.com
```
Find Sub-Subdomains |
------------------- |
```
site:*.*.domain.com
```
WordPress Dork |
-------------- |
```
site:domain.com inurl:wp-content | inurl:wp-includes
```
Search in BitBucket & Altassian |
------------------------------- |
```
site:atlassian.net | site:bitbucket.org "domain.com"
```

GitHub Search |
------------- | 
```
"*.domian.com"
```

Test Crossdomain |
---------------- |
```
domain.com/crossdomain.xml
```
.git folder |
----------- |
```
inurl:"/.git "domain.com -github
```
Digital Ocean Spaces |
-------------------- |
```
site:digitaloceanspaces.com "domain.com"
```

Find .SWF file |
-------------- |
```
inurl:domain.com ext:swf
```

FInd .SWF file (Yandex) |
----------------------- |
```
site:domain.com mime:swf
```
Traefik |
------- |
```
intitle:traefik inurl:8080/dashboard"domain.com"
```

SharePoint RCE CVE-2020-0646 |
---------------------------- |

```
.sharepoint.com/_vti_bin/webpartpages/asmx -docs -msdn -mdsec site:domain.com
```
API End Points WSDL |
------------------- |

```
site:domain.com filetype:wsdl | filetype:WSDL | ext:svc | inurl:wsdl | Filetype: ?wsdl | inurl:asmx?wsdl | inurl:jws?wsdl | intitle:_vti_bin/sites.asmx?wsdl | inurl:_vti_bin/sites.asmx?wsdl
```

GitHub GIST Searches |
-------------------- |
```
*."domain.com"
```
Search in crt.sh logs |
--------------------- |
```
https://crt.sh/?q=domain.com
```

Plain text Pass wordleak |
```
site:throwbin.io domain.com
```

What CMS? |
--------- |
```
What CMS?
https://whatcms.org/?s=domain.com
```













 












