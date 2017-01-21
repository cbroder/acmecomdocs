---
date: 2017-01-17T16:58:30+02:00
prev: /magento-connector-setup-and-configuration/time-setting
next: /magento-connector-setup-and-configuration/sync-scheduler
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

<p> Navigate to category details page and click on the "Sync Now" button as shown below</p>

![category-sync-2](images/category-sync-2.png?classes=shadow)

#### Sync Direction

Sync direction for each entity can be configured as follows. 
Refer > **SYNC DIRECTIONS** section for more details on the direction type

![category-sync-3](images/category-sync-3.png?classes=shadow)

<p> By default Auto Cron will be ‘NO’. If, Auto Cron is set to ‘Yes’ then, Category will sync automatically based on the setting. Click Save Config to save the changes made. </p>

![category-sync-4](images/category-sync-4.png?classes=shadow)

### 3.4.4	Product Sync

*	Enable Product Sync to display it on Manual Sync page
*	By default, Individual Sync and Auto Cron are disabled
*	If Indexing after sync is set to ‘yes’, indexing job will be performed after the Product sync is completed.
*	Click on Save Config to save changes made to configuration

![product-sync](images/product-sync.png?classes=shadow)

<p>After saving the configuration, Navigate to Manual sync page</p>

![product-sync-1](images/product-sync-1.png?classes=shadow)

#### Individual Sync

<p> Navigate to product details page and click on the "Sync Now" button as shown below</p>

![product-sync-2](images/product-sync-2.png?classes=shadow)
 
### 3.4.5	Product Inventory and Price Sync

*	Enable Inventory and Price Sync to display it on Manual Sync page
*	By default Auto Cron will be set to ‘No’

![product-sync-3](images/product-sync-3.png?classes=shadow)

![product-sync-4](images/product-sync-4.png?classes=shadow)

Below are the options for Sync:

*	Inventory only: Only Inventory would be synced
*	Price only: Only Price would be synced
*	Inventory and Price: Both Inventory and Price would be synced

![product-sync-5](images/product-sync-5.png?classes=shadow)

### 3.4.6	Product Image Sync

*	Enable Image Sync to display it on Manual Sync page
*	Web service Name should be same as the Service ID configured in Acumatica. Refer the below path. 
“System > Integration > Web services”

![product-sync-6](images/product-sync-6.png?classes=shadow)

<p>After saving the configuration, Navigate to Manual sync page</p>

![product-sync-7](images/product-sync-7.png?classes=shadow)

### 3.4.7	Product Configurator Sync

*	Enable Product Configurator Sync as shown below, to display it on Manual Sync page

![product-sync-8](images/product-sync-8.png?classes=shadow)

![product-sync-9](images/product-sync-9.png?classes=shadow)

### 3.4.8	Customer Sync

{{% notice tip %}} 
Navigation: Magento Admin Panel > Acumatica > Configuration > Acumatica > Sync Configuration
{{% /notice %}}

*	Enable Customer Sync to display it on Manual Sync page and enable Individual Sync to display it on Customer detail page.
*	By default, Individual Sync and Auto Cron are disabled
*	Click Save Config to save changes made to configuration
*	Default Customer Class: Values will be fetched from Acumatica and user can also click on “update Customer Class Data” to fetch the latest data from Acumatica. 
*	Default Customer Terms: Values will be fetched from Acumatica and user can also click on “update Customer Terms Data” to fetch the latest data from Acumatica.
*	Default Customer Statement Cycle: Values will be fetched from Acumatica and user can click on “update Customer Statement Cycle Data” to fetch the latest data from Acumatica.

![customer-sync](images/customer-sync.png?classes=shadow)

<p>After saving the configuration, Navigate to Manual sync page</p>

![customer-sync](images/customer-sync-1.png?classes=shadow)

#### Individual Sync

<p> Navigate to customer details page and click on the "Sync Now" button as shown below</p>

![customer-sync](images/customer-sync-2.png?classes=shadow)

### 3.4.9	Order Sync

*	Enable Order Sync to display it on Manual Sync page and enable Individual Sync to display it on Order detail page
*	By default Individual Sync and Auto Cron will be disabled
*	Order Type: Mention the Order Type to be considered for Sync
*	Real Time Sync: If enabled, after successfully placing an order, sync will execute and create an order in Acumatica. If Real time sync is not enabled, system will wait for the cron to execute the sync or admin can use individual sync option to sync specific order.
*	Default Sales Account: The data will be fetched from Acumatica Instance and user can also click on “update Sales Account Data” to fetch the latest data from Acumatica.
*	Default Payment Method: Select the default payment method from the dropdown list.  To update the payment method data click on “Update Payment Method Data”
*	Cash Account: Add the cash account number as configured in Acumatica
*	Retry Failed Orders: When Retry Failed Orders is set to ‘Yes’, Order Sync considers the failed orders for the number of times it is configured. By default number of Retries value is set to ‘3’ For e.g. If Order ‘123456’ is failed to sync to Acumatica, and the number of retries value is set to ‘4’ then during Order sync, system will consider this order for sync for 4 times and the 5th time system will skip this order to sync if the order still fails to sync.
* Order Statuses: Select the Order status to sync the Orders with those statuses to Acumatica

![order-sync](images/order-sync.png?classes=shadow)

![order-sync-1](images/order-sync-1.png?classes=shadow)

#### Individual Sync

<p> Navigate to order details page and click on the "Sync Now" button as shown below</p>

![order-sync-2](images/order-sync-2.png?classes=shadow)

### 3.4.10	Failed Order Sync

{{% notice tip %}} 
Navigation: Magento Admin Panel > Acumatica > Configuration > Acumatica > Sync Configuration
{{% /notice %}}

*	Enable Failed Order Sync to display it on Manual Sync screen. 
*	By default Auto Cron will be disabled
*	Set Number of days  and Connector will consider the failed orders only from the current date to last ‘x’ days duration to sync

![order-sync-3](images/order-sync-3.png?classes=shadow)

![order-sync-4](images/order-sync-4.png?classes=shadow)



















