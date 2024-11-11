# Quality Requirements
[*Optional Section, not currently used*]
Since quality requirements will have a lot of influence on architectural decisions you should know for every stakeholder what is really important to them, concrete and measurable.

Quality Requirements are often also referred to as "Non-Functional" Requirements, and there implementation is dealt with in detail in the Well Architected Frameworks of [AWS](https://aws.amazon.com/architecture/well-architected/) and [Azure](https://learn.microsoft.com/en-us/azure/well-architected/).

Both AWS and Azure use the same categories, known as "pillars". Neither frameworks mention "Usability", but we include it here for completeness:
 - **Cost Optimization**: Cloud Financial Management, Expenditure and usage awareness, Cost-effective resources, Demand and supply Resource Management, Resource Optimization over time
 - **Operational Excellence**: Procedures, DevOps, Observability, Remedition, Risk Mitigation
 - **Performance Efficiency**: Throughput, Scalabilility Latency, Monitoring, Data, Compute, Network
 - **Reliability**: Resiliency, Availability, Recovery
 - **Security**: Data Protection, Threat Detection,  Mitigation
 - **Sustainability**: Region selection, Alignment to demand, Software and architecture, Data, Hardware and services, Process and culture
 - **Usability**: Error handling, User Documentation, User Experience, Internationalization, Localization, Accessibility, Personalization, Customization

A full analysis and comparison of the WAF frameworks is included in this [spreadsheet](./WAF-Checklists.xlsx)

In the following sections we provide some examples of questions for each of the pillars.

<br>

## Sample Questions for Pillars
### Cost Optimization
 - Who is responsible for Cost Optmization and how is the team organized? 
 - What is the Finanancial/ Cost Model?
 - How are spending guardrails - budgets and forecasts, specified and enforced?
 - How is usage and cost data monitored, collected and reviewed?
 - How are resource demand and supply managed?
 - How are resource costs optimized?
 - How are end-of-life resources identified and decommissioned?
 - How is technical debt identified and removed?"
 - How are potential financial risks mitigated?
 - What is the market and financial strength of the Service Provider?
 - How mature are the products / services used and how strong is their roadmap?
 - Which [Cost Optimization Design Patterns](https://learn.microsoft.com/en-us/azure/well-architected/cost-optimization/design-patterns) are applicable?

<br>

### Operational Excellence
- How are Engineering and Operations organized into an Operating Model?
- How are routine and emergency operational tasks formalized?
 - How are DevOps principals and practices applied to ensure workload quality?
 - How is the system instrumented and monitored?
 - What is the Emergency Response Strategy?
 - To what degree can changes to components be anlayzed and implemented without affecting other components
 - How easily can the system be installed modified, adapted…?
 - Which [Operational Excellence Design Patterns](https://learn.microsoft.com/en-us/azure/well-architected/operational-excellence/design-patterns) are applicable to this system?

<br>

### Performance Efficiency
 - How many concurrent users/ sessions are expected? 
 - Maximum Rate of transactions/ messages per second/minute…? 
 - Type of Message Delivery required: In order? At Most Once? At Least once?
 - How large are the transactions/ messages?
 - How does the system scale to meet varying load? 
 - How quickly must the system respond in key scenarios? 
 - How is system performance measured?
 - How much data is stored currently?  
 - Does existing data have to be migrated and/or transformed? 
 - What is the expected growth in the volume of data - daily/weekly…? 
 - How is data stored, managed, and access controlled?
 - How are networking resources selected and configured?
 - How are compute resources selected and used ?
 - What processes are employed to support optimum performance efficiency?
 - With which external systems and standards must the system be compatible?
 - Which [Performance Efficiency Design Patterns](https://learn.microsoft.com/en-us/azure/well-architected/performance-efficiency/design-patterns) are applicable to this system?

<br>

### Reliability
 - Which User and System Flows exist and how are they prioritized?
 - What potential failures could occur and what are their associated risks and effects?
To what excent can the system continue operation despite these failures?"
 - How frequently can failures occur?
 - How long can the workload be unavailable (Recovery Time Objective - RTO)?
 - How much data is it acceptable to lose during a disaster (Recovery Point Objective - RPO)?
 - Are there any availability targets such as Service Level Agreements (SLAs) or Service Level Objectives (SLOs)?
 - What is the plans for Business Continuity and Disaster Recovery?
 - Which [Reliability Design Patterns](https://learn.microsoft.com/en-us/azure/well-architected/reliability/design-patterns) are applicable to this system?


<br>

### Security
 - What potential threats exist to this workload/component?
 - How are corporate or legal requirements for compliance and governance fulfilled?
 - How the must security principals (humans and machines) be Authenticated and Authorized? 
 - What kinds of network controls are required to detect, filter or block intrusions and attacks?
 - How are the requirements for encryption of data at rest, in transit and in use fulfilled?
 - Where the can the IT Infrastructure (Compute, Data, Network…) be located?
 - From where can users or external systems access this workload/component?
 - How is workload data classified according to sensitivity?
 - How is the system monitored and threats detected?
 - How are actions on the system logged?
 - What incident response procedures are required?
 - How will the Software Development Lifecycle be secured?
 - Which [Security Design Patterns](https://learn.microsoft.com/en-us/azure/well-architected/security/design-patterns) are applicable to this system?

<br>

### Sustainability
 - What are the organization's policies with regard to Sustainability?
 - Can the solution help sustainability through the cloud?
 - How is the optimum utilization of resources achieved?
 - Where are the optimum locations for resources?
 - How are potential environmental risks mitigated?
 - Which [Sustainability Design Patterns](https://learn.microsoft.com/en-us/azure/well-architected/sustainability/sustainability-application-design) are applicable to the System?

<br>

### Usability
 - How is the Funcional Suitability (appropriate, complete, correct targeted) of the system ensured?
 - How are potential risks to people mitigated?
 - How are user and system errors reported to the user and logged?
 - How do users learn to use the system effectively? 
What Manuals, wikis, help and other documentation are required for users?
 - How does the system enable usage in an intuitive and pleasing way?
 - How must the system adapt to different countries and regions?
 - How are people with disabilities enabled use to the system?
 - How is the user experience adapted to specific user profiles?
 - How can the end-user adapt  the system?





[Back](../README.md)
