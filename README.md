# zabbix-api-client-poc

Illustrates how to use the zabbix api to create items and triggers using powershell.

Powershell scripts to create Zabbix items, triggers using the Zabbix API.

## Overview

- Tested with Zabbix 5.4, 6.0, 6.1, 6.2
- Has been tested on Windows 10, Windows Server 2016.
- Includes sample `gitlab-ci.yml` file to showcase how to use the script from gitlab pipelines.
- Includes information regarding how to install the Zabbix client on the servers being monitored.
- Includes information regarding how to install the the go Zabbix client (*Zabbix client 2*) on the servers being monitored.
- Includes information regarding how to add new Zabbix hosts using the Zabbix UI.

### Different item types tested

- Zabbix agent (active) using *logrt* to read log files on disk
- Dependent item
- Trigger (on error)
- Trigger (no data)

### Not included

- Installation of Zabbix server
