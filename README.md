# Diversity Cyber Council Proposal

Presented by

![logo](img/logo.png)

## Table of Contents

```diff
1. Overview
 a. About Diversity Cyber Council
  i. Site
  ii. Mission
 b. Vision
 c. Kata Project Goal
2. Kata Program
 a. Program Name
 b. Program Summary
 c. Technology Solution Description
3. About Team
 a. Team Name
 b. Tagline
 c. Technology Proposal Summary
4. Captured Requirements
 a. Users Personas & Cohorts
 b. Platform Feature Characteristics
 c. Hard Platform Requirements
5. Implied Requirements
 ?fixme update TBDs?
 ?fixme TBD?. Total Cost of Ownership
  i. Operational Costs
  ii. Infrastructure & Cloud Costs
  iii. Security Update Costs
6. Proposed Solution
 a. Overview & Value Proposition
 b. High Level Archecture Diagram
  i. HLD Components
 c. Report & Business Intelligence (BI)
 d. Deployments
 e. User interactions
 f. Sequence Diagram
  i. Processes
  ii. UI Wireframes
  iii. Editable/Markdown fields
 g. Backlog
  i. Epics & Milestones
  ii. Defined User Stories & Epics
 h. Active Design Reviews (ADRs)
  i. ADR 0001 - Choice of Serverless
  ii. ADR 0002 - Choice of Cloud Provider
  iii. ADR 0003 - Process Modeling
  iv. ADR 0004 - Observability
  v. ADR 0005 - Amplify Frontend
  vi. ADR 0006 - Amplify Backend
7. Definitions / Glossary
```

## 1. Overview

### a. About Diversity Cyber Council

#### i. Site

[Diversity Cyber Council](https://diversitycybercouncil.com) (fixme link)

#### ii. Mission

Diversity Cyber Council is a 501c3 Non-Profit that serves under-represented demographics in the tech industry by facilitating education, training, and staffing opportunities to establish a sustainable and diverse talent pipeline to the workforce.

### b. Vision

Our vision is to enhance inclusion and representation in the tech industry through training, mentoring, networking, and visibility programs.

### c. Kata Project Goal

Our goal is to establish a sustainable and diverse talent pipeline that extends career equity to underrepresented demographics by providing access to competent training programs that lead to direct employment opportunities.

## 2. Kata Program

### a. Program Name

Spotlight App/Platform

### b. Program Summary

The Spotlight App Project is a sustained effort to amass a coalition of nonprofits in order to address specific needs within the communities we serve by leveraging a centralized platform as the base of operations to collaborate and make a collective impact.

**Problem Statement #1:** The decentralization and lack of support between nonprofits create gaps of service and overall impact.
**Problem Statement #2:** The lack of visibility of nonprofit groups and offerings creates a barrier of access to the people we aim to serve.

### c. Technology Solution Description

Nonprofit Networking Hub & Diverse Candidate Career Case Management Tool

## 3. About Team

```diff
- Donald
```

### a. Team Name

TheGlobalVariables

### b. Tagline

Illuminate Possibilities

### c. Technology Proposal Summary

A technology solution that serves the purpose of enhancing visibility, support, and collaboration of nonprofits serving similar needs in the community and operate as a candidate case management platform.

## 4. Captured Requirements

### a. Users Personas & Cohorts

| Persona | Definition |
|---|---|
| **Non-Profit with offering (“Non-Profit”)** | group with a platform integration offering |
| **Candidate** | consumer of non-profit offerings, delivered via the platform |
| **Administrators** | Management of the platform, registering Non-Profits |

### b. Platform Feature Characteristics

- The Platform must establish a way to incentivize engagement such as sharing of resources, collaboration, networking, facilitating introductions, and partnerships
- The Platform must provide a way to allow Non-Profits to publicize offerings to the platform that can provide some level of automatic matching for Candidate requests.
- The Platform allows offerings to contain rich text, links, and downloadable readable content such as PDFs, but no other downloads.
- Each offering must support a certain list of properties (defined by the platform), such as name, organization description, website, unique identifier (assigned by the Administrators) and other identification information.
- The Platform must provide both operational reports (number of candidate matches / period, number of offerings / region, and so on) and analytical reports (projections of future desirable career paths, Offering gaps in a region based on demand, and so on) for use by Administrators.
- The Platform must categorize/tag nonprofit support services to match candidate needs that are identified during the onboarding assessment to include (but not limited to):
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

## 5. Implied Requirements

## 6. Proposed Solution
fixme add back top 5-7 tomorrow, add link

### a. Overview & Value Proposition

```diff
- Samira
```

### b. High Level Archecture Diagram

![Architecture Diagram](docs/architecture.png)

```diff
Review FRIDAY last before submit
```

#### i. HLD Components

For a detailed breakout of components from the HLD, and their handling, see [here](docs/Components.md)

```diff
- Donald to review sub page
```

### c. Reporting & Business Intelligence (BI)

```diff
- ????
```

### d. Deployments

  TODO statement on handling amplify/CICD process here

```diff
- Donald
```

### e. User interactions

```diff
- ???? future?
```

### f. Sequence Diagram

![Diagram](docs/sequence_diagram.jpg)

#### i. Processes

  [click here for processes fixme](docs/Processes.md)
  TODO Samria

```diff
- Samira - Processes doc
- Donald - Add Phase 2 statement RE refinement
```
  
#### ii. UI Wireframes

User interface wireframes will be expanded at if this proposal endures its self into the semifinals, and afterwards refined significantly with stakeholder feedback rounds as required if selected past the semi-finals/finals.

#### iii. Editable/Markdown fields

Editable/Markdown fields will be expanded at if this proposal endures its self past the semi-finals/finals. When the schema and data fields are created, we'll work with the stakeholders to define which fields require rich editing capabilities, and utilize visual markdown editors and viewers as much as possbile and where appropriate.

### g. Backlog

The Backlog refinement and entries will begin if this proposal endures its self into the semifinals, with refinement at each stage into the and past the finals.

#### i. Epics & Milestones

To be defined if a semifinalist, if appropriate.

#### ii. Defined User Stories & Epics

Epics with some known stories to be flushed out in the semifinalist stage, with additional refinement post-finalist, if appropriate, and then on a milestone start and sprint start basis, milestone by milestone and sprint by sprint.

### h. Active Design Reviews (ADRs)

#### i. ADR 0001 - Choice of Serverless

[ADR 0001](ADR/ADR%200001-Choice%20of%20Serverless.md)

#### ii. ADR 0002 - Choice of Cloud Provider

[ADR 0002](ADR/ADR%200002-Choice%20of%20Cloud%20Provider.md)

#### iii. ADR 0003 - Process Modeling

[ADR 0003](ADR/ADR%200003-Process%20Modeling.md)

#### iv. ADR 0004 - Observability

[ADR 0004](ADR/ADR%200004-Observability.md)

#### v. ADR 0005 - Amplify Frontend

```diff
- Donald RE vue vs. hugo vs react and nodejs (aka Runtime)
```

#### vi. ADR 0006 - Amplify Backend

```diff
- Scott RE Amplify Backend
```

## 7. Definitions / Glossary

```diff
- Marc (add words by everyone, he'll define)
```

### <a name="501c3 Non-Profit"></a> 501c3 Non-Profit

A non-profit corporation or trust that is tax-exempt. See [wikipedia](https://en.wikipedia.org/wiki/501(c)(3)_organization)

### <a name="Architecture Decision"></a> Architecture Decision

A design choice with larger significance.

### <a name="ADR - Architectural Decision Record"></a> Architectural Decision Record

A document that captures an important architecture decision along with the context and consequences.

### <a name="Backlog"></a> Backlog

A 'to-do' list of features or tasks to be performed to complete work.

### <a name="Epic"></a> Epic

A high-level task that can be broken down into smaller tasks that are to be added to a backlog.

### <a name="HLD - High-Level Design"></a> High-Level Design

A general system design that provides an overview of the entire system.

### <a name="PII - Personally Identifiable Information"></a> Personally Identifiable Information

Data that when used alone or in conjunction with other information can identify an individual.

### <a name="TCO - Total Cost of Ownership"></a> Total Cost of Ownership

The complete calculation of costs pertaining to a software property. In software, this refers to not only the runtime cost but also the cost of operation.

### <a name="UI - User Interface"></a> User Interface

Any means that a user may use to interact with a system.

### <a name="User Story"></a> User Story

An explanation of a software feature written from the perspective of a user persona.
