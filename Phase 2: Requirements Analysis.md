# The Universal SDLC Framework

---

## Phase 2: Requirements Analysis

### Phase Overview

The Requirements Analysis phase builds upon the foundation established in Discovery and Definition by transforming high-level understanding into detailed, actionable specifications. This phase is where the "what" of the system is meticulously defined, ensuring that all stakeholders have a clear, shared understanding of exactly what the software must accomplish.

During this phase, the discovery insights are elaborated into comprehensive requirements that serve as the blueprint for all subsequent development activities. The focus shifts from understanding the problem to specifying the solution in precise, testable terms. This phase requires close collaboration between business analysts, product owners, technical architects, and subject matter experts to balance user needs with technical feasibility and business constraints.

The primary objective is to produce requirements that are complete, consistent, unambiguous, and verifiable—qualities that prevent costly rework and ensure the final product meets stakeholder expectations. Without thorough requirements analysis, projects risk building the wrong features, missing critical functionality, or creating systems that fail to deliver business value.

This phase typically involves iterative refinement, where initial requirements are progressively detailed and validated through reviews, prototyping, and stakeholder feedback. The investment in comprehensive requirements analysis pays dividends by reducing defects, improving development efficiency, and increasing the likelihood of project success.

---

### Phase Goal

**Define exactly what the system must do**

The goal of this phase is to produce a complete, detailed specification of the software system's functional and non-functional requirements. This specification serves as the authoritative source of truth for what the system must accomplish, how it must perform, and what constraints it must operate within.

Requirements analysis achieves this through systematic decomposition of high-level needs into specific, measurable requirements that can be implemented and tested. The phase concludes when all requirements are documented, prioritized, validated, and approved by key stakeholders.

---

### Core Tasks

#### 1. Requirements Elicitation and Gathering

Building on discovery research, this task involves comprehensive collection of requirements from all relevant sources. Techniques include:

- **Stakeholder Interviews:** Deep-dive sessions with users, business owners, and technical teams to uncover detailed needs
- **Requirements Workshops:** Facilitated sessions using techniques like use case modeling, user story mapping, and requirements prioritization
- **Document Analysis:** Review of existing systems, contracts, regulations, and business processes
- **Prototyping:** Creation of low-fidelity mockups or wireframes to validate understanding and elicit feedback
- **Observation:** Shadowing users in their work environment to understand implicit requirements
- **Surveys and Questionnaires:** Gathering input from larger user groups for quantitative validation

Requirements are captured in multiple formats to accommodate different stakeholder preferences and use cases.

#### 2. Functional Requirements Definition

Functional requirements specify what the system must do—the behaviors, features, and capabilities that deliver business value. This includes:

- **Business Rules:** The logic and constraints that govern system behavior
- **User Workflows:** Step-by-step processes users will follow to accomplish tasks
- **Data Processing:** How the system transforms, validates, and manages data
- **Integration Requirements:** How the system interacts with external systems and APIs
- **User Interface Requirements:** Screen layouts, navigation flows, and interaction patterns
- **Reporting and Analytics:** What information the system must provide and how it should be presented

Functional requirements are documented using clear, concise language with acceptance criteria that define when a requirement is satisfied.

#### 3. Non-Functional Requirements Definition

Non-functional requirements specify how well the system must perform its functions—quality attributes that are critical to user satisfaction and system success. Categories include:

**Performance Requirements:**
- Response time targets for different operations
- Throughput and concurrency requirements
- Resource utilization limits (CPU, memory, storage)
- Scalability requirements for future growth

**Security Requirements:**
- Authentication and authorization mechanisms
- Data protection and privacy requirements
- Compliance with security standards (e.g., GDPR, HIPAA)
- Audit and logging requirements

**Usability Requirements:**
- User experience standards and accessibility requirements
- Training and support needs
- Localization and internationalization requirements

**Reliability Requirements:**
- Availability targets (uptime percentages)
- Mean time between failures (MTBF)
- Recovery time objectives (RTO) and recovery point objectives (RPO)
- Fault tolerance and error handling requirements

**Maintainability Requirements:**
- Code quality standards and documentation requirements
- Modularity and extensibility requirements
- Testing and deployment automation requirements

**Compatibility Requirements:**
- Supported platforms, browsers, and devices
- Integration with existing systems and third-party services
- Backward compatibility requirements

#### 4. Requirements Prioritization and Trade-off Analysis

Not all requirements are equally important. This task involves:

- **Prioritization Frameworks:** Using MoSCoW (Must have, Should have, Could have, Won't have) or other methods to rank requirements
- **Value vs. Effort Analysis:** Assessing business value against implementation complexity
- **Risk Assessment:** Identifying requirements that carry high technical or business risk
- **Dependency Mapping:** Understanding how requirements relate to and depend on each other
- **Release Planning:** Determining which requirements will be delivered in which releases

Prioritization ensures that the most valuable features are delivered first and that trade-offs are made consciously.

#### 5. Requirements Validation and Verification

Requirements must be correct, complete, and feasible. Validation activities include:

- **Requirements Reviews:** Formal inspection of requirements by cross-functional teams
- **Prototyping and Proof-of-Concepts:** Building small demonstrations to validate feasibility
- **User Acceptance Testing (UAT) Planning:** Defining how users will validate the final implementation
- **Traceability Analysis:** Ensuring requirements can be traced from business needs to implementation
- **Consistency Checks:** Verifying that requirements don't conflict with each other
- **Feasibility Reviews:** Confirming that requirements can be implemented within constraints

Validation ensures that requirements accurately reflect stakeholder needs and are implementable.

#### 6. Requirements Documentation and Management

Requirements must be organized and maintained throughout the project lifecycle. This includes:

- **Requirements Repository:** A centralized system for storing and versioning requirements
- **Requirements Traceability Matrix:** Mapping requirements to business objectives, test cases, and implementation
- **Change Control Process:** Managing requirements changes through formal approval processes
- **Requirements Baselines:** Establishing approved versions of requirements that serve as change control baselines
- **Requirements Attributes:** Tracking metadata like priority, status, source, and verification method

Effective documentation ensures requirements remain current and traceable throughout the project.

#### 7. Risk Assessment and Mitigation Planning

Requirements analysis identifies and addresses risks that could impact project success:

- **Technical Risks:** Requirements that push technological boundaries or require unproven solutions
- **Business Risks:** Requirements that depend on uncertain business conditions or external factors
- **Resource Risks:** Requirements that require scarce skills or specialized knowledge
- **Schedule Risks:** Requirements that could delay delivery if not addressed early
- **Scope Risks:** Requirements that could lead to scope creep or feature bloat

Risk assessment produces mitigation strategies and contingency plans for high-risk requirements.

#### 8. Requirements Modeling and Specification

Complex requirements benefit from visual and formal modeling:

- **Use Case Diagrams:** Illustrating system interactions with external actors
- **Activity Diagrams:** Modeling complex workflows and business processes
- **Data Flow Diagrams:** Showing how data moves through the system
- **Entity-Relationship Diagrams:** Defining data structures and relationships
- **State Diagrams:** Modeling system behavior over time
- **User Story Maps:** Organizing features into user journeys and release plans

Modeling helps stakeholders visualize complex requirements and identify gaps or inconsistencies.

#### 9. Acceptance Criteria Development

Each requirement needs clear criteria for determining when it's successfully implemented:

- **Functional Acceptance Criteria:** Specific conditions that must be met for a feature to work correctly
- **Quality Acceptance Criteria:** Standards for performance, usability, and other non-functional attributes
- **Business Acceptance Criteria:** Business outcomes that must be achieved
- **Testable Criteria:** Requirements phrased in ways that enable automated or manual testing

Well-defined acceptance criteria prevent ambiguity about whether requirements have been met.

#### 10. Requirements Communication and Stakeholder Alignment

Requirements must be effectively communicated to all stakeholders:

- **Requirements Presentations:** Regular reviews and walkthroughs of requirements
- **Stakeholder Feedback Loops:** Mechanisms for ongoing input and validation
- **Requirements Training:** Educating stakeholders on how to read and provide feedback on requirements
- **Conflict Resolution:** Processes for resolving disagreements between stakeholders
- **Sign-off Processes:** Formal approval of requirements by authorized stakeholders

Effective communication ensures everyone understands and agrees on what will be built.

---

### Key Deliverables

#### Software Requirements Specification (SRS)

The SRS is the comprehensive document that captures all system requirements. A well-structured SRS includes:

**1. Introduction**
- Purpose and scope of the document
- Definitions, acronyms, and abbreviations
- References to related documents
- Overview of the system's context and constraints

**2. Overall Description**
- Product perspective (system context and interfaces)
- Product functions (high-level capabilities)
- User characteristics (user profiles and technical background)
- Constraints (business, technical, regulatory)
- Assumptions and dependencies

**3. Specific Requirements**
- External interface requirements (user, hardware, software, communication)
- Functional requirements (detailed behaviors and features)
- Performance requirements (speed, capacity, throughput)
- Design constraints (standards, protocols, hardware limitations)
- Software system attributes (security, reliability, usability, etc.)
- Other requirements (database, operations, administration)

**4. Appendices**
- Analysis models and diagrams
- Detailed mathematical formulations
- Requirements traceability matrix
- Glossary and index

The SRS serves as the contract between stakeholders and the development team, providing the basis for design, implementation, and testing.

#### Product Backlog

The product backlog is a living, prioritized list of all potential work items for the product. For requirements analysis, it includes:

- **Epics:** Large, high-level features that represent major system capabilities
- **User Stories:** Detailed, user-centric requirements following the format: "As a [user type], I want [functionality] so that [benefit]"
- **Acceptance Criteria:** Specific conditions that must be met for each story
- **Story Points or Estimates:** Relative sizing of implementation effort
- **Priority Rankings:** Business value and urgency assessments
- **Dependencies:** Relationships between backlog items
- **Definition of Ready:** Criteria that must be met before a backlog item can be worked on

The product backlog evolves throughout the project, with requirements analysis establishing the initial comprehensive list that guides development prioritization.

#### Requirements Traceability Matrix

A traceability matrix links requirements to their sources and ensures comprehensive coverage:

- **Business Requirements Traceability:** Links to business objectives and stakeholder needs
- **Functional Requirements Traceability:** Links to specific features and capabilities
- **Test Case Traceability:** Links to verification and validation activities
- **Implementation Traceability:** Links to code, designs, and other artifacts
- **Change Traceability:** Tracks how requirements evolve through changes

The matrix ensures that all requirements are implemented, tested, and maintained appropriately.

#### Use Case Specifications

Detailed use case documents that describe system interactions:

- **Use Case Name and Identifier:** Unique identification
- **Actors:** Users or systems involved in the use case
- **Preconditions:** What must be true before the use case begins
- **Postconditions:** What will be true after successful completion
- **Main Success Scenario:** The primary path through the use case
- **Alternative Flows:** Variations and exception handling
- **Business Rules:** Constraints and business logic
- **Non-Functional Requirements:** Performance and quality attributes

Use cases provide detailed behavioral specifications that complement the SRS.

#### User Story Repository

A collection of user stories with supporting information:

- **Story Cards:** Concise user story statements
- **Acceptance Criteria:** Detailed conditions for story completion
- **Story Mapping:** Visual organization of stories into user journeys
- **Prioritization:** Business value and effort assessments
- **Dependencies:** Relationships between stories
- **Wireframes/Mockups:** Visual representations of story implementations

The repository serves as the foundation for agile development approaches.

#### Requirements Risk Register

Documentation of requirements-related risks:

- **Risk Description:** What could go wrong with requirements
- **Impact Assessment:** Potential consequences if the risk materializes
- **Probability Assessment:** Likelihood of the risk occurring
- **Mitigation Strategies:** Actions to reduce risk probability or impact
- **Contingency Plans:** Backup approaches if mitigation fails
- **Risk Owner:** Person responsible for monitoring and managing the risk

The risk register ensures proactive management of requirements uncertainties.

---

### Phase Checklist

**Pre-Phase Activities:**
- [ ] Review discovery artifacts and validate understanding
- [ ] Assemble requirements analysis team
- [ ] Establish requirements management tools and processes
- [ ] Schedule stakeholder workshops and interviews

**Elicitation Activities:**
- [ ] Conduct stakeholder interviews and workshops
- [ ] Review existing documentation and systems
- [ ] Perform user observations and contextual inquiries
- [ ] Create initial prototypes or mockups
- [ ] Document all elicited requirements

**Analysis Activities:**
- [ ] Classify requirements (functional, non-functional, constraints)
- [ ] Identify and document business rules
- [ ] Model complex workflows and data flows
- [ ] Assess technical feasibility of requirements
- [ ] Identify requirements dependencies and conflicts

**Specification Activities:**
- [ ] Write detailed functional requirements
- [ ] Define non-functional requirements with measurable criteria
- [ ] Develop acceptance criteria for each requirement
- [ ] Create use case specifications
- [ ] Document interface and integration requirements

**Validation Activities:**
- [ ] Conduct requirements reviews with stakeholders
- [ ] Validate requirements through prototyping
- [ ] Perform consistency and completeness checks
- [ ] Establish requirements traceability
- [ ] Obtain stakeholder sign-off on requirements

**Documentation Activities:**
- [ ] Create Software Requirements Specification
- [ ] Develop product backlog with prioritized user stories
- [ ] Build requirements traceability matrix
- [ ] Document requirements models and diagrams
- [ ] Establish requirements baseline

**Risk Management Activities:**
- [ ] Identify requirements-related risks
- [ ] Assess risk impact and probability
- [ ] Develop mitigation and contingency plans
- [ ] Assign risk owners and monitoring responsibilities
- [ ] Create requirements risk register

**Phase Closure:**
- [ ] Obtain formal approval of requirements deliverables
- [ ] Conduct requirements analysis retrospective
- [ ] Handoff approved requirements to design team
- [ ] Archive requirements analysis artifacts
- [ ] Communicate requirements to all stakeholders

---

### Common Pitfalls to Avoid

**1. Requirements Creep**
Allowing uncontrolled addition of requirements leads to scope expansion and delayed delivery. Establish clear change control processes and require formal approval for all changes.

**2. Ambiguous Requirements**
Vague or unclear requirements lead to misinterpretation and incorrect implementation. Use clear, concise language with specific acceptance criteria.

**3. Missing Stakeholder Involvement**
Failing to engage all relevant stakeholders results in incomplete or incorrect requirements. Maintain active stakeholder participation throughout the phase.

**4. Overlooking Non-Functional Requirements**
Focusing only on features while ignoring performance, security, and usability leads to unusable systems. Dedicate specific effort to identifying and specifying quality attributes.

**5. Poor Requirements Organization**
Unorganized requirements make it difficult to manage changes and ensure completeness. Use structured formats and maintain traceability throughout the project.

**6. Lack of Validation**
Producing requirements without stakeholder validation leads to incorrect assumptions becoming embedded in the project. Build validation checkpoints into the requirements process.

**7. Technical Bias in Requirements**
Allowing technical considerations to dominate business needs results in over-engineered solutions. Keep business value as the primary driver of requirements decisions.

**8. Insufficient Risk Assessment**
Failing to identify and mitigate requirements risks leads to unexpected challenges during implementation. Conduct thorough risk analysis for all significant requirements.

**9. Inadequate Traceability**
Without proper traceability, it's impossible to verify that all requirements are implemented and tested. Maintain comprehensive traceability from requirements to implementation.

**10. Premature Commitment to Solutions**
Jumping to design solutions during requirements analysis limits exploration of alternatives. Focus on "what" not "how" during this phase.

---

### Best Practices

**Adopt a Collaborative Approach**
Requirements analysis is a team sport. Involve stakeholders early and often, using workshops and collaborative tools to build shared understanding.

**Use Multiple Elicitation Techniques**
Different stakeholders respond to different approaches. Combine interviews, workshops, prototyping, and observation to capture diverse perspectives.

**Write Testable Requirements**
Phrase requirements in ways that enable clear verification. Include specific, measurable acceptance criteria for each requirement.

**Maintain Requirements Living**
Requirements evolve as understanding deepens. Use version control and change management to keep requirements current without losing control.

**Prioritize Ruthlessly**
Not all requirements are equally important. Use data-driven prioritization to focus effort on the most valuable features.

**Model Complex Requirements**
Use diagrams and models to communicate complex requirements more effectively than text alone.

**Validate Early and Often**
Don't wait until the end to validate requirements. Use prototypes, reviews, and feedback loops throughout the process.

**Document Assumptions Explicitly**
Every requirement rests on assumptions. Document them clearly so they can be validated and managed as risks.

**Establish Clear Ownership**
Assign clear ownership for each requirement, including responsibility for clarification, validation, and change management.

**Plan for Change**
Requirements will change. Build flexibility into the process and establish efficient change management procedures.

---

### Tools and Techniques

**Requirements Management:**
- Requirements management tools (Jira, Azure DevOps, IBM DOORS)
- Collaborative documentation platforms (Confluence, Notion, Google Docs)
- Version control systems for requirements artifacts

**Modeling and Analysis:**
- UML modeling tools (Enterprise Architect, Visual Paradigm)
- Business process modeling tools (Bizagi, Signavio)
- Wireframing and prototyping tools (Figma, Sketch, Adobe XD)

**Elicitation and Collaboration:**
- Workshop facilitation tools (Miro, Mural)
- Survey and feedback platforms (SurveyMonkey, Typeform)
- Video conferencing for remote stakeholder engagement

**Validation and Review:**
- Requirements review checklists and templates
- Automated requirements validation tools
- Traceability management systems

**Prioritization:**
- Prioritization frameworks (Kano analysis, MoSCoW method)
- Value vs. effort mapping tools
- Story mapping canvases

---

### Timeline Guidance

The Requirements Analysis phase typically spans **3-8 weeks** depending on project complexity:

| Project Scale | Duration | Typical Activities |
|---------------|----------|-------------------|
| Small/Internal Tool | 3-4 weeks | Focused requirements gathering, basic modeling, stakeholder validation |
| Medium/Business Application | 4-6 weeks | Comprehensive elicitation, detailed specification, extensive validation |
| Large/Enterprise System | 6-8 weeks | Multi-phase analysis, complex modeling, regulatory compliance requirements |

Timeline factors affecting duration:
- Number and diversity of stakeholders
- Complexity of business domain and processes
- Regulatory and compliance requirements
- Availability of subject matter experts
- Level of existing documentation
- Need for prototyping and validation

---

### Exit Criteria for Phase Completion

The Requirements Analysis phase is complete when:

1. **Requirements Complete:** All functional and non-functional requirements are identified, documented, and prioritized.

2. **Requirements Validated:** Requirements have been reviewed and approved by all key stakeholders.

3. **Requirements Feasible:** Technical feasibility has been confirmed for all requirements.

4. **Requirements Traceable:** All requirements can be traced to business objectives and stakeholder needs.

5. **Requirements Testable:** Each requirement has clear, measurable acceptance criteria.

6. **Deliverables Produced:** SRS, product backlog, and supporting artifacts are complete and approved.

7. **Risks Mitigated:** Requirements-related risks are identified and mitigation plans are in place.

8. **Stakeholder Alignment:** All stakeholders understand and agree on the requirements.

9. **Baseline Established:** Approved requirements are baselined for change control.

10. **Handoff Ready:** Requirements are organized and documented for effective handoff to the design team.

---

### Transition to Phase 3

Upon completion of Phase 2, the project team transitions to **Phase 3: Architecture and Design**. The requirements artifacts—particularly the SRS and product backlog—provide the detailed specifications that guide architectural decisions and design activities.

Key handoff activities include:
- Review of requirements with architecture and design team
- Clarification of complex or ambiguous requirements
- Discussion of architectural implications and constraints
- Transfer of requirements models and specifications
- Briefings on stakeholder priorities and business context

The quality of requirements analysis directly impacts the effectiveness of subsequent phases. Thorough, well-validated requirements enable efficient design and implementation while minimizing costly rework.
