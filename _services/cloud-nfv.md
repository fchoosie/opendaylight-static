---
title: "Cloud & NFV"
date: 2018-11-28T15:14:39+10:00
featured: true
weight: 2
layout: service
---

Agile service delivery on cloud infrastructure in either the enterprise or service provider environment. The underlay will frequently be OpenStack, and services may be implemented using Network Functions Virtualization (NFV).

## Overview
In recent years, Enterprise and SMBs have embraced Cloud technology as a critical tool to enhance their competitiveness. Hybrid and public clouds offer the potential to improve business agility and decrease overall costs, but they impose significant demands on traditional networks. Cloud computing requires dynamic computing and a high degree of automation to address rapidly changing demands. While major advances have been made to automate the compute and storage domains, network automation has proven far more complex to realize, thus hindering most cloud deployments.

Communications Service Providers (CSPs) are also exploiting cloud technologies to enhance the manageability and cost-effectiveness of their vast network infrastructures, while enhancing service agility as well. Many of the world’s leading telecommunications and cable operators have collaborated on Network Functions Virtualization (NFV) to promote an open architectural framework and ecosystem to support a broad range of use cases. NFV has enabled a fresh view of existing network architecture, which must be far more flexible in the face of dramatically rising capacity demands and requirements for diverse services.

Software Defined Networking (SDN) is rapidly emerging as a dynamic networking architecture to address cloud and NFV networking demands. At the core of the architecture is the SDN Controller, which exposes open APIs to a diverse set of applications, multivendor support for a range of networking devices, and network programmability enabling intelligent control and management of the network.

Network operators are striving for an open platform that supports diverse use cases for end-user requirements, while simultaneously reducing overall costs. Vendor-neutral, open source software is the critical enabler, motivating operators and vendors to collaborate and benefit from this collective innovation over the long term, while avoiding the lock-in that has characterized networking for generations.

## Challenges
For all its promise, migration to virtualized networks is not without obstacles. The new network must accommodate an existing base of technologies and devices provided by multiple vendors. Operational procedures must be overhauled to exploit the benefits of automation. Network management and planning are also impacted, as traditional approaches were developed and refined assuming static infrastructure and services. Another important addition is open source, whose usage in networks lags far behind the compute and storage domains.

Cloud networks must enable efficient dynamic deployment and management of virtual machines that support varied and changing workloads. Enterprises seeking to build private clouds and hybrid clouds are looking to open alternatives (such as OpenStack, an open source cloud management platform) to the established virtualization vendors.

OpenStack provides open APIs to support a range of applications and infrastructure, including the Neutron API and Neutron/Multi-Layer 2 (ML-2) for networking. However, Neutron provides a relatively low-level interface, and was not designed to manage the underlays required for cloud data centers. Neutron ML2 was designed to expose Layer 2 data center switch capabilities, but is currently limited to a few common virtual (software) and hardware switches.

Existing enterprise networks are often quite complex, typically based on many technologies, vendors, and products. While it can be tempting to build a separate networking stack for an enterprise private cloud, there is great value in holistically managing cloud infrastructure, other datacenter networking, and campus and WAN together using common devops teams, toolkits and metrics. For this reason, many enterprises are evaluating a common SDN architecture platform that can span these domains and provide end-to-end visibility and control. The solution must be highly scalable and provide a dynamic, flexible, and policy-based multivendor network environment.

Carriers and CSPs are also embarking upon their own journey to adopt virtualization technology. Major operators are looking to NFV to reduce their dependence on purpose-built hardware and associated management tools, while improving service agility as well as operational responsiveness through automation and intelligence.

Additional networking capabilities are needed to virtualize service delivery and operations, including Virtualized Network Function (VNF) Forwarding Graphs (commonly referred to as service function chaining), inter-domain networking (including across service provider boundaries), and the ability to onboard, deploy, and manage diverse VNFs from many vendors.

Migrating to virtualized networking represents a significant change, one that necessitates a transformation of the infrastructure, operations, and mindset. As a result, many organizations are making the shift to SDN.

## Why OpenDaylight?
OpenDaylight is an open source framework for migrating to an SDN network architecture. It has been deployed in data centers, enterprises, and carrier networks, supporting a broad range of use cases. OpenDaylight provides the abstraction, programmability, and openness that paves the way towards an intelligent, software-defined infrastructure.

OpenDaylight provides the open platform to migrate existing networks to SDN, featuring:

- Vendor-neutral platform with broad support for industry leaders from the operator and vendor community
- Model-driven automation to readily add support for existing devices through standard and proprietary management interfaces SDN support for OpenFlow, OVSDB, NETCONF, LISP, etc. 
- Intent-based Northbound API framework to support a broad range of applications 
- Open ecosystem with a broad set of products and OpenDaylight-based network applications and services

![Figure 1: OpenStack and OpenDaylight Integration](/images/illustrations/nfv_cloud_2016.jpg)
**Figure 1**: *OpenStack and OpenDaylight Integration*

Enterprises can leverage OpenDaylight to control and manage their data center networks to support cloud deployments. Extensive support for OpenStack has been built into OpenDaylight (see Figure 1 above) to overcome the challenges addressed earlier:

- Support for the Neutron API and ML2 plug-in
- Intent-based northbound interface that accommodates a wide range of applications
- Built-in network services including network virtualization, overlay support, conventional switching and routing, policy management, etc.
- Service Abstraction Layer (SAL) to readily add support for traditional and SDN-capable devices
- Available plug-ins for OVSDB, OpenFlow, NETCONF, and a range of proprietary switches and routers

OpenDaylight bridges the gap from the existing network to the open SDN architecture, to enable a smooth transition to the cloud. An open platform provides a common set of management tools to avoid an “SDN or Cloud silo,” while providing broad interface support for both existing and SDN-enabled equipment, and a model-driven methodology to add new devices

OpenDaylight also supports a range of overlay technologies (including OpenFlow, Layer 2 and 3 Tunnels, among others) to interwork with existing networks, and provide secure, end-to-end connectivity across existing infrastructure and WAN services.

OpenDaylight provides SDN-based Control for NFV OpenDaylight is also beginning to be adopted by CSPs who are deploying NFV. CSPs intend to deploy NFV over SDN, and have been experimenting with ODL in a series of ETSI NFV Proof of Concepts (PoCs). For instance, NFV PoC  #19 Service Acceleration of Network Functions in Carrier Networks adopted OpenDaylight to demonstrate how SDN can enable VNF deployment and service chaining, orchestrated by OpenStack. The PoC was sponsored by AT&T, and involved switches and software from multiple vendors.

OpenDaylight was selected as one of the key underlying platform technologies for the Open Platform for NFV (OPNFV) open source project, (now reformed as Anuket)  also administered by the Linux Foundation. Several operators and vendors are collaborating on Anuket in order to validate NFV concepts, integrate open source building blocks, and ultimately accelerate NFV deployment.