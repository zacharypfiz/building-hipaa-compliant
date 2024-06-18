# **Chapter 3**: **Planning Your HIPAA-Compliant MVP**



* Identifying Protected Health Information (PHI)
* Risk Assessment and Management
* Developing a Compliance Plan
* Setting Compliance Goals and Milestones


### **Identifying Protected Health Information (PHI)**

Protected Health Information (PHI) includes any information that can identify an individual and relates to their health status, healthcare provision, or payment for healthcare services. To ensure your systems are HIPAA-compliant, you must identify and handle PHI and other identifiers effectively.


### Catalog All Data Points

List all data points your systems will collect, store, process, or transmit. This includes user inputs, system-generated data, and any data from third-party services.


### Classify Data Types



* **Health-Related Data Points**: Identify which data points are directly related to an individual's health (e.g., medical records, treatment details, diagnoses).
* **Personal Identifiers**: Identify personal identifiers that could be used to identify an individual. These are considered PHI if associated with health information.


### Common Identifiers



* **Personal Identifiers**: Names, addresses, birth dates, Social Security numbers.
* **Health Information**: Medical records, treatment details, diagnoses.
* **Payment Information**: Insurance details, billing records.
* **Contact Information**: Telephone numbers, fax numbers, email addresses.
* **Identification Numbers**: Social security numbers, medical record numbers, health plan beneficiary numbers, account numbers, certificate/license numbers.
* **Vehicle and Device Identifiers**: Vehicle identifiers and serial numbers, device identifiers and serial numbers.
* **Online Identifiers**: Web URLs, IP addresses.
* **Biometric Identifiers**: Fingerprints, voice prints.
* **Images**: Full-face photographs and any comparable images.
* **Other Identifiers**: Any other unique identifying number, characteristic, or code.


### Map Data Flow

Create a detailed map showing how data moves through your systems. Include data collection points, storage locations, processing steps, and transmission paths.

Highlight where PHI and identifiers are collected, stored, or transmitted.


### Minimize PHI Exposure



1. **Collect and Store Minimal PHI:**
    * Gather only the essential PHI needed for your systems’ functionality to reduce compliance burdens and risks.
2. **Use De-identification and Anonymization Techniques:**
    * **De-identification**: Remove or mask specific identifiers to further lower the burdens and risks.
    * **Anonymization**: Apply techniques to ensure data cannot be re-identified, offering higher privacy assurance but with trade-offs in data utility, complexity, cost, and flexibility. De-identification often strikes a better balance, offering sufficient privacy protection while preserving data usability.
    * **Key Uses**: These techniques can be particularly useful for data stored at-rest, internal use, sharing with third-party vendors, data analytics and research, public sharing and publications, and training and education.
3. **Evaluate Application Performance:**
    * Assess whether your application can function effectively with reduced PHI or with de-identified or anonymized data.
4. **Periodic Evaluation:**
    * Regularly assess data flows and storage practices to minimize PHI exposure and continuously apply best practices for data protection to mitigate risks.


### Implement Safeguards

For all identified PHI and relevant identifiers, implement appropriate administrative, physical, and technical safeguards to protect the data, as outlined in the HIPAA Security Rule.


### Use Business Associate Agreements (BAAs)

Ensure that any business partner or subcontractor handling PHI signs a BAA and is considered a business associate.


### Risk Analysis and Management

Conducting a thorough risk assessment helps identify potential vulnerabilities in your systems that could compromise PHI. Follow these steps:



1. **Identify Assets**: List all systems, applications, and data repositories that store or process PHI.
2. **Identify Threats and Vulnerabilities**: Determine potential threats (e.g., unauthorized access, data breaches) and vulnerabilities (e.g., weak passwords, outdated software).
3. **Evaluate Risks**: Assess the likelihood and impact of each threat exploiting a vulnerability.
4. **Mitigation Strategies**: Implement security measures to reduce risks (e.g., encryption, access controls).

Regularly review and update your risk assessment to adapt to new threats and vulnerabilities. 

Tools like [ONC’s HIPAA Security Risk Assessment Tool](https://www.healthit.gov/topic/privacy-security-and-hipaa/security-risk-assessment-tool) can be helpful in this process. The tool is designed to help conduct a security risk assessment as required by the HIPAA Security Rule.


### Developing a Compliance Plan

A compliance plan outlines how your business will adhere to HIPAA regulations. Key components include:



* **Policies and Procedures**: Document your organization's policies for handling PHI, including data access, storage, and transmission.
* **Training Programs**: Ensure all employees understand HIPAA requirements and your organization's policies through regular training sessions.
* **Incident Response Plan**: Establish a plan for responding to data breaches, including notification procedures and mitigation strategies.

Ensure your compliance plan is comprehensive, regularly updated, and accessible to all employees.


### Setting Compliance Goals and Milestones

Setting clear compliance goals and milestones helps track your progress and ensure timely completion of necessary tasks. Consider the following steps:



1. **Define Goals**: Identify specific, measurable goals for achieving HIPAA compliance (e.g., implementing encryption, conducting employee training).
2. **Create a Timeline**: Develop a timeline with milestones for each goal, prioritizing tasks based on their impact on compliance.
3. **Assign Responsibilities**: Allocate tasks to specific team members, ensuring accountability and clear communication.
4. **Monitor Progress**: Regularly review progress towards your milestones, adjusting the timeline and resources as needed.
