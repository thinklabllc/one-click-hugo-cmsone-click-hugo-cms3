---
layout: post
title: The goals of Xesty
author: Sean Westfall
description: The technical concepts behind Xesty
date: 2025-03-12T22:28:21.415Z
image: img/mark.png
---
* Supply Chain
* EDI\
  EDI 850 - Purchase Order

  A purchase order (PO) is the most common EDI transaction set because it's used when a customer buys something from a manufacturing company. Within the EDI purchase order, it contains information including which specific items were ordered as well as the quantity of the item to be manufactured. It also includes pricing information as well as shipping details.\
  \
  EDI 997 - Functional Acknowledgment

  An EDI functional acknowledgment (FA) is the document used when a vendor notifies a customer acknowledging that it successfully received a purchase order. It is a receipt that the EDI document was either received or rejected. This allows for customers to resubmit the document quickly if it was rejected, and it helps avoids any potential costly delay in processing.\
  \
  EDI 855 - Purchase Order Acknowledgment

  The Purchase Order Acknowledgement (POA) is an outbound EDI document that essentially confirms what was included within the purchase order. The manufacturing company is telling the customer that they received the PO, and they will in fact take the job. The POA confirms the order electronically and indicates whether it was rejected. Customers also can update their systems in order to make any changes to the document as needed.\
  \
  EDI 856 - Advanced Shipping Notice

  An EDI advanced shipping notice (ASN) alerts a customer when a manufacturer is shipping an order. Inside the advanced shipping, notice are details of the contents and packaging of a shipment, which includes carrier elements, quantity and item information, and tracking numbers for the package. This allows customers to more easily schedule inbound deliveries and reduce the time to receive shipments into inventory.
* [GTIN barcodes](https://www.gs1.org/standards/id-keys/gtin)
* Consignment