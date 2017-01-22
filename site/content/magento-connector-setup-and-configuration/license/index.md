---
date: 2017-01-17T16:58:30+02:00
prev: /magento-connector-setup-and-configuration
next: /magento-connector-setup-and-configuration/common-configuration
title: Magento Connector Setup And Configuration
toc: true
aliases :
  - /magento-connector-setup-and-configuration/license
icon: "<b>3.1</b>"
weight: 301
---

## 3.1 License

### 3.1.1 License Detail

{{% notice goto %}}
Navigation: Acumatica > Configuration > Acumatica > License > License Details
{{% /notice %}}

**License Key:** Enter the received license key, and click on apply button. Once the license is applied successfully License details will be displayed.

![license-details](images/license-details.png?classes=shadow)

### 3.1.2 Add Domain Request

{{% notice goto %}}
Navigation: Acumatica > Configuration > Acumatica > License > Add Domain Request
{{% /notice %}}

<p>To Change the License Request or Export the License Request, please follow the below steps</p>

* Domain Name: Data will be fetched from store configuration
* IP Address: Data will be fetched from server
* MAC ID: Data will be fetched from server
* Email Recipient: Data will be fetched from server

1.	License Type: Choose a license type from the dropdown
2.	Select Terms & Conditions
3.	Upon Clicking on the “Send License Request”, System will send license request with the details provided and an email notification to the provided email address

*	Upon Clicking on the “Export License Request”, System exports license request fields in a “txt” file in encrypted format and same file will be used for requesting license.

![add-domain-request](images/add-domain-request.png?classes=shadow)

### 3.1.3 Delete Domain Request

<p> Please follow the below steps to send “Delete Domain Request”
1.	Enter the domains for which the license need to be deleted
2.	Click on Delete License Request </p>

![delete-domain-request](images/delete-domain-request.png?classes=shadow)
