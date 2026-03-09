# Assignment 2: Software Process Models, Team Roles, and Project Management
**Course:** Software Engineering
**Group Members:** [Student 1], [Student 2], [Student 3]
**Date:** March 2026

---

## Overview

This report analyzes three major software process models — Waterfall, Spiral, and Agile (Scrum) — examining their phases, characteristics, advantages, disadvantages, and suitable use cases. It also provides a comparative analysis to determine which model best fits specific project types, followed by an explanation of key software team roles and their contributions to project success.

---

## Task 1: Model Explanation

### 1.1 Waterfall Model

#### Description and Phases
The Waterfall Model is a linear, sequential software development process where progress flows in one direction — downward through clearly defined phases, like a waterfall. Each phase must be fully completed before the next begins, and there is no going back to a previous phase once it is finished.

**Phases:**
1. **Requirements** – All system requirements are gathered and documented in full before any design begins.
2. **System Design** – The software architecture and technical specifications are defined based on the requirements.
3. **Implementation** – Developers write the actual code according to the design documents.
4. **Integration & Testing** – The system is tested for defects and verified against the original requirements.
5. **Deployment** – The finished product is delivered to the client or end users.
6. **Maintenance** – Ongoing support, bug fixes, and minor updates are applied post-delivery.

#### Key Characteristics
- Strictly sequential with no overlap between phases
- Heavy documentation at each stage
- Requirements must be fully defined upfront
- Progress is measured by phase completion
- Little to no customer involvement after the requirements phase

#### Advantages
- Simple and easy to understand and manage
- Well-structured with clear milestones and deliverables
- Strong documentation makes it easy to onboard new team members
- Works well when requirements are stable and well-understood
- Easy to track progress and estimate costs

#### Disadvantages
- Very inflexible — changes are difficult and expensive to implement once a phase is complete
- Customers do not see a working product until late in the process
- High risk of delivering a product that no longer meets user needs (requirements may become outdated)
- Poor handling of uncertainty and complexity
- Testing happens late, making defects more costly to fix

#### Suitable Project Types
- Projects with well-defined, stable, and unlikely-to-change requirements
- Government and defense contracts with strict documentation requirements
- Construction and manufacturing software
- Short-duration projects with clear deliverables
- Example: A payroll system for a company with fixed regulatory rules

---

### 1.2 Spiral Model

#### Description and Phases
The Spiral Model, introduced by Barry Boehm in 1986, combines elements of both iterative development and systematic risk management. The process is represented as a spiral with each loop representing one complete development cycle (called a "spiral"). Each cycle passes through four quadrants, progressively building the software while continuously assessing and mitigating risks.

**Phases (per spiral loop):**
1. **Planning** – Objectives, constraints, and alternatives are identified. Scope of the current spiral is defined.
2. **Risk Analysis** – Potential risks are identified, analyzed, and mitigation strategies are developed. Prototypes are often created at this stage.
3. **Engineering (Development & Testing)** – The actual software product is designed, coded, and tested.
4. **Evaluation** – The customer reviews the output of the current spiral and provides feedback, which feeds into the planning for the next cycle.

#### Key Characteristics
- Risk-driven: every cycle begins with a risk analysis
- Iterative — software is built incrementally across multiple spirals
- Combines prototyping with systematic development
- Strong customer involvement throughout the process
- Each spiral produces a progressively more complete version of the system

#### Advantages
- Excellent risk management — risks are identified and addressed early and continuously
- Highly flexible — new requirements can be incorporated in subsequent spirals
- Customer feedback is incorporated at every cycle
- Suitable for large, complex systems where requirements evolve
- Prototyping reduces the chance of building the wrong product

#### Disadvantages
- Expensive and resource-intensive due to constant risk analysis
- Complex to manage — requires significant expertise
- Not suitable for small or simple projects
- Risk analysis requires specialized skills that not all teams have
- Can result in an indefinite number of spirals if not properly controlled

#### Suitable Project Types
- Large-scale, high-risk projects (e.g., aerospace, defense, financial systems)
- Projects where requirements are not fully known at the start
- Systems requiring multiple rounds of prototyping and refinement
- Projects with large budgets and long timelines
- Example: Developing flight control software for a commercial aircraft

---

### 1.3 Agile Model (Scrum)

#### Description and Phases
Agile is an iterative and incremental software development methodology that emphasizes flexibility, collaboration, and customer satisfaction. Scrum is the most widely used Agile framework. Work is organized into short, fixed-length iterations called **Sprints** (typically 1–4 weeks), each delivering a potentially shippable product increment.

**Scrum Phases / Events:**
1. **Product Backlog Creation** – The Product Owner creates and prioritizes a list of features and requirements (user stories).
2. **Sprint Planning** – The team selects items from the backlog to complete during the upcoming sprint.
3. **Sprint Execution (1–4 weeks)** – Developers build the selected features. Daily Scrum meetings (stand-ups) keep the team aligned.
4. **Sprint Review** – The team demonstrates the completed work to stakeholders and gathers feedback.
5. **Sprint Retrospective** – The team reflects on the process and identifies improvements for the next sprint.
6. **Repeat** – The cycle continues until the product is complete or the backlog is exhausted.

**Key Scrum Roles:**
- **Product Owner** – Manages the product backlog and represents the customer
- **Scrum Master** – Facilitates the process and removes obstacles
- **Development Team** – Self-organizing team that builds the product

#### Key Characteristics
- Time-boxed iterations (sprints)
- Continuous customer collaboration and feedback
- Working software delivered frequently
- Self-organizing, cross-functional teams
- Adaptive planning — requirements can change between sprints
- Minimal upfront documentation; focuses on working software

#### Advantages
- Highly flexible and responsive to change
- Customers see working software early and often
- Early detection of issues through frequent testing and review
- High team collaboration and morale
- Faster time-to-market for core features
- Continuous improvement through retrospectives

#### Disadvantages
- Difficult to predict final cost and timeline upfront
- Requires active and continuous customer involvement (which may not always be possible)
- Can lead to scope creep if the backlog is not well managed
- Less emphasis on documentation can cause issues for future maintenance
- Not ideal for teams that are geographically distributed or lack discipline
- Scaling to very large teams requires additional frameworks (e.g., SAFe, LeSS)

#### Suitable Project Types
- Startups and products with evolving or unclear requirements
- Web and mobile application development
- Projects where rapid delivery and iteration are priorities
- Small to medium-sized teams (5–12 people per team)
- Example: Developing a social media mobile application for a startup

---

## Task 2: Comparative Analysis

### 2.1 Comparison Table

| Criteria                | Waterfall              | Spiral                      | Agile (Scrum)              |
|-------------------------|------------------------|-----------------------------|----------------------------|
| **Flexibility**         | Low — rigid sequential | Medium — iterative but structured | High — changes welcome anytime |
| **Risk Handling**       | Poor — risks addressed late | Excellent — continuous risk analysis | Good — risks visible early through sprints |
| **Customer Involvement**| Low — mainly at requirements phase | Medium — reviewed at each spiral | High — involved every sprint |
| **Documentation Level** | Very High              | High                        | Low to Medium              |
| **Team Size**           | Any (works well for larger teams) | Large, specialized teams | Small to Medium (5–12 per team) |
| **Project Size**        | Small to Medium        | Large to Very Large         | Small to Medium            |
| **Cost Implications**   | Lower upfront cost, higher cost of late changes | High overall cost due to risk analysis | Moderate — pay-as-you-go per sprint |

---

### 2.2 Analysis: Which Model Best Fits Each Project Type?

#### A Banking System — Recommended: Waterfall (with elements of Spiral)

A banking system is a large-scale, mission-critical application that typically has strict regulatory requirements, compliance standards (e.g., PCI-DSS, Basel III), and well-defined functional specifications that are unlikely to change significantly once established. Security and reliability are paramount.

**Why Waterfall fits:**
- Banking requirements are typically defined in full before development begins, making the sequential approach effective.
- Heavy documentation is a regulatory necessity — banks must demonstrate what the system does and how, which aligns with Waterfall's documentation-heavy approach.
- The structured phase gates make it easy to conduct formal audits and compliance reviews.
- Changes to a live banking system are tightly controlled, meaning the inflexibility of Waterfall is actually a feature rather than a limitation.

**Why Spiral elements help:**
- For particularly complex banking modules (e.g., core banking engine, fraud detection), incorporating Spiral's risk analysis at the design stage can prevent costly failures.

A hybrid of Waterfall with embedded risk management practices from Spiral is the most pragmatic approach for modern banking systems.

---

#### A Mobile Startup App — Recommended: Agile (Scrum)

A mobile startup operates in a fast-moving, competitive environment where requirements evolve rapidly based on user feedback, market trends, and investor direction. Speed to market and the ability to pivot are critical success factors.

**Why Agile (Scrum) fits:**
- Requirements are rarely fully known at the start. Agile's iterative sprints allow the team to learn and adapt based on real user feedback.
- A startup needs to ship a Minimum Viable Product (MVP) quickly to validate ideas — Scrum enables this by delivering working software incrementally.
- Small, cross-functional teams (typical in startups) are the ideal environment for Scrum.
- The Sprint Review process ensures that the product evolves in the direction that users and stakeholders actually want.
- Scrum's transparency (sprint boards, velocity charts) helps founders communicate progress to investors.

A startup that uses Waterfall would likely build the wrong product — investing months of work into a specification that becomes obsolete by the time the product ships.

---

#### A Government Defense System — Recommended: Spiral Model

Government defense systems (e.g., radar tracking, missile guidance, military communications) are among the most complex, high-risk, and high-stakes software projects in existence. They involve strict safety requirements, long development timelines, large budgets, and catastrophic consequences for failure.

**Why Spiral fits:**
- The Spiral Model's continuous risk analysis is essential when a failure could cost lives or compromise national security.
- Defense projects often begin without fully defined requirements — the Spiral Model accommodates this by building the system progressively through multiple iterations.
- Prototyping in early spirals allows the government client to evaluate the system before full-scale development is committed.
- The model scales well to very large, multi-year projects with multiple teams working on different subsystems.
- Formal reviews and documentation at each spiral align with defense procurement standards (e.g., MIL-STD, DO-178C for avionics).

Agile would lack the rigor and documentation required by defense standards. Waterfall would be too inflexible for a multi-year project where technology and threat landscapes change.

---

## Task 3: Software Team Roles

### 3.1 Project Manager

**Responsibilities:**
- Plans, executes, and closes software projects
- Defines project scope, timeline, and budget
- Allocates resources and manages the project schedule
- Identifies and mitigates project risks
- Acts as the primary point of contact between the development team and stakeholders
- Tracks progress and ensures deliverables meet quality standards

**Required Skills:**
- Leadership and communication
- Risk management and problem-solving
- Proficiency with project management tools (Jira, MS Project, Trello)
- Knowledge of software development lifecycles
- Budgeting and resource planning

**Contribution to Process Success:**
The Project Manager ensures that the team stays on track, within budget, and aligned with business goals. Without effective project management, teams suffer from scope creep, missed deadlines, and miscommunication.

**Real-World Example:**
At Microsoft, Project Managers coordinate between product teams, engineering, and marketing to ensure that major releases (e.g., Windows updates) are delivered on schedule. They manage cross-team dependencies and resolve blockers to keep hundreds of engineers moving in sync.

---

### 3.2 Software Architect

**Responsibilities:**
- Designs the overall structure (architecture) of the software system
- Makes high-level technical decisions about technology stack, frameworks, and system components
- Establishes coding standards and architectural guidelines
- Evaluates trade-offs between competing design approaches
- Reviews code to ensure conformance with architectural decisions
- Mentors developers on architectural patterns

**Required Skills:**
- Deep knowledge of software design patterns (MVC, microservices, event-driven, etc.)
- Experience with system integration and API design
- Proficiency in multiple programming languages and platforms
- Strong analytical and problem-solving skills
- Ability to communicate complex technical concepts to non-technical stakeholders

**Contribution to Process Success:**
The Software Architect prevents costly structural problems by designing the system correctly before implementation begins. A poor architecture leads to technical debt, performance issues, and systems that are difficult to scale or maintain.

**Real-World Example:**
At Netflix, software architects designed the transition from a monolithic DVD rental platform to a highly available, globally distributed microservices architecture. This architectural decision is the foundation that allows Netflix to serve 200+ million users simultaneously with high reliability.

---

### 3.3 Developer (Software Engineer)

**Responsibilities:**
- Writes, tests, and maintains application code
- Translates design specifications and user stories into functional software
- Performs code reviews and collaborates with teammates
- Debugs and resolves software defects
- Participates in sprint planning and technical discussions
- Keeps technical skills current with evolving tools and languages

**Required Skills:**
- Proficiency in one or more programming languages (Python, Java, JavaScript, etc.)
- Understanding of data structures, algorithms, and design patterns
- Familiarity with version control systems (Git)
- Ability to write unit tests and conduct code reviews
- Problem-solving and attention to detail

**Contribution to Process Success:**
Developers are the core of any software project — they transform requirements and designs into a working product. Their technical skill, collaboration, and adherence to coding standards directly determine the quality and maintainability of the software.

**Real-World Example:**
At Google, software engineers work in small, autonomous teams using a peer review process (code review via Gerrit) before any code is merged. This practice, combined with strong engineering culture, is a key reason why Google's products can handle billions of requests per day with minimal downtime.

---

### 3.4 QA Engineer (Quality Assurance)

**Responsibilities:**
- Designs and executes test plans, test cases, and test scripts
- Performs manual and automated testing (functional, regression, performance, security)
- Identifies, documents, and tracks software defects through to resolution
- Verifies that the software meets specified requirements and quality standards
- Collaborates with developers to reproduce and fix bugs
- Ensures non-functional requirements (performance, usability, security) are met

**Required Skills:**
- Knowledge of testing methodologies and tools (Selenium, JUnit, Postman, JMeter)
- Analytical thinking and attention to detail
- Understanding of software development processes
- Experience with bug tracking systems (Jira, Bugzilla)
- Knowledge of scripting/programming for test automation

**Contribution to Process Success:**
QA Engineers act as the safety net of the project. By catching defects before the software reaches users, they protect the organization from costly post-release failures, reputational damage, and security breaches.

**Real-World Example:**
At Amazon, QA teams use a combination of automated testing pipelines and chaos engineering (deliberately injecting failures into the system) to verify that the platform remains stable even under extreme conditions. This rigorous QA approach supports Amazon's ability to deploy thousands of times per day without major outages.

---

### 3.5 Business Analyst (BA)

**Responsibilities:**
- Elicits, analyzes, and documents business requirements from stakeholders
- Translates business needs into functional specifications for the development team
- Creates user stories, use cases, and process flow diagrams
- Acts as a bridge between business stakeholders and the technical team
- Validates that the delivered software satisfies the original business requirements
- Identifies process improvements and opportunities for automation

**Required Skills:**
- Strong communication and facilitation skills
- Requirements elicitation techniques (interviews, workshops, surveys)
- Proficiency with modeling tools (UML, BPMN, Visio)
- Understanding of both business processes and software capabilities
- Analytical and critical thinking

**Contribution to Process Success:**
A Business Analyst ensures that the team builds the right product — not just a technically correct one. Misunderstood requirements are one of the leading causes of project failure; the BA prevents this by ensuring clarity between business intent and technical implementation.

**Real-World Example:**
At a major bank like JPMorgan Chase, Business Analysts work with compliance officers and risk managers to translate complex regulatory requirements (e.g., new reporting rules) into detailed functional specifications that development teams use to update the bank's core systems.

---

### 3.6 DevOps Engineer

**Responsibilities:**
- Builds and maintains Continuous Integration / Continuous Deployment (CI/CD) pipelines
- Automates software build, test, and release processes
- Manages cloud infrastructure (AWS, Azure, GCP) and containerization (Docker, Kubernetes)
- Monitors system performance, availability, and security in production
- Collaborates with developers to improve deployment reliability and speed
- Manages configuration management and infrastructure as code (Terraform, Ansible)

**Required Skills:**
- Experience with CI/CD tools (Jenkins, GitHub Actions, GitLab CI)
- Cloud platforms (AWS, Azure, GCP)
- Containerization and orchestration (Docker, Kubernetes)
- Scripting (Bash, Python)
- Monitoring tools (Prometheus, Grafana, Datadog)
- Security best practices (DevSecOps)

**Contribution to Process Success:**
DevOps Engineers dramatically reduce the time between writing code and delivering it to users, while ensuring reliability and stability. They eliminate the "it works on my machine" problem by standardizing environments and automating the delivery pipeline. In Agile teams, DevOps is essential for enabling the frequent, reliable deployments that Scrum requires.

**Real-World Example:**
At Spotify, DevOps engineers support a deployment pipeline that allows over 300 microservices to be independently deployed by small development teams (called "squads") multiple times per day. The DevOps infrastructure is what makes the "Spotify model" of autonomous Agile teams actually work at scale.

---

## Conclusion

This report has demonstrated that no single software process model is universally superior — the right choice depends on the nature of the project, the stability of requirements, the team size, and the risk tolerance of the organization. Waterfall excels in structured, well-defined projects; Spiral provides the risk management framework needed for large, complex systems; and Agile (Scrum) delivers the speed and flexibility demanded by modern software startups and product teams.

Equally important is the human element: the success of any software project ultimately rests on the collaboration and competence of its team members. Project Managers, Architects, Developers, QA Engineers, Business Analysts, and DevOps Engineers each play a distinct and critical role. Understanding how these roles interact — and aligning them with the appropriate process model — is the foundation of effective software engineering.
