# SiteScan


***
## Install

#### requirement
+ celery
+

run `python3 ./database/database.py` to create database

***
## Run

### run as promgram

run `python3 ./sitescan.py -d [domain]` to collect infomation of that domain

run `python3 ./web.py` to open the web interface

### run as web service

run `celery -A cel worker -l info --config=celeryconfig`

run `python3 ./web.py` to open the web interface

***
## Example

![subdomain](https://raw.githubusercontent.com/jasonsheh/SiteScan/master/doc/subdomain.png)

![port](https://raw.githubusercontent.com/jasonsheh/SiteScan/master/doc/port.png)
