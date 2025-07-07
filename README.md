

### Authentication Interfaces 
```
inurl:/admin/login.php
inurl:/administrator/index.php
inurl:/wp-admin/admin-ajax.php
intitle:"Login" inurl:/cms/
inurl:/user/login ext:aspx
inurl:/console/login.do
inurl:/Account/Login ext:cshtml
inurl:/admin/auth/login
inurl:/admincp/login.php
inurl:/_admin/login.aspx
inurl:/manager/html
inurl:/umbraco/login.aspx
inurl:/siteadmin/login.aspx
inurl:/admin123/login.php
inurl:/admin_area/login
inurl:/adminpanel/login.jsp
inurl:/admin/login.asp
inurl:/admin/account/login
inurl:/admin/login.html
inurl:/admincenter/login
inurl:/admin/login.action
inurl:/admin/index.php?route=common/login
inurl:/admin/login.jsp?msg=invalid
inurl:/admin/login?redirect_to=
inurl:/admin/login?error=1
inurl:/admin/login?failed=true
inurl:/admin/login?ReturnUrl=
inurl:/admin/login?denied
inurl:/admin/login?expired
inurl:/admin/login?session=expired
```

### Database & Configuration Files 
```
filetype:env DB_USERNAME DB_PASSWORD
filetype:ini "mysql_connect"
filetype:properties "jdbc.password"
filetype:yml "spring.datasource.password"
filetype:conf "pass =" site:github.com
filetype:config "connectionString" "Password="
filetype:json "apiSecret" -git -sample -test
filetype:sql "CREATE USER" "IDENTIFIED BY"
filetype:log "Failed password for"
filetype:xml "mail.password"
filetype:sh "export PGPASSWORD="
filetype:php "define('DB_PASS'"
filetype:pl "DBI->connect('DBI:mysql"
filetype:rb "establish_connection password:"
filetype:py "SQLALCHEMY_DATABASE_URI"
filetype:java "DataSource.setPassword"
filetype:jsp "jdbc:mysql://"
filetype:asp "conn.open \"Driver={SQL Server}"
filetype:aspx "SqlDataSource.ConnectionString"
filetype:bak intext:"db_user" ext:sql
filetype:inc "mysql_pconnect"
filetype:txt "ftp://user:pass@"
filetype:reg "Windows Registry Editor" "Password"
filetype:inf "DefaultPassword"
filetype:ldif "userPassword::"
filetype:vbs "strPassword ="
filetype:ps1 "$cred = Get-Credential"
filetype:bat "sqlcmd -U" -" -P"
filetype:cfg "oauth_token_secret"
filetype:yaml "aws_secret_access_key"
filetype:toml "secret_key_base"
filetype:tf "aws_secret_key"
filetype:ppk "Private-Lines:"
filetype:pem "BEGIN RSA PRIVATE KEY"
filetype:key "-----BEGIN PRIVATE KEY-----"
filetype:cer "Subject:" "Issuer:"
filetype:jks "keystore password"
filetype:pfx "PKCS12 Certificate"
```

### Version Control & Source Code 
```
intitle:"index of" /.git/HEAD
intitle:"index of" /.svn/entries
intitle:"index of" /.hg/store
intitle:"index of" /CVS/Root
filetype:gitignore "secret" -example
inurl:".git/config" intitle:"index of"
inurl:"/.git/logs/HEAD"
inurl:"/bitbucket/rest/api" -atlassian
inurl:"/api/v3/repos" ext:json
inurl:"/raw/" ext:java | ext:py | ext:php
inurl:"/blob/master/" ext:env
inurl:"/commit/" ext:diff
inurl:"/pull/" ext:patch
inurl:"/releases/download/"
inurl:"/tree/master/" ext:md
inurl:"/raw/master/package.json"
inurl:"/raw/master/config/"
inurl:"/raw/master/src/" ext:js
inurl:"/.github/workflows/" ext:yml
inurl:"/package-lock.json" "dependencies"
inurl:"/pom.xml" "properties"
inurl:"/build.gradle" "repositories"
inurl:"/requirements.txt" "pkg-resources"
inurl:"/composer.json" "require-dev"
inurl:"/Dockerfile" "ENV" "PASSWORD"
```

### API Endpoints & Developer Tools 
```
inurl:"/swagger-ui.html"
inurl:"/v2/api-docs" ext:json
inurl:"/graphql" "query {"
inurl:"/api/v1/users" ext:json
inurl:"/oauth/token" ext:json
inurl:"/actuator/health" ext:json
inurl:"/phpinfo.php" intitle:"phpinfo()"
inurl:"/debug/default/view"
inurl:"/_profiler/phpinfo"
inurl:"/web-console/"
inurl:"/jmx-console/"
inurl:"/adminer.php" intitle:"Adminer"
inurl:"/phpMyAdmin/" intitle:"phpMyAdmin"
inurl:"/pgadmin/" intitle:"pgAdmin"
inurl:"/redis-admin/"
inurl:"/elasticsearch/_plugin/head/"
inurl:"/kibana/app/kibana"
inurl:"/druid/index.html"
inurl:"/hawtio/login"
inurl:"/solr/admin/cores"
inurl:"/manager/status" ext:xml
inurl:"/jenkins/script"
inurl:"/nexus/#browse"
inurl:"/sonarqube/api"
inurl:"/artifactory/api"
inurl:"/gitlab/api/v4"
inurl:"/teamcity/app/rest"
inurl:"/v1/keys?recursive=true"
inurl:"/api/v1/namespaces/default/pods"
inurl:"/api/v1/nodes" ext:json
```

### Industrial & IoT Systems 
```
intitle:"SCADA" inurl:/login
intitle:"HMI" inurl:/Runtime
inurl:"/portal/DeviceList"
inurl:"/webvisu.htm" intitle:"WebVisu"
inurl:"/Portal/Portal.mwsl"
inurl:"/ViewerFrame?Mode="
inurl:"/snap.jpg" intitle:"Camera"
inurl:"/videostream.cgi" intitle:"MJPG"
inurl:"/cgi-bin/CGIProxy.fcgi"
inurl:"/axis-cgi/com/ptz.cgi"
inurl:"/ISAPI/Streaming/channels/"
inurl:"/onvif/device_service"
inurl:"/cgi-bin/snapshot.cgi"
inurl:"/webcapture.jpg?stream="
inurl:"/live/index2.html"
inurl:"/mobile.html" intitle:"IP Camera"
inurl:"/cgi-bin/viewer/video.jpg"
inurl:"/camera-cgi/admin/param.cgi"
inurl:"/config/system.ini"
inurl:"/cgi-bin/nobody/Machine.cgi"
inurl:"/cgi-bin/hi3510/param.cgi"
inurl:"/cgi-bin/net/Network.cgi"
inurl:"/cgi-bin/guest/Video.cgi"
inurl:"/cgi-bin/viewer/get_status.cgi"
inurl:"/cgi-bin/luci/admin/status"
```

### Cloud & DevOps 
```
inurl:"/aws/credentials" ext:ini
inurl:"/.aws/credentials" ext:txt
filetype:tfvars "access_key"
inurl:"/metadata/v1/" ext:json
inurl:"/latest/meta-data/iam/"
inurl:"/storage/v1/b/" ext:json
inurl:"/computeMetadata/v1/"
inurl:"/secretsmanager/listsecrets"
inurl:"/v1/secret/" ext:json
inurl:"/api/v1/namespaces/kube-system/pods"
inurl:"/apis/apps/v1/deployments"
inurl:"/v2/_catalog" ext:json
inurl:"/v1.32/containers/json"
inurl:"/api/v1beta1/namespaces"
inurl:"/api/v1/services"
inurl:"/api/v1/pods" ext:json
inurl:"/api/v1/nodes" ext:yaml
inurl:"/v3/project/" ext:json
inurl:"/v2.0/tokens" ext:json
inurl:"/v1/auth/tokens" ext:xml
```

### Financial & Retail Systems 
```
inurl:"/pos/printreceipt.php"
inurl:"/payment/process" ext:do
inurl:"/gateway/transaction"
inurl:"/merchant/account"
inurl:"/api/v1/transactions"
inurl:"/checkout/cart" ext:asp
inurl:"/account/statement"
inurl:"/transfer/confirm"
inurl:"/invoice/download"
inurl:"/pos/printreceipt.php"
inurl:"/reports/financial"
inurl:"/account/balance"
inurl:"/api/v1/merchants"
inurl:"/v1/payments/"
inurl:"/transaction/details"
```

### Healthcare Systems 
```
inurl:"/ehr/patient/view"
inurl:"/emr/api/patients"
inurl:"/his/labresults"
inurl:"/phr/records"
inurl:"/cerner/patientportal"
inurl:"/epic/MyChart"
inurl:"/meditech/webpatient"
inurl:"/pharmacy/orders"
inurl:"/lab/results/view"
inurl:"/radiology/images"
inurl:"/api/fhir/Patient"
inurl:"/dicom/viewer"
inurl:"/hl7/listener"
inurl:"/clinical/notes"
inurl:"/immunization/records"
```
Here are 50 highly specialized Google Dork queries for uncovering niche vulnerabilities and hidden systems:

### Industrial Control Systems (10)
```
inurl:/scada/WebHMI.html
intitle:"Wonderware InTouch" inurl:/Runtime
inurl:/RSLinxRemoteOPC -demo
inurl:/config/iop.xsl (Siemens)
inurl:/Portal/Portal.mwsl (Beckhoff)
inurl:/ccw/main.aspx (Rockwell)
inurl:/CimWeb/ (GE Cimplicity)
inurl:/Vijeo-Citect (Schneider)
filetype:ccp (CoDeSys projects)
inurl:/webvisu (WAGO controllers)
```

### Medical Imaging Systems (8)
```
inurl:/dicom/query? (PACS)
inurl:/orthanc/instances (DICOM servers)
inurl:/weasis-pacs-connector/
intitle:"DICOM Query Retieve" -demo
inurl:/api/v1/studies ext:json
inurl:/ohif/viewer?studyUIDs=
inurl:/pacsgateway/dicom.ashx
filetype:wlms (DICOM worklists)
```

### Aviation & Maritime (7)
```
inurl:/fms/flightdata (FMS systems)
inurl:/aisweb/ais (AIS tracking)
inurl:/ecdis/ (ECDIS chart systems)
inurl:/jrc/radar (Radar systems)
inurl:/ams2/ (Aircraft maintenance)
filetype:flt (Flight plan files)
inurl:/transas/ (Navigation systems)
```

### Automotive Systems (5)
```
inurl:/xentry/aftertreatment (Mercedes)
inurl:/tech2win/ (GM diagnostics)
inurl:/idsclient/ (Ford diagnostics)
filetype:prg (ECU flash files)
inurl:/asm/ (Audi Service Mode)
```

### Building Automation (5)
```
inurl:/niagara/ax (Tridium)
inurl:/desigo/ (Siemens)
inurl:/eikon/ (Honeywell)
inurl:/continuum/ (Automated Logic)
inurl:/metasys/ (Johnson Controls)
```

### Scientific Research (5)
```
inurl:/lims/sample (Lab systems)
inurl:/epicore/ (Clinical trials)
filetype:cdf (NASA data)
inurl:/irisws/ (Seismic data)
inurl:/helioviewer/api/ (Solar imaging)
```

### Military & Defense (5)
```
inurl:/falconview/ (Mapping)
inurl:/jalc/ (Joint systems)
filetype:afm (Flight manuals)
inurl:/dcgs/ (Surveillance)
inurl:/milstar/ (Satellite coms)
```

### Space Systems (5)
```
inurl:/ccsds/ (Space protocols)
inurl:/omms/ (NASA maintenance)
filetype:eph (Ephemeris data)
inurl:/soc/ (Spacecraft ops)
inurl:/tletrak/ (Satellite tracking)
```

