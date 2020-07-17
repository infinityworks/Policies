# External Dependency Policy

## Context

Infinity Works uses a number of externally provided tools and services in support of standard business operations. In some cases, an external dependency forms a crucial part of our own customer obligations and so must be diligently selected and carefully managed. At the other end of the spectrum, some dependencies support internal processes which only distantly impact our client obligations and may be subject to softer mitigation controls. This policy identifies four categories of dependency which can be summarised as follows:

|Type|Description|Definition                                                                                                                                                                                                 |
|----|-----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|A   |Commercial |Infinity Works have a contract which directly includes the external party product or services within our own commercial obligations.                                                                       |
|B   |Process    |Infinity Works use a tool or service for which there is no direct commercial obligation to the customer, but it is depended upon as part of an agreed process which is part of our contractual obligations.|
|C   |People     |Infinity Works employ external contractors where necessary to fulfil short term demand or specialist roles required as part of our customer obligations.                                                   |
|D   |Tools      |Infinity Works employ external contractors where necessary to fulfil short term demand or specialist roles required as part of our customer obligations.                                                   |

These categories each have a level of mitigation proportionate to the immediacy of their impact on Infinity Works’ own obligations. A detailed description of each category follows.

## Type A : Commercial

### Definition

Infinity Works have a contract which directly includes the external party product or services within our own commercial obligations.

### Examples
* Customer A managed service which includes AWS instances under the Infinity Works account and costs are encapsulated in the managed service fee.
* Customer B tool includes AWS instances under the Infinity Works account and costs are directly passed through to the customer.

### Mitigations
* Partnership. Infinity Works establish a formal partnership agreement with the product or service provider to provide a contractual foundation and access to people, information and training as far as necessary.
* Accreditation. Infinity Works ensure a sufficient number of consultants involved in providing the service are formally qualified to the appropriate level as defined by the partnering organisation.
* Process. Workflows for changes and incidents which are sensitive to nuances of the specific external dependency, documented separately [here](https://docs.google.com/document/d/1DO-PgCj7JPJ1FAzSJVw1lbFdnfQiLkF9IzdGVpMY6l0/edit#heading=h.d77mzha2ty26 "External Dependency Change Management").

## Type B : Process

### Definition

Infinity Works use a tool or service for which there is no direct commercial obligation to the customer, but it is depended upon as part of an agreed process which is part of our contractual obligations.

### Examples
* Customer C uses an Infinity Works provisioned instance of Atlassian’s JIRA tool to document, track and audit tasks as part of the development process.
* Customer D uses an Infinity Works provisioned Pagerduty system to provide a 24/7 on-call number with an in-built rota, escalations etc. as part of incident management.

### Mitigations
* Reputation. Infinity Works only source tools directly in support of essential customer processes from providers who are ubiquitous throughout the industry and have a long-standing, proven standard of performance.
* Contract. Infinity Works reviews the terms of any tool purchase to ensure that in all critical areas (e.g. both in the service level provided and in the features) it meets our needs in performing the required service to the customer.
* Escalation. Each team that uses an externally provided tool as part of a critical service is required to ensure that escalation routes exist between the two companies so that they can be used to agree appropriate alternative plans in the event of that service unexpectedly failing.

## Type C : People

### Definition

Infinity Works employ external contractors where necessary to fulfil short term demand or specialist roles required as part of our customer obligations.

### Examples
* Customer E DBAs were brought in on a contractor basis due to their niche skill set and the lack of consistent demand across all clients.
* Customer F engineers were brought in on a contract basis to allow a quick ramp up for a team that needed to be established at short notice.

### Mitigations
* Contractor agreement. Infinity Works ensures that contractors are employed with terms that are suitable and in line with our customer commitments.
* Customer agreement. Infinity Works ensures that the necessary stipulations are written into client agreements where contractors may be a necessary part of the team make up.
* Management. Contractors are given day-to-day guidance within the established Infinity Works team to ensure actions and deliverables conform to contracted expectations.

## Type D : Tools

### Definition

Infinity Works use a number of tools which are not directly exposed to the customer in any way, but which provide key internal processes and are indirectly part of our ability to fulfil customer obligations.

### Examples
* Kimble is used to record consultant time spent so that we can provide accurate invoices to our customers.
* GitHub is used to manage and store internal documentation including knowledge base articles which consultants use as a guideline for best practice.

### Mitigations
* Timeliness. Internal tools in this category are never directly servicing an immediate client need which allows a reasonably large grace period on any issues being resolved before they impact our ability to fulfil our obligations.
* Backup and Restore policies. Each tool which we depend on for an internal process has its own backup and restore policy to allow a suitable speed of recovery for the function it performs.
* Contract. When purchasing such tools, we ensure that contractual terms such as service level agreements and warranties are commensurate with the level of impact on the business should the tool prove to be defective or faulty, and the ease of replacement of the tool.
