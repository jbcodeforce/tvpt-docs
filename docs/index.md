# Travelport
Travelport Worldwide Ltd, headquartered in Langley, Slough, UK, provides distribution, technology, and payment solutions for the travel and tourism industry. It is one of the top three global distribution systems after Amadeus IT Group and Sabre Corporation. 

# Travelport Event-Driven Microservice practices
Welcome to this site! This site shares some best practices for adopting a  cloud native, event-driven microservice implementation using Kafka, CI/CD pipeline, Spring Boot Cloud Stream, and API Management.

## Travelport MVP

The Travelport MVP is a simple proof of technology running on the IBM Cloud that presents the following components:

![](./images/rail-booking.png)

In essence, Travelport wanted to develop the basic skeleton of an API that will allow for shopping trips through two or more different vendors, comparing features/prices through normalized content, and creating a train booking. 

Through this API, their Rail developers should receive normalized content from the train consolidators, so that they don’t have to handle vendors’ content differences. The API needs to support incremental change and be backward compatible. 

The main purpose of this initial MVP was to serve as a template for best practices around applied Domain Driven Design (DDD), and the use of Kafka.

The MVP will allow Travelport to utilize patterns, observe best practices and understand the capabilities of the future toolstack.

### Key Dates

* <b>14th May</b> (API Management Demo #2)
* <b>7th May</b> (DevOps pipeline/Argo CD. Non-breaking changes) 
* <b>30th April</b> (Addition of SNCF alongside live Trainline API content. Mongo DB storage of reservation) 
* <b>27th April</b> (API Management Demo #1) 
* <b>15th April</b> (Demo of Event Driven Architecture with Domain and Atomic Services for Trainline API) 
* <b>6th April</b> (Initial Event Driven Architecture with Domain and Atomic Services demonstrated through OpenShift)
* <b>12th March</b> (Inception meeting, User Story definition begins, Infrastructure build begins). 

### MVP Toolstack & Principles

For the MVP toolstack, Travelport dictated the following principles:
* The selection will utilize open source where possible.
* Where a licensed product is used it should be for quantified reasons considering the full lifecycle / Scale costs.
* Any product selected must be industry best practice and market dominant to ensure portability / future proof / and skills accessibility.
* Products must consider the entire lifecycle including deployment, support, monitoring, visualization, infrastructure etc.
* Leading edge not bleeding edge.
* The entire framework solution must have the least possible integration and customization possible.


### Repositories for the MVP
We created the following repositories in GitHub for this MVP:

* [Rail Query](https://github.com/Travelport-Enterprise/rail-shop-domain)
* [Shop atomic](https://github.com/Travelport-Enterprise/trainline-shop-atomic) Trainline atomic transforms the Rail catalog request to Trainline request and vice versa

## Code you can access too

* [EDA Reference Implementation with polyglot microservices, CI/CD, SAGA, SQRS](https://ibm-cloud-architecture.github.io/refarch-kc/)
* [IBM active - open source EDA content](https://ibm-cloud-architecture.github.io/refarch-eda/) with labs, and technology practices
* [A repository to get started with more than hello world on EDA implementation](https://github.com/ibm-cloud-architecture/eda-quickstarts)
* [Implementation of the Outbox pattern with Debezium in Quarkus](https://github.com/ibm-cloud-architecture/vaccine-order-mgr-pg)
* [MQ source to Kafka Lab with Strimzi or Confluent](https://github.com/ibm-cloud-architecture/eda-lab-mq-to-kafka)
* [Kafka Connector Sink lab for Mongodb](https://github.com/ibm-cloud-architecture/eda-lab-mongodb)

Most of those repositories are work in progress. You can ask for improvement via git issue, by opening a PR.

For additional details, you can navigate through the different topics in this site or search for a particular topic of interest. Enjoy!