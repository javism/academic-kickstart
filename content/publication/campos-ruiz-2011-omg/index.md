---
title: "High-level Programming of DDS Systems"
date: 2011-03-01
publishDate: 2020-06-11T11:26:55.382159Z
authors: ["Alejandro de~Campos~Ruiz", "Gerardo Pardo-Castellote", "GianPiero Napoli", "Fernando Crespo-Sanchez", "J. Sánchez-Monedero"]
publication_types: ["0"]
abstract: "Analysis of the DDS API and the source code of typical DDS applications reveals three types of application code: (a) DDS Configuration and Setup code, (b) DDS Action code, and (c) Domain-Specific code that does not involve the use of the DDS API. If we discount the domain-specific code (c), which for the most part is independent of the middleware, we can see that in typical applications 80% of the DDS code is setup code. Moreover looking at the DDS API itself, we also see that about 50% of the API itself supports configuration and setup (e.g. QoS policy definitions, factory operations to construct entities) and only the remaining 50% supports action code. These observations suggest there can be tremendous benefits to providing a mechanism that allows application developers to configure the system declaratively and, in doing so, avoid the need to explicitly learn and use the Configuration and Setup part of the DDS API. We will present recent research on a new approach to developing DDS applications where the configuration & setup code is replaced with declarative statements written in XML and interpreted at run-time. We suggest extensions to the DDS standard API to allow the high-level programming approach to work on top of any DDS-compliant implementation."
featured: false
publication: "*Workshop on Real-time, Embedded and Enterprise-Scale Time-Critical Systems*"
url_pdf: "http://www.omg.org/news/meetings/realtime2011/program.htm"
---

