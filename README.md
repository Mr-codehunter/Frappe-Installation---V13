# Frappe-Installation --V13

## Pre-requisites 

```
Python 3.8.10
  Node.js 14+
  Redis 5                                                           (caching and real time updates)
  MariaDB 10.3.x / Postgres 9.5.x                                   (to run database driven apps)
  yarn 1.12+                                                        (js dependency manager)
  pip 20+                                                           (py dependency manager)
  wkhtmltopdf                                                       (for pdf generation)
  cron                                                              (bench's scheduled jobs: automated certificate renewal, scheduled backups)
  nginx                                                             (proxying multitenant sites in production)
```

## ***Step1 For update***

```
sudo apt update
```
## ***Step2 Software-Properties***

```
sudo apt install software-properties-common
```
