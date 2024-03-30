---
title: Requirements Definition
layout: default
nav_order: 3
parent: Project Premise
has_children: true
last_modified_date: March 29th, 2024
---

{: .fs-8 .fw-700}
# Requirements Definition

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

## Why Requirements?
{: .fw-700}

Establishing well written requirements is foundational for the success of a midsize to large project. By drafting requirements, project managers and members can continuously verify development efforts push forwards the end goal of the product. For the Open Source Femtosatellite Project, establishing high level requiremnts which can be decomposed to lower level requirements (See [Logical Decomposition](http://femtosat.marvinlin.space/src/projectPremise/requirements/logicalDecomp.html)) ensures the logevity of the project, as well as ensuring collaborators can easily understand project objectives.

{: .note-title }
> What makes a good requirement(s)?
>
> The age-old question of systems engineering. While this is _can be_ subjective, there are a few guiding principles of every good requirement:
> 0. **Necessary** - Is this requirement needed?
> 1. **Specificity & Clarity** - Ensure each requirement is specific (ie. numerical descriptions and tolerances) and clear in the intent. ***Itnent should not be left to interpretation***
> 2. **Implementation-Free** - The requirement should never describe the approach and/or implementation, only high level needs.
> 3. **Complete** - Do your reqirement(s) cover all your basis?
> 4. **Consistent** - Verify your requirements do not have conflicts between each other!
> 5. **Tracible** - Each requiremet should be tracible to foundational Stakholder Expectations.
> 6. **Verifibility and Testibility** - A main function of requirements is guiding the verification and validation of parts, subsystems, and the encompasing project. Ensure each requirement can be tested/verified in some way.
>
> For a more complete and comprehensive overview of writing quality and effective requirements, please reference the [NASA Systems Engineering Handbook](https://www.nasa.gov/wp-content/uploads/2018/09/nasa_systems_engineering_handbook_0.pdf)

## Requirement Format
{: .fw-700}

The folliowing is an example format of a requirement. Each requirment for this project will be described as such throughout any and all documentation.

### Example Requirement
{: .fw-700}

This is the decription for an example requirement.
> <dl>
>   <dt>Requirement ID</dt>
>   <dd>EXAMPLE-0.1</dd>
>   <dt>Rationale</dt>
>   <dd>Insert Rationale Here</dd>
>   <dt>Traced From</dt>
>   <dd>Insert Parent Requirement ID here</dd>
>   <dt>Verification Method</dt>
>   <dd>Describe Verification Method Here</dd>
>   <dt>Verification Level</dt>
>   <dd>Describe Hierarchy Level of Verification</dd>
> </dl>