# Supervisory Communication on Outsourcing to Cloud Providers
Updated February 2024
**COURTESY TRANSLATION**

## I. Introduction

In recent years, the topic of outsourcing to cloud providers in the financial sector has steadily gained relevance. Accordingly, the German Federal Financial Supervisory Authority (BaFin) and the Deutsche Bundesbank have increasingly engaged in discussions with supervised companies about outsourcing to cloud providers in the last few years. At the same time, the German regulatory authority has also entered into dialogue with various cloud providers. The focus of these discussions was initially on the design of (standard) contracts or contractual supplemental agreements, which are also intended to fulfill and regulate the regulatory requirements, e.g., information and audit rights of the supervised companies or the regulator. Furthermore, in the discussions between cloud providers, cloud users, and the regulator, specific challenges in the use of cloud services were addressed, for example, regarding further outsourcing, cloud operations, use of third-party audit results, aspects of IT operations, and the representation of cloud services in the configuration management database (hereinafter referred to as CMDB). [^1]

In exchange with the regulator, supervised companies have described challenges in the application practice of regulatory requirements, particularly when using leading cloud providers. From the perspective of the supervised companies, the core characteristics of cloud providers, especially the high degree of standardization and virtualization, the global availability, and high scalability of a technologically very innovative service offering, as well as the high concentration on a few cloud providers from third countries, present both opportunities and risks. On one hand, cloud providers usually make current, market-leading technological innovations available to all customers. Moreover, there is a high level of security. On the other hand, the supervised companies report operational difficulties in the auditability of the cloud provider to demonstrate the adequate and effective implementation of security and compliance requirements. Furthermore, a low flexibility of cloud providers due to the high standardization of the service offering and the service delivery processes has been observed. This means that the service offering and the manner of service delivery can hardly be influenced by individual supervised companies. Also, individual agreements in contract design are not or only to a limited extent possible.

Similarly, compared to established providers in the financial sector, the high frequency of adjustments in the service offering of cloud providers has implications for internal processes.

Regulatory requirements have also evolved in recent years. The Financial Market Integrity Strengthening Act introduced, among other things, an obligation to report (significant) outsourcing and to maintain an internal outsourcing register in the Banking Act (KWG), Payment Services Supervision Act (ZAG), Securities Institutions Act (WpIG), and Investment Code (KAGB), which also include specific inquiries regarding outsourcing to cloud providers. The specific details on the notification requirement are regulated in notification ordinances published on the BaFin website.

Also, at the European level, the topic continues to be in regulatory focus. A steady exchange on handling outsourcing to cloud providers has developed at the level of EIOPA, ESMA, and EBA, within the SSM, but also bilaterally between national regulatory authorities. The result of this exchange are the EBA Guidelines on Outsourcing (EBA/GL/2019/02 of 25 February 2019), the EIOPA Guidelines on Outsourcing to Cloud Providers (EIOPA-BoS-20-002 of 6 February 2020), and the ESMA Guidelines on Outsourcing to Cloud Providers (ESMA50-164-4285 of 10 May 2021).

This supervisory communication is to be understood as guidance in which BaFin and the Deutsche Bundesbank share their joint assessment of outsourcing to cloud providers. However, it does not set new requirements but reflects the current regulatory assessment in such outsourcing cases. The supervisory communication aims to make the regulatory evaluation of various formulations in contract clauses transparent and to provide guidance on monitoring and controlling cloud outsourcing and the requirements to be ensured by the supervised companies. Furthermore, the supervisory communication gives an outlook on the requirements for contractual agreements on the use of Information and Communication Technologies (ICT) between supervised companies and ICT third-party service providers, which are regulated in the Regulation of the European Parliament and of the Council on digital operational resilience for the financial sector (Digital Operational Resilience Act – DORA). DORA came into force on 16 January 2023 and will apply directly from 17 January 2025.

The German regulator is not aware of all types of cloud outsourcing or all (standard) contracts or contractual supplemental agreements, so the supervisory communication does not claim to be exhaustive.

The supervisory communication is addressed to supervised companies in the financial sector (including credit institutions, financial service institutions, insurance companies, institutions for occupational retirement provision, pension funds, securities institutions, other securities service companies, capital management companies, payment institutions, and e-money institutions). The following explanations should therefore be read in the context of the applicable regulatory requirements.

Due to the nature of the supervisory communication, "should" formulations are deliberately used. This does not lead to a weakening of the existing regulatory requirements; the requirements for outsourcing and IT remain unaffected. The principle of proportionality applicable to these requirements also applies to the guidance formulated in this supervisory communication. Outsourcing must not lead to a transfer of responsibility from the management of the supervised company for the outsourced matters to the cloud provider. The supervised company remains responsible for complying with the legal provisions it is subject to when outsourcing.

[^1]: For more information, refer to the protocols published at: [BaFin's IT Committee page](https://www.bafin.de/DE/Aufsicht/BankenFinanzdienstleister/Fachgremien/IT/informationstechnologie_node.html) or [Bundesbank's IT Committee page](https://www.bundesbank.de/de/aufgaben/bankenaufsicht/einzelaspekte/fachgremien/fachgremium-informationstechnologie-598056)

> Outlook on DORA
> 
> **Digital Operational Resilience Act**
>
> In the future, Regulation (EU) 2022/2554 of the European Parliament and of the Council on digital operational resilience in the financial sector (Digital Operational Resilience Act – DORA) will, as part of the information and communication technology (ICT) third-party risk management, establish concrete requirements for contractual agreements on the use of ICT services between financial companies (see Art. 2(2) DORA) and ICT third-party service providers, and regulate these requirements across sectors. DORA entered into force on January 16, 2023, and will be directly applicable from January 17, 2025. In addition to regulations on ICT third-party risk management, DORA will particularly include regulations in the areas of ICT governance and risk management, testing of digital operational resilience, reporting mechanisms for significant ICT incidents, and regarding a European supervisory framework for critical ICT third-party service providers. The provisions made in DORA will precede or supplement existing regulations as lex specialis.
>
> DORA contains several bases for the adoption of delegated acts, Regulatory Technical Standards (RTS), Implementing Technical Standards (ITS), guidelines, and reports to supplement the principles and provisions set out in DORA, from which detailed requirements will emerge.
>
> In preparation for DORA, it is advisable to consider the new additional provisions by DORA when modifying business processes and negotiating new contracts for outsourcing to the cloud.

## II. Explanations

The term "outsourcing" in this supervisory communication refers to "outsourcing" in the sense of § 25b of the Banking Act (KWG), § 40 of the Securities Institutions Act (WpIG), § 80 of the Securities Trading Act (WpHG), § 26 of the Payment Services Supervision Act (ZAG), and § 36 of the Investment Code (KAGB) and "divestitures" in the sense of Article 274 of the Delegated Regulation (EU) 2015/35 as well as § 32 of the Insurance Supervision Act (VAG). The term "sub-outsourcing" is used analogously.

Furthermore, the term "material" is used for the terms "important/critical" in the sense of Article 274 of the Delegated Regulation (EU) 2015/35 and § 32 VAG as well as for the term "material" in the sense of § 25b KWG, § 26 ZAG, and § 40 WpIG.

The term "matters" is used collectively for "activities and processes" in the sense of § 25b KWG, § 26 ZAG, or "important functions/insurance activities" in the sense of Article 274 of the Delegated Regulation (EU) 2015/35 and § 32 VAG, as well as "tasks" in the sense of § 36 KAGB.

The terms "cloud environment" and "cloud application" are used in this supervisory communication as follows: Cloud environments are tenant-capable resources provided by cloud providers and largely configurable by the supervised company, in which individual cloud services of the cloud provider can be utilized. Cloud applications refer to application programs that are based on the cloud services provided by cloud providers but are outside the operational responsibility of the cloud provider.

"Cloud services" are services delivered using cloud computing, i.e., a model that enables ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources (such as networks, servers, storage, applications, and services) that can be rapidly provisioned and released with minimal management effort or service provider interaction.[^2]

Cloud services are typically provided as the following service models:
- Infrastructure as a Service (IaaS, providing computing power and storage space),
- Platform as a Service (PaaS, providing development platforms), or
- Software as a Service (SaaS, providing software applications/web applications).

These service models differ in terms of the organizational or technical control possibilities of the user. With IaaS, the user has full control over the IT system from the operating system upwards (i.e., control of the physical environment always lies with the provider), as everything within his area of responsibility is operated, with PaaS, the user only retains control over his applications that run on the platform, and with SaaS, the user essentially hands over all control to the cloud provider.[^3] Thus, the higher the complexity of the service model, the generally lower the user's control possibilities in the cloud. However, the loss of control by the supervised company does not alter its regulatory responsibility regarding compliance with legal provisions. In practice, four deployment models of cloud services are distinguished[^4]:

- **Private Cloud:** Cloud infrastructure that can be exclusively used by a single company.
- **Community Cloud:** Cloud infrastructure that can be exclusively used by a specific community of companies, including several supervised companies of a single group.
- **Public Cloud:** Cloud infrastructure that can be freely used by the public.
- **Hybrid Cloud:** Cloud infrastructure that consists of two or more distinct cloud infrastructures.

Depending on the chosen service model, there is a division of labor between the supervised company and the cloud provider regarding responsibility for the operation of the cloud. Depending on the chosen cloud service and service model, the demarcation of responsibilities lies at different points in the abstract layer model (so-called abstraction boundary).[^5]


[^2]: EBA/GL/2019/02, Tz. 12 (Begriffsbestimmungen).
[^3]: Vgl. https://www.bsi.bund.de/dok/6622124
[^4]: EBA/GL/2019/02, Tz. 12 (Begriffsbestimmungen).
[^5]: Siehe dazu auch Kapitel V.1

The following explanations apply regardless of the chosen service or deployment model:

> Outlook on DORA
> 
> **ICT Services**
> 
> DORA defines the term of ICT service in Article 3(21) as digital services and data services that are permanently provided to one or more internal or external users via ICT systems. Under DORA, the distinction between "outsourcing" and "other external procurement (of IT services)" is no longer made.
> 
> **Critical or important function**
> 
> DORA contains special provisions for the use of ICT services to support "critical or important functions" as defined in Article 3(22). These are functions,
> - whose failure would significantly impair the financial capability, solidity, or continuation of business activities and services, or
> - whose interrupted, defective, or failed performance would significantly impair the ongoing compliance with the licensing conditions and obligations of a financial company or its other obligations under the applicable financial services law.
> 
> In preparation for DORA, it is advisable to more heavily weigh the impact of ICT services on the financial capability, solidity, or continuation of business activities and services, as well as the ongoing compliance with the licensing conditions and obligations of the financial company or its other obligations under the applicable financial services legislation in the risk analysis.

## III. Preparatory Actions and Governance Framework for Cloud

### 1. Strategic Considerations
The supervised company should reflect considerations for using cloud services in its (IT) strategy. Besides, it should develop and document a process that covers all steps relevant to outsourcing to the cloud provider, from strategy through migration into the cloud to the exit strategy. It is important that the supervised company first checks all relevant internal processes to see if they are "ready for the cloud" before undertaking such outsourcing. In addition to the matters to be outsourced, the risk management and control processes of the supervised company should be considered above all.

### 2. Analysis and Materiality Assessment
After the strategic decision for third-party procurement of matters from a cloud provider, at the beginning of the process, the supervised company should check, based on the applicable regulatory requirements, whether an outsourcing exists and whether it is to be classified as material.[^6] In general, the conditions for outsourcing are met. The risk analysis should consider all aspects relevant to the supervised company in connection with outsourcing to cloud providers, with the intensity of the analysis depending on the nature, scope, complexity, and risk content of the outsourced matters. The supervised company should evaluate and document, based on the risk analysis, what risks are associated with an outsourcing and whether it constitutes a material outsourcing. If there are regulatory requirements for materiality, these must be observed.

In the context of the **risk analysis**, the following should generally be considered:
- the design of the used cloud service,
- the impact of inadequate service quality (solidity or continuation of business activities),
- the criticality of the matter to be outsourced, i.e., an assessment of whether the matter is critical for the business continuity of the supervised company,
- an assessment of the risks arising from the chosen service and deployment model,
- an assessment of the financial, operational (e.g., system failure, sabotage) risks, including legal risks (e.g., enforcement risks, data protection risks) as well as reputation risks and risks that can affect financial capability,
- an assessment of the suitability of the cloud provider (capabilities, infrastructure, economic situation, corporate and regulatory status, etc.); where appropriate, evidence/certificates based on common standards (e.g., International Security Standard ISO/IEC 2700X of the International Organization for Standardization, C 5 requirements catalog of the Federal Office for Information Security), audit reports of recognized third parties or internal audit reports of the cloud provider can be used,
- an assessment of concentration risks, including the risks in the case of outsourcing several matters to one cloud provider,
- an assessment of the risks in case of non-compliance with regulatory and settlement legal requirements (ongoing compliance with the licensing conditions and obligations of the financial company or its other obligations under the applicable financial services law, ensuring data availability incl. access) and an assessment of the risks associated with supervisory restrictions in the countries where the matters are provided or the data is stored or processed,
- an assessment of the location where data is stored or processed, the location of the cloud provider's corporate headquarters, the geopolitical situation (general stability of politics and security), and the applicable laws (including data protection laws) in the relevant jurisdictions, as well as the enforcement regulations applicable in these jurisdictions, including insolvency regulations in case of the cloud provider's failure,
- an assessment of the risks to the integrity, availability, confidentiality, and authenticity of the matters as well as the processed or stored data, taking into account
  - possible access to data by other jurisdictions,
  - risks due to different interfaces between own and third-party systems,
  - risks due to extraordinary, also unintentional and unexpected contract termination e.g., data loss, limited portability of data to a new service provider,
- an assessment of the risks from further outsourcing by the cloud provider.

In the event of becoming aware of significant defects or significant changes in outsourcing, it should be noted that this can have an impact on the risk situation of the outsourcing and thus of the outsourcing company. In these cases, the risk analysis should be reviewed or re-conducted, regardless of the regular cycle, and if necessary, the outsourcing to the cloud provider should be reversed or initiated to an alternative provider.

[^6]: This approach should be taken if it is stipulated in the respective regulatory requirements. An exception, for example, are the non-differentiated outsourcings according to KAGB.

### 3. Internal Guidelines for the Use of the Cloud
The supervised company should supplement suitable guidelines in its written order for the use of the cloud, both in terms of the development of cloud applications and for operation. Where sensible, a distinction should be made between general requirements for all applications and providers and specific regulations related to the peculiarities of the individual cloud providers and their cloud services.

Regarding the general requirements, the supervised company should formulate appropriate guidelines that are consistent with the (IT) strategy of the supervised company and its policies and guidelines on information security and IT. Provider and service-specific regulations should be derived based on the risk analysis, advice from cloud providers, own measures for risk reduction, and further insights. Inconsistencies with the general requirements should be avoided. In particular, risk-based guidelines for the use of the cloud should be made depending on the data protection requirements and the location of storage and processing.

The guidelines for the use of the cloud should cover at least the topics of cloud compliance, identity and rights management, encryption and key management, development and operation, hardening of applications, interfaces and environments, control of subcontractors, and IT emergency management, in accordance with the relevant circulars.[^7]

[^7]: Circular 05/2023 (BA) - Minimum Requirements for Risk Management (MaRisk) dated 29.06.2023; Circular 10/2017 (BA) as of 16.08.2021 - Supervisory Requirements for IT in Banking (BAIT); Circular 11/2021 (BA) as of 16.08.2021 - Supervisory Requirements for IT of Payment and E-Money Institutions (ZAIT); Circular 10/2018 (VA) as of 03.03.2022 - Supervisory Requirements for IT in Insurance (VAIT); Circular 11/2019 (WA) - Capital Management Supervisory Requirements for IT (KAIT) dated 01.10.2019.


### 4. Resource Allocation and Qualification
Supervised companies should provide and organizationally anchor sufficient quantitative and qualitative resources for the use of the cloud (personnel, financial, and other resources). This particularly affects governance, risk management, and outsourcing management. The monitoring, control, and audit of cloud outsourcing as well as the development, operation, and security of cloud applications and cloud environments should be adequately considered.

Persons tasked with responsibilities in the cloud environment should have appropriate and relevant competencies and knowledge about the functioning of the cloud, the associated risks, and the technical and organizational specifics associated with cloud operation. 

The extent of the necessary knowledge depends on the tasks to be performed by the person. The more technical the tasks, the more specific the knowledge about the cloud provider and the cloud services should be. The necessary knowledge can be demonstrated through training certificates, participation in relevant further education measures, or relevant practical experience.

### 5. Contract Design for (Material) Outsourcing
Depending on the regulatory requirements, the following contents should be agreed upon in the outsourcing contract for material outsourcings or for the non-differentiated outsourcings according to KAGB.

>Outlook on DORA
>
>**Mandatory Contract Provisions for All ICT Services**
>
>Articles 28(7) and 30 of DORA establish minimum requirements for the design of contractual agreements on the use of ICT services between financial companies and ICT third-party service providers. Considering these requirements is also sensible in contract negotiations and arrangements before DORA comes into effect. DORA includes general principles and mandatory contract provisions for contractual agreements on the use of ICT services. For ICT services supporting critical or important functions, additional minimum requirements apply.

#### 5.1 Scope of Services
The contract should specify and, if necessary, delineate the services to be provided by the cloud provider. The following should generally be determined:
- the matter to be outsourced and its implementation (e.g., type of service and deployment model, scope of services offered such as computing power or available storage space, availability requirements, response times),
- customization options for the service in case of a change in needs during the contract term, e.g., the addition of extra security measures if the protection requirement changes or an adjustment of the service level promised by the provider to the demand notifications from performance and capacity management
- Support services,
- Responsibilities, cooperation, and provision obligations (e.g., for updates),
- Location of service provision, data processing, and data storage (e.g., locations of data centers),
- Start and possibly end of the outsourcing contract,
- Metrics for ongoing review of service quality, where possible, quantitative metrics should be used, and
- Indicators for identifying unacceptable service quality, e.g., related to non-availability and data loss.
These aspects can be specifically tailored for the used cloud services.

>Outlook on DORA
>
>**Description of All Functions and ICT Services**
>
>According to Article 30(2)(a) of DORA, financial companies and ICT third-party service providers are obliged to agree on a clear and complete description of all functions and ICT services as a contractual element. This applies regardless of whether the ICT services support critical or important functions.

#### 5.2 Information and Audit Rights of the Supervised Company
The information and audit rights as well as control possibilities of the supervised company must not be contractually restricted. It must be ensured that the supervised company receives timely the information it needs for the appropriate management and monitoring of the risks associated with the outsourcing. This information should generally be retained by the supervised company for at least five years.

To ensure the information and audit rights, the following should particularly be agreed upon contractually:
- the provision of unrestricted access to information and data as well as access to the business premises of the cloud provider, including all data centers, devices, systems, and networks used to provide the outsourced matters; this includes the related processes and controls,
- effective control and audit possibilities as well as the option of conducting on-site audits at the cloud provider.

Regarding significant sub-outsourcing, it should be ensured that equivalent information and audit rights are agreed upon for the entire outsourcing chain.

##### 5.2.1 No (Indirect) Restriction of Rights
The effective exercise of information and audit rights must not be restricted by contractual agreements. The German supervisory authority particularly considers agreements that grant these rights only under certain conditions as an impermissible restriction of the information and audit rights.

These include in particular:
- the agreement of tiered information and audit procedures, e.g., the obligation to first rely on the audit reports, certificates, or other proofs of compliance with recognized standards by the cloud provider before the supervised company can carry out its own audit actions,
- a limitation of fulfilling the information and audit rights to the presentation of audit reports, certificates, or other proofs of compliance with recognized standards by the cloud provider,
- linking access to information to prior participation in special training programs,
- the formulation of a clause in which the conduct of an audit is made dependent on commercial reasonableness,
- a temporal and personal limitation on the conduct of audits, where a restriction of access to usual business hours upon prior notification is generally considered reasonable,
- a reference to the exclusive use of management consoles for exercising the company's information and audit rights,
- a specification of the procedure and scope of exercising the information and audit rights by the cloud provider,
- a reference to internal implementation guidelines of the cloud provider that provide for restrictions of the contractually agreed rights, and
- costs that could limit or hinder the exercise of the information and audit rights due to their amount. The same applies to access to information and documents that is only available on-site.

##### 5.2.2 Alternative Audit Approaches
Depending on the relevant regulatory requirements, supervised companies can use alternative audit approaches to make their audit actions more efficient.[^8]  If the supervised company intends to use these alternative audit approaches, they should be appropriately considered in the contract design with the cloud provider.

If a supervised company takes advantage of one of the alternative audit approaches mentioned in Chapter V.4.2, this must not lead to a restriction of its information and audit rights. However, the supervised company should not be obligated by the cloud provider to utilize one of the alternative audit approaches.

[^8]: Refer also to Chapter V.4.2 for more details.

>Outlook on DORA
>
>**Exception for Micro-enterprises**
>
>According to Article 30(3) second sentence of DORA, the ICT third-party service provider and the micro-enterprise (see Art. 3(60) DORA) may agree that the access, inspection, and audit rights of the financial company can be transferred to an independent third party designated by the ICT third-party service provider. However, the financial company should then be able to demand information and assurance from the third party regarding the services at any time.

#### 5.3 Information and Audit Rights of the Supervisory Authority
The information and audit rights as well as the control capabilities of the supervisory authority must not be contractually or through internal implementation guidelines of the cloud provider restricted. The supervisory authority must be able to control the outsourced matter at the cloud provider just as it would at the supervised company according to the respective relevant laws. Accordingly, it must be contractually agreed that the supervisory authority can properly and unrestrictedly exercise its information and audit rights as well as control capabilities in regard to the outsourced matter; this also applies to those persons whom the supervisory authority uses in the conduct of audits. In particular, it should be possible for the supervisory authority to exercise information and audit rights at least for a period of five years after the end of the contract.

To ensure the information and audit rights of the supervisory authority, the following should particularly be agreed upon contractually:
- the obligation of the cloud provider to cooperate fully with the supervisory authority,
- the provision of unrestricted access to information and data as well as access to the business premises of the cloud provider, including all data centers, devices, systems, and networks used to provide the outsourced matters; this includes the related processes and controls,
- effective control and audit possibilities as well as the option of conducting on-site audits at the cloud provider.

Regarding significant sub-outsourcings, it should be ensured that equivalent information and audit rights are agreed upon for the entire outsourcing chain.

Regulations that grant these rights only under certain conditions are considered an impermissible restriction of the information and audit rights as well as control capabilities of the supervisory authority. To avoid repetition, reference is made to the above statements on the restriction of the rights of the supervised companies (see 5.2.1).

#### 5.4 Instruction Rights
Instruction rights of the supervised companies should be agreed upon. These instruction rights should ensure that all necessary instructions required for the fulfillment of the agreed service can be issued, i.e., there needs to be a possibility of influence and control over the outsourced matter. Instructions can be given technically (management console, Application-Programming-Interfaces (APIs)). The implementation can be individually designed.

If the supervised company utilizes evidence/certifications or audit reports (see Chapter V.4.2.3.), it should also have the possibility to influence the scope of the evidence/certifications or audit reports, so that it can be extended to relevant systems and controls. The number and frequency of such instructions should be proportionate.

Furthermore, the supervised company should always be authorized to issue instructions to the cloud provider regarding the correction, deletion, and blocking of data, and the cloud provider may only collect, process, or use the data within the framework of the instructions issued by the supervised company. The right of instruction should also include the possibility of issuing an instruction for the immediate and unrestricted repatriation of the data processed by the cloud provider to the supervised company at any time.

If it is possible to forgo the explicit agreement of instruction rights in favor of the supervised company, the service to be provided by the outsourcing company must be specified clearly enough in the outsourcing contract.

#### 5.5 Data Security/Protection (Note on the Location of Service Provision)
Agreements must be made to ensure that both data protection regulations and regulatory requirements for information security are complied with.

The location of service provision should be known to the supervised company and specifically include the location of the data centers. Generally, naming the city is sufficient. However, if a supervised company requires the exact address of the data centers, the cloud provider should provide it.

Moreover, the redundancy of data and systems according to their protection needs should be ensured so that the continuity of cloud services is guaranteed in case of a data center failure. This can usually be implemented configuratively by the supervised company, depending on the cloud services.

The protection and security of data and systems must also be ensured within the entire outsourcing chain.

The supervised company should always be able to access its data stored with the cloud provider and, if necessary, repatriate it. It should be ensured that the chosen form of repatriation does not restrict or make impossible the use of data. Therefore, platform-independent standard data formats should be agreed upon where possible. The compatibility of different systems must be considered.

>Outlook on DORA
>
>**Consideration of the Latest and Highest Quality Standards for Information Security**
>
>Article 28(5) of DORA requires financial companies, before concluding agreements with ICT third-party service providers concerning critical or important functions, to appropriately consider whether ICT third-party service providers apply the latest and highest quality standards for information security. Corresponding contractual agreements must ensure the availability, authenticity, integrity, and confidentiality of data.

#### 5.6 Termination Provisions
Termination rights and appropriate notice periods should be agreed upon. In particular, a special right of termination should be agreed for the supervised company, which provides for termination for cause if the supervisory authority demands the termination of the contract. Termination for cause should also be possible, in particular, if
- the cloud provider violates applicable law, regulations, or contractual provisions concerning the outsourced matter,
- obstacles exist that may impair the performance of the outsourced matters, or unacceptable impacts on the quality of service are identified,
- significant changes occur that affect the outsourcing agreement or the cloud provider (e.g., sub-outsourcing or changes among subcontractors), and
- deficiencies regarding the handling and security of confidential, personal, or otherwise sensitive data or information occur.

It must be ensured that the matters outsourced to the cloud provider are provided until a complete transfer to another (cloud) provider or back to the supervised company has taken place, in case of termination. In particular, it must be ensured that the cloud provider adequately supports the supervised company in transferring the outsourced matters to another (cloud) provider or directly back to the supervised company.

The manner, form, and quality of the handover of the outsourced matter and data should be defined. To the extent that data formats are adapted to the individual needs of the supervised company, the cloud provider should provide documentation of these adaptations upon termination.

It should be agreed that, after the data has been transferred back to the supervised company, its data will be completely and irrevocably deleted by the cloud provider.

For supervised companies that fall under the scope of the Act on the Recovery and Resolution of Institutions and Financial Groups (SAG), the agreements made for material outsourcing must take into account the powers of directive in the sense of § 80 paragraphs 1 and 2 SAG.

To ensure the continuity of the outsourced areas in the event of planned or unplanned termination of the contract, the supervised company should maintain an exit strategy and verify its feasibility.

>Outlook on DORA
>
>**Extended Special Termination Rights and Minimum Notice Periods**
>
>Article 28(7) of DORA mentions additional special termination rights as a mandatory contractual component in agreements on the use of ICT services. Likewise, according to Article 30(2)(h) of DORA, termination rights and related minimum notice periods for ending contractual agreements are to be agreed upon according to the expectations of the competent authorities and resolution authorities.
>
>Furthermore, according to Article 28(8) in conjunction with Article 30(3)(f) of DORA, for ICT services supporting critical or important functions, exit strategies are to be developed and a binding appropriate transition period is to be agreed upon. The contractual agreements made must be designed in such a way that uninterrupted business activity, compliance with regulatory requirements, and the continuity and quality of services provided to the customer are ensured.

#### 5.7 Sub-outsourcing
Agreements must be made regarding the possibility and the modalities of sub-outsourcing, ensuring that regulatory requirements continue to be met. Restrictions to the effect that only broadly similar obligations are assumed are not permissible. In particular, it must be ensured that the information and audit rights as well as control capabilities of the outsourcing supervised company and the supervisory authority are maintained in the case of sub-outsourcing, also towards the subcontractors.

Regarding sub-outsourcing, consent provisions of the outsourcing company or specific conditions under which sub-outsourcings are allowed should be agreed upon in the outsourcing contract. It should be defined which outsourced matters or parts thereof may be sub-outsourced and which may not. Where this is not possible, at least obligations for prior notification should be agreed upon. The supervised company should be informed in writing well in advance about sub-outsourcings of the outsourced matters or parts thereof, or where required, the consent of the supervised company should be obtained. The potentially relevant subcontractors and the matters or parts thereof that are sub-outsourced to them should be known to the supervised company.

In the event of a new or changed sub-outsourcing, it must be considered that this affects the risk situation of the outsourcing and thus of the outsourcing company. Accordingly, in the event of a new or changed sub-outsourcing, the risk analysis should at least be reviewed or re-conducted. This also applies in the event of becoming aware of significant defects as well as significant changes in the cloud service provided by subcontractors.

#### 5.8 Information Obligations of Cloud Providers
Agreements must be made to ensure that the cloud provider informs the supervised company about developments that can impair the proper execution of the outsourced matters. The obligation to provide information includes, for example, the reporting of incidents and information security incidents in the provision of the cloud service. This is intended to ensure appropriate monitoring of the outsourced matter by the company.

The cloud provider should immediately inform the supervised company about circumstances that could pose a threat to the security of the data to be processed by the cloud provider for the supervised company, e.g., due to actions by third parties (e.g., seizure or confiscation), through insolvency or settlement proceedings, or due to other events.

The scope and preparation of the information provided by the cloud provider should be such that the supervised company can respond appropriately. In particular, the supervised company should be enabled to recognize and assess changes in its risk situation.

It should be ensured that the supervised company is appropriately informed in advance about relevant changes to the cloud service to be provided by the cloud provider. Service descriptions and their possible changes should be made available to the supervised company in text form or communicated. It should be ensured that the supervised company is informed about inquiries/requests by third parties for the release of the supervised company's data, to the extent that this is legally permissible.

#### 5.9 Note on Applicable Law
Especially for reasons of legal certainty, care should be taken when agreeing on a choice of law clause to ensure that – unless German law is agreed upon – the law of a state of the European Union or the European Economic Area applies to the contract. If this is not possible, all requirements for legal enforceability should remain guaranteed.

## IV. Secure Application Development and IT Operation in the Cloud 

>Outlook on DORA
>
>**ICT Risk Management**
>
>Chapter II of DORA contains extensive regulations on ICT risk management. The requirements for ICT risk management are based on international, national, and industry-specific best practices and standards. They include the following specific elements in the area of ICT risk management: identification, protection and prevention, detection, response and recovery, learning processes, further development, and communication.
>
>They aim to maintain or, if necessary, restore the operational capacity of financial companies, especially with regard to cyber threats. Thus, the requirements ensure that financial companies achieve appropriate digital operational resilience for themselves – meaning they are resilient and adaptable enough to maintain their digital operational processes during and after a disruption.
>
>The principles and regulations set out in DORA, including those related to application development and IT operation in the cloud, will be further specified by RTS, so the concrete requirements are not yet determined.

### 1. Application Development and IT Operation by the Supervised Company
Supervised companies are increasingly relying on the development of application programs based on cloud services provided by cloud providers. These applications can also be highly complex and use cloud services with complicated configuration options, which are partly provider-specific. The risks arising in this context should be appropriately considered both in application development and IT operation.

The guidance provided in this chapter, based on existing regulatory requirements, addresses the specific challenges and risks associated with the use of the cloud and outlines possible solutions. It aims to create transparency about the supervisory understanding of problem areas in application development and IT operation in the cloud and describe commonly appropriate measures.

#### 1.1 Development of Cloud Applications and Configuration of Cloud Environments
Cloud applications are often developed using agile methods, employing DevOps and DevSecOps principles. Alongside further requirements from relevant circulars, it is particularly important to ensure that requirements for the separation of duties are not violated and potential conflicts of interest are avoided. This can be partially supported by organizational measures or the use of technical tools, e.g., CI/CD pipelines or automated tests. Regardless of possible automated testing processes, risk-oriented manual testing actions, such as code reviews, may still be necessary.

#### 1.2 Use of (Architecture) Guidelines
Cloud providers typically offer design principles and best practices for development and IT operation in the cloud (commonly referred to as "Well-Architected Frameworks"). These usually include recommendations on reliability, security, cost, operation, and efficiency. Additionally, cloud providers typically recommend in their documentation for various cloud services the activation of specific security settings.

These recommendations should be aligned with the supervised company's own (architecture) guidelines when using complex cloud services and applications. If risks arise from deviations from the cloud provider's recommendations, they should be managed within the risk management framework.

#### 1.3 Technical Implementation of (Architecture) Guidelines
To ensure that deviations from key points of standard architectures and operational requirements cannot occur, supervised companies should specify (architecture) guidelines in the cloud to technically implement them in the development of cloud applications and in the configuration of cloud environments.

If these are not technically implemented, deviations should ideally be technically monitored. The risks arising from non-implementation should be documented and managed within the risk management framework.

Particularly, the following non-exhaustive aspects should be considered:
- the restriction of permissible cloud services and locations or regions of data centers,
- the use of encryption and permitted cryptographic methods, depending on the protection requirements of the processed data,
- setting secure default settings for cloud services and the cloud environment to ensure the protection goals of confidentiality, integrity, availability, and authenticity,
- restrictive restriction of cloud access paths not intended for the public, e.g., to explicitly authorized hardware, software, and network areas with defined security features, differentiated by the criticality of individual cloud applications,
- the separation of production environments from development, test, and other environments,
- the use of multi-factor authentication for non-technical users,
- the regular (automated) execution of backups,
- the use of logging and monitoring data and the protection of this data from unauthorized access, manipulation, or unauthorized deletion.

To avoid unauthorized changes to standard configurations and architectures, access to cloud environments should be restricted and preferably occur only through programmatic API calls ("Infrastructure-as-Code").

#### 1.4 Monitoring of the Supervised Company's Cloud Operational Processes
The cloud environments set up by the supervised company, the cloud services used, and the cloud applications developed should be continuously monitored by the supervised company.

This includes regular exchanges between supervised companies and cloud providers on topics such as performance and capacity management or lifecycle management, and the risk-based and possibly automated evaluation of notifications from the cloud provider, occurring error and warning messages, and the monitoring of the integrity of cloud configurations. Depending on the availability requirements, the availability of cloud applications should be checked and evaluated.

### 2. Cyber and Information Security
Cloud applications often contain sensitive data and thus, in the event of a failure, can impact critical business processes. Simultaneously, the development, operation, and use of cloud applications are often associated with a significant increase in the attack surface on the internet. As cloud technologies are utilized by many companies, even complex attack methods can often be applied, potentially even in an automated manner. Concurrently, the complexity of the cloud can facilitate potential misconfigurations and the loss of a comprehensive overview of infrastructure and utilized resources (including tools and interfaces for cloud administration provided by the providers), thereby easing the facilitation of cyber attacks.

The foundation should be an analysis of potential attackers, attack targets, and attack methods, covering both a general, non-targeted cyber threat landscape and company- and application-specific threats (Threat Intelligence). This information should be considered in all phases of development, operation, and use, and contribute to the determination of cyber and information risks.

To ensure an adequate level of cyber and information security, supervised companies should particularly take measures to secure their network connections against disruption and unauthorized monitoring, e.g., through DDoS mitigation, transport encryption, or dedicated connections to the cloud provider. Application and infrastructure architectures should be designed to make penetration or the spread of unauthorized access as difficult as possible, e.g., through the use of firewalls, network segmentation, multi-factor authentication, or Zero Trust. This also includes the detection and protection against unauthorized data exfiltration, e.g., through Data Loss Prevention.

The rule-based evaluation of potentially security-relevant information from supervised companies should be integrated with the data sources of the cloud provider. In case of separate structures and data sources (SOC, SIEM, etc.) on the part of the supervised company for monitoring the cloud environment and other IT systems, these should be fully integrated.

In the compilation and evaluation of potentially security-relevant information, responsibilities and procedures for investigating security-relevant events and resulting information security incidents should be defined, this also affects the interface to the cloud provider. Supervised companies should also agree that they are promptly informed by the cloud provider about events and information security incidents relevant to the supervised company's security.

In the event of an information security incident, appropriate measures should ensure that administrative access is possible even if primary connection pathways and devices are disrupted. Backups of business-critical data and configurations should be stored at regular intervals additionally outside the affected cloud, e.g., on-premise or with another cloud provider.

Cloud applications that are critical services (KRITIS) or substantially support these, as well as cloud applications identified as particularly important in the context of protection needs analyses, should undergo regular penetration testing. There is also the possibility of conducting Threat-Led Penetration Testing (TLPTs) involving the cloud provider. Training on cyber and information security should be mandatory for all internal and external employees using cloud applications, and should be tailored to their prior knowledge, tasks, and the potential risks they face.

### 3. Emergency Management
The emergency concepts and IT contingency plans of the cloud provider and the supervised company should be coordinated. If the cloud provider's emergency concepts and IT contingency plans cannot be adapted to those of the supervised company, the outsourcing company should gain knowledge about the cloud provider's emergency procedures and align its own processes, architectures, and other precautions accordingly. Possible risks from deviations in the cloud provider's processes should be managed within the framework of risk management.

IT contingency plans should be tested regularly[^9], and the supervised company should use suitable emergency scenarios for these tests. If a joint test with the cloud provider is not possible, it should be ensured that all affected components are sufficiently covered by own tests or by appropriate test evidence.

[^9]: Sector-specific regulations must be observed; for example, annual IT emergency tests according to section 10.4 of the BAIT (Banking Supervisory Requirements for IT).

### 4. Exit Strategy
Part of an exit strategy should be the identification of specific alternative solutions and the development of appropriate and feasible plans for a change of provider or a repatriation to the outsourcing company, with a view to the respective cloud applications. The requirements of emergency management should also be considered in the transfer.

The supervised company should develop exit plans against the backdrop of exit scenarios that specifically relate to the used cloud services. These exit plans should risk-based reflect the scope and time horizon of a termination of service provision. The use of different cloud providers should be considered. The exit scenarios to be considered also include the unintended or unexpected permanent loss of the specifically used cloud services.

Supervised companies should be able to switch to alternative solutions, taking into account proportionality, without interruption of business activities, restriction of regulatory compliance, or impairment of the availability and quality of services to customers.

Exit plans should be sufficiently documented and tested, with particular emphasis on the necessary resources, time frames, responsibilities, and support services both internally and on the part of the cloud provider.

## V. Monitoring and Control of Outsourcing to Cloud Providers
### 1. Information Network and Model of Shared Responsibility
Depending on the chosen service model, there is a division of labor between the supervised company and the cloud provider regarding responsibility for the operation of the cloud. Simplistically, these areas of responsibility can often be schematically represented in layers (e.g., data center, network, physical servers, virtualization, operating system, middleware, application, data).[^10]

Depending on the chosen cloud service and service model, the demarcation of responsibilities lies at different points in the abstract layer model. The supervised company should define and document a clear distribution of well-defined tasks and responsibilities in relation to the operational functions and activities within its information network for all used cloud services.

Supervised companies should ensure a complete representation in an inventory directory of IT system components and their relationships to each other for the layers that fall under their own responsibility. From a proportionality perspective, there can be different ways to meet the requirements for an inventory directory of IT system components and their interrelations. For example, a CMDB serves to ensure a documented overview of the components/service elements and their configuration necessary for maintaining or restoring the business process. The supervised company should individually decide which information of those layers that fall under the cloud provider's responsibility should also be included in the CMDB of the supervised company. For layers solely under the cloud provider's responsibility, components of the cloud provider are usually not included in the supervised company's CMDB.

[^10]: Cloud providers often use the term "Shared Responsibility" for this concept.

### 2. Monitoring of Service Provision
Supervised companies should take appropriate technical and procedural precautions, oriented towards risk, to monitor the services provided by cloud providers, to collect, analyze, and evaluate the necessary information in a timely, complete, and comprehensive manner. Cloud providers and supervised companies should jointly ensure that all required information can be provided and accessed in a suitable format.

#### 2.1 Monitoring of Service Quality
Supervised companies should continuously monitor the quality of service, regardless of whether the cloud service is provided by the cloud provider or their subcontractors, using the measures from 4.1 as a reference.

For significant outsourcing or non-differentiated outsourcing according to KAGB, both the service quality metrics (as contractually agreed in the Service-Level Agreement (SLA)) and company-specific indicators should be regularly collected and evaluated. The data provided by the cloud provider should be validated as needed through appropriate analyses or measurements. For ongoing monitoring, supervised companies should define internal processes and threshold values for warning levels when approaching unacceptable service quality. Upon exceeding these thresholds, predefined communication and escalation processes to internal stakeholders and the cloud provider should be activated.

If the actual service quality falls below the contractually agreed level, the supervised company should ad hoc evaluate any potential limitations and risks that may arise and take measures for risk reduction if necessary. If the service quality drops below the pre-established threshold for an unacceptable level for a significant period, the supervised company, in addition to risk reduction measures, should consider preparatory steps for changing providers and possibly initiate the termination of the outsourcing relationship.

#### 2.2 Monitoring Changes to the Service Scope
Supervised companies should ensure that they are informed by the respective cloud providers about changes to the service scope, such as changes to interfaces, the performance of cloud services, SLAs, or planned maintenance, with sufficient lead time, or align the internal processes of the supervised company with the agreed deadlines with the cloud provider. Supervised companies should continuously monitor changes and planned changes to the service scope by evaluating notifications from cloud providers on an ongoing basis and holding regular discussions with the service provider.

Changes should be documented and evaluated in an impact analysis before their implementation, focusing in particular on information security objectives and initiating necessary measures, such as changes to application architecture. For major changes, periods with increased support requirements on the part of the supervised company should also be planned.

### 3. Monitoring of Information Security
#### 3.1 Monitoring the Security Level
Supervised companies should continuously ensure that the respective cloud providers maintain an adequate level of data and system security in processing, transmitting, and storing data, in line with the respective protection needs, and implement information security measures. Measures from 4.1 can be utilized for this purpose. For significant outsourcing, or non-differentiated outsourcing according to KAGB, these measures should at least include:
- Organization of information security and risk management,
- Identity and rights management,
- Encryption and key management,
- Operational security aspects (incident management, change management, logging and monitoring, backup, vulnerability management, network security, etc.),
- Security of Application Programming Interfaces (API),
- Management of subcontractors,
- IT emergency management.
Supervised companies should regularly and on an ad-hoc basis determine the achieved security level.

#### 3.2 Monitoring of Information Security Incidents and Disruptions at the Cloud Provider
In addition to the integration of processes to ensure cyber and information security described in Chapter IV.2, supervised companies should ensure that cloud providers promptly report unplanned deviations from regular operations (disruptions) and information security incidents to the supervised company with a preliminary, predefined risk assessment. If possible, the cloud provider should provide temporary workarounds for errors. Based on predefined escalation levels and thresholds, the supervised company should identify and address information security incidents with the cloud provider.
In case of disagreements in managing information security incidents between the supervised company and the cloud provider, escalation procedures and possibly directive rights should be agreed upon. Following the initial report, cloud providers should also promptly provide the company with a comprehensive presentation of the facts and a root cause analysis, including any additional security measures taken. These should be evaluated by the supervised company and considered in risk management if necessary.
Furthermore, the supervised company should, possibly together with the cloud provider, conduct learning processes, in which, among other things, the communication between the cloud provider and the supervised company is examined.

### 4. Implementation of Monitoring and Control Measures
The supervised company should allocate an appropriate budget for the costs arising from planned monitoring, control, and audit measures.

#### 4.1 Regular and Ad-Hoc Monitoring and Control Activities
Monitoring measures by supervised companies can take various forms and should be oriented towards the risks associated with the outsourced matter. Regular monitoring activities should be scheduled and performed by the technically and professionally responsible departments in the supervised company and control functions according to a monitoring plan. In addition, ad-hoc monitoring measures should be carried out, especially in the event of incidents, uncertainties about the functioning of certain aspects of the cloud, or to develop a better understanding of the risk situation. Suitable measures could include:
- Discussions with customer service representatives of the cloud provider,
- Evaluation of the technical documentation and whitepapers of the cloud providers,
- Evaluation of customer-specific and general metrics (e.g., KPI, KCI, KRI), reports, and analyses of the cloud provider,
- Audit reports and certificates[^11],
- Inspections, and
- In-depth analyses with experts of the cloud provider on specific topics.
Monitoring measures should be documented and can lead to the agreement of further measures, the implementation of which should again be monitored by the supervised company.

[^11]: See the minutes of the Special Expert Committee on Cloud on the topic "Certificates" from October 7, 2021. Link see footnote 1.

#### 4.2 Audits at Cloud Providers
Supervised companies are obligated to ensure appropriate information and audit rights in the event of outsourcing (significant) matters. The supervisory framework provides organizational options to facilitate the implementation of these rights (see BT 2.1 Tz. 3 Circular 05/2023 (BA) - Minimum Requirements for Risk Management – (MaRisk); Guideline 11 Tz. 42 lit. a EIOPA Guidelines on Outsourcing to Cloud Providers; Guideline 6 Tz. 37 lit. a ESMA Guidelines on Outsourcing to Cloud Providers).
Such facilitations include pooled audits, commissioning third parties to conduct an audit, or external/internal audit reports from cloud providers. The internal audit department of the supervised company may also rely on evidence/certificates created by third parties. These alternative audit approaches and the use of certifications in the conduct of audit actions must meet supervisory requirements. Such facilitations must not lead to a restriction of the information and audit rights of the supervised company.

##### 4.2.1 Conducting Pooled Audits
Audit activities can be conducted as a "pooled audit" or "pooled audit" on behalf of several outsourcing supervised companies through the internal audits of the supervised companies or by a third party commissioned by the outsourcing supervised companies. It should be ensured that the supervised company has sufficient influence on the planning and execution of the audit.
All supervised companies involved in the audit should have access to audit evidence. If this audit evidence is stored in a (shared) data room, the protection objectives must be ensured. To prove integrity, at least an overview of the audit evidence and associated hash values should be stored at the supervised companies and checked on a sample basis and as needed.

##### 4.2.2 Using Reports from the Internal Audit of the Cloud Provider
The audit activity of the supervised company regarding the outsourcing to the cloud can be taken over by the internal audit of the cloud provider if it meets the supervisory requirements for the internal audit of the supervised company itself. It is initially irrelevant whether the audit activities are performed by the audit of the cloud provider or outsourced to an external third party. The audit reports should be transmitted directly from the internal audit of the cloud provider to the internal audit of the supervised company. To avoid audit gaps, the audit scope should not be limited to the contracted matters but should also include the resources and processes needed for their provision. The internal audit of the outsourcing company must regularly verify compliance with these conditions, e.g., through appropriate certifications (e.g., DIIR Audit Standard No. 3 or IDW PS 983) or its own audit actions.

##### 4.2.3 Using Evidence/Certificates and Audit Results from Independent Third Parties
The internal audit of the outsourcing supervised company can also rely on evidence/certificates from independent third parties but should not solely base on them for significant outsourcings.
A prerequisite for using such certificates and audit evidence is that they specifically concern the used cloud services, cover a relevant period, and were created by a suitable, independent auditor observing common audit standards. The same applies to internal audit reports of the cloud provider.
Commonly accepted standards for information security and cloud (e.g., ISO 27001, BSI C5, SOC2, CSA CCM), audited by auditing firms according to generally recognized audit standards (e.g., SSAE 18, ISAE 3402, IDW PS 951) or by accredited auditors, are typical.
When using evidence/certificates and audit results from independent third parties in the form of audit reports, it is important to note that the themes and depth of various audit forms can vary greatly. The supervised company should particularly consider the scope, detail, currency, and suitability of the audit reports as well as the suitability of the auditor. Therefore, it is generally not sufficient for a supervised company to merely ensure that evidence (e.g., just the certificate itself) exists. Rather, it should analyze the associated audit report to consider which emphases were made, what findings were made, and what comments were made. Under this condition, the use of audit results may be sufficient for areas of low complexity and low risk (e.g., physical security, fire extinguishing system in the data center), but for complex matters or higher risk, additional own control and monitoring actions are necessary. Furthermore, findings from audits by the internal audit of the supervised company can also be considered.



