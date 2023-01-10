---
title: "MaaS Integration - Data Integration"
permalink: /maas/dataintegration/
excerpt: "Data Integration in MaaS"
last_modified_at: 2022-12-16T11:00:00 +01:00
redirect_from:
  - /dataintegration/
toc: true
---

MaaS requires the integration of data from a multitude of sources. Different data formats and  data exchange standards are in use, contributing to syntactic and semantic heterogeneity which makes integration tasks complex and resource-demanding. 

ReiseNavet develops tools based on semantic technology to support data integration in a MaaS setting. Two ontologies have been developed in the project. Both ontologies are available as OWL files on [GitHub](https://github.com/ReiseNavet/MaaSOntology). The maas-ontology is developed on the basis of a set of use case scenarios. The scenarios are split into a basic MaaS scenario and extended MaaS scenario. The basic MaaS scenarios describes the fundamental functions of MaaS mobility, while the extended MaaS scenarios describes how for example the use of open and linked data can enhance basic functionality and create innovative MaaS services. The second ontology is transmodel-onto. This is a shallow OWL ontology transformed from an UML model of [Transmodel](https://www.transmodel-cen.eu/) version 6, including the new modes extension as described in CEN TS 17413:2019. 

In collaboration with a group of students from the Norwegian University of Science and Technology (NTNU) ReiseNavet has developed a prototype [data integration tool](https://github.com/ReiseNavet/data-integration-tool) that automatically identifies mappings between different data formats.

