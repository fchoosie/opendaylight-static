---
title: 'Platform Overview'
date: 2018-02-22T17:01:34+07:00
layout: page
bodyClass: page-about
---
OpenDaylight (ODL) is a modular open platform for customizing and automating networks of any size and scale. The OpenDaylight Project arose out of the SDN movement, with a clear focus on network programmability. It was designed from the outset as a foundation for commercial solutions that address a variety of use cases in existing network environments.

OpenDaylight is the most widely deployed open source SDN controller platform and in just 8 years, OpenDaylight boasts 13 releases, 1000+ authors/submitters, 100K+ commits, and powers networks of 1B+ global subscribers.

OpenDaylight code has been integrated or embedded in more than 35 vendor solutions and apps, and can be utilized within a range of services. It is also at the core of broader open source frameworks, [including ONAP](https://www.onap.org/).

As part of [LF Networking](http://www.lfnetworking.org/), ODL is driven by a global, collaborative community of vendor and user organizations that continuously adapts to support the industry’s broadest set of SDN and NFV [use cases](/use-cases/).

### The OpenDaylight Architecture

### Model-Driven

The core of the OpenDaylight platform is the Model-Driven Service Abstraction Layer (MD-SAL). In OpenDaylight, underlying network devices and network applications are all represented as objects, or models, whose interactions are processed within the SAL.

The SAL is a data exchange and adaptation mechanism between YANG models representing network devices and applications. The YANG models provide generalized descriptions of a device or application’s capabilities without requiring either to know the specific implementation details of the other. Within the SAL, models are simply defined by their respective roles in a given interaction. A “producer” model implements an API and provides the API’s data; a “consumer” model uses the API and consumes the API’s data. While ‘northbound’ and ‘southbound’ provide a network engineer’s view of the SAL, ‘consumer’ and ‘producer’ are more accurate descriptions of interactions within the SAL. For example, protocol plugin and its associated model can either be a producer of information about the underlying network, or a consumer of application instructions it receives via the SAL.

The SAL matches producers and consumers from its data stores and exchanges information. A consumer can find a provider that it’s interested in. A producer can generate notifications; a consumer can receive notifications and issue RPCs to get data from providers. A producer can insert data into SAL’s storage; a consumer can read data from SAL’s storage. A producer implements an API and provides the API’s data; a consumer uses the API and consumes the API’s data.

### Modular and Multiprotocol

The ODL platform is designed to allow downstream users and solution providers maximum flexibility in building a controller to fit their needs. The modular design of the ODL platform allows anyone in the ODL ecosystem to leverage services created by others; to write and incorporate their own; and to share their work with others. ODL includes support for the broadest set of protocols in any SDN platform – OpenFlow, OVSDB, NETCONF, BGP and many more – that improve programmability of modern networks and solve a range of user needs.

Southbound protocols and control plane services, anchored by the MD-SAL, can be individually selected or written, and packaged together according to the requirements of a given use case. A controller package is built around four key components (odlparent, controller, MD-SAL and yangtools). To this, the solution developer adds a relevant group of southbound protocols plugins, most or all of the standard control plane functions, and some select number of embedded and external controller applications, managed by policy.

ODL is the primary place for the development and testing of different approaches to policy and intent such as ALTO, Group Based Policy and Network Intent Composition. We are working closely with a number of industry groups like Open Networking Foundation and IETF to vet and test the different approaches.

Each of these components is isolated as a Karaf feature, to ensure that new work doesn’t interfere with mature, tested code. OpenDaylight uses OSGi and Maven to build a package that manages these Karaf features and their interactions.

This modular framework allows developers and users to:

- Only install the protocols and services they need
- Combine multiple services and protocols to solve more complex problems as needs arise

- Incrementally and collaboratively evolve the capabilities of the open source platform
- Quickly develop custom, value-added features for highly specialized use cases, leveraging a common platform shared across the industry

### S3P: Security, Scalability, Stability and Performance

The ODL community provides continual improvements across all its projects in the areas of security, scalability, stability and performance, or “S3P”. Our Testing and Integration groups, along with people from each individual project, work together to run ongoing tests that give developers real-time results to see how changes affect S3P. We continue to evolve our development process to ensure that we can understand and monitor improvements in each of these four areas. ODL is also working with OPNFV in support of a Controller Performance Testing project that would create industry wide performance tests for SDN controllers in realistic, large, automated deployments.

Security is a key area of focus for ODL. The platform provides a framework for Authentication, Authorization and Accounting (AAA), as well as automatic discovery and securing of network devices and controllers. We have a strong security team and process to respond to any vulnerabilities immediately. In general, open source software has major advantages when it comes to security: anyone can find and report vulnerabilities; we can draw on a wide array of experts and developers across companies to discuss and fix vulnerabilities; and the community-at-large can see how such issues are addressed transparently and understand if the issue really has been fixed.

## Summary

The modularity and flexibility of OpenDaylight allows end users to select whichever features matter to them and to create controllers that meets their individual needs. We have a very supportive, growing and active community of hundreds of developers who are continuously evolving and expanding the platform.

## Learn More

- [Get started as a developer](/getting-started/)
- [View common use cases](/use-cases/)
- [Download the OpenDaylight platform and user guides](/getting-started/)
- [Review OpenDaylight Tutorials and other education materials](/getting-started/)
- [Read industry user stories](/use-cases/)
- [Find an OpenDaylight solution provider to get you started quickly](/solutions/)