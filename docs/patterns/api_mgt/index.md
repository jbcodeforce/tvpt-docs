# Modernization from API lifecycle

In this note we summarize some of the best practices to introduce API management in their development practices and architecture patterns.

## Move from a pure API gateway to API management

API Gateway helps provide security, control, integration, and optimized access to a full range of mobile, web, application programming interface (API), service-oriented architecture (SOA), B2B and cloud workloads. Gateways are used in the following patterns:

* Security Gateway, placed between the consumer facing firewall and the system of records facing firewall (DMZ), it is used for both policy enforcement and consistent security policies across business channels.
* API gateway, both as internal and external gateway, with centralized service governance and policy enforcement, and with traffic monitoring.
* Providing connectivity (HTTP) and mediation (XML, JSON) services in the internal network, close to the system of record. 

Adopting a broader scope for API lifecycle using API management product to address:

* API lifecycle management to active, retire, or stage API product.
* API governance with security, access, and versioning.
* Analytics, dashboards, third party data offload for usage analysis.
* API socialization based in a portal that allows self-service for developer community.
* API developer toolkit,

### Classical pain points

When the following pain points are becoming more important, it is time to consider adopting a broader API management product:

* The current API details like endpoints, request/response message format, error conditions, test messages,
SLAs are not easily available.
* Difficult to tell which subscribers are really using the API and how often, without building a custom solution.
* Difficult to differentiate between business-critical subscribers versus low value subscribers.
* No dynamic scaling that is built into the solution, which often means making hardware investment for max load or worst availability scenario.
* Difficult to move from SOAP based web service to RESTful services
* No support of AsynchAPI
* Ensure consistent security rules
* Integrating CI/CD pipelines with API life cycle

## Enterprise APIs across boundaries


## Further Readings

* [Agile integration IBM red book](https://www.redbooks.ibm.com/abstracts/sg248452.html)