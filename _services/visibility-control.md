---
title: "Visibility & Control"
date: 2018-11-28T15:15:34+10:00
featured: true
weight: 3
layout: service
---

Centralized administration of the network and/or multiple controllers. This is sometimes used by carriers or enterprises as a precursor to NRO.



## Overview
While the control plane garners the lion’s share of attention in the SDN community, the transformation of the network management plane is equally important. SDN offers great promise to improve agility while simultaneously reducing costs across a wide range of use cases. However, managing virtual, physical and hybrid networks, diverse applications, and hardware from multiple vendors all together is very challenging.

By enabling automation, unprecedented intelligence, and domain-wide views, SDN offers the potential to transform network management as much if not more than services delivery. Those qualities also enhance security management, which is already benefitting from SDN architecture. And in a dramatic break from the past, network and security management can be effectively delivered in a vendor-neutral and multi-vendor environment.

## Challenges
Traditional FCAPS (Fault, Configuration, Accounting, Performance, and Security) management has been highly proprietary, and constrained by capabilities embedded in the hardware. In particular, network management varies widely across different platforms, many times only accessible through proprietary management interfaces, Management Information Bases (MIBs), and APIs.

Recent advances in model-driven automation have motivated vendors to adopt the YANG (RFC 6020) modeling language and the NETCONF protocol (RFC 6241) to establish a common model and protocol for management information modeling and control. While subsequent implementations have streamlined the process for managing many devices with a common Network Management System (NMS), the proprietary boundary shifts from the management interface to the NMS.

Another challenge is that network management has evolved over decades based on a physical object paradigm. Management operations are typically based on ports, subnets, IP addresses, and VLANs, while operators are most interested in how network behavior impacts services and the end-users who consume them. For instance, if a router fails, typical management systems indicate the links and ports affected, not the number of users, and the services and applications that may be affected.

Similarly, security management has been traditionally based on a physical perimeter. With mobility reshaping Enterprise IT, as users demand anytime/anywhere/any device access to their applications, current-generation security solutions are often inadequate to secure the services and applications on a global basis.

Network security products, like their network management counterparts, typically address specific domains (e.g., WiFi, Campus LANs, etc.), and cannot be readily integrated. Introducing virtual networking resources into the mix results in an even-more complex environment.

Enhanced network visibility and control is needed to address these increasingly complex NMS and security requirements. Among the key needs include:

- An open platform capable of bridging the gap between the physical, virtual, and user domains.
- Ability to support a flexible range of network applications
- Robust topology and network state in both the physical and virtual domains
- Flexible policy management options and enforcement
- Network programmability to enable enhanced network operations to support diagnosis, troubleshooting, and analysis
- Ability to operate over multi-vendor infrastructure including non-SDN-enabled hardware

## Why OpenDaylight
OpenDaylight (ODL) is an open source framework for migrating to an SDN network architecture. It has been deployed in data center, enterprise, and carrier networks, supporting a broad range of use cases. OpenDaylight provides the abstraction, programmability, and openness that paves the way towards an intelligent, software-defined infrastructure.

OpenDaylight facilitates development of an open platform capable of migrating networks to SDN, and ushering in an open and intelligent network infrastructure. One of the fundamental differences between SDN and traditional networks is a logically centralized control model, based on rich topology and state that enables global, multi-layer views across the physical and virtual infrastructure.

Because the journey to SDN will take years and not months, OpenDaylight serves to bridge between the traditional network management control model and SDN architecture. Key capabilities that provide enhanced visibility and control include:

- Logically centralized topology and state for both physical and virtual network resources, which enables unprecedented domain-wide visibility
- Non-disruptive monitoring capabilities that do not impact mission-critical communications
- Model-Driven Service Abstraction Layer (MD-SAL) that leverages industry standard YANG models to map network applications to underlying devices
- A modular, plug-in southbound (i.e., controller-to-device) interface with extensive support for standard network management interfaces (i.e., OpenFlow), and proprietary interfaces and devices
- Intent-based northbound (i.e., application-to-controller) interfaces exposing SDN capabilities to diverse network applications, while abstracting the underlying infrastructure details
- Readily supports proprietary and extended network services, to support domain-wide visibility and analytics to manage both virtual and physical domains
- Multiple built-in mechanisms for policy enforcement
- Broad industry acceptance, including the largest community for any controller

For security management, SDN and OpenDaylight opens the door to sophisticated capabilities that would otherwise be infeasible. Domain-wide and global visibility enhance the ability to administer effective network-wide threat monitoring. Ability to enforce policies based on applications, services and groups (as opposed to physical resources) enable more relevant and finer-grained management. Flows are particularly well-matched to security applications that are seeking to protect end-to-end communications independent of network constraints. Finally, programmatic control through an open, intent-based API enables dynamic policy control, and the ability to modify network behavior to improve security and performance.