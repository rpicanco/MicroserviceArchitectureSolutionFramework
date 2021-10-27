# Microservice Architecture Solution Framework
<br>
<img src="/framework/images/Microservice Architecture Solution Framework - Boundaries.png">

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About the Project</a>
    </li>
    <li>
      <a href="#what-is-the-purpose-of-this-framework">What is the purpose of this framework?</a>
    </li>
    <li>
       <a>Boundaries' deliverables</a>
    </li>
    <ul>
      <li>
        <a href="#business-domain-boudary">Business Domain Boudary</a>
      </li>
      <li>
        <a href="#solution-architecture-boudary">Solution Architecture Boudary</a>
      </li>
      <li>
        <a href="#software-architecture-boudary">Software Architecture Boudary</a>
      </li>
	  <li>
        <a href="#development-boudary">Development Boudary</a>
      </li>
      </li>
	  <li>
        <a href="#delivery-boudary">Delivery Boudary</a>
      </li>
    </ul>
  </ol>
</details>

## About the Project
The aim of this project is to propose a Microservice Architecture Solution Framework for standardizing deliverables in Microservices Architecture projects. It was designed with boundaries and deliverables. Each boundary has many deliverables and they can be done in any order and/or in parallel and being enriched throughout the project lifecycle.

## What is the purpose of this framework?
You have been invited to a new initiative in your consulting firm for leading the first Microservice Architecture Project (MAP) to an important client. So, where to start?

When adopting a MAP, there are some important benefits for your business that we must consider:
Agility;
Resilient / Fault isolation;
Scalability;
High availability;
Mix of technologies;
Easy and fast deployment of new functionalities/ideias in production (fast Time to Market).

After acquiring the aforementioned benefits, we're justifying the use of this complex architecture in comparison to a monolithic architecture.

The main problem when companies are running a MAP is not to achieve those benefits, either because it doesn't follow some best practices or there is no guideline to help them. That means you're running a complex architecture without achieving their benefits that justify its adoption.

What to deliver beyond code to achieve those benefits and, in consequence, to become a competitive company in the market?

Many clients believe the MAP has only the "coding phase", if in the beginning of the MAP the developers are coding, which means the MAP is going well.

Unfortunately, this kind of mindset is very common, either because of being pressured on scope or; deadlines or even budget. Consequently the neglected part has been a deep understanding of the client’s problem by getting to know the client’s business domain, as well as being aware of the functional and nonfunctional requirements and test scenarios using some methodology like Behaviour Driven Development (BDD). 

If the understanding of the client’s problem and test scenarios are not clearly understood and aligned with stakeholders since the early stages of the MAP, it will be doomed.

The main purpose of the framework is to standardize the MAPs through well-defined and straightforward deliverables, being a reference guide that helps the companies to achieve those benefits.

To conclude, as each MAP has its own needs and has its own peculiarities, not all deliverables are applied to all types of MAPs, such as: re-architecting MAP; greenfield MAP; redesign a poorly designed solution MAP, as well as a Minimum Viable Product (MVP) project.

## Business Domain Boudary

<img src="/business-domain/images/Business Domain - Deliverables.png">

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Deliverables</summary>
  <ol>    
    <li>
      <a href="/business-domain/deliverables/domain-discovery.md">Domain Discovery</a>
    </li>
    <li>
      <a href="/business-domain/deliverables/functional-requirements.md">Functional Requirements</a>
    </li>
    <li>
      <a href="/business-domain/deliverables/bounded-contexts-context-mapping.md">Bounded Contexts Context Mapping</a>	    
    </li>
    <li>
      <a href="/business-domain/deliverables/system-context-diagram.md">System Context Diagram</a>	   
    </li>      
    <li>
      <a href="/business-domain/deliverables/microservice-catalog.md">Microservice Catalog</a>
    </li>
  </ol>
</details>

## Solution Architecture Boudary

<img src="/solution-architecture/images/Solution Architecture - Deliverables.png">

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Deliverables</summary>
  <ol>    
    <li>
     <a href="/solution-architecture/deliverables/architecture-solution-design.md">Architecture Solution Design</a>
    </li>
    <li>
     <a href="/solution-architecture/deliverables/microservice-patterns.md">Microservice Patterns</a>
    </li>
    <li>
     <a href="/solution-architecture/deliverables/architecture-decision-records.md">Architecture Decision Records</a>
    </li>
    <li>
     <a href="/solution-architecture/deliverables/architectural-caracteristics.md">Architectural Caracteristics</a>
    </li>      
    <li>
     <a href="/solution-architecture/deliverables/event-specification.md">Event Specification (AsyncAPI)</a>
    </li>
    <li>
     <a href="/solution-architecture/deliverables/constraints-records.md">Constraints Records</a>
    </li>
    <li>
     <a href="/solution-architecture/deliverables/api-management.md">API Management</a>
    </li>      
    <li>
     <a href="/solution-architecture/deliverables/uml-behavioral-diagrams.md">UML Behavioral Diagrams</a>
    </li>
    <li>
     <a href="/solution-architecture/deliverables/container-diagram.md">Container Diagram</a>
    </li>
  </ol>
</details>

## Software Architecture Boudary

<img src="/software-architecture/images/Software Architecture - Deliverables.png">

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Deliverables</summary>
  <ol>    
    <li>
     <a href="/software-architecture/deliverables/architecture-software-design.md">Architecture Software Design</a>
    </li>
    <li>
     <a href="/software-architecture/deliverables/microservice-archetype.md">Microservice Archetype</a>
    </li>
    <li>
     <a href="/software-architecture/deliverables/uml-structure-diagrams.md">UML Structure Diagrams</a>
    </li>
    <li>
     <a href="/software-architecture/deliverables/coding-standards-and-guidelines.md">Coding Standards and Guidelines</a>
    </li>      
    <li>
     <a href="/software-architecture/deliverables/branching-workflow.md">Branching Workflow</a>
    </li>    
  </ol>
</details>

## Development Boudary

<img src="/development/images/Development - Deliverables.png">

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Deliverables</summary>
  <ol>    
    <li>
     <a href="/development/deliverables/microservice-api-design.md">Microservice API Design (OpenAPI)</a>
    </li>
    <li>
     <a href="/development/deliverables/microservice-specification.md">Microservice Specification</a>
    </li>
    <li>
     <a href="/development/deliverables/features-and-scenarios-behaviour-driven.md">Features & Scenarios - Behaviour Driven</a>
    </li>
    <li>
     <a href="/development/deliverables/test-automation.md">Test Automation</a>
    </li>      
    <li>
     <a href="/development/deliverables/source-code.md">Source Code</a>
    </li>    
  </ol>
</details>

## Delivery Boudary

<img src="/delivery/images/Delivery - Deliverables.png">

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Deliverables</summary>
  <ol>    
    <li>
     <a href="/delivery/deliverables/deployment-diagram.md">Deployment Diagram</a>
    </li>
    <li>
     <a href="/delivery/deliverables/infrastructure-as-code.md">Infrastructure As Code (IaC)</a>
    </li>
    <li>
     <a href="/delivery/deliverables/deployment-pipeline-flow.md">Deployment Pipeline Flow (CI/CD)</a>
    </li>
    <li>
     <a href="/delivery/deliverables/monitoring.md">Monitoring</a>
    </li>      
    <li>
     <a href="/delivery/deliverables/chaos-engineering.md">Chaos Engineering</a>
    </li>    
  </ol>
</details>
