# zabbix-templates
Collection of zabbix Templates

1 Template for Ruckus Unleashed access point
You must “enable snmp” on master.
You must create a host with the ip of the master and add the macros  {$SNMP_COMMUNITY} with the name of your community (example: public).
Modify in Template the trigger “Rukus Access Point Offline” with the number of your access point.
Add in your zabbix server the mib of Ruckus in your snmp

2 Template for Datek UPS

3 Template for windows 2008 R2 and 2012 for italian but should word also with all language
