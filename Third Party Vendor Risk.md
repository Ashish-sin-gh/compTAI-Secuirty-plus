# THIRD PARTY VENDOR RISK
- Potential Security and operational Challenge introduced by external entities in an organization.
- Vendors, service providers, suppliers
### Supply Chain Risk
- **Hardware manufactures**
	- all the components to make that hardware must be checked too.
	- after market hardware devices must be thoroughly checked for trojans or RAT in their code.
- **Software and software providers**
	- licensed software 
	- free of vulnerability and bugs
	- scan software with NGAV or anti malware solns
	- Do **vulnerability assessments** 
- **Managed Service Providers (MSP)**
	- evaluate data security measures
	- ensure confidentiality and integrity
	- assess cyber security protocols
	- response to the security breach
### Supply Chain Attacks
- It is an attack that take advantage of weakness in an external entity to the system to gain access to the target system.
- cisco | **chip washing** (2000-2010)
	- chip washing - repacking a chips content with cheap / malware contained functionalities .
- Deliberately embedding **rootkit** within devices by overseas suppliers 
	- Can be used against govts 
	- spy on them or steal sensitive data
- 2021 - Solarwinds Orion 
	- one of the biggest s/w based supply chain attack 
	- **infiltrated s/w update and used it to distribute malware** 
	- compromised n/w of huge population and organizations (including govt) 
- Preventions:
	- **Vender due diligence**
	- **Regular monitoring and audit**
	- **Education and collaboration**
	- **Contractual safeguards**
### Vendor Assessments 
- Vendors: 
	- businesses or individuals that provide goods or services
	- Example: Microsoft
- Suppliers
	- Businesses / Individuals involved in delivery/ production of products
- Managed service providers (MSPs)
	- Individuals hired by a company to  manage IT service on behalf of an organization.
	- Example: AWS

- #### Penetration Testing:
	- Simulated cyberattack against the suppliers system to check for exploitable vulnerabilities.

- #### Right to audit clause:
	- hiring company is allowed to audit and assess the vendor periodically to ensure CIANA is being implemented 
	- not 'Lack of Trust'
	- method to ensure **transparency**. (Trust but verify) 

- **Internal audit**:
	- Vendors self assessments
	- share it with the hiring company.

- **Independent assessments: **
	- Evaluation conducted by third party entities.
	- ISO audit, SOC2 audit

- **Supply Chain Analysis:**
		- Assess vendor's supply chain

### Vendor Selection and Monitoring
#### Vendor Selection
- Look out for:
	- **Due Diligence** 
		- Financial stability 
		- operational history
		- client testimonials 
		- on-the-ground practice
	- **Conflicts of interest**
	- **Vendor Questionnaires**
		- Example : if vendor is a cloud provider
			- data redundancy measures
			- security protocols
			- uptime guarantees
			- disaster recovery plans
	- **Rules of engagement**
		- Terms of interaction btn organization and potential vendor
		- Cover aspects like
			- communication protocols
			- data sharing policies
			- negotiation boundaries
#### Monitoring
- Way to ensure that selected vendor still align with organizational needs and standards.
- **Performance reviews**
- **Feedback loops**
	- 2-way communication model, where both organizations and vendor share feedbacks. 
	- Collaborative growth 
	- Refinements.

### Contracts and Agreements:
#### Basic Contract
- Formally establish a relationships btn parties.
- Dictates roles, responsibilities and repercussions.
#### Service level agreement (SLA)
- The type of services Client can expect from the vendor 
- example 
	- for a IT service vendor - 2 hour downtime max for the servers or client can charge a fee if fails 
#### MoA and MoU
- **Memorandum of Agreement**
	- formal 
	- Outline the roles and responsibilities of party involved.
- **Memorandum of Understandings** 
	- Less Binding 
	- Declaration of mutual intent 