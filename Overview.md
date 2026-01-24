# The Universal SDLC Framework

---

## Phase 1: Discovery and Definition

**Goal:** Align on the problem being solved

**Core Tasks:**
- Stakeholder and market research
- Feasibility analysis
- Success metrics

**Key Documents:**
- Vision Statement
- Project Charter

---

## Phase 2: Requirements Analysis

**Goal:** Define exactly what the system must do

**Core Tasks:**
- Define functional requirements (features, user workflows, and logic)
- Define non-functional requirements (security, scalability, and performance)
- Assess risks such as technical and resource bottlenecks

**Key Deliverables:**
- Software Requirements Specification
- Product Backlog

---

## Phase 3: Architecture and Design

**Goal:** Create the technical and visual blueprint

**Core Tasks:**
- Prepare system design (schemas, API structures, and cloud infrastructure)
- Design the UX/UI (user journeys, wireframes, and mockups)
- Build the tech stack for the project

**Key Deliverables:**
- Design Document Specification

---

## Phase 4: Test Planning and Development

**Goal:** Define the "definition of done" before coding starts

**Core Tasks:**
- Create test cases (TDD and BDD)
- Create automation scripts for setting up the test environment and hooks
- Do security reviews to identify potential vulnerabilities in the design

**Key Deliverables:**
- Test Plan and Automated Test Scripts

---

## Phase 5: Implementation

**Goal:** Build the software to pass the pre-written tests

**Core Tasks:**
- Write code that satisfies all test cases
- Ensure continuous integration by running tests every time code is written
- Peer code reviews

**Key Deliverables:**
- Tested, Functional Code

---

## Phase 6: Deployment and Release

**Goal:** Move the code into the hands of users

**Core Tasks:**
- Automate the path to production using CI/CD
- Move existing data to the hosting system (self-hosted server, Vercel, etc.)
- Set up environment variables and security certificates

---

## Phase 7: Maintenance and Evolution

**Goal:** Keep the software healthy and relevant

**Core Tasks:**
- Have monitoring systems in place to track errors, latency, and server health
- Address user-reported bugs
- Plan for v2.0 based on user data

**Key Deliverables:**
- Performance Logs and Feedback Loops

---

## Phase 8: Decommissioning (End of Life)

**Goal:** Safely retire the system when it is no longer needed.

**Core Tasks:**
- Data Archival: Securely back up data according to compliance rules.
- Transition Management: Migrate users to a successor system.
- Infrastructure Teardown: Shut down servers and revoke access permissions.

**Key Deliverables:**
- Final Data Archive
- Shutdown Report
