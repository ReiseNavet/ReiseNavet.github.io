---
title: "MaaS - Actors"
permalink: /maas/actors/
excerpt: "Actors in MaaS"
last_modified_at: 2023-01-05T11:20:00 +01:00
redirect_from:
  - /actors/
toc: true
---

The MaaS ecosystem and the provision of MaaS services involve several actors. So far, and the literature provides no common definitions of these stakeholders and   operates with different names and different stakeholder definitions. Here we define a set of generic roles that represent stakeholder archetypes with non-overlapping responsibilities. The roles are partly  aligned with ongoing work in ISO, but are more detailed to arrange for modularity and flexibility. Thus the roles and responsibilities can be fulfilled in different ways by different actors in the real world. 

One real actor may have one or more roles, and there may be several actors with the same role. Some examples :
- An actor with the MaaS Provider role may also have the Transport Service Provider role. This is for example the case if a public transport provider is a MaaS provider. 
- Several actors may be MaaS Providers. They may cover different modes, areas, and regions, but the modes and geographical areas they cover may also partly or fully overlap.
- An actor with the MaaS Provider role may also be a MaaS Data integrator. This is the case if the actor collects and integrates data from one or more Transport Service Providers. 
- Several actors may be MaaS Data Integrators, but there may also be just one, e.g. at a national level. 
-	Several actors may be MaaS Facilitators, and they may provide different types of solutions and services to MaaS Providers. A MaaS Facilitator may be a commercial service provider or a national entity providing national services, e.g. a national travel planner.
-	An actor with the MaaS Provider role may also be a MaaS Facilitator if the actor develops its own solutions (travel planner, payment solutions, etc.). 
-	One actor may be both a MaaS Data Integrator and a MaaS Facilitator. Such actors may for example provide one or more generic services based on collected data.

The main roles are defined below.

## Traveller
A Traveller is a person with a mobility demand. Travellers need to travel from one location to another, and they may also have demands regarding the scheduling as well as preferences regarding price, quality, use of modes, etc. 
## Customer
A Customer pays for one or more Travellers' use of MaaS services. 
## MaaS Provider
A MaaS Provider delivers mobility services to Travellers, and should among others
- Package and deliver the transport services provided by Transport Service Providers as one service
- Allow Travellers to seamlessly select, pay for and use different types of transport services, through a single interface
- Offer Travellers an advanced travel experience and remove pain points related to travelling.
## Transport Service Provider
A Transport Service Provider offers its transport capacity to the MaaS ecosystem, and the Travellers may choose to use the transport services they provide.  By transport service we mean all types of transport related services, such as transport with all types of modes as well as services like  parking, and charging.  The modes may for example be all types of public transport, on demand services like taxi, and new modes like micro mobility and car sharing. The Transport Service Providers of all modes should arrange for digital support for booking and payment, and for some modes there is also a need for digital verification of driver licences, keys-less access, digital insurance agreements, etc.
## MaaS Data Integrator
A MaaS Data Integrator does technical integration of data and mediates data offerings from several Data Providers to MaaS Providers and MaaS Facilitators. The data integration must ensure the data quality and that the data are formatted according to standards. The data are provided via well defined (preferably standardised) interfaces. The MaaS Data Integrator may  provide metadata about the data to the National Access points (NAPs) and/or ICT Infrastructure Providers providing Mobility Data Spaces. 
## MaaS Facilitator
A MaaS Facilitator provides services that support, facilitate and ease the establishment and provision of MaaS services. The MaaS Facilitator may provide generic services that can be used by several MaaS Providers, e.g. services supporting travel planning, booking and payment, and electronic business agreements.
The MaaS Facilitator may through the provision of services also generate or collect business related data, e.g. data on searches in travel planners, data on sales of products, data on the journeys accomplished, and data on the use of different transport services. Thus, the MaaS Facilitator may also provide data management services and value-added services to MaaS Providers, Transport Service Providers and Regulators based on these data, e.g. statistics, data on mobility patterns, etc.
The MaaS Facilitator depends on data from among others the MaaS Data Integrator.
## Clearing House
Clearing Houses support the financial clearing between actors involved in the MaaS ecosystem according to well defined settlement terms. The actors may for example be the MaaS Provider and Transport Service Providers.
## Auxiliary Service Provider
Auxiliary Service Providers offer services via the MaaS ecosystem and may have a discount arrangement with the MaaS Provider. An Auxiliary Service Provider may for example provide deliveries from for example libraries, grocery stores, restaurants and coffee shops, and they may offer discounts for events (e.g. for theatres and concerts) as a part of a MaaS product.
## National Access Point (NAP) 
A NAP is a portal facilitating access to open data. This is transport related data as described by the ITS Directive and the Delegated Regulation, as well as other open data. The NAP provides services for the discovery and information about the data as well as information about how the data can be accessed from data pProviders. 
Actors producing data may publish metadata about the data via NAP and provide the data via data repositories. 
## ICT Infrastructure Provider
ICT Infrastructure Providers offer technical infrastructures and services needed in MaaS. This may for example be generic infrastructures and services such as communication infrastructures (e.g. Internet) and backend services (e.g. cloud services), as well as more specific services, for example:
- Mobility Data Spaces. Mobility Data Spaces is a European ICT infrastructure initiative providing access to all types of mobility related data, open data as well as commercial data and data owned by persons and entities and associated services aligned with a data use policy. At the moment, there is no commonly used Mobility Data Spaces in operation. Work on the design and implementation is however ongoing. Services for the discovery of and information about the data and how the data can be accessed from Data Providers will be provided (see above). 
- Verification of driver licences. Transport authorities will provide services where the licences of Travellers can be verified. This is needed by some of the transport services provided via the MaaS service, e.g. car sharing. 
## Payment Provider
Payment Providers enable electronic payment transactions, e.g. when debit and credit cards are used. 
## Insurance Provider
Insurance Providers offer insurance services to Travellers (see 3.1) that choose to use a transport service where they operate shared or rented transport means (cars, city bikes, e-scooters, etc.). The Travellers may be obliged to enter digital insurance agreements via the MaaS interface when such transport services are used. 
## Regulator
There may be several types of regulators. Regulators may be politicians and/or authorities at a local, regional and/or national level defining policies, strategies and goals and related regulations.  Thus, Regulators will impact aspects of importance to MaaS such as for example the data sharing, the ability to re-sell products, priorities, economic issues, etc.
## Authority
Authorities may be at local (city or municipality), regional (e.g. county) or national levels, and they are responsible for the implementation of the policies and strategies defined by the Regulator and also to some extent the enforcement and regulations.  Depending on the governance structure, transport authorities are responsible for public transport and/or other transport services that may need a licence to operate. Local or regional transport authorities may define the premises for public MaaS Providers and/or Transport Service Providers operating in their governance area.
## Business
A Business may be the owner of a private MaaS Provider and may define the premises for the commercial operation.
## Transport Infrastructure Operator
Transport Infrastructure Operators are responsible for the planning, establishment and/or operation of transport infrastructures needed in MaaS, e.g. mobility stations for integration of first/last mile transport services with other transport services (e.g. public transport), parking areas for micro mobility means, and infrastructures for soft modes (e.g. bike lanes and pedestrian areas). Depending on the type of infrastructure (e.g. public or private), Transport Infrastructure Operators may for example be local authorities or residential developers.



