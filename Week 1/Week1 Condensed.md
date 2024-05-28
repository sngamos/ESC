# Week 1: Software Engineering - Revision Notes

## Introduction
### Lecture 1: Introduction to Software Engineering & Software Modelling
- **Scope**:
  - Definition and principles of Software Engineering
  - Software Development Life Cycle (SDLC)
  - Software Engineering methodologies
  - Unified Process (UP)
  - Requirement Gathering (functional and non-functional)
  - Software modelling with UML

## Learning Outcomes
1. Define Software Engineering.
2. Describe main issues in Software Engineering.
3. Explain SDLC, its phases, and objectives.
4. Describe software engineering methodologies.
5. Differentiate between functional and non-functional requirements.
6. Explain the purpose of software modelling.
7. Explain UML.

## What is Software Engineering?
- Discipline focused on producing quality software on time, within budget, and satisfying user needs.
- Involves processes, management techniques, and technical methods.

### Addressing Software Engineering Issues
1. **Management Techniques**: Control changes, monitor progress, project planning.
2. **Software Development Processes**: Requirement development and gathering techniques.
3. **Technical Methods**: Object Oriented Analysis and Design (OOAD), UML modelling, testing, and coding.

## Software Development Life Cycle (SDLC)
- **Definition**: Process of building, deploying, using, and maintaining a system.
- **Phases**:
  1. Planning
  2. Analysis
  3. Design
  4. Implementation
  5. Support
- Commonly known as the Waterfall model.

## Software Engineering Methodologies
- **Definition**: Framework or approach for software development.
- **Examples**:
  - Waterfall
  - Unified Process (UP)
  - Agile
  - Scrum
  - DevOps

### Unified Process (UP)
- Iterative and incremental approach.
- Suitable for large and complex systems.
- Based on "divide and conquer" principles.
- Includes activities and deliverables for each development step.

## Unified Process (UP) Phases
- **Iterations**: Each phase can have multiple iterations with defined objectives.
- **Disciplines**: Set of functionally related activities producing artifacts (models, documents, code, etc.).

### UP Disciplines
1. **Development Disciplines**:
   - Business Modeling
   - Requirements
   - Design
   - Implementation
   - Testing
   - Deployment
2. **Support Disciplines**:
   - Project Management
   - Configuration and Change Management
   - Environment

### Requirements Discipline
- Establish and maintain agreement on system requirements.
- Define system boundaries.
- Basis for planning technical content of iterations.

#### Functional Requirements
- Activities/processes the system must perform.
- Examples (ATM system):
  - Check card validity.
  - Validate PIN.
  - Dispense money.

#### Non-Functional Requirements
- Constraints like performance, usability, reliability, security.
- Examples (ATM system):
  - Written in C++.
  - 256-bit encryption for communication.
  - PIN validation within 5 seconds.

### Information Gathering Approaches
- Techniques: Questioning, observing, researching, modeling.
- Questions cover Who, What, When, Why, and How.

## Software Models
- **Definition**: Representation of system aspects being built.
- **Purpose**:
  - Reduce complexity.
  - Visual cues for user feedback.
  - Clarify and refine requirements early.
  - Documentation for future reference.
  - Effective teamwork platform.
  - Promotes informal training.

## UML (Unified Modeling Language)
- Visual modeling language for software engineering.
- Not a programming language.
- Used to visualize, specify, construct, and document software systems.
- Contains graphic notations for object-oriented software systems.

### UML Diagrams
- Numerous types depicting different system aspects.

## Summary
- **Software Engineering**: Discipline for quality software production.
- **SDLC**: Set of activities for system development.
- **UP**: Iterative and incremental development cycle.
- **Requirements Discipline**: Information gathering and defining functional/non-functional requirements.
- **Software Models**: Tools for reducing complexity and clarifying requirements.
- **UML**: Visual language for software system modeling.


# Week 1: UML Use Cases - Revision Notes

## Introduction
### Lecture 2: UML Use Cases
- **Scope**:
  - Use cases and misuse cases
  - Use case model and its components
  - Include and extend use cases
  - Developing Use Case Model
  - Use Case Description and its components
  - Guidelines for writing Use Case Descriptions

## Learning Outcomes
- Explain what a Use Case is.
- Explain what misuse cases are.
- Explain what a Use Case Description is and why it is needed.
- Explain what use case scenarios are.
- Write an acceptable Use Case Description.
- Identify alternate flows in use case description.
- Incorporate `<<include>>` and `<<extend>>` relationships in use case description.

## UML Use Case Diagrams
- Contribute to understanding system behaviors.
- Provide a high-level overview of system requirements.
- Components of a Use Case Diagram:
  - **Use Cases**: Described by ovals, representing user goals or system functions.
  - **Actors**: Represented by stick figures, they interact with the system.
  - **Associations**: Connecting lines between actors and use cases.
  - **System Boundary**: A box that defines the scope of the system.
  - **Packages** (optional): Organize model elements into groups.

## Developing a Use Case Diagram
- **Process**:
  1. Identify actors and roles.
  2. Extract system capabilities.
  3. Map relationship lines for each actor.
  4. Map relationship lines for system capabilities to actors.
  5. Iterate until the model stabilizes.

## Use Case Description Components
1. **Use Case Name**: Results-oriented name appearing in the use case diagram.
2. **Use Case ID**: Unique identifier for tracking.
3. **Use Case Description**: Reason, outcome, high-level sequence of actions, input data, business rules, constraints.
4. **Primary Actor**: Initiates the use case.
5. **Secondary Actor**: Interacts with the use case after initiation.
6. **Preconditions**: Activities or conditions that must be true before the use case starts.
7. **Postconditions**: State of the system after the use case execution.
8. **Main Flow**: Normal sequence of user actions and system responses.
9. **Alternative Flows**: Other legitimate usage scenarios with user actions and system responses.

## Use Case Relationships
- **Inclusion (`<<include>>`)**: Common functionality shared across multiple use cases. Base use case is incomplete without included use cases.
- **Extension (`<<extend>>`)**: Additional functionality extending a base use case. Base use case is complete without extensions.

## Misuse Cases
- Opposite of use cases, describing how a system can be abused or attacked.
- Identify potential security threats and vulnerabilities.
- Represent misuse cases as extensions of the use case diagram, identifying threat actors and converting use cases to misuse cases.

## Guidelines for Writing Use Case Descriptions
- Use simple grammar.
- Clearly indicate who is in control at each point.
- Avoid imposing constraints on user interface.
- Document user input and system responses clearly.
- **Template**:
  - Use case name/title
  - Use case ID
  - Use case description
  - Primary actor
  - Secondary actor
  - Preconditions
  - Postconditions
  - Main flow
  - Alternative flows

## Summary
- **UML Use Cases**: Understanding system behaviors, high-level requirements.
- **Relationships**: `<<include>>` and `<<extend>>`.
- **Use Case Diagram**: Visual representation of system functionality.
- **Use Case Description**: Detailed documentation of use case scenarios and flows.
- **Misuse Cases**: Identifying and mitigating potential security threats.

## Cohort Exercise – Case Study
- Develop a web application for loaning software items to staff.
- Identify functional and non-functional requirements.
- Construct a use case diagram with potential misuse cases.
- Write accompanying use case descriptions for each identified use case.

By understanding and utilizing these principles and techniques, you can effectively model and describe software system functionalities, ensuring robust and secure application development.