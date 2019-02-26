# WHMCS Bahasa Indonesia

Language Translation for WHMCS - Web Hosting Billing and Automation Platform
Translated from English to Bahasa Indonesia

### Compatibility
Tested with WHMCS
* v7.6.1
* v7.7.7

### Installation
#### Using Git
1. Install Git
```
RHEL (Centos/Red Hat/Cloudlinux)
# sudo yum install git

DEB (Debian/Ubuntu)
# sudo apt-get install git
```

2. Download language file into temporary folder e.g. /tmp
```
# git clone https://github.com/satriyowibowo/whmcs-bahasa.git
```

3. Copy language file into WHMCS language folder
```
# cp whmcs-bahasa/indonesian.php [whmcs-installation]/lang/
```
replace [whmcs-installation] with actual folder location of your WHMCS installation directory

4. Give proper permission and ownership
``` 
# chmod 644 [whmcs-installation]/lang/indonesian.php
# chown user:group [whmcs-installation]/lang/indonesian.php
```
again, replace [whmcs-installation] with actual folder location of your WHMCS installation directory

5. Open your WHMCS Client Area and make sure language 'Bahasa Indonesia' appears in language selection3

