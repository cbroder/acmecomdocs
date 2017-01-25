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

### 3.1.1 License Details

{{% notice Go To %}}
Navigation: Acumatica > Configuration > Acumatica > License > License Details
{{% /notice %}}

**License Key:** Enter the received license key and click the apply button. Once the license is applied successfully, license details will be displayed.

![license-details](images/license-details.png?classes=shadow)

### 3.1.2 Add Domain Request

{{% notice Go To %}}
Navigation: Acumatica > Configuration > Acumatica > License > Add Domain Request
{{% /notice %}}

<p>To change or export the license request, follow the steps below.</p>

* Domain Name: Data will be fetched from the store configuration
* IP Address: Data will be fetched from the server
* MAC ID: Data will be fetched from the server
* Email Recipient: Data will be fetched from the server

1.	Choose a field from the License Type dropdown.
2.	Check the Terms and Conditions checkbox.
3.	Click on the Send License Request button. This will send the license request with details and an email notification to the provided email address.

*	Clicking the Export License Request button will result in the system exporting license request fields in an encrypted “txt” file. The same file will be used for requesting the license.

![add-domain-request](images/add-domain-request.png?classes=shadow)

### 3.1.3 Delete Domain Request

<p> Follow the steps below to send a Delete Domain Request. </p>

1.	In the Domain Name field, enter the domains for which the license needs to be deleted.
2.	Click the Delete License Request button.

![delete-domain-request](images/delete-domain-request.png?classes=shadow)
