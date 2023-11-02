# Sonderfachgremium Cloud/CMDB
## Special IT Panel on Cloud on the topic of "CMDB" 01.03.2022
Video Conference
Special IT Panel on Cloud on 26.01.2021, 09:30 – 13:30 via Video Conference

## Welcome
The supervisory authority introduces the guests of today's event from the insurance industry (IT Expert Panel) and explains the differences and commonalities between the Expert Panel and the Special IT Panel. Additionally, the other participants briefly introduce themselves to the Expert Panel.

## Discussion of the Focus Topic CMDB in the Context of 8.2 BAIT
A participant from the Cloud Practice Working Group IT/Ops of the IT Roundtable explains the focus topic CMDB (Configuration Management Database) and the associated handling with respect to Cloud Service Providers (CSP) regarding IT operations according to 8.2 BAIT. From a proportionality perspective, there can be different ways to meet the requirements for an inventory of components of the IT systems and their relationships to each other. A CMDB, for example, serves to ensure a documented overview of the building blocks/service elements and their configuration/interaction (CSP/customer) necessary for maintaining or restoring the business process.

In the case of public cloud usage of large hyperscalers, it is always about virtual assets, the location of which is not always known and which, as well as the configuration, possess a certain dynamic. Sometimes changes occur in real-time, therefore their capture in a CMDB of the customer is not fully possible. In practice, the classic sourcing mechanisms are difficult to apply in the cloud environment, therefore the goal is to identify best practices and derive, develop, and establish implementation concepts from them. For this purpose, the operational responsibility in the context of 8.2 BAIT on the part of the CSP and on the part of the customer as well as the interfaces including their documentation must be clarified.

Using a schematic representation of the layered layers in different models of cloud outsourcing, it was discussed how control within the CMDB could take place, taking into account the abstraction layers or their boundaries. This schematic view includes, for example, seven layers (data center, network & storage, physical servers, virtualization, operating system, database, application) and four service models (on-premise, Infrastructure as a Service (IaaS), Platform as a Service (PaaS), Software as a Service (SaaS)). The service models differ in which layers are operated by the customer and which by the CSP. Commonly operated layers form the so-called abstraction boundary. The layers above (below) the abstraction boundary are usually operated exclusively by the customer (CSP). Abstraction layers have different manifestations that can change dynamically. Crucial for risk management is what the customer consumes from the CSP and how he captures this consumption. It should be noted that this is a schematic representation. In practice, it is essential which cloud services are used by the institution. That is, it may be that an institution uses both IaaS and highly functional PaaS or SaaS.

Various selected practical case examples for the mentioned service models are discussed.

## Discussion Results
Regarding IT operations, the requirements of BAIT according to item 8.2 state: "The components of the IT systems and their relationships to each other are to be managed in a suitable manner, and the inventory data recorded for this purpose are to be updated regularly and as required."

From a proportionality perspective, there can be different ways to meet the requirements for an inventory of components of the IT systems and their relationships to each other. A Configuration Management Database (CMDB) of IT operations serves to ensure a documented overview of the elements necessary for maintaining or restoring the business processes of the institute and their configuration as well as interaction.

The goal is to develop a common understanding between institutes and the supervisory authority on the following points:
- Capture of elements and configuration data on the side of the CSP and the customer
- Responsibility for the interfaces including their documentation on the side of the CSP and the customer.

There is agreement that for further discussion, an abstraction using a schematic view of the cloud services (cf. leaflet - guidance on outsourcing to cloud providers) based on seven layers (from bottom to top: data center, network & storage, physical servers, virtualization, operating system, database, application) is purposeful. In addition, a basic distinction according to service and delivery models seems sensible (e.g., on-premise, Infrastructure as a Service, Platform as a Service, Software as a Service).

The service models differ in that the layers for the respective service are operated by the institute and which by the CSP. The services purchased from the CSP form the abstraction boundary in the respective service model and are usually the only element that is included in the institute's configuration management. The layers above (below) the abstraction boundary are usually operated exclusively by the institute (CSP).

There is consensus on the following principles:
1. Above the abstraction boundary, the institute operates the layers. The integration of the services/assets/processes is fully included in the IT operational functions of the institute. Above the abstraction boundary, in particular, a complete mapping and complete documentation within the institute's CMDB is possible and necessary.
2. Below the abstraction boundary, the CSP operates the layers. Components of the CSP are usually not included in the institute's CMDB.
3. At the abstraction boundary (which is the respective cloud service used by the institute), inclusion in the institute's CMDB takes place: The CMDB includes both the parameterizations of the services to be undertaken by the institute using the services and the service descriptions of the CSP. For the service descriptions, corresponding regular updates are made based on agreements between the institute and the CSP (according to the further development of the use of services in terms of type and scope).

This means in particular that at and below the abstraction boundary, agreements between the institute and the CSP must regulate which data are recorded in the institute's CMDB. Above the abstraction boundary, there is a normal process of the company, below this boundary it is the process of the CSP, and at the boundary, it may be necessary to agree and set up new processes. One measure for this can be that an institute has an interface to the CSP's CMDB to be able to retrieve necessary information (e.g., about the actual location of data or accesses to their data by the CSP).

Regarding the abstraction boundary, the supervisory authority points out that institutes may have to examine more closely whether determining the abstraction boundary depending on the usage model is sufficient or needs to be more individual, and that the exact setting of the abstraction boundary cannot be represented in a blanket manner.

## Farewell
An outlook on the next Special IT Panel on 03.05.2022 follows.

## Participants of the Special IT Panel on Cloud on the topic of "CMDB" 01.03.2022
[List of participants]

