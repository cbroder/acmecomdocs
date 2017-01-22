---
date: 2017-01-17T16:58:30+02:00
prev: /magento-connector-setup-and-configuration/license
next: /magento-connector-setup-and-configuration/time-setting
title: Common Configuration
toc: true
aliases :
  - /magento-connector-setup-and-configuration/common-configuration
icon: "<b>3.2</b>"
weight: 302
---

## 3.2 Common Configuration

### 3.2.1	Acumatica connection

{{% notice goto %}} 
Navigation: Acumatica > Configuration > Common Configuration > Acumatica Connection
{{% /notice %}}

Enter details in the following fields:

1.	Server URL: Provide Acumatica Server URL
2.	Username: Acumatica Admin Username
3.	Password: Password of the user 
4.	Confirm Password: Password of the user
5.	Company Name: Name of your company
6.	Click on Test Connection

![acumatica-connection](images/acumatica-connection.png?classes=shadow)

### 4.2.2	Logs

{{% notice goto %}} 
Navigation: Acumatica > Configuration > Common Configuration > Logs
{{% /notice %}}

When "EnableLog cleaning" is set to ‘Yes’ system will ask whether log data need to be deleted or stored in the Archive folder. If ‘Archive’ is selected then system will ask for how many days the data need to be stored. For e.g. if the value is set to 30days, the log data will be deleted after 30days. There is also an option to configure the Archive data path.

![log-setting](images/log-setting.png?classes=shadow)

If send log report is set to ‘Yes’, then the  below fields should be enabled
* Error Email Recipient: Email Address of the recipient, if user wants to add mulgotole email address then those should be comma separated
* Email  Template: Select the default Template

![log-setting-1](images/log-setting-1.png?classes=shadow)


