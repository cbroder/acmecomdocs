---
date: 2017-01-17T16:58:30+02:00
prev: /magento-connector-setup-and-configuration/time-setting
next: /magento-connector-setup-and-configuration/sync-logs
title: Sync Configuration
toc: true
aliases :
  - /magento-connector-setup-and-configuration/sync-configuration
icon: "<b>3.4</b>"
weight: 304
---

## 3.4 Sync Configuration

{{% notice tip %}} 
Navigation: Acumatica > Configuration > Acumatica > Sync Configuration
{{% /notice %}}

![sync-configuration](images/sync-configuration.png?classes=shadow)

 
### 3.4.1	Warehouse Details

<p>On warehouse details screen(as shown below) user can select the “Default Warehouse” and fetch the updated warehouse details from Acumatica 
by clicking on “Update Warehouse Data” and after selecting the warehouse click on Save Config button.</p>

![warehouse-details](images/warehouse-details.png?classes=shadow)

### 3.4.2	Attribute Sync

* Enable Product and Customer sync option in Attribute Sync list to display and enable Product Attribute Sync and Customer Attribute Sync on the Manual Sync page
* Click “Save Config” to save the changes made to configuration

![attribute-sync](images/attribute-sync.png?classes=shadow)

{{% notice tip %}} 
Navigation: Magento Admin Panel > Acumatica > Manual Sync
{{% /notice %}}

![manual-sync](images/manual-sync.png?classes=shadow)

#### Action

<p> When user clicks on “Sync now” button, manual sync of that particular entity will execute
When user clicks on “Sync Status” it will redirect to Sync Logs page and by default it will show the entity for which “Sync Status” is clicked. </p>

![sync-status](images/sync-status.png?classes=shadow)

### 3.4.3	Category Sync

*	Enable Category Sync to display it on Manual sync page and Enable Individual Sync to display it on every Category page. 
*	Click save Config to save the changes made to configuration	

![category-sync](images/category-sync.png?classes=shadow)

{{% notice tip %}} 
Navigation: Magento Admin Panel > Acumatica > Manual Sync
{{% /notice %}}

![category-sync-1](images/category-sync-1.png?classes=shadow)

#### Individual sync

![category-sync-2](images/category-sync-2.png?classes=shadow)

####	Sync Direction

Sync direction for each entity can be configured as follows. 
Refer > **SYNC DIRECTIONS** section for more details on the direction type

![category-sync-3](images/category-sync-3.png?classes=shadow)

<p> By default Auto Cron will be ‘NO’. If, Auto Cron is set to ‘Yes’ then, Category will sync automatically based on the setting. Click Save Config to save the changes made. </p>

![category-sync-4](images/category-sync-4.png?classes=shadow)
















