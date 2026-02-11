# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards while maintaining code quality and system reliability.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain unit tests, integration tests, and documentation
- Participate in design reviews, code reviews, and pair programming
- Assist in estimating and planning work during sprint planning
- Help identify technical risks and propose mitigations
- Collaborate on technical architecture and design decisions
- Support production systems and respond to incidents as needed

### Goals
- Deliver reliable, maintainable, and well-tested code
- Reduce cycle time from idea to production
- Maintain high test coverage and system observability
- Continuously improve code quality and development practices

### Interactions with Other Roles
- **Product Owner**: Clarifies requirements, discusses technical feasibility, and validates completed work
- **QA Lead**: Collaborates on test strategies, reproduces bugs, and ensures testability of features
- **UX Designer**: Implements designs, provides feedback on feasibility, and ensures responsive behavior
- **Project Manager**: Reports progress, identifies blockers, and participates in sprint planning
- **Release Manager**: Provides deployment artifacts and supports release activities
- **Business Analyst**: Discusses technical implementation of business requirements

### Typical Communication
- Daily standups and sprint planning sessions
- Pull request descriptions and code review comments
- Technical design documents and architecture decision records
- Slack/Teams for quick questions and collaboration

---

## Product Managers

### Role Summary
Product Managers define the long-term product vision and strategy to deliver customer and business value. They own product direction, market positioning, and measure business outcomes across multiple releases.

### Responsibilities
- Define and communicate product vision and strategy
- Conduct market research and competitive analysis
- Define success metrics and track product performance
- Make strategic prioritization decisions across features and initiatives
- Collaborate with stakeholders on long-term roadmap planning

### Goals
- Maximize customer value and business impact
- Ensure product-market fit and competitive positioning
- Drive data-informed strategic decisions
- Build and maintain product roadmap aligned with business goals

### Interactions with Other Roles
- **Product Owner**: Provides strategic direction; Product Owner translates this into actionable backlog items
- **Project Manager**: Aligns on release timing and resource needs for strategic initiatives
- **Developers**: Communicates product vision and validates technical feasibility of strategic features
- **UX Designer**: Collaborates on long-term user experience strategy

### Typical Communication
- Monthly roadmap reviews with leadership
- Quarterly strategic planning sessions
- Product performance reviews and metrics dashboards
- Market research findings and competitive analysis

---

## Product Owner

### Role Summary
Product Owner translates product strategy into actionable work, manages the product backlog, and ensures the development team delivers features that meet acceptance criteria and business requirements.

### Responsibilities
- Maintain and prioritize the product backlog
- Write and refine user stories with clear acceptance criteria
- Make day-to-day prioritization decisions during sprints
- Validate completed work against acceptance criteria
- Act as the primary point of contact for the development team on requirements

### Goals
- Maximize value delivered in each sprint
- Ensure clarity and completeness of requirements
- Maintain a healthy, prioritized backlog
- Enable efficient team velocity

### Interactions with Other Roles
- **Product Manager**: Receives strategic direction and translates it into tactical backlog items
- **Developers**: Provides detailed requirements, clarifies acceptance criteria, and answers questions
- **QA Lead**: Collaborates on test scenarios and validates acceptance criteria
- **Business Analyst**: Works together to refine requirements and document business processes
- **UX Designer**: Reviews designs and ensures implementation aligns with user experience goals

### Typical Communication
- Daily availability for developer questions
- Sprint planning and backlog refinement sessions
- Acceptance criteria documentation in user stories
- Sprint reviews and demos

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities across the project lifecycle, manage schedules, risks, and communications. They enable cross-functional teams to deliver on commitments efficiently and maintain stakeholder alignment.

### Responsibilities
- Create and maintain project plans, timelines, and schedules
- Manage risks, dependencies, and resource constraints
- Facilitate key meetings (kickoff, planning, retrospectives)
- Track project progress and identify blockers
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication
- Escalate issues and manage stakeholder expectations

### Goals
- Deliver projects on time, within scope, and on budget
- Minimize unplanned work and escalations
- Maintain transparency and alignment across all stakeholders
- Ensure smooth coordination between all project roles

### Interactions with Other Roles
- **Product Manager/Product Owner**: Aligns on priorities, scope changes, and delivery timelines
- **Developers**: Tracks progress, identifies blockers, and facilitates resource allocation
- **QA Lead**: Coordinates testing schedules and ensures quality gates are met
- **Release Manager**: Aligns on release planning and deployment schedules
- **Stakeholders**: Provides regular status updates and manages expectations

### Typical Communication
- Weekly status updates and stakeholder reports
- Daily stand-ups and sprint planning
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA Lead

### Role Summary
QA Lead oversees quality assurance activities throughout the project lifecycle, ensures comprehensive test coverage, and acts as the primary point of contact for quality-related decisions and defect triage.

### Responsibilities
- Develop and maintain test strategy and test plans
- Coordinate testing activities across unit, integration, and end-to-end tests
- Lead defect triage sessions and prioritize bug fixes
- Define quality gates and acceptance criteria for releases
- Mentor team members on testing best practices
- Maintain and improve test automation frameworks
- Track and report on quality metrics and test coverage

### Goals
- Ensure high-quality releases with minimal production defects
- Increase test automation coverage and efficiency
- Reduce time spent on manual testing through automation
- Establish and maintain quality standards across the team

### Interactions with Other Roles
- **Developers**: Collaborates on test strategies, reviews code for testability, and pairs on complex test scenarios
- **Product Owner**: Validates acceptance criteria are testable and helps define quality requirements
- **Project Manager**: Reports on testing progress, identifies quality risks, and coordinates test schedules
- **Release Manager**: Provides sign-off on quality gates and coordinates release testing activities
- **Business Analyst**: Reviews test scenarios to ensure business requirements are validated

### Typical Communication
- Test plan documentation and test case reviews
- Daily bug triage sessions and defect reports
- Quality metrics dashboards and test coverage reports
- Sprint planning and retrospective participation

---

## Release Manager

### Role Summary
Release Manager plans, coordinates, and executes deployment activities, ensuring smooth and reliable releases to production environments while minimizing deployment risks and downtime.

### Responsibilities
- Create and maintain release schedules and deployment plans
- Coordinate release activities across multiple teams and stakeholders
- Manage release artifacts, version control, and documentation
- Execute deployment procedures and rollback plans when needed
- Communicate release status and deployment windows to stakeholders
- Maintain and improve CI/CD pipelines
- Conduct post-deployment verification and monitoring

### Goals
- Achieve zero-downtime deployments
- Reduce deployment time and manual intervention
- Ensure smooth coordination across all release stakeholders
- Maintain comprehensive release documentation and runbooks

### Interactions with Other Roles
- **Project Manager**: Aligns on release timing, coordinates stakeholder communication, and manages dependencies
- **QA Lead**: Ensures quality gates are met before releases and coordinates release testing
- **Developers**: Collaborates on deployment procedures, troubleshoots deployment issues, and manages release artifacts
- **Product Owner**: Validates release scope and coordinates on feature toggles or phased rollouts
- **DevOps/Infrastructure**: Works closely on infrastructure changes, monitoring, and deployment automation

### Typical Communication
- Release calendars and deployment schedules
- Pre-release and post-release checklists and status updates
- Deployment runbooks and rollback procedures
- Release notes and stakeholder announcements

---

## UX Designer

### Role Summary
UX Designer ensures user experience is considered throughout the product lifecycle, creating intuitive and accessible interfaces that meet user needs while collaborating with product and engineering teams.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Design user interfaces following accessibility and usability standards
- Maintain design systems and component libraries
- Validate implementations match design specifications
- Advocate for user needs throughout the development process
- Collaborate on information architecture and user flows

### Goals
- Create intuitive, accessible, and delightful user experiences
- Ensure consistency across product interfaces
- Reduce user friction and support tickets through better design
- Balance user needs with technical constraints and business goals

### Interactions with Other Roles
- **Product Manager/Product Owner**: Translates product vision into user experience, validates designs solve user problems
- **Developers**: Provides design specifications, discusses technical feasibility, and reviews implementations
- **QA Lead**: Collaborates on usability test scenarios and validates user experience in testing
- **Business Analyst**: Understands business processes to design workflows that align with user tasks
- **Stakeholders**: Presents designs for feedback and validates alignment with brand guidelines

### Typical Communication
- Design presentations and critique sessions
- Figma/Sketch files and design specifications
- User research findings and usability test reports
- Design system documentation and component guidelines

---

## Business Analyst

### Role Summary
Business Analyst bridges communication between technical and business teams by eliciting requirements, analyzing processes, documenting business needs, and ensuring solutions align with organizational goals.

### Responsibilities
- Elicit and document business requirements from stakeholders
- Analyze current business processes and identify improvement opportunities
- Create process flow diagrams, data models, and business rules
- Translate business needs into clear, actionable requirements
- Facilitate requirements workshops and stakeholder interviews
- Validate that delivered solutions meet business needs
- Maintain requirements traceability throughout the project

### Goals
- Ensure clear understanding of business needs across all teams
- Reduce ambiguity and rework through thorough requirements analysis
- Bridge gaps between business stakeholders and technical teams
- Improve business processes through technology solutions

### Interactions with Other Roles
- **Product Owner**: Collaborates on refining user stories and ensuring business value is clear
- **Developers**: Clarifies business logic, answers domain questions, and validates implementations
- **Stakeholders**: Gathers requirements, facilitates workshops, and validates solutions
- **Project Manager**: Provides requirements documentation and assists with scope management
- **QA Lead**: Collaborates on test scenarios to ensure business requirements are validated
- **UX Designer**: Provides context on business workflows to inform user experience design

### Typical Communication
- Business requirements documents (BRDs) and functional specifications
- Process flow diagrams and use case documentation
- Requirements workshops and stakeholder interviews
- Requirements traceability matrices

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

