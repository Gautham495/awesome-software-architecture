# 🎨 Awesome Software Architecture [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

[![Twitter URL](https://img.shields.io/badge/-@mehdi_hadeli-%231DA1F2?style=flat-square&logo=twitter&logoColor=ffffff)](https://twitter.com/mehdi_hadeli)
[![Linkedin Url URL](https://img.shields.io/badge/-mehdihadeli-blue?style=flat-square&logo=linkedin&logoColor=ffffff)](https://www.linkedin.com/in/mehdihadeli/)
[![blog](https://img.shields.io/badge/blog-dotnetuniversity.com-brightgreen?style=flat-square)](https://dotnetuniversity.com/)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-brightgreen.svg?style=flat-square)](http://creativecommons.org/publicdomain/zero/1.0/)
[![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)][tweet]

![](./banner.png)

> Curated list of awesome articles and resources to learn and practice about software architecture, patterns and principles. this repository will be updated continuously, keep yourself up to date

> **This awesome list is available here with better UI and searching feature: [https://mehdihadeli.github.io/awesome-software-architecture](https://mehdihadeli.github.io/awesome-software-architecture)**

Contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/mehdihadeli/awesome-software-architecture/blob/master/contributing.md) pages first.

Thanks to all [contributors](https://github.com/mehdihadeli/awesome-software-architecture/graphs/contributors), you're awesome and wouldn't be possible without you! The goal is to build a categorized community-driven collection of very well-known resources.


## Contents

- [Software Architecture](docs/software-architecture.md)
- [Architectural Style](docs/architectural-style.md)
  - [NLayer Architecture](docs/architectural-style/nlayer-architecture.md)
  - [Clean Architecture](docs/architectural-style/clean-architecture.md)
  - [Onion Architecture](docs/architectural-style/onion-architecture.md)
  - [Hexagonal Architecture](docs/architectural-style/hexagonal-architecture.md)
  - [Vertical Slice Architecture](docs/architectural-style/vertical-slice-architecture.md)
  - [Event Driven Architecture](docs/architectural-style/event-driven-architecture.md)
  - [Service Oriented Architecture](docs/architectural-style/service-oriented-architecture.md)
  - [Component Based Architecture](docs/architectural-style/component-based-architecture.md)
- [Architectural Design Principles](docs/architectural-design-principles.md)
  - [Crosscutting Concerns](docs/architectural-design-principles/crosscutting-concerns.md)
  - [Encapsulation](docs/architectural-design-principles/encapsulation.md)
  - [Dependency Inversion](docs/architectural-design-principles/dependency-inversion.md)
  - [Interface Segregation Principle](docs/architectural-design-principles/interface-segregation-principle.md)
  - [Single Responsibility](docs/architectural-design-principles/single-responsibility-principle.md)
  - [Open/Closed Principle](docs/architectural-design-principles/open-closed-principle.md)
  - [Command Query Separation](docs/architectural-design-principles/cqs.md)
  - [Favor Composition over Inheritance](docs/architectural-design-principles/favor-composition-over-inheritance.md)
  - [DRY](docs/architectural-design-principles/dry.md)
  - [KISS](docs/architectural-design-principles/kiss.md)
  - [YAGNI](docs/architectural-design-principles/yagni.md)
  - [Coupling](docs/architectural-design-principles/coupling.md)
  - [Cohesion](docs/architectural-design-principles/cohesion.md)
  - [Persistence Ignorance](docs/architectural-design-principles/persistence-ignorance.md)
  - [GRASP](#docs/architectural-design-principles/grasp.md)
- [Architectural Patterns](docs/architectural-patterns)
  - [Domain Driven Design - Domain Centric](docs/architectural-patterns/domain-driven-design/domain-driven-design.md)
    - [Aggregation](docs/architectural-patterns/domain-driven-design/aggregation.md)
    - [Anemic Domain Model](docs/architectural-patterns/domain-driven-design/anemic-domain-model.md)
    - [Application Service](docs/architectural-patterns/domain-driven-design/application-service.md)
    - [Bounded Context](docs/architectural-patterns/domain-driven-design/bounded-context.md)
    - [Domain Events](docs/architectural-patterns/domain-driven-design/domain-events.md)
    - [Domain Primitives](docs/architectural-patterns/domain-driven-design/domain-primitives.md)
    - [Domain Service](docs/architectural-patterns/domain-driven-design/domain-service.md)
    - [Enums](docs/architectural-patterns/domain-driven-design/enums.md)
    - [Exception And Validation](docs/architectural-patterns/domain-driven-design/exception-and-validation.md)
    - [Infrastructure](docs/architectural-patterns/domain-driven-design/infrastructure.md)
    - [Mapping](docs/architectural-patterns/domain-driven-design/mapping.md)
    - [Strategic Design Patterns](docs/architectural-patterns/domain-driven-design/strategic-design-patterns.md)
    - [Tactical Design Patterns](docs/architectural-patterns/domain-driven-design/tactical-design-patterns.md)
    - [Value Objects](docs/architectural-patterns/domain-driven-design/value-objects.md)
  - [Data Driven Design - Data Centric](docs/architectural-patterns/data-driven-design.md)
  - [CQRS](docs/architectural-patterns/cqrs.md)
  - [Event Sourcing](docs/architectural-patterns/event-sourcing.md)
  - [Microservices](docs/architectural-patterns/microservices/microservices.md)
    - [Distributed Tracing](docs/architectural-patterns/microservices/distributed-tracing.md)
    - [Observibility](docs/architectural-patterns/microservices/observibility.md)
    - [Reverse Proxy](docs/architectural-patterns/microservices/reverse-proxy/revers-proxy.md)
      - [YARP](docs/architectural-patterns/microservices/reverse-proxy/yarp.md)
      - [Envoy](docs/architectural-patterns/microservices/reverse-proxy/envoy.md)
    - [Service Discovery](docs/architectural-patterns/microservices/service-discovery/service-discovery.md)
      - [Consul](docs/architectural-patterns/microservices/service-discovery/consul.md)
    - [Tools](docs/architectural-patterns/microservices/tools/tools.md)
      - [Dapr](docs/architectural-patterns/microservices/tools/dapr.md)
      - [SteelToe](docs/architectural-patterns/microservices/tools/steeltoe.md)
      - [Tye](docs/architectural-patterns/microservices/tools/tye.md)
  - [Serverless Architectural Pattern](docs/architectural-patterns/serverless.md)
  - [MicroKernel Architectural Pattern](docs/architectural-patterns/micro-kernel.md)
  - [Modular Monolith](docs/architectural-patterns/modular-monolith.md)
- [Design Patterns](docs/design-patterns/design-patterns.md)
  - [Singleton](docs/design-patterns/singleton.md)
  - [Decorator Pattern](docs/design-patterns/decorator-pattern.md)
  - [Specification Pattern](docs/design-patterns/specification-pattern.md)
  - [Repository Pattern](docs/design-patterns/repository-pattern.md)
  - [Query Object Pattern](docs/design-patterns/query-object-pattern.md)
  - [Factory Pattern](docs/design-patterns/factory-pattern.md)
  - [Strategy Pattern](docs/design-patterns/strategy-pattern.md)
- [Cloud Design Patterns](docs/cloud-design-patterns/cloud-design-patterns.md)
  - [Ambassador Pattern](docs/cloud-design-patterns/ambassador-pattern.md)
  - [Anti Corruption Layer Pattern](docs/cloud-design-patterns/anti-corruption-layer-pattern.md)
  - [Bulkhead Pattern](docs/cloud-design-patterns/bulkhead-pattern.md)
  - [Circuit Breaker Pattern](docs/cloud-design-patterns/circuit-breaker.md)
  - [Exactly One Delivery](docs/cloud-design-patterns/exactly-one-delivery.md)
  - [Gateway Aggregation](docs/cloud-design-patterns/gateway-aggregation.md)
  - [Gateway Pattern](docs/cloud-design-patterns/gateway-pattern.md)
  - [Outbox Pattern](docs/cloud-design-patterns/outbox-pattern.md)
  - [Saga Pattern](docs/cloud-design-patterns/saga.md)
  - [Strangler Fig Pattern](docs/cloud-design-patterns/strangler-fig-pattern.md)
- [Object Oriented Design](docs/object-oriented-design.md)
- [Distributed Systems Design](docs/distributed-systems-design.md)
- [Scalable Software Architecture](docs/scalable-software-architecture.md)
- [Clean Code](docs/clean-code.md)
- [Design Best Practices](docs/design-best-practices/design-best-practices.md)
  - [12 Factor](docs/design-best-practices/12-factor.md)
  - [Strongly Type Ids](docs/design-best-practices/strongly-type-ids.md)
  - [Thin Controllers](docs/design-best-practices/thin-controllers.md)
- [Anti Patterns](docs/anti-patterns/anti-patterns.md)
  - [Code Smells](docs/anti-patterns/code-smells.md)
- [Messaging Patterns](docs/messaging/messaging.md)
  - [Kafka](docs/messaging/kafka.md)
  - [RabbitMQ](docs/messaging/rabbitmq.md)
- [Distributed Transactions](docs/distributed-transactions.md)
- [Concurrency](docs/concurrency.md)
- [Eventual Consistency](docs/eventual-consistency.md)
- [RESTful API Design](docs/rest.md)
- [Caching](docs/caching.md)
- [Aspect Oriented Programming](docs/aop.md)
- [Packaging](docs/packaging.md)
- [Refactoring](docs/refactoring.md)
- [Azure Application Architecture](docs/azure/azure-application-architecture.md)
  - [Azure Active Directory](docs/azure/azure-active-directory.md)
  - [Azure Functions](docs/azure/azure-functions.md)
  - [Azure Service Bus](docs/azure/azure-service-bus.md)
  - [Azure Template](docs/azure/azure-template.md)
  - [Azure Identity](docs/azure/azure-identity.md)
- [Modeling](docs/modeling/modeling.md)
  - [Architecture Diagram](docs/modeling/architecture-diagram.md)
  - [Class Diagram](docs/modeling/class-diagram.md)
  - [Component Diagram](docs/modeling/component-diagram.md)
  - [Conceptual Diagram](docs/modeling/conceptual-diagram.md)
  - [Conceptual Modeling](docs/modeling/conceptual-modeling.md)
  - [Data Modeling Notations](docs/modeling/data-modeling-notations.md)
  - [ER Diagrams](docs/modeling/er-diagrams.md)
  - [Logical Modeling](docs/modeling/logical-modeling.md)
  - [Physical Modeling](docs/modeling/physical-modeling.md)
  - [Relationship](docs/modeling/relationship.md)
  - [Tools](docs/modeling/tools.md)
  - [Use Case Diagram](docs/modeling/use-case-diagram.md)
- [Event Storming](docs/event-storming.md)
- [Engineering Blogs](docs/engineering-blogs.md)
- [Other](docs/other.md)


## Support ⭐
If you like my work, feel free to:

- ⭐ this repository. And we will be happy together :)
- [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)][tweet] about Awesome Software Architecture


Thanks a bunch for supporting me!

[tweet]: https://twitter.com/intent/tweet?url=https://github.com/mehdihadeli/awesome-software-architecture&text=A%20curated%20list%20of%20awesome%20articles%20and%20resources%20to%20learn%20and%20practice%20about%20software%20architecture%2C%20patterns%2C%20and%20principles&hashtags=dotnetcore,dotnet,csharp,microservices,netcore,aspnetcore,ddd,cqrs,softwarearchitecture,designpatterns,modularmonolith

