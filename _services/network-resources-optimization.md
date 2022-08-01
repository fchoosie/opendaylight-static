---
title: "Network Resources Optimization"
date: 2018-11-28T15:15:26+10:00
featured: true
weight: 4
layout: service
---

Dynamically optimizing the network based on load and state. This is the most common carrier use case as it optimizes the network using the near-real-time state of traffic, topology and equipment. NRO uses a variety of southbound protocols (for example, NETCONF, BGP-LS or OpenFlow) depending on the underlying network. In addition to being used “under the covers” by many telcos and cable operators, this is a top use case for enterprise and financial institutions.

## Overview
Network infrastructure is being significantly challenged by a strong traffic growth driven by mobile computing, streaming video and audio, and the advent of cloud-based services. Simply adding more hardware and increasing the teams that manage it is often not an option. Enterprises and service providers are under pressure from investors to do more with less and, as a result, network operators have never been more motivated to ensure the highest ROI from their network investments.

Enterprises and service providers are turning to SDN to improve the efficiency of their infrastructure and operations. By centralizing control, and offering unprecedented intelligence and openness, SDN can provide network operators with the tools to optimize their infrastructure like never before.

## Challenges

Improving and ultimately optimizing network performance remains an ever-present challenge for networking. No matter what the technology, where it’s deployed and by whom, the first rule of networking is that it is always about economics.

As line rates exponentially increase, both network inefficiencies and the need for network optimization are magnified. While bandwidth and latency are high priorities, operators and their users also seek to optimize cost, network resiliency and other QoS metrics across heterogeneous network technologies and equipment. Network optimization proves to be particularly important for the most expensive bandwidth, including the WAN (for enterprise and cloud providers), submarine networks, and transport networks (for carriers).

Few operators have the luxury to be able to start from scratch. Operators have invested significant amounts of money in their existing infrastructures and therefore need to evolve and manage this over time while leveraging massive investments in their existing networks. Viable Network Resource Optimization solutions, therefore, need to enable operators to obtain more out of existing infrastructure while leveraging new innovations as they become viable.

Strong Network Resource Optimization solutions should provide:

- Ability to optimize on a range of parameters (bandwidth, latency, cost, availability, etc.)
- Ability to execute a range of optimization algorithms
- Robust topology and network state, including multi-layer topology (for carrier networks)
- Support for diverse technologies and applications
- Policy enforcement
- Ability operate over multi-vendor infrastructure including non-SDN-enabled hardware

Why OpenDaylight?
By maintaining network topology and configuration along with fault and performance state, OpenDaylight provides a rich set of basic and extended network services for Network Resource Optimization (NRO). Large enterprise can benefit from NRO algorithms that exploit OpenDaylight’s logically centralized network state, analytics, and policy to achieve traffic engineering across heterogeneous infrastructure. Carriers are implementing multi-layer control for converged packet-optical networks based on OpenDaylight that optimize bandwidth utilization, protection bandwidth, and service placement in a dynamic services environment.

OpenDaylight enables operators to realize the potential for software-defined networks by providing an open SDN platform with:

    Model-Driven Service Abstraction Layer (MD-SAL) that leverages industry standard YANG models to map network applications to the underlying devices to readily support
    Modular, plug-in southbound interface approach (i.e., Controller to Device) with extensive support for standard network management interfaces (e.g. BGP, PCEP), OpenFlow, and proprietary interfaces and devices
    Intent-based Northbound (i.e., Network Application to Controller) interfaces exposing SDN capabilities to diverse network applications, while abstracting the underlying infrastructure details
    Readily supports proprietary and extended network services, including path computation, resource management, analytics for both virtual and physical domains
    Multiple built-in mechanisms for policy enforcement
    Broad industry acceptance, including the largest community for any controller
    By enabling operators to mix and match network applications and devices, OpenDaylight provides a powerful platform to automate and operationalize intelligent service delivery, while enabling operators to migrate to SDN at their own pace.

## Examples | End Users

### Tencent Data Center Interconnect (DCI)

As a leading provider of Internet services in China, Tencent operates in the highly competitive consumer space where minimizing costs is critical, especially for the WAN. Tencent developed an OpenDaylight-based controller to optimize bandwidth utilization while improving service delivery among its vast data centers.
China Mobile NovoNet

China Mobile is among the largest service providers in the world. NovoNet represents the company’s network vision for 2020 based on SDN and NFV. One key use case is Traffic Optimization, encompassing “self-provision(ing), self-management, smart traffic scheduling, and real-time awareness.”

![China Mobile SDN Use Case](/images/illustrations/cm-sdn-usecase.png)

### Multi-Layer Transport Controller Solutions

One of the key SDN use cases for the telecommunications industry is Transport-SDN, which is focused on controlling the packet-optical infrastructure for Metro and long-haul connectivity. A number of major OEMs have developed Transport SDN controllers based on OpenDaylight to control the multi-layer infrastructure.
Ericsson SDN Controller

Ericsson’s Transport SDN product offers an end to end abstracted view of network resources and topology, optimizing resource allocation and network engineering across the IP and Optical layers.”

![Ericsson SDN Controller](/images/illustrations/ericsson-sdn.png)

### Fujitsu Virtuora® NC Network Control and Management Platform

Built on an open-source platform, Virtuora NC provides a framework for a collection of applications and interfaces that enables the control and management center of the virtual network.
HPE ContextNet

HPE ContexNet is an OpenDaylight-based carrier-grade distributed SDN fabric that leverages proven virtualization and grid-computing technologies.