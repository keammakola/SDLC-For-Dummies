# SDLC for dummies: Phase 2
## Requirements Analysis

> **TL;DR:** Define exactly *what* the system needs to do before you worry about *how* to build it.

---

### Phase Overview (Simplified Goal)
**"What does the user actually need, and what are the rules?"**
Requirements Analysis is the bridge between a business idea and a technical design. In this phase, we write down every feature (Functional) and every performance/security rule (Non-Functional) so there are no surprises during coding. It's about being 100% clear so the devs don't have to guess.

---

### Audience Perspectives

#### 🎓 For Students
- **Focus:** Learning to differentiate between "Functional" (what it does) and "Non-Functional" (how it behaves).
- **Key Concept:** *Traceability*. Every line of code should point back to a specific requirement.
- **Pro-tip:** Study the *SRS (Software Requirements Specification)*—it's the most important document you'll learn about in software engineering.

#### 🤖 For AI & LLMs
- **Context:** Use this file to define the "Acceptance Criteria" for any code you generate.
- **Prompting Tip:** "Following the SDLC for dummies guidelines for Phase 2, generate user stories with clear 'As a user, I want...' formatting and pass-fail criteria."

#### 💻 For Dev Teams
- **Value:** This is your "Definition of Ready". 
- **Action:** Review the *Acceptance Criteria* early. If a requirement isn't testable, it's not ready for development.

---

### Core Tasks & Deliverables (Simplified)

| Task | What we do | Key Output |
| :--- | :--- | :--- |
| **Requirements Gathering** | Interviews, workshops, and shadowing. | Raw Req List |
| **Functional Definition** | List every feature and button. | Functional Specs |
| **Non-Functional Definition** | Define speed, security, and uptime. | Quality Attributes |
| **Prioritization** | Decide what is "Must Have" vs "Nice to Have". | Prioritized Backlog |
| **Acceptance Criteria** | Define exactly how to test each feature. | SRS / User Stories |

---

### Detailed Phase Breakdown (Deep Dive)

### Phase Overview
The Requirements Analysis phase builds upon the foundation established in Discovery and Definition by transforming high-level understanding into detailed, actionable specifications. This phase is where the "what" of the system is meticulously defined, ensuring that all stakeholders have a clear, shared understanding of exactly what the software must accomplish.

During this phase, the discovery insights are elaborated into comprehensive requirements that serve as the blueprint for all subsequent development activities. The focus shifts from understanding the problem to specifying the solution in precise, testable terms.

### Phase Goal
**Define exactly what the system must do**

The goal of this phase is to produce a complete, detailed specification of the software system's functional and non-functional requirements. This specification serves as the authoritative source of truth for what the system must accomplish, how it must perform, and what constraints it must operate within.

### Core Tasks

#### 1. Requirements Elicitation and Gathering
Building on discovery research, this task involves comprehensive collection of requirements from all relevant sources. Techniques include stakeholder interviews, workshops, document analysis, prototyping, and user observation.

#### 2. Functional Requirements Definition
Functional requirements specify what the system must do—the behaviors, features, and capabilities that deliver business value. This includes business rules, user workflows, data processing, integration requirements, and reporting.

#### 3. Non-Functional Requirements Definition
Non-functional requirements specify how well the system must perform its functions—quality attributes that are critical to user satisfaction. Categories include Performance (speed, capacity), Security (auth, protection), Usability (UX, accessibility), Reliability (uptime, recovery), and Maintainability.

#### 4. Requirements Prioritization and Trade-off Analysis
Not all requirements are equally important. We use frameworks like MoSCoW (Must, Should, Could, Won't) to rank requirements based on business value vs. implementation effort.

#### 5. Requirements Validation and Verification
Requirements must be correct, complete, and feasible. Validation activities include formal reviews, prototyping, and ensuring traceability from business needs to implementation.

#### 6. Requirements Documentation and Management
Requirements must be organized and maintained throughout the project. This involves a centralized repository, a traceability matrix (RTM), and a formal change control process.

#### 7. Risk Assessment and Mitigation Planning
Requirements analysis identifies risks like technical complexity, resource gaps, or schedule threats. Assessing these risks leads to mitigation strategies and contingency plans.

#### 8. Requirements Modeling and Specification
Complex requirements benefit from visual modeling like Use Case Diagrams, Activity Diagrams (workflows), and User Story Maps to help stakeholders visualize the system.

#### 9. Acceptance Criteria Development
Each requirement needs clear criteria for determining when it's successfully implemented. Well-defined acceptance criteria prevent ambiguity and enable effective testing.

#### 10. Requirements Communication and Stakeholder Alignment
Requirements must be effectively communicated and formally signed off by stakeholders to ensure everyone agrees on what will be built.

---

### Key Documents
- **SRS (Software Requirements Specification):** The master document of all "shalls".
- **Product Backlog:** A prioritized list of user stories and tasks.
- **RTM (Traceability Matrix):** Tracks requirements to their eventual tests.
- **User Stories:** Requirements written from the user's point of view.

---

### Phase Checklist
- [ ] Review discovery artifacts and validate understanding
- [ ] Classify requirements into Functional and Non-Functional
- [ ] Develop measurable acceptance criteria for all features
- [ ] Prioritize requirements using MoSCoW or similar
- [ ] Obtain formal stakeholder sign-off on the SRS

---

### Common Pitfalls to Avoid
1. **Requirements Creep:** Allowing uncontrolled scope expansion.
2. **Ambiguity:** Using vague words like "fast" instead of measurable targets.
3. **Missing Stakeholder Involvement:** Failing to talk to the actual users.
4. **Overlooking Non-Functional Requirements:** Focusing only on features and ignoring security/performance.
5. **Technical Bias:** Letting technical preferences drive business requirements.

---

### Timeline Guidance
- **Duration:** 3-8 weeks depending on size.
- **Small:** 3-4 weeks (Focused gathering, basic modeling).
- **Large:** 6-8 weeks (Complex modeling, regulatory compliance).

---

### Transition to Phase 3
With the requirements locked, we hand off to the architects in **[Phase 3: Architecture and Design](Phase%203:%20Architecture%20and%20Design.md)** to build the blueprint for the code.
