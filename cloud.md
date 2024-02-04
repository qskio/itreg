# Supervisory Communication on Outsourcing to Cloud Providers
Updated February 2024




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
After the strategic decision for third-party procurement of matters from a cloud provider, at the beginning of the process, the supervised company should check, based on the applicable regulatory requirements, whether an outsourcing exists and whether it is to be classified as material. In general, the conditions for outsourcing are met. The risk analysis should consider all aspects relevant to the supervised company in connection with outsourcing to cloud providers, with the intensity of the analysis depending on the nature, scope, complexity, and risk content of the outsourced matters. The supervised company should evaluate and document, based on the risk analysis, what risks are associated with an outsourcing and whether it constitutes a material outsourcing. If there are regulatory requirements for materiality, these must be observed.

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
