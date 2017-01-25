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

### 3.2.1	Acumatica Connection

{{% notice Go To %}} 
Navigation: Acumatica > Configuration > Common Configuration > Acumatica Connection
{{% /notice %}}

Input details in the following fields:

1.	Server URL: Enter the Acumatica server URL.
2.	User Name: Enter the Acumatica admin user name.
3.	Password: Enter the password of the user. 
4.	Confirm Password: Enter the password of the user again.
5.	Company Name: Enter the name of the company.

Click the Test Connection button.

![acumatica-connection](images/acumatica-connection.png?classes=shadow)

### 3.2.2	Log Setting

{{% notice Go To %}} 
Navigation: Acumatica > Configuration > Common Configuration > Log Setting
{{% /notice %}}

When Enable Log Cleaning is set to "Yes," the system will ask whether the log data need to be deleted or stored in the archive folder. If "Archive" is selected, the system will ask for how many days the data need to be stored. For example, if the value is set to 30 days, the log data will be deleted after 30 days. There is also an option to configure the archive data path.

![log-setting](images/log-setting.png?classes=shadow)

<p>If Send Log Report is set to "Yes," the fields below should be enabled.</p>

* Error Email Recipient: Enter the email address of the recipient. Multiple email addresses can be added, with a comma separating each one. 
* Email Template: Select the default template.

![log-setting-1](images/log-setting-1.png?classes=shadow)


