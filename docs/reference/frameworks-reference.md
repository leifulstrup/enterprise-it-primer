---
tags:
  - Reference
  - Frameworks
---

# Frameworks Quick Reference

This page is a quick-reference companion to the detailed topic pages throughout the primer. Each card below summarizes a major IT framework -- what it is, its key components, when to use it, and where to find the full discussion. Use this page when you need an at-a-glance refresher before a meeting, exam, or case discussion.

---

???+ info "COBIT 2019"

    **What It Is**
    :   A comprehensive IT governance and management framework developed by ISACA. COBIT provides a structured approach for organizations to make decisions about technology, manage IT-related risks, and ensure IT investments deliver business value. It covers both governance (board-level direction) and management (operational execution).

    **Key Components**
    :   - **5 Core Principles** -- Meeting stakeholder needs, covering the enterprise end-to-end, applying a single integrated framework, enabling a holistic approach, and separating governance from management
        - **Goals Cascade** -- Links stakeholder needs to enterprise goals, alignment goals, and 40 specific governance and management objectives
        - **5 Domains** -- EDM (Evaluate, Direct & Monitor), APO (Align, Plan & Organize), BAI (Build, Acquire & Implement), DSS (Deliver, Service & Support), MEA (Monitor, Evaluate & Assess)
        - **Capability Maturity Model** -- Levels 0-5 for assessing process maturity

    **When to Use It**
    :   When your organization needs a comprehensive governance structure connecting board-level oversight to operational IT processes -- particularly for audit and compliance, enterprise-wide governance standardization, or linking IT activities to business outcomes through the goals cascade.

    :material-arrow-right: [Full discussion in Governance Frameworks](../governance/frameworks.md)

???+ info "ITIL 4"

    **What It Is**
    :   The world's most widely adopted framework for IT Service Management (ITSM), developed by Axelos (originally the UK Government). ITIL focuses on how IT delivers and supports services to the business -- from email and network access to ERP systems and customer-facing applications.

    **Key Components**
    :   - **Service Value System (SVS)** -- Takes opportunity and demand as inputs and produces value as output
        - **7 Guiding Principles** -- Focus on value, start where you are, progress iteratively, collaborate, think holistically, keep it simple, optimize and automate
        - **Service Value Chain** -- Six activities: Plan, Improve, Engage, Design & Transition, Obtain/Build, Deliver & Support
        - **34 Practices** -- Including incident management, change enablement, problem management, service level management, and service desk

    **When to Use It**
    :   When your organization needs to improve day-to-day IT service delivery and support -- managing incidents, controlling changes, defining service levels, and continuously improving how IT serves the business.

    :material-arrow-right: [Full discussion in Governance Frameworks](../governance/frameworks.md)

???+ info "ISO/IEC 38500"

    **What It Is**
    :   An international standard that provides high-level guiding principles for the effective, efficient, and acceptable use of IT within organizations. Unlike COBIT and ITIL, ISO/IEC 38500 operates at the board level -- it defines *what* the governing body should do regarding IT, not *how* to do it. Think of it as a constitution for IT governance.

    **Key Components**
    :   - **6 Principles** -- Responsibility, Strategy, Acquisition, Performance, Conformance, and Human Behavior
        - **Evaluate-Direct-Monitor (EDM) Cycle** -- The three activities the governing body performs for each principle: evaluate current and future IT use, direct through policies and plans, and monitor performance against those plans

    **When to Use It**
    :   When the board of directors or senior executives need a clear, non-technical framework for setting IT governance expectations -- particularly for public companies, government entities, or any organization that needs a globally recognized standard for board-level IT oversight.

    :material-arrow-right: [Full discussion in Governance Frameworks](../governance/frameworks.md)

???+ info "TOGAF (The Open Group Architecture Framework)"

    **What It Is**
    :   The most widely adopted enterprise architecture framework in the world, maintained by The Open Group. TOGAF provides a structured approach for designing, planning, implementing, and governing enterprise architecture. It tells organizations *how to do* enterprise architecture through a repeatable, iterative process.

    **Key Components**
    :   - **Architecture Development Method (ADM)** -- An iterative cycle of eight phases: Architecture Vision, Business Architecture, Information Systems, Technology Architecture, Opportunities & Solutions, Migration Planning, Implementation Governance, and Architecture Change Management
        - **Architecture Repository** -- Centralized store of all architecture artifacts, standards, and reference models
        - **Architecture Building Blocks (ABBs) and Solution Building Blocks (SBBs)** -- Reusable components at the logical and product-specific levels
        - **Transition Architectures** -- Intermediate states between current and target architecture

    **When to Use It**
    :   When your organization needs to plan and execute an enterprise architecture program -- particularly for post-merger technology integration, large-scale modernization, or establishing architecture governance with an Architecture Review Board.

    :material-arrow-right: [Full discussion in Enterprise Architecture](../technology/enterprise-architecture.md)

???+ info "Zachman Framework"

    **What It Is**
    :   A classification schema (ontology) for organizing and categorizing architectural artifacts, developed by John Zachman in the 1980s. Unlike TOGAF, which provides a process methodology, the Zachman Framework provides a structured way to describe *what exists* in the enterprise from multiple perspectives. It does not tell you what to do first -- it tells you what to document.

    **Key Components**
    :   - **6x6 Matrix** -- Six rows (perspectives) crossed with six columns (interrogatives), producing 36 cells
        - **Six Perspectives (Rows)** -- Executive/Scope, Business Management/Concepts, Architect/Logic, Engineer/Physics, Technician/Component, Enterprise/Operations
        - **Six Interrogatives (Columns)** -- What (Data), How (Function), Where (Network), Who (People), When (Time), Why (Motivation)

    **When to Use It**
    :   When your organization needs to ensure completeness of architecture documentation, identify gaps in existing artifacts, or organize architecture deliverables by audience and dimension. Best used alongside a process methodology like TOGAF's ADM.

    :material-arrow-right: [Full discussion in Enterprise Architecture](../technology/enterprise-architecture.md)

???+ info "NIST Cybersecurity Framework (CSF 2.0)"

    **What It Is**
    :   A risk-based, outcome-oriented cybersecurity framework developed by the National Institute of Standards and Technology. The NIST CSF is the most widely adopted cybersecurity framework in the United States and provides a structured approach for organizations of any size or sector to understand, manage, and reduce cybersecurity risk.

    **Key Components**
    :   - **6 Core Functions** -- Govern, Identify, Protect, Detect, Respond, Recover
        - **Govern Function (new in 2.0)** -- Wraps around the other five functions, covering risk strategy, policies, roles, oversight, and supply chain risk
        - **Categories and Subcategories** -- Detailed outcomes within each function that describe desired cybersecurity results
        - **Implementation Tiers** -- Allow organizations to set maturity targets appropriate to their risk profile

    **When to Use It**
    :   When your organization needs a flexible, technology-neutral framework for managing cybersecurity risk -- particularly for aligning security investments with business risk, reporting to the board, or establishing a common language across IT, security, legal, and business teams.

    :material-arrow-right: [Full discussion in Cybersecurity for Managers](../risk-security/cybersecurity.md)

???+ info "Henderson & Venkatraman Strategic Alignment Model (SAM)"

    **What It Is**
    :   The foundational academic framework for understanding IT-business alignment, introduced by John Henderson and N. Venkatraman in 1993. The SAM identifies four domains that must be coordinated and four dominant alignment perspectives that describe how alignment flows through an organization.

    **Key Components**
    :   - **4 Domains** -- Business Strategy, IT Strategy, Organizational Infrastructure & Processes, IT Infrastructure & Processes
        - **Strategic Fit** -- Linking external strategy to internal execution in both business and IT
        - **Functional Integration** -- Linking business and IT at both strategic and operational levels
        - **4 Alignment Perspectives** -- Strategy Execution (business drives IT execution), Technology Transformation (business vision drives IT strategy), Competitive Potential (IT creates new business opportunities), Service Level (IT excellence enables business agility)

    **When to Use It**
    :   When diagnosing why IT and business are misaligned, when evaluating whether your organization treats IT as a strategic driver or merely an order-taker, or when building the case for elevating the CIO's role from execution to strategy.

    :material-arrow-right: [Full discussion in IT-Business Alignment](../governance/it-business-alignment.md)

???+ info "McKinsey 4Ds of Digital Transformation"

    **What It Is**
    :   A consulting framework from McKinsey & Company that organizes digital transformation into four interconnected domains that must be addressed holistically. McKinsey's research shows that organizations addressing all four domains are three times more likely to achieve a successful transformation.

    **Key Components**
    :   - **Discover** -- Map the value chain, identify digital opportunities, benchmark against competitors and digital natives, prioritize use cases by business impact
        - **Design** -- Define the target operating model, architect the technology platform, redesign customer journeys, plan organizational structure
        - **Deliver** -- Build cross-functional agile teams, develop MVPs, scale successful pilots, modernize legacy systems
        - **De-risk** -- Manage change and adoption, address talent gaps, handle cultural resistance, establish governance, track value realization

    **When to Use It**
    :   When your organization needs to develop a comprehensive transformation strategy from scratch -- particularly for large enterprises with multiple business units and geographies where the risk of a technology-first approach is high.

    :material-arrow-right: [Full discussion in Digital Transformation](../transformation/digital-transformation.md)

???+ info "Agile / Scrum"

    **What It Is**
    :   Agile is a family of iterative, incremental methodologies for software development that emerged from the Agile Manifesto (2001). Scrum is the most widely adopted Agile framework, used by an estimated 60-70% of Agile teams. Agile delivers working software in short cycles (sprints), enabling continuous stakeholder feedback and adaptation.

    **Key Components**
    :   - **Agile Manifesto Values** -- Individuals and interactions over processes and tools; working software over comprehensive documentation; customer collaboration over contract negotiation; responding to change over following a plan
        - **Scrum Roles** -- Product Owner (defines what to build), Scrum Master (facilitates the process), Development Team (builds the product)
        - **Scrum Events** -- Sprint Planning, Daily Standup, Sprint Review, Sprint Retrospective
        - **Artifacts** -- Product Backlog (prioritized list of user stories), Sprint Backlog, Potentially Shippable Increment

    **When to Use It**
    :   When requirements are uncertain or evolving, when continuous stakeholder feedback is available, and when the project benefits from delivering working increments early and often rather than a single delivery at the end.

    :material-arrow-right: [Full discussion in IT Project & Portfolio Management](../management/project-management.md)

???+ info "PMBOK (Project Management Body of Knowledge)"

    **What It Is**
    :   The global standard for project management published by the Project Management Institute (PMI). The PMBOK Guide (currently in its 7th edition) defines project management principles, performance domains, and practices used to deliver projects across industries. It is the foundation for the PMP (Project Management Professional) certification.

    **Key Components**
    :   - **12 Project Management Principles** -- Stewardship, team, stakeholders, value, systems thinking, leadership, tailoring, quality, complexity, risk, adaptability, and change
        - **8 Performance Domains** -- Stakeholders, Team, Development Approach & Lifecycle, Planning, Project Work, Delivery, Measurement, Uncertainty
        - **Tailoring Guidance** -- The 7th edition emphasizes adapting the approach (predictive, adaptive, or hybrid) to the project context rather than prescribing a single methodology
        - **Complementary Standards** -- PMI also publishes the *Agile Practice Guide* and standards for portfolio, program, and organizational project management

    **When to Use It**
    :   When your organization needs a recognized, comprehensive standard for project management -- particularly for establishing PMO practices, training project managers, or governing projects in regulated industries where a formal, documented approach is required.

    :material-arrow-right: [Full discussion in IT Project & Portfolio Management](../management/project-management.md)

---

## Comparison Table

| Framework | Focus Area | Best For | Complexity |
|-----------|-----------|----------|------------|
| **COBIT 2019** | Enterprise IT governance & management | Audit, compliance, linking IT to business outcomes | High -- 40 objectives across 5 domains |
| **ITIL 4** | IT service management | Improving day-to-day service delivery and support | Moderate -- 34 practices within the SVS |
| **ISO/IEC 38500** | Board-level IT governance principles | Setting board expectations for IT oversight | Low -- 6 principles, EDM cycle |
| **TOGAF** | Enterprise architecture development | Planning and executing architecture programs | High -- 8-phase ADM cycle with extensive artifacts |
| **Zachman Framework** | Architecture artifact classification | Ensuring completeness of architecture documentation | Moderate -- 6x6 matrix (36 cells) |
| **NIST CSF 2.0** | Cybersecurity risk management | Aligning security with business risk | Moderate -- 6 functions with categories and subcategories |
| **Henderson & Venkatraman SAM** | IT-business strategic alignment | Diagnosing and improving IT-business alignment | Low -- 4 domains, 4 alignment perspectives |
| **McKinsey 4Ds** | Digital transformation strategy | Comprehensive transformation planning | Moderate -- 4 interconnected domains |
| **Agile / Scrum** | Iterative software delivery | Projects with evolving requirements | Low-Moderate -- 3 roles, 4 events, 3 artifacts |
| **PMBOK** | Project management standard | Establishing PM practices and governance | Moderate-High -- 12 principles, 8 performance domains |

---

## See Also

For the full discussion of each framework, including real-world examples, common pitfalls, and discussion questions, see the following topic pages:

- **[IT Governance Frameworks](../governance/frameworks.md)** -- Detailed coverage of COBIT 2019, ITIL 4, and ISO/IEC 38500, including how the three frameworks layer together in practice
- **[Enterprise Architecture](../technology/enterprise-architecture.md)** -- In-depth treatment of TOGAF (including the full ADM cycle), the Zachman Framework, legacy modernization strategies, and architecture governance
- **[Cybersecurity for Managers](../risk-security/cybersecurity.md)** -- Complete discussion of the NIST Cybersecurity Framework, the threat landscape, regulatory compliance (SOX, HIPAA, GDPR, PCI-DSS), and board-level governance
- **[IT-Business Alignment](../governance/it-business-alignment.md)** -- Full treatment of the Henderson & Venkatraman Strategic Alignment Model, Luftman's maturity model, CIO-LOB negotiation dynamics, and IT operating models
- **[Digital Transformation](../transformation/digital-transformation.md)** -- Comprehensive coverage of the McKinsey 4Ds, MIT CISR framework, digital maturity models, change management, and transformation success/failure analysis
- **[IT Project & Portfolio Management](../management/project-management.md)** -- Detailed discussion of Agile/Scrum, Waterfall, hybrid approaches, the PMBOK standard, the PMO, portfolio governance, and DevOps
