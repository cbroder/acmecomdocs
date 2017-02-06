---
date: 2017-01-17T16:58:30+02:00
prev: /acumatica-magento-attribute-mapping
next: /acumatica-magento-attribute-mapping/category-mapping
title: Product Mapping
toc: true
aliases :
  - /acumatica-magento-attribute-mapping/product-mapping
icon: "<b>4.1</b>"
weight: 401
---

## 4.1 Product Mapping

<p>On the Acumatica-Magento Connector Product Mapping page, map the Magento attributes with the respective Acumatica attributes as shown below.</p>

![product-mapping](images/product-mapping.png?classes=shadow)

**Note**: If Acumatica Attributes are not displayed in the dropdown, click the Update Schema button. This has to be done for every change in the Acumatica envelope for respective mapping.
Once the Update Schema operation is complete, use the Recommended Mappings option to automatically map the Acumatica attributes with the Magento attributes that are mandatory for the sync.


![product-mapping](images/product-mapping-1.png?classes=shadow)

<p>Map the Magento Attribute with the Acumatica Attribute from dropdown and define the direction. Click the Save button.</p>

![product-mapping](images/product-mapping-2.png?classes=shadow)

##	SYNC DIRECTIONS 

* **Acumatica to Magento** - During the sync process, the system will always sync the changes from Acumatica and update in Magento. This is determined by the selection made under Direction.

* **Magento to Acumatica** - During the sync process, the system will always sync the changes from Magento and update in Acumatica. This is determined by the selection made under Direction.

* **Bi-Directional (Last Update Wins)** - During the sync process, the system will update the changes in both Magento and Acumatica in a bi-directional fashion. In the case of a conflict, the system will consider the most recent update, whether it is in Magento or Acumatica, to be correct. It will sync as such.


* **Bi-Directional (Magento Wins)** - During the sync process, the system will update the changes in both Magento and Acumatica in a bi-directional fashion. In the case of a data conflict, the system will consider the Magento information to be correct and sync the Magento information to Acumatica. 


* **Bi-Directional (Acumatica Wins)** - During the sync process, the system will update the changes in both Magento and Acumatica in a bi-directional fashion. In the case of a data conflict, the system will consider the Acumatica information to be correct and sync the Acumatica information to Magento. 
