# Diversity Cyber Council Proposal

Presented by

![logo](img/logo.png)

---

## Table of Contents

- [Diversity Cyber Council Proposal](#diversity-cyber-council-proposal)
  - [Table of Contents](#table-of-contents)
  - [1. Overview](#1-overview)
    - [a. About Diversity Cyber Council](#a-about-diversity-cyber-council)
      - [i. Site](#i-site)
      - [ii. Mission](#ii-mission)
    - [b. Vision](#b-vision)
    - [c. Kata Project Goal](#c-kata-project-goal)
  - [2. Kata Program](#2-kata-program)
    - [a. Program Name](#a-program-name)
    - [b. Program Summary](#b-program-summary)
    - [c. Technology Solution Description](#c-technology-solution-description)
  - [3. About the Team](#3-about-the-team)
    - [a. Team Name](#a-team-name)
    - [b. Tagline](#b-tagline)
    - [c. Technology Proposal Summary](#c-technology-proposal-summary)
  - [4. Captured Requirements](#4-captured-requirements)
    - [a. Users Personas & Cohorts](#a-users-personas--cohorts)
    - [b. Platform Feature Characteristics](#b-platform-feature-characteristics)
    - [c. Hard Platform Requirements](#c-hard-platform-requirements)
  - [5. Architectural Characteristics](#5-architectural-characteristics)
    - [a. Usability](#a-usability)
    - [b. Responsiveness](#b-responsiveness)
    - [c. Feasibility](#c-feasibility)
      - [i. Operational Costs](#i-operational-costs)
      - [ii. Infrastructure & Cloud Costs](#ii-infrastructure--cloud-costs)
      - [iii. Security Update Costs](#iii-security-update-costs)
    - [d. Elasticity](#d-elasticity)
    - [e. Security](#e-security)
    - [f. Privacy](#f-privacy)
    - [g. Interoperability](#d-interoperability)
    - [h. Data Integrity](#f-data-integrity)
  - [6. Proposed Solution](#6-proposed-solution)
    - [a. Overview & Value Proposition](#a-overview--value-proposition)
    - [b. High-Level Architecture Diagram](#b-high-level-architecture-diagram)
      - [i. HLD Components](#i-hld-components)
    - [c. Reporting & Business Intelligence (BI)](#c-reporting--business-intelligence-bi)
    - [d. Deployments](#d-deployments)
    - [e. User Interactions](#e-user-interactions)
    - [f. Sequence Diagram](#f-sequence-diagram)
      - [i. Processes](#i-processes)
      - [ii. UI Wireframes](#ii-ui-wireframes)
      - [iii. Editable/Markdown fields](#iii-editablemarkdown-fields)
    - [g. Backlog](#g-backlog)
      - [i. Epics & Milestones](#i-epics--milestones)
      - [ii. Defined User Stories & Epics](#ii-defined-user-stories--epics)
    - [h. Architectural Decision Records (ADRs)](#h-architectural-decision-records-adrs)
  - [7. Definitions / Glossary](#7-definitions--glossary)
    - [501c3 Non-Profit](#501c3-non-profit)
    - [Architecture Decision](#architecture-decision)
    - [Architectural Decision Record](#architectural-decision-record)
    - [AZ - Availability Zone](#az---availability-zone)
    - [Backlog](#backlog)
    - [Doherty Threshold](#doherty-threshold)
    - [Epic](#epic)
    - [High-Level Design](#high-level-design)
    - [Personally Identifiable Information](#personally-identifiable-information)
    - [Total Cost of Ownership](#total-cost-of-ownership)
    - [User Interface](#user-interface)
    - [User Story](#user-story)

---

## 1. Overview

### a. About Diversity Cyber Council

#### i. Site

[Diversity Cyber Council](https://diversitycybercouncil.com)

#### ii. Mission

Diversity Cyber Council is a 501c3 Non-Profit that serves under-represented demographics in the tech industry by facilitating education, training, and staffing opportunities to establish a sustainable and diverse talent pipeline to the workforce.

### b. Vision

Our vision is to enhance inclusion and representation in the tech industry through training, mentoring, networking, and visibility programs.

### c. Kata Project Goal

Our goal is to establish a sustainable and diverse talent pipeline that extends career equity to underrepresented demographics by providing access to competent training programs that lead to direct employment opportunities.

---

## 2. Kata Program

### a. Program Name

Spotlight App/Platform

### b. Program Summary

The Spotlight App Project is a sustained effort to amass a coalition of non-profits to address specific needs within the communities we serve by leveraging a centralized platform as the base of operations to collaborate and make a collective impact.

**Problem Statement #1:** The decentralization and lack of support between non-profits create gaps in service and overall impact.

**Problem Statement #2:** The lack of visibility of non-profit groups and offerings creates a barrier to access to the people we aim to serve.

### c. Technology Solution Description

Nonprofit Networking Hub & Diverse Candidate Career Case Management Tool

---

## 3. About the Team

The minimal team information is below. Per the proposal's instructions individual team identifying information, including our backstories, has been removed. We hope to communicate this information at an appropriate time. The absolute bare information is available including the team name, tag line, and a summary of our proposal.

### a. Team Name

TheGlobalVariables

### b. Tagline

Illuminate Possibilities

### c. Technology Proposal Summary

A technology solution that serves the purpose of enhancing visibility, support, and collaboration of non-profits serving similar needs in the community and operates as a candidate case management platform.

---

## 4. Captured Requirements

### a. Users Personas & Cohorts

| Persona | Definition |
|---|---|
| **Non-Profit with offering (“Non-Profit”)** | Group with a platform integration offering |
| **Candidate** | Consumer of non-profit offerings, delivered via the platform |
| **Administrators** | Management of the platform, registering Non-Profits |
| **Community Leader** | Member of the Admin team who consults non-profits to identify their service capabilities, responsibilities, & expectations |
| **Mentor** | Member of Non-Profit, who consults candidates and updates their profile |

### b. Platform Feature Characteristics

- The Platform must establish a way to incentivize engagement such as sharing of resources, collaboration, networking, facilitating introductions, and partnerships
- The Platform must provide a way to allow Non-Profits to publicize offerings to the platform that can provide some level of automatic matching for Candidate requests.
- The Platform allows offerings to contain rich text, links, and downloadable readable content such as PDFs, but no other downloads.
- Each offering must support a certain list of properties (defined by the platform), such as name, organization description, website, unique identifier (assigned by the Administrators) and other identification information.
- The Platform must provide both operational reports (number of candidate matches/period, number of offerings/region, and so on) and analytical reports (projections of future desirable career paths, Offering gaps in a region based on demand, and so on) for use by Administrators.
- The Platform must categorize/tag non-profit support services to match candidate needs that are identified during the onboarding assessment to include (but not limited to):
  - Resume Writing Services
  - Interview Prep
  - Free Business Attire
  - Apprenticeship Program Registration
  - Training Program Registration
  - College & University Registration
  - Free Grocery & Meal Services
  - Discounted Rent & Housing Services
  - Daycare/Child Care Services
  - Mentorship/Career Advocate Services

### c. Hard Platform Requirements

- End-Use Ease of Use is a hard requirement
- Tracking candidate progress is a hard requirement
- Tracking engagement is a hard requirement

---

## 5. Architectural Characteristics

### a. Usability

The end users are not tech-savvy; therefore the success of this product depends on how easy the user can learn new features and how easy it is to use the system on different devices.

### b. Responsiveness

Since Spotlight is a user-facing application, it is important to ensure the system responds to the end-user requests promptly. All user interactions *MUST* be coded in such a way as to provide some form of feedback for all actions. This feedback must occur within the [Doherty Threshold of 400ms](https://www.uxtoast.com/ux-laws/doherty-threshold).

### c. Feasibility

The cost and time to develop and maintain this application are driving factors. The consumers of this platform are the non-profit organizations for whom, it is important to minimize the operational cost.
The total cost of ownership comprises a significant number of factors. In this particular architecture, excluding new feature development, 3 primary cost factors will make up the majority of the costs.

#### I. Operational Costs

Generally the people costs, by way of employees, consultants, or services firms. The subsequent phase, if applicable and if chosen for the semifinals, will provide an expected high-level budget of operational costs and expected expenses in this category.

#### II. Infrastructure & Cloud Costs

Generally, these would include all the infrastructure, cloud, services, licenses, API subscriptions, and other costs associated with running the application frontend and backend, excluding development. The subsequent phase, if applicable and if chosen for the semifinals, will provide an expected high-level budget of operational costs and expected expenses in this category. The budget will be created utilizing example scenarios, or, more precise numbers if real-world expected user figures are available. A cost breakdown of services will be provided.

#### III. Security Update Costs

The primary ongoing development costs not related to feature development on this platform, in addition to responding to events and the infrastructure itself, will be the updates to the application libraries to address ongoing security concerns. The application frontend is by far the most vulnerable part of this system in terms of security and will require ongoing updates. The subsequent phase, if applicable and if chosen for the semifinals, will provide an expected high-level budget of operational costs and expected expenses in this category.

### d. Elasticity

The choice of serverless as a platform allows much faster scaling than if a container or VM-based infrastructure were used. Also, the scaling characteristics of the services are, for the most part, handled by the cloud provider (AWS). Some services have scaling limits (i.e. lambda defaults to 1000 concurrent functions running at a time) and these should be monitored so that the limits can be increased before they become an issue.

A further benefit of the use of a Serverless platform is that idle cost (the cost when there is no load) will be lower than when VMs or containers are used.

### e. Security

The application is exposed on the web which always has the risk of cyberattacks; should the application be accessed by unauthorized users. Moreover, the system stores sensitive information, such as personal data.

### f. Privacy

The system needs to handle the PII of candidates. Personal information must be accessed by authorized administrators, mentors, and non-profit representatives.

### g. Interoperability

The purpose of this product is to facilitate collaboration between non-profits. To achieve this goal, Spotlight needs to communicate with external systems (such as childcare/housing services) and legacy systems.

### h. Data Integrity

The candidate's career path and progress, as well as non-profit information, are accessed by multiple personas. It is crucial to ensure the data is accessed by the authorized person, and the accuracy of the data is maintained throughout its lifecycle.

---

## 6. Proposed Solution

### a. Overview & Value Proposition

The Spotlight App project aims to solve two issues that are faced by any non-profit organization: minimizing the operating cost and increasing the visibility of available services.

Many non-profits choose to minimize their operating costs by cutting the budget of anything other than direct program expenses or to “support the cause”. Most often, this causes non-profits to experience slow growth or an inability to become sustainable due to [a lack of investment in infrastructure and management](https://ssir.org/articles/entry/the_nonprofit_starvation_cycle). In many cases, the non-profit is left with a few volunteers to shoulder much of the work.

On the other hand, the lack of visibility of non-profits and their offerings creates a barrier to access for the people who can benefit most from these programs. The decentralization and lack of support between non-profits create gaps in service and overall impact.

Our proposed solution tackles the lack of visibility by enabling Spotlight App to be a central hub where non-profits are empowered to identify their service capabilities and publicize their offerings. The Spotlight App also enables the candidates to find services by providing smart recommendations based on the information provided by users and their geographical preferences. Moreover, the notification service enables non-profits to advertise their new offerings to candidates, based on their location/desired services. The Spotlight Mobile App brings the non-profit services closer to the candidates, as [85% of Americans currently own a smartphone](https://www.pewresearch.org/internet/fact-sheet/mobile/). The map view of the non-profit offerings makes it convenient for candidates to locate the services closest to their desired locations (school, home, work). In addition, the prediction capability of our solution helps non-profits identify the offering gaps, and predict the future desirable career paths. Our solution leverages AWS Pinpoint to collect usage data which essentially provides meaningful metrics to guide administrators and non-profits to improve their offerings and the application usability.

During the design process, we prioritized finding a cost-effective solution, without compromising the efficiency or the usability of the product. Our proposed solution reduces the cost of human resources by automating most of the manual processes that are typically performed by volunteers and employees. This frees them to focus on what is the most important for non-profits (conducting fundraising events, meeting candidates and nonprofits). Calendly is used to replace the traditional means of communication (such as phone calls and emails) for scheduling meetings. A recommendation engine is used to simplify the interview process by taking the candidate's profile and needs as inputs and providing smart initial recommendations for a career roadmap.

To reduce the cost of infrastructure, we introduced Serverless along with an affordable technology stack (such as D3, Vuejs, AWS Amplify). The use of serverless means that the development team does not need to spend time building, securing and maintaining servers. By using D3 and Vuejs for the frontend development, and AWS Amplify for the backend development, the Spotlight App can be developed and deployed faster and within a reasonable budget.

### b. High-Level Architecture Diagram

![Architecture Diagram](docs/architecture.png)

#### i. HLD Components

For a detailed breakout of components from the HLD, and their handling, see [here](docs/Components.md).

#### ii. C4 Diagrams
We leverage C4 model to describe our proposed software architecture.

##### a. System Context Diagram
![System Context Diagram](docs/system-context.jpg)

##### b. Container Diagram
![Container Diagram](docs/container-diagram.jpg)

### c. Reporting & Business Intelligence (BI)

We will use AWS Sagemaker to create models as well as for recommendations and predictions. These will be based on the processes that are currently defined and allow others yet to be defined to be modeled as required.

Initially, these models will be trained with test data, but the models will be retrained as users use the system and refinements will be made based on system usage. This will allow the models to become more accurate as the system is used.

The atomic data sources we intend to use are:

- Amplify analytics
- DynamoDB schemas
- Geolocation data obtained from Amplify
- Other data sources not presently defined or considered

*NOTE:* We will augment user data with geolocation data obtained through Amplify for more geo-specific recommendations.

Interactive reports for the data will be built using Vuejs templates and D3 visualizations.

### d. Deployments

![CI/CD Flow](docs/cicd_flow.png)

Two CI/CD pipelines are proposed to facilitate updates to the infrastructure and applications on the platform:

- AWS Cloudformation will be used to deploy a Route53 zone and subsequent record changes, SageMaker instance, IAM roles and policies, and observability tools. Cloudformation will also bootstrap Amplify.
- AWS Amplify will be used to deploy all the services necessary for the application to run (e.g. Lambda, Cloudfront, Appsync, DynamoDB). It will also handle deployment to services that it depends on, including data models and required accesses.

Updates will be triggered on commit, and the tools will be triggered via webhook.

### e. User Interactions

User interactions will be expanded should this proposal be selected for the semifinals, and refined significantly with stakeholder feedback rounds as required if selected past the semi-finals/finals. In particular, the user interactions will rely on the processes defined.

### f. Sequence Diagram

![Diagram](docs/sequence_diagram.jpg)

#### i. Processes

Process descriptions, steps, and individual flow diagrams (as required) will be expanded should this proposal be selected for the semifinals, and refined significantly with stakeholder feedback rounds as required if selected past the semi-finals/finals.

#### ii. UI Wireframes

User interface wireframes will be expanded should this proposal be selected for the finals, and refined significantly with stakeholder feedback rounds as required.

<p float="center">
  <img src="docs/ui-mockup/login.png" width="200" />
  <img src="docs/ui-mockup/dashboard.png" width="200" /> 
  <img src="docs/ui-mockup/list_view.png" width="200" />
  <img src="docs/ui-mockup/map_view.png" width="200" />
   <img src="docs/ui-mockup/non_profit_edit_profile.png" width="200" />
</p>

#### iii. Editable/Markdown fields

Editable/Markdown fields will be expanded should this proposal be selected for the semifinals. When the schema and data fields are created, we'll work with the stakeholders to define which fields require rich editing capabilities and utilize visual markdown editors and viewers as much as possible and where appropriate.

### g. Backlog

The Backlog refinement and entries will begin if this proposal endures itself into the semifinals, with refinement at each stage into the and past the finals.

#### i. Epics & Milestones

To be defined if a semifinalist, if appropriate.

#### ii. Defined User Stories & Epics

Epics with some known stories to be flushed out in the semifinalist stage, with additional refinement post-finalist, if appropriate, and then on a milestone start and sprint start basis, milestone by milestone and sprint by sprint.

### h. Architectural Decision Records (ADRs)

| ADR Link | Topic |
|---|---|
| [ADR 0001](ADR/ADR%200001-Choice%20of%20Serverless.md) | Choice of Serverless |
| [ADR 0002](ADR/ADR%200002-Choice%20of%20Cloud%20Provider.md) | Choice of Cloud Provider |
| [ADR 0003](ADR/ADR%200003-Process%20Modeling.md) | Process Modeling |
| [ADR 0004](ADR/ADR%200004-Observability.md) | Observability |
| [ADR 0005](ADR/ADR%200005-Amplify.md) | Amplify |

---

## 7. Definitions / Glossary

### 501c3 Non-Profit

A non-profit corporation or trust that is tax-exempt. See [Wikipedia](https://en.wikipedia.org/wiki/501(c)(3)_organization)

### Architecture Decision

A design choice with larger significance.

### Architectural Decision Record

A document that captures an important architecture decision along with the context and consequences.

### AZ - Availability Zone

A cloud provider's data center housed in a physically separated location. Deploying to multiple availability zones means that an application can survive the loss of a given data center. Multiple availability zones make up a region.

### Backlog

A 'to-do' list of features or tasks to be performed to complete work.

### Doherty Threshold

An objective for keeping a user engaged while interacting with a software system. If the system does not respond within ~400ms the user may become disinterested.

### Epic

A high-level task that can be broken down into smaller tasks that are to be added to a backlog.

### High-Level Design

A general system design that provides an overview of the entire system.

### Personally Identifiable Information

Data that when used alone or in conjunction with other information can identify an individual.

### Total Cost of Ownership

The complete calculation of costs of a software property. In software, this refers to not only the runtime cost but also the cost of operation.

### User Interface

Any means that a user may use to interact with a system.

### User Story

An explanation of a software feature written from the perspective of a user persona.
