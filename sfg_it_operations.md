## Protocol
Special Expert Committee IT on the topic "Cloud/IT Operations"
December 13, 2022, 10:00 – 12:00
May 31, 2023, 10:00 – 12:00
via video conference

### Preamble

In the present protocol, the main aspects of the discussion as well as the results from two dates of the Special Expert Committee IT on the topic "Cloud/IT Operations" are summarized. Subsequently, the processes and procedures that are usually assigned to the IT operations units and are dealt with in Chapter 8 of the BAIT / VAIT are considered.

Among the participants of the Special Expert Committee, there is a consensus that future practical experiences or changing regulatory conditions (e.g., DORA) may require an adjustment of the discussion results. Precisely for this reason, the discussion results do not represent a concluded implementation guide for supervised companies. Rather, a framework should be created, the elements of which must be fleshed out, agreed upon, implemented, and regularly evaluated by the supervised companies with the cloud providers.

### Supervisory Requirements for IT Operations

The supervisory requirements for IT operations are derived for banks primarily from the EBA guidelines for the management of ICT and security risks (esp. Section 3.3), as well as the guidelines on outsourcing, the MaRisk (esp. AT 7.2 Tz. 1 - 5), and the BAIT (esp. Chapter 8 in conjunction with Chapter 2). For the insurance industry, the requirements are derived from the EIOPA guidelines on outsourcing to cloud providers and the guidelines on security and governance in the area of information and communication technology, the minimum requirements for the business organization of insurance companies (MaGo, MaGo for EbAV, MaGo for small insurance companies), as well as the VAIT.

Subsequently – especially along the lines of the BAIT/VAIT – the focus is on the following processes:

- Process for the management of changes (8.4 and 8.5 BAIT / VAIT),
- Disturbance and problem handling (8.6 BAIT / VAIT),
- Data backup concepts (8.7 BAIT / VAIT),
- Lifecycle management of IT components (8.3 BAIT / VAIT), and
- Capacity management (8.8 BAIT / VAIT).

### Problem Statement of the Supervised Companies

Also, in the area of IT operations, an important challenge is that the provision of cloud services by the cloud provider is characterized by an abstraction boundary[^1]. The abstraction boundary runs differently according to the specific cloud service used, depending on the commissioned service model (e.g., SaaS, PaaS, IaaS) and the type of use by the supervised company. Thus, the abstraction boundary represents the boundary of responsibility between supervised companies and the cloud provider. With respect to IT operations – according to this distribution of responsibilities – below the abstraction boundary, the processes and procedures of the cloud provider are fundamentally relevant, above the abstraction boundary, those of the respective supervised company.



To ensure safe and stable IT operations and appropriate detection and control of IT risks, the interface between the cloud provider and the supervised company must be appropriately designed across the abstraction boundary. The following cloud-specific challenges arise in particular:

- Limited detailed information on the concrete design of the cloud services, e.g., related to architecture or specific IT components used.
- Usually, no provision of customer-specific reporting documents by the service provider, instead, independent information procurement by the supervised company on a fetch principle via configurable dashboards/information platforms, sometimes with limited data basis, e.g., when displaying platform-wide failures or service restrictions via Availability Dashboards.
- Usually, no influence on the internal process design of the cloud provider in IT operations.
- The service portfolio of a cloud provider is usually globally oriented – this can mean that not all services are available in all regions.

However, the responsibility for the cloud outsourcing remains with the supervised company, regardless of the distribution of responsibilities. Thus, the questions arise in particular (i) whether the IT operations processes at the cloud provider meet the supervisory and own requirements and (ii) how the appropriate linkage between the two spheres of responsibility can be ensured by the supervised company.

### Discussion Results

The appropriateness of the IT operational processes of cloud providers must be assessed in connection with the service and provider management by the supervised company. Cloud providers typically offer a Service Level Agreement (SLA) as a quality assurance for the provided services, in which the quality of service is described and contractually guaranteed. In this context, solutions were developed in past special expert committees, especially in the Special Expert Committee Cloud on the topic of "Certificates" on 07.10.2021[^2], which are also applicable in the context of IT operations.

When using the cloud, information for the customer is usually not individually prepared and sent by the service provider. As a rule, there is a provision of information by the cloud provider that the supervised company must specifically retrieve ("fetch principle"). Instead of direct communication from the cloud provider about relevant changes in the services, for example, about incidents or changes to the service descriptions, there is client-neutral communication on the platform of the cloud provider. This requires additional or adapted IT operational processes on the part of the supervised company. Therefore, regarding the linkage between the spheres of responsibility, an appropriate integration into the IT operational processes of the supervised company is necessary through sufficient information transfer and the suitable configuration of the cloud services. In particular, this involves:

- A sufficient understanding of the used cloud services, including the relevant underlying procedures, IT systems, IT components, and interfaces of the cloud provider,
- Independent procurement of information/data from the cloud provider to enable the supervised company to carry out the IT operational processes in its own area of responsibility ("above the abstraction boundary"), and
- Implementation of a suitable configuration of the cloud services related to the specific cloud usage by the supervised company.

In principle, the supervised company must determine which information is relevant for the operation of the services, which of this information is provided by the cloud provider, what residual risks arise from a lack of transparency, and what mitigation or risk treatment strategies need to be implemented. The following points are to be understood as possible solution outlines and do not constitute a universally valid implementation guide.

#### Description and Monitoring of Service Quality

1. Contractual arrangements form the basis for control by the supervised companies. A description of the quality of service by the cloud provider is required for the used services.[^3]

2. For appropriate control of the services, the supervised company must compare its own specifications with the contractually assured quality of service. For deviations from the specifications, the supervised company must conduct a risk analysis and check whether the services can be used against this background with the descriptions of service quality (e.g., SLAs) offered by the cloud provider. The supervised company can take additional information, e.g., in dialogue with the cloud provider, to improve the assessment of the services.

#### Risk Management

3. Depending on the risk content of the IT system, an analysis of the inherent risks of the services provided by the cloud provider must be carried out before using the cloud service, whereby use is only permissible if the resulting risks are bearable. The risk analysis must be validated regularly.

4. According to the risk content of the outsourced matter and the used services, the establishment of a service and provider management for controlling the cloud provider must be designed, at least by conducting regular meetings between the supervised company and cloud provider across various organizational levels for information procurement of the used services.

#### Information Procurement and Processing

5. Information on the lifecycle (changes or shutdown) of used services is matched with one's own planning to be able to react in time to changes.

6. To be able to process the information provided by the cloud provider, the supervised company must get an overview of the information offer and the used communication channels. This includes recording the information relevant for controlling the services and the associated communication channels through which the cloud provider informs, for example, about changes to its services. Depending on the relevance and frequency of change, different approaches to implementing the fetch principle can be used:

   a. For short-term relevant information, e.g., the incident dashboard of the hyperscaler, processes and applications of IT operations ensure that information is evaluated and processed promptly (e.g., email notification and assessment in the case of a service restriction shown on the Availability Dashboard). Integration of a corresponding monitoring process into the processes of the supervised company is necessary with the dashboards provided by cloud providers, e.g., definition and setting up of triggers, alarms, etc.

   b. For medium- to long-term relevant information, e.g., changes in the Service Terms or APIs, announced changes must be regularly reviewed and assessed for any impact on the used services and corresponding measures derived.[^4]

#### Adjustment of the Configuration of Cloud Services

7. Recommendations of the cloud provider (e.g., sizing) should be regularly reviewed, and the allocated services adjusted according to one's own specifications, taking into account the recommendations of the cloud providers.

8. Requirements for the location of data backups are based on the concepts for regions and zones provided by cloud providers. In principle, it is up to the supervised company, if it uses the cloud provider's data backup services, to continuously monitor and regularly test the successful implementation of data backup orders, e.g., through log analyses or dashboards.

9. The supervised company can configure aspects of capacity planning in the corresponding service commissioning with the cloud provider, provided that the service configuration allows it.

[^1]: See protocol of the Special Expert Committee Cloud on the topic "CMDB": [Link to document](https://www.bafin.de/SharedDocs/Downloads/DE/Protokoll/dl_01032022_Protokoll_Sonderfachgremium_IT.pdf)

[^2]: See protocol of the Special Expert Committee Cloud on the topic "Certificates": [Link to document](https://www.bafin.de/SharedDocs/Downloads/DE/Protokoll/dl_07102021_Protokoll_Sonderfachgremium.pdf?__blob=publicationFile&v=1)

[^3]: According to MaRisk, banks must specify in the outsourcing contract agreed in text form, among other things, the service to be provided by the cloud provider and, if necessary, define it, and the quality of service must be agreed with clearly defined performance targets (AT 9 Tz. 7 MaRisk). From January 17, 2025, the DORA regulation (Article 64 DORA) applies. According to Article 30 (2) lit e, (3) lit a DORA, the contractual agreements on the use of ICT services include, among other things, descriptions of the quality of service.

[^4]: From January 17, 2025, the DORA regulation (Article 64 DORA) applies. According to Article 30 (2) lit e, (3) lit a DORA, the contractual agreements on the use of ICT services include, among other things, descriptions of the quality of service.

