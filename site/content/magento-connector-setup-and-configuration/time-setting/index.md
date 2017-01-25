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

{{% notice Go To %}} 
Navigation: Acumatica > Configuration > Common Configuration > Time Setting
{{% /notice %}}

If there is a time difference between servers, server timings must be synced. To do this, there are two options:

Set Automatically Sync Magento Server Time with Acumatica Server’s Time as "No" or "Yes." Steps for syncing with each method follow.

For "No": Click on verify button. The application verifies the server’s time and, if the value is greater than the desired time, it displays the Sync Now button. Click the Sync Now button for the application to sync the times. The Verify button will then be displayed.
![time-setting](images/time-setting.png?classes=shadow)
<p>For "Yes": If there is an undesired time difference in the servers, the application will display the Sync Now button. Click the Sync Now button to sync the server times.</p>

![time-setting-1](images/time-setting-1.png?classes=shadow)
