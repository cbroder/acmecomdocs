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

{{% notice Go To %}} 
Navigation: Acumatica > Configuration > Acumatica > Sync Configuration
{{% /notice %}}

![sync-configuration](images/sync-configuration.png?classes=shadow)

 
### 3.4.1	Warehouse Details

<p>On the Warehouse Details screen (shown below), select the Default Warehouse from the dropdown and fetch the updated warehouse details from Acumatica by clicking the Update Warehouse Data button. To save the details, click the Save Config button.</p>

![warehouse-details](images/warehouse-details.png?classes=shadow)

### 3.4.2	Attribute Sync

* Enable the Product and Customer sync options under Attribute Sync to display and enable Product Attribute Sync and Customer Attribute Sync on the Manual Sync page.
* Click the Save Config button to save the changes made to configuration.

![attribute-sync](images/attribute-sync.png?classes=shadow)

{{% notice Go To %}} 
Navigation: Magento Admin Panel > Acumatica > Manual Sync
{{% /notice %}}

![manual-sync](images/manual-sync.png?classes=shadow)

#### Action

<p> Select “Sync Now” from the dropdown to manually sync the particular entity or select “Sync Status” to redirect to the Sync Logs page. By default, it will show the entity for which “Sync Status” is clicked. </p>

![sync-status](images/sync-status.png?classes=shadow)

### 3.4.3	Category Sync

*	Enable Category Sync to display it on the Manual Sync page and enable Individual Sync to display it on every category page. 
*	Click the Save Config button to save the changes made to the configuration.	

![category-sync](images/category-sync.png?classes=shadow)

{{% notice Go To %}} 
Navigation: Magento Admin Panel > Acumatica > Manual Sync
{{% /notice %}}

![category-sync-1](images/category-sync-1.png?classes=shadow)

#### Individual sync

<p> Navigate to the Category Details page and click the Sync Now button as shown below</p>

![category-sync-2](images/category-sync-2.png?classes=shadow)

#### Sync Direction

Sync direction for each entity can be configured as follows. 
Refer to the **SYNC DIRECTIONS** section for more details on the direction type.

![category-sync-3](images/category-sync-3.png?classes=shadow)

<p> By default, Auto Cron will be set to "No." Set Auto Cron to "Yes" to automatically sync the category based on the determined settings. Click the Save Config to save the changes. </p>

![category-sync-4](images/category-sync-4.png?classes=shadow)

### 3.4.4	Product Sync

*	Enable Product Sync to display it on Manual Sync page.
*	By default, Individual Sync and Auto Cron are disabled.
*	If Indexing after sync is set to "Yes," indexing will be performed after the product sync is complete.
*	Click the Save Config button to save changes made to configuration.

![product-sync](images/product-sync.png?classes=shadow)

<p>After saving the configuration, navigate to Manual Sync page.</p>

![product-sync-1](images/product-sync-1.png?classes=shadow)

#### Individual Sync

<p> Navigate to the Product Details page and click the Sync Now button as shown below.</p>

![product-sync-2](images/product-sync-2.png?classes=shadow)
 
### 3.4.5	Product Inventory and Price Sync

*	Enable Inventory and Price sync to display it on the Manual Sync page.
*	By default Auto Cron will be set to "No."

![product-sync-3](images/product-sync-3.png?classes=shadow)

![product-sync-4](images/product-sync-4.png?classes=shadow)

Below are the options for Sync:

*	**Inventory only** - Only inventory is synced.
*	**Price only** - Only price is synced.
*	**Inventory and Price** - Both inventory and price are synced.

![product-sync-5](images/product-sync-5.png?classes=shadow)

### 3.4.6	Product Image Sync

*	Enable Image Sync to display it on the Manual Sync page.
*	Webservice Name should be indentical to the Service ID configured in Acumatica. Refer the path below. 
“System > Integration > Web services”
* Click the Save Config button to save changes made to configuration.

![product-sync-6](images/product-sync-6.png?classes=shadow)

<p>After saving the configuration, navigate to the Manual Sync page.</p>

![product-sync-7](images/product-sync-7.png?classes=shadow)

### 3.4.7	Product Configurator Sync

*	Enable Product Configurator Sync to display it on the Manual Sync page.

![product-sync-8](images/product-sync-8.png?classes=shadow)

![product-sync-9](images/product-sync-9.png?classes=shadow)

### 3.4.8	Customer Sync

{{% notice Go To %}} 
Navigation: Magento Admin Panel > Acumatica > Configuration > Acumatica > Sync Configuration
{{% /notice %}}

*	Enable Customer Sync to display it on Manual Sync page and enable Individual Sync to display it on Customer Detail page.
*	By default, Individual Sync and Auto Cron are disabled.
*	Click the Save Config button to save changes made to configuration.
*	For Default Customer Class, values will be fetched from Acumatica. Click the Update Customer Class Data button to fetch the latest data from Acumatica. 
*	For Default Customer Terms, values will be fetched from Acumatica. Click the Update Customer Terms Data button to fetch the latest data from Acumatica.
*	For Default Customer Statement Cycle, values will be fetched from Acumatica. Click the Update Customer Statement Cycle Data button to fetch the latest data from Acumatica.
* Click the Save Config button to save changes made to configuration.

![customer-sync](images/customer-sync.png?classes=shadow)

<p>After saving the configuration, navigate to the Manual Sync page.</p>

![customer-sync](images/customer-sync-1.png?classes=shadow)

#### Individual Sync

<p> Navigate to the Customer Details page. Click the Sync Now button.</p>

![customer-sync](images/customer-sync-2.png?classes=shadow)

### 3.4.9	Order Sync

*	Enable Order Sync to display it on Manual Sync page and enable Individual Sync to display it on Order Detail page.
*	By default, Individual Sync and Auto Cron will be disabled.
*	For Order Type, select the order type to be considered for the sync from the dropdown.
*	When Real Time Sync is enabled, the sync will execute following order placement and create an order in Acumatica. If disabled, the system will wait for the cron to execute the sync, or the admin can manually sync specific orders.
*	For Default Sales Account, the data will be fetched from Acumatica. Click the Update Sales Account Data button to fetch the latest data from Acumatica.
*	For Default Payment Method, select the default payment method from the dropdown. To update the payment method data, click the Update Payment Method Data button.
*	For Cash Account, select the appropriate cash account number from the dropdown.
*	When Retry Failed Orders is set to "Yes," the order sync considers the failed orders for the specified number of times. By default, Number of Retries is set to 3. Change this value if desired. This number determines how many times the system will consider the order before skipping it, given the order fails to sync on each of the preceding tries. 
* For Order Statuses, select every order status which should be included in the sync to Acumatica.

![order-sync](images/order-sync.png?classes=shadow)

![order-sync-1](images/order-sync-1.png?classes=shadow)

#### Individual Sync

<p> Navigate to the Order Details page and click the Sync Now button./p>

![order-sync-2](images/order-sync-2.png?classes=shadow)

### 3.4.10	Failed Order Sync

{{% notice Go To %}} 
Navigation: Magento Admin Panel > Acumatica > Configuration > Acumatica > Sync Configuration
{{% /notice %}}

*	Enable Failed Order Sync to display it on the Manual Sync screen. 
*	By default, Auto Cron will be disabled.
*	Set Number of days to desired amount. This value determines how many days the sync will cover. 

![order-sync-3](images/order-sync-3.png?classes=shadow)

![order-sync-4](images/order-sync-4.png?classes=shadow)



















