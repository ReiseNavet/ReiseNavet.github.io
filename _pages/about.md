---
permalink: /about/
title: "About ReiseNavet"
---

ReiseNavet is an innovation project funded by the [Transport 2025](https://www.forskningsradet.no/en/about-the-research-council/programmes/transport/) program of the [Norwegian Research Council](https://www.forskningsradet.no/en/). The project started June 1st 2019 and will end May 31st 2022.

The topic of ReiseNavet is Mobility as a Service (MaaS). MaaS offers digital support to door-to-door journeys via one single interface. Different transport services can be combined, and there is only one payment. It should be possible to buy both "pay-as-you-go" tickets and mobility packages that combine different transport services. The intention is to facilitate and encourage a change in behaviour towards more sustainable mobility and to reduce the need for private car ownership.

The project partners are [Entur](https://om.entur.no/bedrift/om-entur/), [SINTEF](https://www.sintef.no/en/), [Ruter](https://ruter.no/en/about-ruter/about-us/), [Kolombus](https://www.kolumbus.no/en/about-kolumbus/about-the-company/), [Hertz](https://www.hertz.no/rentacar/reservation/), [Hyre](https://www.hyre.no/) and [Urban Sharing](https://urbansharing.com/).

## Objective

The main objective of ReiseNavet is to provide knowledge on how a nationwide and digital MaaS platform efficiently and flexibly can support the realisation of MaaS. The project will explore possible platform capabilities regarding data integration and supporting services to MaaS providers and transport operators. 

Date integration for "all modes" (public transport, city bikes, taxis, car sharing, car rental, etc. ) will be supported. By using the platform, MaaS providers can avoid demanding digital integration with transport operators and focus on the end user support (Apps for travel planning and assistance, mobility package designs, price models, ticketing, etc.). By sharing their data with the platform, transport operators can more easily be integrated in several MaaS-services. The platform will publish the data as open data that can be used as a basis for novel services.

Services supporting the interaction between MaaS providers and transport operators will be addressed. Such services may simplify the establishment of MaaS. The role of the platform will be investigated, among others how a semantic model for MaaS can support the definition of mobility packages, as well as route planning and orchestration of door-to-door journey, and associated bookings.Project activities and results (links to wiki when relevant) 

## Research activities and results

### Systematic Mapping Study (SMS) on MaaS

SINTEF has performed a SMS targeting the scientific literature on MaaS. The study has identified the MaaS topics of relevance and related publications, as well as the research strategies used and the contributions made. Based on these findings, research gaps are identified. 

The main identified topics related to MaaS are:
*	User aspects - the users of MaaS, who they are, their relation to MaaS, their wishes and needs, and the effects of MaaS on these users.
*	Societal aspects - how MaaS is affected by and affects aspects such as transport and traffic, environment, economy, policy, etc.
*	MaaS functionality - functionality supporting the MaaS users and promoting desired user behaviour, as well as functionality facilitating good service quality, business models, and learning.
*	MaaS integration - the integration of systems and data into the MaaS ecosystem.
*	MaaS implementation – aspects such as the MaaS ecosystem with actors and systems, the implementation process, barriers, enablers, the role of regulation, etc.
*	Business aspects - market and business modelsas well as contractual issues.
*	Technology aspects – technology areas of relevance to the implementation of MaaS ecosystems.
*	Privacy and security aspects - security and privacy issues related to MaaS and MaaS reliability.

Status: A scientific publication will document the results of the study.

### MaaS Wiki

The Wiki provides an overview of aspects of relevance to MaaS and lessons learned based on literature studies and interviews with stakeholders in the MaaS ecosystem. The Wiki can be found [here](https://reisenavet.no/maas/intro/).

### Semantic modelling

SINTEF has defined a methodology to be used for the establishment of a semantic model for MaaS. The methodology is intended to be agile and easy to apply, and builds on existing methodologies from the ontology engineering area, such as Methontology, NeOn, Upon and 101. 
Existing ontologies of relevance to MaaS are identified, among others the ontologies from the European SNAP project (building on Transmodel) and from DATEXII (on traffic information). These ontologies are used as a starting point for the MaaS semantic model which contains:
*	MaaS usage patterns (used as a basis for the concepts). 
*	Concepts related to car sharing, micro mobility, on-demand transport, etc. harmonised with CEN TS 17413 (a Transmodel extension)
*   Additional concepts that enables MaaS to be integrated with data from other domains in order to yield enhanced functionality (e.g., traffic management, smart cities)
Status: The results are used as input the work on the data integration tool and the MaaS ecosystem architecture. 

Status: The Wiki is continuously updated.

### Data integration 

The integration of data on transport services will be done by means of common data formats, and the project also investigates how semantic tools can support the transformation of data to these formats:
*	Relevant data formats are identified. Several of them build upon standards such as Transmodel, NeTEx, and SIRI. Partner Entur has defined new formats for micro mobility and on-demand transport; extended the NeTEx format to cover new data types of relevance to MaaS such as parking and charging, prices and products; and defined APIs for on-demand transport. Entur has also contributed to a new standard for data on micro mobility (CEN TS 17413 – an extension of Transmodel). In addition, other formats are in use and are emerging within a MaaS setting, such as GTFS (including GTFS-Flex), GBFS, IXSI, and MDS. 
* A web-based tool for data integration is prototyped by a group of NTNU students (supervised by SINTEF). The tool automatically generates different semantic relations (mappings) between data elements of different data formats. This tool aims to simplify and semi-automate the task of mapping data elements from one data format to another data format. The prototype data integration tool is available [here](http://dataintegrasjon.reisenavet.no/). 

Status: The results mentioned above is input to new activities on data integration and to the work on the architecture. 

### MaaS ecosystem architecture
SINTEF defines a reference architecture for the MaaS ecosystem. The architecture is designed according to the [ARCADE methodology](http://arcade-framework.org/) and different diagrams provide relevant views upon the MaaS ecosystem.

Motivation diagrams address the relevant stakeholder types (traveller, MaaS provider, transport operator, and integrator) and identify: 
*	Their drivers for their participation in the MaaS ecosystem, i.e., what may make such a change towards MaaS attractive to them.
*	An assessment of the current situation with respect to the drivers, i.e. barriers encountered.
*	Goals to be met to overcome the barriers.
*	Overall requirements to the MaaS solutions derived from the goals. 

Use case diagrams define:
*	The functionality needed by the stakeholders, taking the motivation models into account. 
*	The use of the semantic model during the establishment and operation of MaaS.

Other models will also be used to define
*	The information content to be exchanged and the interfaces through which the information is exchanged. Existing standards and specifications will be re-used when this is appropriate.
*	The processes related to MaaS establishment and operation. 
*	Logical system components/services.

Status: The first versions of the motivation diagrams are ready. Work on the use cases is ongoing.

