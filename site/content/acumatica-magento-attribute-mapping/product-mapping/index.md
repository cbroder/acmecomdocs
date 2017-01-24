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

<p>On Acumatica-Magento Connector mapping Page, map the Magento attributes with respective Acumatica attributes as shown below.</p>

![product-mapping](images/product-mapping.png?classes=shadow)

<p>Note: If Acumatica Attributes are not displayed in the drop down then click on Update Schema. This has to be done for every change in the Acumatica envelope for the respective mapping.
Recommended Settings: Once the Update schema is completed.  We can use the recommended settings option to automatically map the Acumatica attributes with the Magento attributes which are mandatory for Sync.
</p>

![product-mapping](images/product-mapping-1.png?classes=shadow)

<p>Map the Magento Attribute with Acumatica Attributes from Drop down list and define the direction and then click on Save.</p>

![product-mapping](images/product-mapping-2.png?classes=shadow)

##	SYNC DIRECTIONS 

* Acumatica to Magento
<p>During sync process, system will always sync the changes from Acumatica and update in Magento. This is unidirectional process and it will depend on the Sync Configuration direction.</p>

* Magento to Acumatica
<p>During sync process, system will always  sync the changes from Magento and update in Acumatica. This is unidirectional process and it will depend on the Sync Configuration direction.</p>

* Bi-Directional (Last Update Wins)
<p>During sync process, system will update the changes in both Magento and Acumatica. This is Bi-directional process and in case of conflict system will consider the “Last Update” whether it is Magento or Acumatica.
When the same record is updated in both the systems, Acumatica-Magento Connector will consider the Last updated record and update the same in both the systems and this update will depend on the SYNC Configuration direction also.
</p>

* Bi-Directional (Magento Wins)
<p>During sync process, system will update the changes in both Magento and Acumatica. This is Bi-directional process and in case of conflict   system will consider the “Magento Changes”
When the same record is modified in both the systems then Acumatica-Magento Connector will update the data of the Magento record in the both irrespective of the Last update.
</p>

* Bi-Directional (Acumatica Wins)
<p>During sync process, system will update the changes in both Magento and Acumatica. This is Bi-directional process and in case of conflict system will consider the “Acumatica Changes”.
When the same record is modified in both the systems then Acumatica-Magento Connector will update the data of the Acumatica record in the both irrespective of the Last update.</p>
