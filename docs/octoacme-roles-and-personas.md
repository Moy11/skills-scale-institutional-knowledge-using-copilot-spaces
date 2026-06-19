# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Personas

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Interactions with Other Roles
- Works with Product Managers on acceptance criteria and feature clarification
- Collaborates with Engineering Managers on technical decisions and career development
- Engages with Security Engineers on code reviews and vulnerability remediation
- Partners with SREs on deployment and observability
- Participates in UX designer reviews for design validation

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Interactions with Other Roles
- Aligns with UX Researchers on customer insights and design requirements
- Partners with Data Analysts to define and measure success metrics
- Works with Support teams to understand customer pain points and feature impact
- Collaborates with Security and Legal on compliance and risk considerations
- Engages with SREs on scaling and performance requirements

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Interactions with Other Roles
- Syncs with Engineering Managers on resource allocation and capacity planning
- Works with Product Managers on scope and timeline trade-offs
- Escalates risks with Security and Legal for compliance-related projects
- Coordinates with SREs on release schedules and deployment windows
- Partners with Scrum Masters on ceremony facilitation (if applicable)

---

## Extended Personas

### Engineering Manager

#### Role Summary
Engineering Managers provide technical leadership, manage team capacity and growth, and ensure engineering excellence. They enable developers to deliver high-quality features while supporting career development and technical decision-making.

#### Responsibilities
- Oversee staffing, hiring, and team capacity planning
- Provide technical mentorship and career development guidance
- Make technical leadership decisions in partnership with architects
- Manage team workload and prevent burnout
- Support developers during technical escalations and complex problems
- Conduct 1-on-1s and performance reviews

#### Goals
- Build and maintain a high-performing, motivated engineering team
- Ensure sustainable delivery velocity and code quality
- Reduce technical debt and improve system reliability
- Support developer growth and skill development

#### Typical Communication
- One-on-ones with direct reports
- Technical design reviews and architectural decisions
- Capacity planning discussions with Project Managers
- Incident postmortems and retrospectives

#### Interactions with Other Roles
- Partners with Project Managers on resource allocation and schedule feasibility
- Collaborates with Product Managers on scope trade-offs and technical risks
- Works with Security Engineers on threat modeling and secure development practices
- Engages with SREs on infrastructure stability and incident response
- Mentors Developers on technical decisions and career growth

---

### UX Researcher / Designer

#### Role Summary
UX Researchers and Designers understand user needs, create intuitive interfaces, and validate design decisions through research and usability testing. They bridge the gap between customer needs and technical implementation.

#### Responsibilities
- Conduct user research (interviews, surveys, usability tests)
- Synthesize research insights into actionable recommendations
- Create design specs, wireframes, and prototypes
- Validate designs with users before handoff to developers
- Ensure accessibility and usability standards are met
- Participate in design critiques and feedback sessions

#### Goals
- Create products that solve real user problems
- Ensure designs are intuitive, accessible, and delightful
- Reduce friction in the handoff between design and engineering
- Maximize adoption and user satisfaction

#### Typical Communication
- Design specs and user research findings
- Prototype demos and feedback sessions
- Accessibility guidelines and design system documentation
- Usability testing reports and insights

#### Interactions with Other Roles
- Collaborates closely with Product Managers to define user problems and success metrics
- Works with Developers during design-to-code handoffs and implementation questions
- Partners with Data Analysts on user behavior metrics and A/B testing results
- Engages with Support teams for user feedback and issue reports
- Coordinates with Security on privacy and data handling implications of designs

---

### Support / Customer Success Representative

#### Role Summary
Support and Customer Success representatives are the voice of the customer. They surface customer issues, validate feature usability post-release, and provide input on prioritization from a customer-impact perspective.

#### Responsibilities
- Respond to customer inquiries and troubleshoot issues
- Track and categorize customer-reported bugs and feature requests
- Validate feature usability and gather customer feedback post-release
- Contribute customer impact perspective to prioritization discussions
- Identify trends and patterns in customer feedback
- Participate in incident response and customer communication

#### Goals
- Maximize customer satisfaction and product adoption
- Reduce time-to-resolution for customer issues
- Surface high-impact bugs and feature gaps early
- Build trust and long-term customer relationships

#### Typical Communication
- Customer feedback summaries and issue reports
- Post-release usability feedback and user acceptance
- Incident communication and status updates
- Feature request prioritization input

#### Interactions with Other Roles
- Feeds customer issues into the Product Manager's backlog prioritization
- Partners with Developers on bug triage and resolution priority
- Works with Product Managers and Engineers on incident response
- Collaborates with Data Analysts on customer usage patterns and trends
- Shares customer testimonials and case studies with stakeholders

---

### Security Engineer / Security Reviewer

#### Role Summary
Security Engineers ensure that products are designed, built, and deployed securely. They perform threat modeling, review code and designs for security risks, and ensure compliance with security standards.

#### Responsibilities
- Perform threat modeling and security design reviews
- Review code and PRs for security vulnerabilities
- Manage security scanning in CI/CD pipelines
- Advise on secure development practices and standards
- Coordinate security incident response
- Ensure compliance with security policies and regulations

#### Goals
- Prevent security breaches and data loss
- Build security into the development process from the start
- Reduce vulnerability remediation time
- Maintain compliance with industry standards and regulations

#### Typical Communication
- Security design review findings and recommendations
- Vulnerability reports and severity assessments
- Security training and best practices documentation
- Incident postmortems and remediation plans

#### Interactions with Other Roles
- Works with Developers and Engineering Managers during code reviews and PR approval
- Advises Product Managers and Project Managers on security risks and mitigations
- Partners with SREs on infrastructure security and incident response
- Collaborates with Legal on compliance and regulatory requirements
- Engages with Support on security incident communication

---

### Site Reliability Engineer (SRE) / Release Engineer

#### Role Summary
SREs and Release Engineers manage deployment pipelines, infrastructure reliability, and incident automation. They enable teams to release features safely, scale systems, and respond quickly to incidents.

#### Responsibilities
- Design and maintain deployment pipelines and automation
- Manage infrastructure, scaling, and performance optimization
- Create and maintain incident runbooks and automation
- Implement observability (logging, metrics, tracing)
- Manage rollback procedures and disaster recovery
- Support incident triage and post-mortem analysis

#### Goals
- Minimize downtime and incident impact
- Enable fast, safe deployments with high confidence
- Automate manual, error-prone processes
- Provide visibility into system health and performance

#### Typical Communication
- Deployment windows and release schedules
- Incident postmortems and action items
- Infrastructure and observability documentation
- On-call schedules and incident escalation

#### Interactions with Other Roles
- Partners with Developers on deployment automation and code instrumentation
- Works with Project Managers on release windows and rollback plans
- Collaborates with Security Engineers on infrastructure hardening
- Engages with Support on incident triage and customer impact assessment
- Works with Engineering Managers on capacity planning and system reliability

---

### Data Analyst / Data Engineer

#### Role Summary
Data Analysts and Engineers define, instrument, and measure product success. They build dashboards, analyze user behavior, and validate hypotheses that inform prioritization decisions.

#### Responsibilities
- Define success metrics and KPIs for features and initiatives
- Instrument code and systems to collect necessary data
- Build dashboards and data pipelines for insights
- Validate A/B experiments and hypothesis testing
- Identify trends and anomalies in product usage and performance
- Present data-driven insights to stakeholders

#### Goals
- Enable data-driven prioritization and decision-making
- Understand customer behavior and product impact
- Identify opportunities for optimization and growth
- Provide real-time visibility into key metrics

#### Typical Communication
- Metric definitions and success dashboards
- A/B testing results and statistical analysis
- Product usage reports and trend analysis
- Data-driven insights and recommendations

#### Interactions with Other Roles
- Works with Product Managers to define measurable outcomes and success criteria
- Partners with Developers and SREs on data instrumentation and collection
- Collaborates with UX Designers on user behavior insights and usability metrics
- Engages with Support on customer usage patterns and feedback trends
- Presents insights to stakeholders and leadership

---

### Scrum Master / Agile Coach

#### Role Summary
Scrum Masters and Agile Coaches facilitate agile ceremonies, remove impediments, and help teams continuously improve their delivery processes. They ensure the team stays focused and can adapt to change.

#### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Identify and help remove team impediments and blockers
- Coach team members on agile principles and practices
- Maintain sprint boards and track progress metrics
- Facilitate retrospectives and drive implementation of improvements
- Protect team focus and manage interruptions

#### Goals
- Maximize team velocity and delivery consistency
- Improve team collaboration and communication
- Foster a culture of continuous improvement
- Reduce unplanned work and context switching

#### Typical Communication
- Sprint ceremonies and meeting facilitation
- Impediment logs and escalations
- Retrospective notes and action item tracking
- Process improvement recommendations

#### Interactions with Other Roles
- Coordinates with Project Managers on sprint planning and resource allocation
- Works with Engineering Managers on team health and capacity management
- Facilitates collaboration between Developers, Product Managers, and other roles
- Supports retrospectives led by Project Managers
- Escalates blockers to appropriate stakeholders

---

### Legal / Compliance Representative

#### Role Summary
Legal and Compliance representatives review features for legal and regulatory risks, advise on data handling and privacy obligations, and ensure the organization meets compliance requirements.

#### Responsibilities
- Review features and changes for legal and regulatory impact
- Advise on data privacy, security, and protection obligations
- Review contracts and terms of service
- Ensure compliance with industry regulations and standards
- Manage legal risk mitigation and incident response
- Document compliance decisions and approvals

#### Goals
- Prevent legal liability and regulatory violations
- Ensure customer data is protected and handled appropriately
- Enable business growth while managing legal risks
- Maintain stakeholder trust and brand reputation

#### Typical Communication
- Legal risk assessments and mitigation plans
- Compliance checklists and approval sign-offs
- Data handling and privacy guidelines
- Incident response and legal communications

#### Interactions with Other Roles
- Engages with Product Managers and Security Engineers during planning for features with legal impact
- Reviews designs and code with Developers for privacy and data handling implications
- Works with Project Managers on compliance timelines and requirements
- Partners with SREs on data retention and security measures
- Advises all teams on regulatory obligations and compliance best practices

---

## How These Personas Are Used in the Exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interactions with Other Roles" section to understand how teams collaborate and depend on each other.
- When working through a scenario, consider which personas are involved and what their responsibilities and goals are.
- Use these personas to simulate realistic cross-functional conversations and decision-making processes.
