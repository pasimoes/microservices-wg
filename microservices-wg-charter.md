# Microservices Working Group

## Primary Authors 
- Paulo Simoes, Oracle
- Tracy Ragan, DeployHub

## Introduction
This charter describes the operations of the CNCF WG Microservices within CNCF Application Delivery TAG. The focus is on delivering cloud native applications 
using a microservice architecture which involves multiple phases of the application delivery process including building, deploying, testing, managing, and operations. Important to understand in the formation of this WG is the disruption of the monolithic practice of deliverying software created by moving to a microservice architecture. Additionally, the TAG produces supporting material and best practices for end-users, and provides guidance and coordination for CNCF projects working within the TAG’s scope.

## Alignment with SIG App Delivery Charter
As an “operating model” for cloud native applications, the microservice architecture fully aligns with "Application delivery workflow and strategy" and 
"Configuration source driven workflow" scopes defined in CNCF SIG App Delivery charter.

## Mission
Consistent with the CNCF WG definition, the mission of CNCF WG Microservices is:

- To collaborate on areas related to developing, distributing, deploying, managing and operating secure microservices architecture
with the target of delivering application in manner of cloud native.

- To develop informational resources including guides, tutorials and white papers to give the community an understanding of best practices, trade-offs, 
and value-adds regarding to microservices development.

- To identify suitable projects and gaps in the landscape, periodically updating the TOC with suggested actions in a structured manner. This includes 
helping the TOC with assessments and due diligence of prospective new projects.

## Areas considered in Scope
WG Microservices focuses on the following topics of the lifecycle of cloud-native applications:

- Microservices architecture and definition, including description, parameter and configuration
- Guidance and practice for microservices design and development
- Microservices bundling, packaging and deployment
- Microservice versioning, configuration management and tracking
- Microservices Security and Observability instrumentation
- Microservices Lifecycle Management, including Release management
- Interoperability including Integration patterns.
- Data Management and Event Management (Data Mesh, Event Mesh)

The MS-WG will work on developing best practices, fostering collaboration between related projects, working on improving tool interoperability as well as 
proposing new initiatives and projects when blank spots in the current landscape are identified.

The following, non exhaustive, sample list of activities and deliverables are in-scope for the MS-WG:
- Education material to help provide guidance for the community
- Microservices definition, development and distribution
- Guidance for microservices development and architecture
- Standard and generic microservice delivery pattern
- Other tools or practices which may be involved in the workflow of microservice delivery, including but not limited to:
  - Building and configuration
  - Testing
  - Deploying, Orchestration and Patching
  - Policy and security
  - Debugging and monitoring

## Areas considered out of Scope
Anything not explicitly considered in the scope above. Example include:
- Non cloud-native applications.
- Developer tools which are not closely related to delivering application to cloud.
- Specific programming model or developing framework.
- Definition of standards for components like container images and other infrastructure-level building blocks of cloud-native applications.

## Roadmap

## Governance
### Cross-group relationships
Lifecycle management of microservices is a broad and mainstream topic of Cloud Native computing; therefore this WG may collaborate with most of the 
other CNCF TAGs, WG and projects. However, the following groups might have the largest potential interactions:

- TAG Security - The publication of guidance or tutorials by the TAG could see the adoption of insecure practices if security isn’t considered as a 
prerequisite for publication. Collaborating with TAG Security on reviews should help to ensure guidance doesn’t lead to propagating insecure patterns of usage.

- Kubernetes SIG Apps - Many projects currently under Kubernetes SIG Apps may overlap with CNCF TAG App Delivery. The application delivery TAG will 
focus on end-to-end aspects of these projects, including non-Kubernetes platforms and projects where applicable; while Kubernetes SIG Apps will focus on 
Kubernetes-specific runtime-level concerns. Close collaboration is expected to happen within these two groups around different phases for application delivery.

- WG GitOps - The process to delivery microservices and the best practices to continuous integration, continuous deployment and continuous delivery overlap 
with this group. 



## Operations
- TOC Liaisons: TBD
- TAG chairs: TBD

## Contact
