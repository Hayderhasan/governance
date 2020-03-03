	
 **3.1**
* Since it isn’t feasible or practical to do individual verification of the cloud provider service’s security, then the solution is of a uniform audit by an independent third party expert who creates a standardised report for the cloud provider to pass it on to customers and prospects is a cost-efficient and reasonable solution to this problem. 

  **3.2**
* Auditing should be done according to the ISAE 3000 (Revised) standard, which is a high-level auditing standard.
* Audits for the implementation of C5 are carried out with as an “attestation engagement” type of assurance.
* The starting point of the audit for the auditor is called the written assertion or written statement.
* When there are special questions regarding the auditing procedure, documentation and reporting, other standards are to be referred to such as ISAE 3402 or IDW PS 951 (new version) or AT section 801 and/or AT section 101.
* There are additional expectations required by BSI besides the standards mentioned above.
* Auditing criteria needs to be based on: relevance, completeness, reliability, neutrality, comprehensibility. This ensures a good assessment for the cloud service by the cloud provider themselves and by an independent auditor.
  **5.1** **Organisation of information security**
* Objective: organisation of information security (to make sure the organisation is correctly utilising a framework regarding information security).
* **OIS-01** ISMS (Information Security Management System): this system should be based on ISO standards of the 2700x series. It should allow for planning, implementing the plan and carrying out the project, reviewing performance and eliminating discovered weaknesses.
* In case the cloud provider cannot submit a certification of its ISMS, the effectiveness of it can be assessed by auditing: OIS-02, OIS-07, SA-01 and 02 and 03, SPN-01.
* The certification of the ISMS should be valid according to ISO/IEC 27001:2013 or ISO 27001 on the basis of IT- Grundschutz.
* **OIS-02** Strategic targets regarding information security and responsibility of the top management: it is required that a security policy with parameters and objectives is documented.
* The security objectives are derived from the corporate objectives and business processes, relevant laws and regulations as well as the current and future expected threat environment with respect to information security 
* Whereas the general security objectives and a strategy to achieve these objectives have to be formulated concisely in the security policy, it typically does not include organisational and technical details. 
* **OIS-03** Authorities and responsibilities in the framework of information security: Depending on the cloud model (IAAS, PAAS or SAAS), responsibilities shared between the cloud provider and customer and other duties should be clearly documented. Furthermore, these roles should be described by the security policy of the cloud provider: Head of IT (CIO), IT Security Officer (CISO) and Representative for the handling of IT security incidents (e. g. Head of CERT) .
* Any changes should be reported in a timely manner to have the appropriate amount of time to apply those changes.
* The appropriateness of the assignment of roles and responsibilities to one or several persons at the cloud provider must be assessed against the backdrop of the size and complexity of the organisation. 
* **OIS-04** Separation of functions: the roles should be separated with respect to the confidentiality, integrity and availability of information of the cloud customers. 
* Controls for the separation of functions are established in the following areas:
  * Administration of roles, granting and assignment of access authorisations for users under the responsibility of the cloud provider.
  * Development and implementation of changes to the cloud service.
  * Maintenance of the physical and logical IT infrastructure relevant to the cloud service (net- works, operating systems, databases) and the IT applications if they are in the cloud provider’s area of responsibility according to the contractual agreements with the cloud customers.
* Any function separation conflicts should be documented by the cloud provider. If it isn’t possible to achieve a separation of duties, appropriate compensating controls are established in order to prevent or uncover improper activities.
* **OIS-5**Contact with relevant government agencies and interest groups:
  They should always be informed about current threat scenarios and countermeasures. Examples of contacts: BSI, OWASP, CERT.
* **OIS-6**Policy for the organisation of the risk management: Policies and instructions for the general proce-dure applicable to the identification, analysis, assessment and handling of risks and IT risks in particular are documented, communicated and provided according to SA-01 
* **OIS-7**Identification, analysis, assessment and handling of risks:
  The procedures for the identification, analysis, assessment and handling of risks, including the IT risks relevant to the cloud service are done at least once a year in order to take internal and external changes and influencing factors into account. 
  The identified risks are comprehensibly documented, assessed and provided with mitigating safeguards according to the safeguards of the risk management. 
* If business processes for the development and/or operation of the cloud service are outsourced to other service companies, the cloud provider still remains responsible for these risks. 
  **5.2** **Security policies and work instructions**
* Objective: providing policies and instructions with respect to the security claim and to support the business requirements. 
* **SA-01** Documentation, communication and provision of policies and instructions:
  Policies are documented clearly  and versioned and approved by top management of the cloud provider. 
* The policies should describe at least: goals, scopes of application, roles and responsibilities, coordination of different company departments, * Security architecture and safeguards for the protection of data, IT applications and IT infrastructures which are managed by the cloud provider or third parties, Safeguards for the compliance with legal and regulatory requirements (compliance) .
* **SA-02**  Review and approval of policies and instructions:
  They are reviewed by specialists at least once a year. The following aspects should be taken into account:
  Organisational changes at the cloud provider, current and future expected threat environment regarding information security, legal and technical changes in the cloud provider’s environment .
* The regular review is followed up by central bodies at the cloud provider. 
* **SA-03** Deviations from existing policies and instructions:
  Exceptions of policies are approved by committees or bodies of the cloud provider authorised to do so. They should be reviewed at least once a year.
  **5.3** **Personnel**
* Objective: making sure that employees, service providers and suppliers understand their tasks and responsibility.
* **HR-01** Security check of the background information:
  It should be done through:  Verification of the person by means of the identity card, Verification of the curriculum vitae, Verification of academic titles and degrees, Request of a police clearance certificate for sensitive posts in the company.
* Special approval is needed for employees who will be granted access to particularly sensitive information.
* **HR-02** Employment agreements:
  include the obligations of the cloud provider’s internal and external employees to comply with relevant laws, regulations and provisions regarding information security.
* **HR-03** Security training and awareness-raising programme:
  It should be available and mandatory for all internal and external employees of the cloud provider.
* The programme includes at least the following contents: 
  Regular and documented instruction on the secure configuration and secure operation of the IT applications and IT infrastructure required for the cloud service, Regular and documented instruction on known basic threats and Regular and documented training on the behaviour in case of security-relevant events. 
* **HR-04** Disciplinary measures:
  Implemented in order to make the consequences of violations of the applicable policies and instructions as well as legal provisions and laws transparent. 
* **HR-05** Termination of the employment relationship or changes to the responsibilities:
  The obligations to comply with the laws regarding information security remain the same even if the area of responsibility changes or the employment relationship is terminated. 
  **5.4** **Asset Management**
* Objective: Identifying the organisation’s own assets and the persons responsible and ensuring an appropriate level of protection. 
* **AM-01** Asset Inventory:
  The assets used to render the cloud service are identified and inventoried. This inventory should remain safe and complete. A history of the changes should be kept.
* The cloud service provider should be able to promptly detect which cloud customers are affected by a failure in one of the assets to ensure a response.
* **AM-02** Assignment of persons responsible for assets:
  All inventoried assets are assigned to a person responsible on the part of the cloud provider. 
* **AM-03** Instruction manuals for assets:
  Policies and instructions with technical and organisational safeguards for the proper handling of assets are documented, communicated and provided according to SA-01 in the respectively current version. 
* **AM-04** Handing in and returning assets:
  All internal and external employees of the cloud provider are obliged to return or irrevocably delete all assets which were handed over to them in relation to the cloud service and/or for which they are responsible as soon as the employment relationship has been terminated. 
* **AM-05** Classification of information:
  The cloud provider uses a uniform classification of information and assets which are relevant to the development and rendering of the cloud service. 
* The classification should consider:  Criticality for the rendering of the cloud service, Sensitivity to unauthorised disclosure or  modification,  Data type, Applicable legislation of the assets, Geographical location, Context, Legal restrictions, Contractual restrictions, Value.
* **AM-06** Labelling of information and handling of assets:
  The labelling of information must be carried out after the classification has been performed and is usually the responsibility of the asset owners. 
* **AM-07** Management of data media:
  Policies and instructions with technical and organisational safeguards for the secure handling of data media of any type are documented, communicated and provided  according to SA-01. They should consider:
  Policies and instructions should take the follow- ing aspects into account: 
  The secure and irrevocable deletion of the data and disposal/destruction of the data media, Encryption of removable media, Transmission of data to new data media when a medium is replaced.
* **AM-08** Transfer and removal of assets:
  Devices, hardware, software or data may only be transferred to external premises after it has been approved by authorised committees or bodies
  of the cloud provider. The transfer should occur securely.
