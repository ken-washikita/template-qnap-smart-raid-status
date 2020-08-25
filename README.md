# zbx-templ-qnap-smart-raid-status
Zabbix Templates for QNAP - Status check SMART and RAID

# Install
1. Add ```Include=/opt/ZabbixAgent/etc/zabbix_agentd.conf.d/``` to QNAP:/opt/ZabbixAgent/etc/zabbix_agentd.conf 
1. Copy smart.conf, raid.conf to QNAP:/opt/ZabbixAgent/etc/zabbix_agentd.conf.d/
1. Reload QNAP Zabbix-agent
1. Import Templates XML on Zabbix server
1. Configure QNAP host
