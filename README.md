# Awesome-Electronic-Health-Records

# Top Electronic Health Records (EHR) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Clinical Documentation, Practice Management, Interoperability & Patient Data Ownership*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Electronic Health Records (EHR)**. These tools help hospitals, clinics, and physician practices document clinical encounters, manage patient demographics, process billing, and exchange health data securely.

**Examples** include Epic, Cerner (Oracle Health), athenahealth, eClinicalWorks, NextGen Healthcare, Practice Fusion, DrChrono, Meditech, Altera Digital Health, and CureMD (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom clinical workflows, and transparent patient data — ideal for resource-constrained clinics, international health systems, and developers building interoperable healthcare solutions without vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Epic](https://www.epic.com/)**
  The dominant EHR in large U.S. health systems. Comprehensive clinical, revenue cycle, and population health modules with extensive interoperability via EpicCare Link and Care Everywhere. Patient portal (MyChart) serves as the de facto standard for patient access.

- **[Cerner (Oracle Health)](https://www.oracle.com/health/)**
  Enterprise EHR for hospitals and large clinics, now part of Oracle. Provides clinical documentation, revenue cycle, and population health management with strong laboratory and radiology integration.

- **[athenahealth](https://www.athenahealth.com/)**
  Cloud-based EHR and revenue cycle management for physician practices. Known for its integrated billing services and network-based approach to clinical data exchange.

- **[eClinicalWorks](https://www.eclinicalworks.com/)**
  Ambulatory EHR with strong presence in small to mid-sized practices. Provides clinical documentation, practice management, and patient engagement tools including healow patient portal.

- **[NextGen Healthcare](https://www.nextgen.com/)**
  EHR and practice management for ambulatory practices across specialties. Offers population health management, telehealth, and revenue cycle solutions.

- **[Practice Fusion](https://www.practicefusion.com/)**
  Free, ad-supported cloud EHR for small practices. Provides charting, scheduling, billing, and e-prescribing with a focus on simplicity.

- **[DrChrono](https://www.drchrono.com/)**
  Cloud-based EHR for small practices and mobile clinicians. Features iPad-native charting, medical billing, and patient scheduling with an app marketplace.

- **[Meditech](https://www.meditech.com/)**
  Hospital EHR with strong presence in community hospitals. Provides clinical, financial, and operational modules with options for cloud or on-premises deployment.

- **[Altera Digital Health](https://www.alterahealth.com/)**
  EHR portfolio including Paragon and Sunrise platforms. Serves hospitals and health systems with clinical, financial, and population health capabilities.

- **[CureMD](https://www.curemd.com/)**
  Cloud-based EHR and practice management with a focus on specialty practices. Provides clinical documentation, billing, and patient portal features.

## Open-Source GitHub Projects

- **[OpenEMR](https://github.com/openemr/openemr)**
  The most popular open-source EHR and medical practice management solution. **ONC Certified** (Ambulatory EHR) with version 8.0.0 achieving certification in February 2026. Features fully integrated electronic health records, practice management, scheduling, electronic billing (ANSI X12 5010), e-prescribing, patient portal (modern UI with scheduling, secure messaging, online payments, and CCDA support), clinical decision rules, and FHIR support for ONC US Core IG 4.0.0 including SMART on FHIR. Runs on Windows, Linux, macOS with PHP and MySQL/MariaDB. Available in 30+ languages. Free and open source (GNU GPL) with no vendor lock-in. ~1.5k+ stars .

- **[OpenMRS](https://github.com/openmrs/openmrs-core)**
  Open-source medical record system designed for resource-constrained environments, particularly in developing countries. Modular architecture with a robust API and strong HL7/FHIR support secured via OpenHIM-based OAuth2. Flexible, modular security capable of enterprise-grade authentication through extensions and external identity providers. Used by Partners In Health, AMPATH, and national health systems across Africa and Asia .

- **[GNU Health](https://github.com/gnuhealth/gnuhealth)**
  Free/Libre health and hospital information system from the GNU Project. Provides hospital management, electronic medical records, laboratory, pharmacy, and epidemiology modules. Licensed under GPLv3, written in Python with PostgreSQL. Used by governments and NGOs including the United Nations University and the Government of Jamaica. More limited authentication capabilities than OpenEMR/OSCAR, but strong for public health and hospital management in resource-limited settings .

- **[Bahmni](https://github.com/Bahmni/bahmni-offline-packages)**
  Open-source EMR and hospital system built on top of OpenMRS and Odoo. Provides a unified interface for clinical documentation, lab, radiology, billing, and inventory. Strong HL7/FHIR support with OpenHIM-based security. Used in low-resource settings as a comprehensive hospital information system. Most capable system for interoperability security due to comprehensive standards support .

- **[OSCAR EMR](https://github.com/oscar-emr/oscar)**
  Open-source EMR developed by McMaster University for Canadian primary care. Strong authentication maturity with native two-factor authentication, enforceable password policies, and comprehensive session controls. Provides clinical documentation, scheduling, billing, and e-prescribing. Customizable for different practice needs with strong HIPAA-oriented technical safeguards .

- **[LibreHealth EHR](https://github.com/LibreHealthIO/lh-ehr)**
  Community-driven fork of OpenEMR with a focus on modernizing the codebase and improving developer experience. Free and open-source EHR with clinical documentation, practice management, and patient portal capabilities. ~238 stars, actively maintained as an alternative for organizations wanting OpenEMR's functionality with a fresh development approach .

- **[Open Hospital](https://github.com/informatici/openhospital)**
  Free and open-source EHR for hospital management, developed by Informatici Senza Frontiere (IT Without Borders). Provides patient records, admissions, laboratory, pharmacy, and reporting. Used in hospitals across Africa and other resource-limited regions. ~504 stars, actively maintained. GPL licensed .

- **[Mere Medical](https://github.com/cfu288/mere-medical)**
  Open-source personal health record (PHR) aggregator that syncs records from multiple patient portals into one place. Supports Epic MyChart, Cerner, Allscripts, DrChrono/OnPatient, and Veradigm via SMART on FHIR. **Offline-first, self-hosted web app** — health records stored directly on the user's device, never on third-party servers. 250+ GitHub stars, MIT licensed. Named a finalist in AMIA's 2025 HL7 FHIR App Competition .

- **[OpenEMR Express Plus](https://www.open-emr.org/)**
  Free, fully hosted OpenEMR for U.S.-based healthcare providers — no servers, no setup, no cost. Built on HIPAA-eligible AWS services with encryption and auditing. Restores true one-click deployment on AWS. Executing a Business Associate Agreement with AWS is required for HIPAA-compliant deployment .

### Additional Strong Open-Source Options

- **EHR Suites**: **OpenEMR** (ONC certified, most popular), **OpenMRS** (developing countries, modular), **Bahmni** (hospital system on OpenMRS), **OSCAR EMR** (Canadian primary care, strong auth) .
- **Hospital Management**: **GNU Health** (GPLv3, hospital + public health), **Open Hospital** (IT Without Borders, resource-limited settings).
- **Personal Health Records**: **Mere Medical** (patient-owned aggregation, SMART on FHIR), **Fasten Health** (self-hosted PHR, FHIR-based) .
- **Interoperability**: **OpenHIM** (health information mediator), **HAPI FHIR** (Java FHIR server).

**Frameworks for building custom systems**: Combine **OpenEMR** for the core EHR and practice management, **OpenMRS** or **Bahmni** for resource-constrained or hospital settings, **Mere Medical** for patient-owned record aggregation, and **PostgreSQL/MySQL** for persistence. Add **Docker** for deployment and **HAPI FHIR** for standards-based interoperability.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- EHR platforms handle protected health information (PHI); ensure compliance with HIPAA, GDPR, and applicable regional healthcare regulations.
- **Open-source reality**: Mature open-source EHR platforms exist and are production-ready — **OpenEMR** is ONC certified and **OpenMRS/Bahmni** are used at national scale. However, a security benchmarking study found that **no open-source EHR provides native application-level encryption for data at rest or file attachments**, and none offer integrated cryptographic key management. All rely on external database or operating system encryption. Organizations deploying these platforms must implement additional security controls .

---

**Made for healthcare IT teams, clinic administrators, health informatics developers, and public health organizations.**
Let's make electronic health records more open, interoperable, and patient-centered.
