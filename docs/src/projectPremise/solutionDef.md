---
title: Design Solution Definition
layout: default
nav_order: 4
parent: Project Premise
last_modified_date: March 29th, 2024
---

# Design Solution Definition
{: .fs-8 .fw-700 .d-inline-block}

WORK IN PROGRESS
{: .label .label-red }

{: .fs-5 .fw-300 }
A comprehensive collection of functional and performance requirements driven by stakeholder expectations.

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

{: .note-title}
> From NGOs and Requirements to Design
> 
> After we've gotten a grasp on the high level requirments of the product (**which may/will iterate and evolve over time**), we can now start exploring solutions!

## System Level Architecture
{: .fw-700}

At a high level, we can first model the system to system interactions. This can help us understand the high level interfaces that we can control through Interface Control Documents (ICDs) and help create layers of abstraction of **system level verification and validation**. Below is a high level system block diagram of the expected design

<br />
<p align:center style="width:85%; margin: auto;">
  <img src="/assets/systemBlock.png" />
</p>
<p align:center style="text-align:center; font-style: italic; font-size:12px; margin: auto;">
  Figure 1: High level logical system architecture block diagram
</p>
<br />

At a high level, the Open Femtosatellite Bus should be able 
Here, we can see that there is an interface between the Open Femtosatellite Bus with the 

## Subsystem Level Architecture
{: .fw-700}

We can further decompose the system to into smaller subsystems, which will help us identify a more specific solution.

<br />
<p align:center style="width:85%; margin: auto;">
  <img src="/assets/subsystemBlock.png" />
</p>
<p align:center style="text-align:center; font-style: italic; font-size:12px; margin: auto;">
  Figure 2: Logical subsystem architecture block diagram
</p>
<br />

### Housekeeping & C3
{: .fw-700}

Foundationally, the bus must have a central avionics/housekeeping system. As the name indicates, it will handle all command, control, and communication of the spacecraft. Moreover, it should be fairly low powered while handling basic housekeeping duties, while also maintaing requried performance for payload/mission tasks.

#### Housekeeping/C3 Requirement Dependancies
{: .fw-700}

| Requirement ID | Requirement Name |
|:---------------|:-----------------|
| FUNCT-1.1 | Low-power Housekeeping & C3 Operations |
| FUNCT-2.3 | Physically Radiation Tolerant Compute |
| FUNCT-2.4 | Logically Hardened Design |
| FUNCT-2.5 | Watchdog Circuit for Radiation Upsets |