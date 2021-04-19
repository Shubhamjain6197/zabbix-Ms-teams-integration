

# Zabbix and Ms teams Integration

This document defines Zabbix and MS Teams Integrations.

## Steps -

### 1. Zabbix + Microsoft Teams Alert

* [Follow this Link and below steps](https://www.zabbix.com/integrations/msteams)
* **Administration** --> **General** --> **Macros** --> Add variable --> **macro [{$ZABBIX.URL}] and value [Zabbix UI Url]** --> Update
![Macros](https://github.com/Shubhamjain6197/zabbix-agent-auto-registration/blob/main/img/custom-macros.png)
* **Configuration** --> **Actions** --> **Trigger actions** --> Enable --> **Report problems to Zabbix administrators**
![Enable Admin Alerting](https://github.com/Shubhamjain6197/zabbix-agent-auto-registration/blob/main/img/enable-admin-alerting.png)
* **Administration** --> **Media Type** --> **MS Teams** --> Add Hook --> teams_endpoint[PLACE WEBHOOK URL HERE] --> Update
* **Administration** --> **Users** --> **Admin** --> Media --> Add Media --> Type [MS Teams] --> Send To [your team channel Url] --> **Add and Update**
![Add Media](https://github.com/Shubhamjain6197/zabbix-agent-auto-registration/blob/main/img/custom-add-media.png)

## Important Links

* [Zabbix Manual](https://www.zabbix.com/documentation/current/manual)


Supported Version 5.0
