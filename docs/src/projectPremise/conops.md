---
title: Concept of Operations
layout: default
nav_order: 2
parent: Project Premise
last_modified_date: March 29th, 2024
---

# Concept of Operations (ConOps)
{: .fs-8 .fw-700 .d-inline-block}

WORK IN PROGRESS
{: .label .label-red }

{: .fs-5 .fw-300 }
A comprehensive overview of system charecteristics, functionality, and lifecycle operations from a user standpoint.

---
<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>
---

## What is a Concept of Operations (ConOps)?
{: .fw-700 }

At a high level, a ConOps is a document considering and describing all stages of nominal and non-nominal operations. This includes human-payload interactions, communication strategies, data architectures, integration/operational scenarios, and more. As a whole, the ConOps should evaluate and analyze all stages of operation for the entire lifecycle of the end product. For more information about ConOps, I reccomend reading Section 4.1.2.1 of the [NASA Expanded Guidance for Systems Engineering](https://ntrs.nasa.gov/api/citations/20170007238/downloads/20170007238.pdf) as well as the [IEEE 29148:2011 Concept of Operations (ConOps)](https://ieeexplore.ieee.org/document/761853).

## Stage 0: Programming the Femtosatellite
{: .fw-700 }

While there certainly may exist variations of hardware depending on usage and mission, the general approach of utilizing the Open Femtosatellite Bus should remain fairly identical. The central bus provides the following:
- Power regulation and conditioning
- Data transmission and package handling
- Attitude control
- Command and control
- Other housekeeing functionality

While there may be science/payload variations depending on the mission, the central bus module functionality remains largely identical across the board. 
### Behavioral Architecture
{: .fw-700 }

From establishing a bus to payload interface, we can establish a behavioral architecture of programming the femtosatellite from different stakeholders/customers:

<br />
<p align:center style="margin: auto;">
  <img src="/assets/BehavioralDiagram.png" />
</p>
<p align:center style="text-align:center; font-style: italic; font-size:12px; margin: auto;">
  Figure 1: Behavioral architecture of Femtosatellite Programming
</p>
<br />

Here, we can see the through different libraries and applications, varying levels of abstraction can be established. This addresses the expectation from secondary/postsecondary educators to have a simple interface to design and program the femtosatellite.

We also see that regardless of interface, the programming of the femtosatellite occurs through a common project toolchain, which id driven by the design of the **Open Femtosatellite Bus**.

## Stage 1: Femtosatellite Integration
{: .fw-700 }

### Stage 1.1: Physical Integration
{: .fw-700 }

### Stage 1.2: Electronic Integration
{: .fw-700 }

### Stage 1.3: (Optional) Coms Integration
{: .fw-700 }



## Stage 2: Launch and Deployment
{: .fw-700 }

## Stage 3: Operation and Communication
{: .fw-700 }

Redundancy of communication is absolutely necessary for an implementation of a femtosatellite-class spacecraft. One of the driving fact

## Stage 4: Disposal and Deorbit
{: .fw-700 }