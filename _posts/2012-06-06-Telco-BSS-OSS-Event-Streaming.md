---
date: 2018-03-12 12:26:40
layout: post
title: Evolving a Cloud-Native BSS/OSS for Telcos
subtitle: Building an Event Streaming Platform on Kafka for Telcos
description: BSS/OSS systems .
image: imagery/3828556.jpg
optimized_image: imagery/3828556.jpg
category: 'Industry'
tags:
  - Telcos
  - BSS
  - OSS
  - Kafka
  - Event Processing
  - Streaming
  - Cloud Native
author: Venkatesh K
---
The traditional BSS/OSS paradigm that sustained in the Telco Industry for decades is now undergoing a radical transformation. BSS comprise of systems for CRM, Order Capture and Billing. Similarly for OSS it encompasses Order Fulfilment, Network Inventory Management and Network Operations.
The landscape was dominated by big vendors who offered “off-the-shelf” solutions that mysteriously needed “customization”. Most Telcos opted for a mix and match of best of breed solutions. The architecture also evolved to include an Enterprise Service Bus to integrate the systems along with ETL jobs to populate an Enterprise Sata warehouse.
![Traditional BSS OSS ](/_site/assets/img/BSSOSS.jpg "Tradiutional BSS OSS Architecture")

All these systems were designed decades ago to deal with Voice only services. They eventually adapted to deal with Data services as well. Growing demands of Digital Customer Experience meant that organizations built custom solutions to cater to these needs on top of BSS layer. The increasing volume of data and need for deeper analysis led to adoption of Big-Data technologies as well. But the underlying architecture remained essentially the same.