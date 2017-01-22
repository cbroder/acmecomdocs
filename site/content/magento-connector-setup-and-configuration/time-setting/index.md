---
date: 2017-01-17T16:58:30+02:00
prev: /magento-connector-setup-and-configuration/common-configuration
next: /magento-connector-setup-and-configuration/sync-configuration
title: Time Setting
toc: true
aliases :
  - /magento-connector-setup-and-configuration/time-setting
icon: "<b>3.3</b>"
weight: 303
---

## 3.3 Time Setting

{{% notice goto %}} 
Navigation: Acumatica > Configuration > Common Configuration > Time Setting
{{% /notice %}}

If there is a time difference between the 2 servers, then we have to sync the server timings. For achieving this, we will be using two options:

1. Automatically Sync Magento Server Time with Acumatica Server’s time value as NO 
2. Automatically Sync Magento Server Time with Acumatica Server’s time value as YES

Using Automatically Sync Magento Server time with Acumatica Server’s time value as ‘No’ option, if we click on verify button, Application verifies the server’s time and if the value is greater than the desired time it displays SYNC NOW button. Once the SYNC NOW button is clicked, application syncs the servers time and displays verify Button.

![time-setting](images/time-setting.png?classes=shadow)

 
<p>Using Automatically Sync Magento Server time with Acumatica Server’s time value as ‘Yes’ option, if there is a time difference in the servers as required, application will display the Sync Now option and if Sync now button is clicked, automatically time of the servers will be synced.</p>

![time-setting-1](images/time-setting-1.png?classes=shadow)
