#### Risk = **uncertainty + potential impact**
- **Uncertainty** → it may or may not happen
- **Impact** → if it happens, it causes loss, damage, or disruption
# Risk Management:

The process of Identifying, Analyzing, treating, monitoring and reporting risk.
## Steps:
1. **Risk Identification**
	- Recognize risk that could -vely effect the organization.
	- follow up - business impact analysis

2. **Risk Analysis**
	- Analyzing potential impact of the risk. 
	- Type :
		- **Qualitative** 
			- Subjective and high-level view of risk
			- descriptive and categorical scales.
			- assessing risk based on their potential impact and likelihood
			- Low, Medium, High
		- **Quantitative** 
			- Objective and numeric evaluation of risk
	- Prioritize risk based on their severity.

3. **Risk Treatment**
	- manage identified risks
		- risk avoidance
		- risk reduction
		- risk sharing
		- risk acceptance 
		
4. **Risk Monitoring** 
	- On going process
	- tracking identified risks
	- monitoring residual risk
	- identifying new risk
	- reviewing the effectiveness of the risk management process.

5. **Risk reporting**
	- communicating risk info and effectiveness of risk management process with all the stakeholders
	- Dashboards
	- heat maps
	- detailed reports
## Risk Assessment Frequency
- When are risk assessment conducted in an organization 
- #### Adhoc :
	- as and when needed
	- in response to some events
		- new risks introduced
		- change in the older risks
	- Example:
		- launch of new product 
		- natural disaster
		- Change in regulations
- #### Recurring :  
	- In regular intervals.
	- part of SOP
	- annually, quarterly, monthly, etc.
	- Example:
		- tech company doing Pen testing quarterly 
- #### One-time :
	- Conducted for specific purpose 
	- **not repeated** unlike adhoc risk assessments  
	- example:
		- Implementing new IT system
		- construction project
		- organizational changes
- #### Continuous :
	- Ongoing monitoring and evaluation of risks.
	- Real-time data collection and analysis 
	- example:
		- cybersec team use continuous risk assessment to monitor threat and vulnerabilities 

### Risk Identification:
- proactive approach 
- identify vulnerabilities and threats
- financial risk 
- operational risk 
- strategic risk
- Reputational risk

- **Techniques :**
	- brainstorming
	- checklists
	- interviews
	- scenario analysis

- **Business impact analysis** (BIA):
	- what is the impact on the business of the risk
	- how quickly the business and process need to be recovered after disruption.

	- **RTO (Recovery time objective)** 
		- System downtime tolerance 
		- max time before the lack of business function severely impacts the organization.
		- example:
			- e-commerce website down due to server failure 
			- 2hr of downtime is only the company can afford
			- RTO - 2hr

	- **RPO (Recovery point objective)**
		- Data loss tolerance.
		- point of time in which data must be resorted to resume business operations.
		- example:
			- If a system fails, max of 10 mins of data loss is accepted.
			- So, You need backups at least every 10 minutes
	
	- **MTTR (mean time to repair)**
		- Average time to repair a failed component or system.
		- example:
			- A factory having a machine and it stop working every month with an average time to repair of 4hrs

	- **MTBF (mean time before failure)**
		- Average time btn failures of system / components.
		- Measures reliability.

### Risk Register - Risk management tool
- a.k.a. Risk log
- Detailed **document** of identified risks
- Shared btn share-holders
- **Contains :**
	- **Risk description**
	- **Risk impact**
		- low, medium, high
	- **Risk likelihood**
		- Probability of risk occurring  
	- **Risk outcome**
		- result of risk
		- directly related to risk impact and likelihood
		- helps in understanding overall effect of the risk on the project
	- **Risk level**
		- prioritize the risk using risk impact and likelihood
		- high, medium and low
	- **Cost**
		- Financial impact on the project
		- cost of mitigating the risk.
- **Risk tolerance :**
	- Max amt of risk organization is ready to accept.
	- reason :
		- level of risk not justifying the cost
		- unavoidable delay before counter measure be deployed.
### Risk Appetite :
- org approach towards risk taking.
- willingness to take on a risk.
- **Expansionary risk appetite :**
	- org is ready to take more risk in the hopes of achieving higher results
- **Conservative risk appetite :**
	- org prefer to take less risk - even if it means it leads to lower returns
- **Neutral risk appetite :**
	- balance btn risk and return.

### Key Risk Indicators (KRI) :
- Predictive metric 
- Signal rising risk levels before a problem actually happens. 
- Allow org to take **proactive** steps to manage the risk before it escalates.
- Example:
	- Number of failed login attempts increase
	- Unpatched vulnerabilities count increase

### Risk Owner :
- Person or grp responsible for managing the risk.

### Quantitative Risk Analysis :
- Objective and numeric view of the risk.
- Evaluation of risk using numeric measurements.
- <u>Component used in Quantitative Risk Analysis</u> :
	- #### Exposure Factor (EF) :
		- Proportion of asserts lost in an event.
		- **in %**
			- 0% - no loss
			- 100% - total loss
	- #### Single Loss Expectancy (SLE) :
		- **Monetary** value expected to be lost in a single event.
		- **SLE = Assert value * EF**
	- #### Annualized Rate of Occurrence (ARO) :
		- Estimated frequency with which a threat is expected to occur within a year.
	- #### Annualized Loss Expectancy (ALE) :
		- Expected Annual loss from a risk
		- **ALE = ARO * SLE**

### Risk Management Strategy (Risk treatment) :
#### Risk transference (risk sharing) :
- **Shifting** risk from org to another party.
- **Don't** eliminate he risk 
-  Done through:
	- insurance
	- contract indemnity clauses. 
#### Risk Acceptance :
- Recognizing the risk.
- No measure to mitigate immediately  
- address it when arises.
- ways:
	- ##### Exemption
		- Provision that allow a party to be exception from a specific rule or requirement.
		- example:
			- Financial regulation - A small fintech company is exempted from certain reporting requirement. No administrative burden of compliance as well.   
	- ##### Exception
		- Provision that permit a party to bypass a rule in **certain situation**. 
#### Risk Avoidance :
- Change in plans or approaches to completely eliminate a specific risk.
#### Risk Mitigation :
- implementing measure to decrease the likelihood or impact of a risk.

### Risk Monitoring and Reporting :
- tracking  identifying risks
- assessing new risks
- response
- evaluating their effectiveness during project lifecycle.
- help in identifying 
	- **Residual risk**
		- likelihood and impact of a risk after its mitigation, transference, acceptance measures
	- **Control risk**
		- assessment of how much security measure has lost its effectiveness overtime.
		- Example:
			- Anti-virus Software used to work on signature 
			- now they are no more effective as hackers have started to hide their code.
- **Risk report** :
	- used to report the details on risk to higher management and stakeholders
	- monthly risk report, yearly risk report etc.
- This process ensure following:
	- **Informed Decision making**
	- **Risk mitigation**
	- **Stakeholder communication**
	- **Regulatory compliance**