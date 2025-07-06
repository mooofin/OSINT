Here’s a clean, **long list of Google Dorks** without emojis, organized by category, ideal for use directly in Firefox or any browser's address/search bar.

---

## Login Pages & Admin Panels

```
inurl:admin
inurl:admin/login
inurl:adminpanel
intitle:"admin panel"
intitle:"login page"
inurl:cpanel
intitle:"Control Panel" inurl:admin
inurl:dashboard
inurl:wp-admin
inurl:administrator
inurl:userlogin
inurl:login.jsp
```

---

## Exposed Passwords & Credentials

```
intext:"password" filetype:log
intext:"password=" ext:env | ext:ini | ext:conf
filetype:env DB_PASSWORD
intext:"Authorization: Basic"
filetype:xml intext:"password"
intext:"ftp" intext:"password"
filetype:txt intext:"password"
filetype:xls intext:"username" intext:"password"
filetype:log intext:"pass"
inurl:"config.php" "DB_PASSWORD"
```

---

## Directory Listings & File Indexes

```
intitle:"index of /"
intitle:"index of" +passwd
intitle:"index of" +secret
intitle:"index of" +.git
intitle:"index of" +/config
intitle:"index of" +/backup
intitle:"index of" +/private
intitle:"index of" +/uploads
intitle:"index of" +/files
```

---

## Configuration Files & Source Code

```
filetype:conf apache
filetype:conf nginx
filetype:env intext:"SECRET_KEY"
filetype:json intext:"aws_access_key_id"
filetype:xml intext:"configuration"
filetype:ini intext:"smtp"
filetype:yaml intext:"token"
filetype:php inurl:config
filetype:rb inurl:secrets
inurl:config.json
```

---

## Leaked Documents & Sensitive Data

```
filetype:pdf "confidential"
filetype:doc "internal use only"
filetype:docx "restricted"
filetype:xls intext:"salary"
filetype:xlsx intext:"budget"
filetype:txt intext:"secret"
filetype:csv intext:"email"
filetype:xls intext:"employee list"
```

---

## Database Exposures

```
filetype:sql "INSERT INTO"
filetype:sql intext:"DROP TABLE"
filetype:sql intext:"password"
filetype:db
filetype:dbf
filetype:mdb
inurl:wp-content/uploads *.sql
filetype:bak intext:"database"
```

---

## Source Code Leaks

```
site:github.com "SECRET_KEY"
site:gitlab.com intext:"api_key"
filetype:py intext:"token"
filetype:js intext:"apikey"
filetype:json intext:"private_key"
filetype:php intext:"define('DB_PASSWORD'"
filetype:env intext:"JWT_SECRET"
```

---

## Public IP Cameras / CCTV

```
inurl:"view/view.shtml"
inurl:"/webcapture.jpg?"
inurl:top.htm inurl:currenttime
intitle:"Live View / - AXIS"
inurl:/axis-cgi/jpg/image.cgi
intitle:"IP Camera" inurl:video.cgi
```

---

## Router & Device Interfaces

```
intitle:"router login"
inurl:8080
inurl:8443
intitle:"D-Link"
intitle:"Netgear"
intitle:"TP-Link"
inurl:setup.cgi
inurl:guest_network
```

---

## Internal Portals & Staging Sites

```
site:*.example.com -www "staging"
site:*.example.com -www "internal"
site:*.example.com -www "dev"
site:*.example.com -www "test"
inurl:test
inurl:staging
inurl:dev
inurl:/private
```

---

## Backup Files & Logs

```
filetype:log
filetype:bak
filetype:old
filetype:zip inurl:backup
filetype:tar.gz inurl:db
filetype:7z inurl:site
filetype:sql.bak
filetype:backup intext:"password"
```

---

## Cloud & API Key Leaks

```
filetype:json intext:"api_key"
filetype:env intext:"AWS_SECRET_ACCESS_KEY"
filetype:yml intext:"token"
intext:"Authorization: Bearer"
site:pastebin.com "api_key"
site:github.com intext:"slack_token"
```

---

## OSINT & Info Leak

```
site:pastebin.com "confidential"
site:github.com "do not share"
site:trello.com "password"
site:linkedin.com/in "admin"
site:*.gov filetype:xls
site:*.edu filetype:pdf
```

---

## Recon Shortcuts (site-specific)

```
site:target.com inurl:login
site:target.com filetype:sql
site:target.com intitle:index.of
site:target.com inurl:admin
site:target.com filetype:env
```

---

