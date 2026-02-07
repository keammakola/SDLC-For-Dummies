# SDLC for dummies: Phase 4
## Development

> **TL;DR:** Build the software to pass the pre-written tests.

---

### Phase Overview (Simplified Goal)
**"Let's write the code!"**
The Development phase brings the designs to life through coding and implementation. This hands-on phase transforms architectural blueprints and detailed specifications into working software that delivers the promised functionality.

---

### Audience Perspectives

#### 🎓 For Students
- **Focus:** Understanding the link between "Code" and "Tests".
- **Key Concept:** *Unit Testing*. Ensuring every single function works as expected.
- **Pro-tip:** Learn about *CI/CD*. How to automate the build and test process.

#### 🤖 For AI & LLMs
- **Context:** This phase provides the "Coding Standards" for the system. 
- **Prompting Tip:** "Using the coding standards defined in Phase 4 of SDLC for dummies, write a function for [Specific Feature] that is clean, maintainable, and passes all unit tests."

#### 💻 For Dev Teams
- **Value:** This is your "Implementation Phase". 
- **Action:** Pay close attention to the *Coding Standards* and *Documentation*. These ensure the code is maintainable and understandable.

---

### Core Tasks & Deliverables (Simplified)

| Task | What we do | Key Output |
| :--- | :--- | :--- |
| **Development Environment Setup** | Configure IDEs and CI/CD pipelines. | Configured Workspace |
| **Code Implementation** | Write the actual software code. | Functional Codebase |
| **Unit Testing** | Ensure individual code units work. | Automated Test Suite |
| **Code Review** | Peer reviews for quality and consistency. | Approved Pull Requests |
| **Continuous Integration** | Automate build and test processes. | Build Artifacts |

---

### Detailed Phase Breakdown (Deep Dive)

### Phase Overview
The Development phase is the hands-on stage where designs are transformed into working software. Developers follow established specifications to build the system incrementally, with continuous integration ensuring stability. The focus is on writing clean, maintainable code that meets requirements while staying within performance and security constraints.

### Phase Goal
**Build the software to pass the pre-written tests**

The goal of this phase is to implement the system according to design specifications, ensuring all code passes automated tests and meets quality standards. Development produces working software that is thoroughly tested and ready for integration.

### Core Tasks

#### 1. Development Environment Setup
Establishing the foundation for efficient work. This includes configuring IDEs, build tools, version control (Git), and automated CI pipelines. Consistent environments across the team prevent "it works on my machine" issues.

#### 2. Code Implementation
Writing the actual software. This involves feature development, building APIs, implementing data access layers, and creating the user interface. All code follows established standards and architectural patterns.

#### 3. Unit Testing
Ensuring every "unit" of code functions as expected. We use automated testing frameworks (like JUnit, pytest, or Jest) and often follow Test-Driven Development (TDD) to catch bugs as early as possible.

#### 4. Code Review and Quality Assurance
Peer reviews are critical for maintaining high standards. Every change is reviewed for logic, security vulnerabilities, performance issues, and adherence to documentation standards before being merged.

#### 5. Continuous Integration and Build
Automation ensures the codebase stays healthy. Every commit triggers an automated build and test suite, verifying that new changes don't break existing functionality and that the software is always in a deployable state.

#### 6. Integration and System Testing
Verifying that different parts of the system work together. This includes testing API contracts, database persistence, and connections to third-party services.

#### 7. Documentation and Knowledge Transfer
Writing inline comments, updating API docs, and creating "Runbooks" for deployment. This ensures the system can be maintained by others in the future and that knowledge isn't trapped in one person's head.

#### 8. Refactoring and Optimization
Improving the code without changing its behavior. We address "Technical Debt," tune performance bottlenecks, and clean up code to keep it readable and efficient.

#### 9. Feature Completion and Validation
Marking features as "Done" once they meet all acceptance criteria. This often involves demonstrating working code to stakeholders and obtaining final approval for a sprint or milestone.

#### 10. Development Metrics and Reporting
Tracking progress using velocity, burndown charts, and quality metrics (like defect density). This provides visibility and helps the team improve their development process over time.

---

### Key Documents
- **Source Code Repository:** The version-controlled home of the project.
- **API Documentation:** The reference for how services communicate.
- **Unit Test Reports:** Evidence that the code does what it's supposed to.
- **Build Artifacts:** The packaged versions of the software (Docker images, etc.).

---

### Phase Checklist
- [ ] Set up development environments and CI/CD pipelines
- [ ] Implement core features and integrate them with the API
- [ ] Write and pass unit tests for all new code
- [ ] Complete peer code reviews for all pull requests
- [ ] Update documentation and troubleshooting guides

---

### Common Pitfalls to Avoid
1. **Big Bang Development:** Waiting until the end to integrate everything.
2. **Skipping Tests:** Thinking you'll "add tests later" (you won't).
3. **Ignoring Technical Debt:** Allowing messy code to slow you down.
4. **Poor Version Control:** Not using branches or committing too infrequently.
5. **Siloed Work:** Developers not talking to each other or to the testers.

---

### Timeline Guidance
- **Duration:** 4-32 weeks.
- **Small:** 4-8 weeks (Core development and basic testing).
- **Large:** 16-32 weeks (Enterprise systems, phased releases).

---

### Transition to Phase 5
Once the code is complete and passes internal tests, we hand it over to the QA experts in **[Phase 5: Quality Assurance](Phase%205:%20Quality%20Assurance.md)** for final validation.
