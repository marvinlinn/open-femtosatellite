---
title: Stakeholder Expectations
layout: default
nav_order: 1
parent: Project Premise
last_modified_date: March 29th, 2024
---

# Stakeholder Expectations
{: .fs-8 .fw-700 .d-inline-block}

RELEASED (V1.0)
{: .label .label-purple }

{: .fs-5 .fw-300 }
A high level description of objectives driven by stakeholders/product users.

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

{: .highlight }
> Recall the "Systems Engineering V" from the [Project Premise](https://femtosat.marvinlin.space/src/premise.html)--identifying Stakeholder Expectations is the first step in this process!

## Defining Stakeholders
{: .fw-700 }

Foundationally, this project is unlike others, where there are not strictly designed customers/stakeholders in this project. However, given the high level project objectives of Education and Reserach/Engineering, two primary stakeholders can be defined:

1. Educators and their students
2. Engineers/Researchers

Ideally, the output of this project should be able to simultaneously cater towards both audiences. This should be addressed in the design of the end product through usage flexibility and introducing layers of abtractions through Block Programming tools.

## Oberving Stakeholder Expectations
{: .fw-700 }

The following table breaks down key expectations from the Open Femtosatellite Project Product:

| Educators/Students        | Engineers/Researchers          |
|:-------------|:------------------|
| A tangible and visual expereince for learning engineering thinking principles | Flexible and open source platform to allow for varying research objectives |
| Easy-to-use interfaces | Demonstration of flight heritage and functionality   |
| Quick and easy setup/usage; Plug and Play | Low-power housekeeping systems |
| Inexpensive and Durable | *Relatively* Low Cost |
| | Capible Multi-satellite (swarm-like) interfaces |
| | Usable data rates for research data donwlink |
| | Reliable but mission flexible hardware & firmware |

## Needs, Goals, and Objectives (NGOs)
{: .fw-700 }

> "Needs, Goals, and Objectives (NGOs) provide a
> mechanism to ensure that everyone (implementer,
> customer, and other stakeholders) is in agreement at
> the beginning of a project in terms of defining the
> problem that needs to be solved and its scope. NGOs
> are not contractual requirements or designs."
> 
> *NASA Systems Engineering Handbook*

Given the stakeholder(s) expectations, we can move towards designing NGOs for the project. We start with a single statement need, and further elaborate to high-level objectives.

### Need Statement
{: .fw-700 }

Spacecraft resaerch and education has notoriously had a very high barrier to entry, requiring specialized education, hands-on experiences, and extensive budgets. As technology continues to turn towards the stars, less expensive tools to teach spacecraft engineering and conduct research has had major increases in demand.

As recently as 2000, the CubeSat standard was born from California Polytechnic Institiute and has remained a cornerstone of modern research and commerical satellites. Despite the major advances from the CubeSat standard, experiences and education still remains widely inacessibly due to costs and lack of pedagogical resources in spacecraft engineering.

Hence, this project explore further mineaturization of spacecrafts in the femtosatellite-class regime in an effort to increase acessibility to space research and education.

### Goals
{: .fw-700 }

At a high level, the designed solution should address the following goals:

- Low-cost spacecraft acessible by all universities and secondary/post-secondary institutions
- Deployable femtosatellite-class spacecraft
- Robust and reliable mineatureized spacecraft bus platform
- Tools to create varying levels of abstraction for pedagogical uses

### Objectives
{: .fw-700 }

These objectives intend to further specify the above goals to tangible and actionable statements.

1. < 50g spacecraft
2. < 10cm x 10cm x 2cm total volume
3. < 500mW satellite housekeeping system
4. < $100 per spacecraft along with development tools
5. Able to deploy 15 or more from a 3U CubeSat
6. Spacecraft must remain operational 90% of lifespan at 99% data integrity
7. Minimum 5 years functionality at geosyncronous radiation environment
8. Programmable by Secondary School students for simple imaging missions
9. Capable of image capture and transmission while in geosyncronous orbit

{: .note }
> A key component of NGOs is regular and consistent iteration. While this is not as directly feasible with this project (due to the lack of a distinct stakeholder), alternatives towards iteration on NGOs includes real-world testing and feedback of the product.

## Closing the Feedback Loop: Involving the Customer/Stakeholder
{: .fw-700 }

One of the foundational principles in systems engineering is the iterative and self-correcting nature. To ensure this feedback loop is closed, the Open Source Femtosatellite project aspires to use the tools developed at both University of California--Berkeley through a student-taught DeCal, as well as at local secondary/post-secondary insitutions as a teaching/research tool. Aspirationally, the project looks to send a constellation of student desining and programmed missions into space.
