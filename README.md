# CloudNativePrinciples

## Business

1. There must be a discussion and agreement with the business about the implications of using cloud hosting (including the switch from capex to opex spending and responsibilities for budget control).
   * Defined agreements around liability for uncontrolled spend.
   * Defined agreements around hard and soft limits on spending
   * Defined agreement on the process to be followed where spikes in demand might exceed budgets
      * spike arrest / traffic throttling.
   * Defined agreements on process taken where budget runs out or payment is queried or project reaches eol.
   * Defined agreements on the circumstances in which services may be turned off (e.g. in response to denial of service, malware attacks, no up-to-date contacts for the business and billing aspects of the service).
   * Defined agreements on the hours of service availability and implications of events occuring OOH.
2. There must be regular discussions on the sustainability and road-map for the service from a business point of view.
2. There should be regular reviews of the configuration and architectureof services provided - to consider improvements to security, resilience, capacity and cost-effectiveness. 
3. There must be named __business owner__, __billing owner__ and __technical owners__ of services for which Azure resources are created - it is digital service's responsibility to maintain the technical contact details and the responsibility of hte client to maintain details of the billing and business owner contacts.
4. Appropriate agreements must be in place to provide monitoring of the service, including (as close as possible to ) real-time indicatin of costs incurred.
 
## Use of 3rd Parties
1. There should be defined agreements with the 3rd party and the business around liability and indemnification for the actions and inactions of the 3rd party supplier.
2. Where 3rd parties are being collaborated with discussions, defined agreements and risk-assessments must include consideration of the implications of this.

## Risk Assessment, documentation and monitoring
1. Each service will be documented and the documentation regularly reviewed to ensure that is it up to date.
2. There must be an appropriate risk-assessment and this should specifically include risks assoicated with the chosen hosting platform.
3. Services must have monitoring in place that will 


## Security
Adherence to cloud security principles https://www.ncsc.gov.uk/guidance/implementing-cloud-security-principles


## Interoperability
Consideration must be given to 



