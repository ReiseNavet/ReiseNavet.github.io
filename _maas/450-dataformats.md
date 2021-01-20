---
title: "MaaS Integration - Data Formats and Standards"
permalink: /maas/dataformats/
excerpt: "Data formats and standards in MaaS"
last_modified_at: 2020-01-15T11:00:00 +01:00
redirect_from:
  - /dataformats/
toc: true
---

Standardised data formats are important for interoperable MaaS solutions. [Network Timetable Exchange (NeTEx)](http://netex-cen.eu/) is a CEN Technical Standard for exchanging schedules and related data for public transport. The [Standard Interface for Real-time Information (SIRI)](http://www.transmodel-cen.eu/standards/siri/) is a CEN Technical Standard for describing real-time information related to public transport operations. Both these standards originate from [Transmodel](http://www.transmodel-cen.eu/), a conceptual reference model describing common public transport concepts and associated data structures. Relevant to MaaS is a recently released extension of Transmodel that describes new transport modes. [CEN/TS 17413](https://standards.cen.eu/dyn/www/f?p=204:110:0::::FSP_PROJECT,FSP_ORG_ID:67003,6259&cs=14977329111ED8832B40505A38640848E) provides provides a data model for describing how new transport modes and services such as carsharing, carpooling, and rental services (car, bike and scooter) can be integrated into urban and multimodal travel services. 

The [General Transit Feed Specification (GTFS)](https://gtfs.org/) is an alternative data format for exchanging public transport data. GTFS is split into a static component for exchanging static transport data (schedules, fares, etc.) and a real-time component for exchanging data such as arrival/departure predictions and vehicle positions. In addition, a proposed extension to GTFS for flexible on-demand transport is being developed. [GTFS-Flex](https://github.com/MobilityData/gtfs-flex) adds the possibility to model services related to demand-responsive transportation to GTFS. [GBFS (General Bikeshare Feed Specification)](https://github.com/NABSA/gbfs) is an open standard for shared mobility with an emphasis on describing the availability of bikes (and the like) at bike stations. 