# Requirement Analysis in Software Development.

- Underlying structure that allows for clarity and precision durinf project execution

## What is Requirement Analysis?

Requirement Analysis is the process of identifying, gathering, analyzing, documenting, validating, and managing the needs and expectations of stakeholders for a software system.

some importance includes:

- Clarity – Remove ambiguity, vagueness, and conflicting statements.
- Consistency – Requirements must not contradict each other.
- Prioritization – Identify “must-haves” vs “nice-to-haves.”

## Why is Requirement Analysis Important?

- Clarity – Remove ambiguity, vagueness, and conflicting statements.
- Consistency – Requirements must not contradict each other.
- Prioritization – Identify “must-haves” vs “nice-to-haves.”

## Key Activities in Requirement Analysis

- Requirement Gatthering
  Goal: Discover what stakeholders really need.

How it’s done:

- Interviews with clients and end-users.
- Surveys & questionnaires for larger groups.
- Workshops & brainstorming sessions.
- Observation/job shadowing to see real workflows.
- Document analysis (policies, existing systems).
- Prototyping to clarify vague needs.

Output: A raw list of requirements (functional, non-functional, domain-specific, constraints).

- Requirement Analysis and Modelling:
  Goal: Refine, prioritize, and organize the gathered requirements.

How it’s done:

- Identify conflicts (different stakeholders want different things).
- Detect ambiguities (“system should be fast” → define fast).
- Perform feasibility checks (budget, technology, timeline).
- Prioritize (MoSCoW: Must-have, Should-have, Could-have, Won’t-have).
- Use modeling tools (UML, data flow diagrams, ERD, use cases).

Output: A structured, clear set of requirements ready for documentation.

- Requirement Documentation:

Goal: Write down requirements in a clear, unambiguous, testable format.

How it’s done:

- Create a Software Requirement Specification (SRS) document.
- Use user stories (Agile) or use cases (traditional).
- Include both functional and non-functional requirements.

Output: An agreed-upon requirements document that acts as a contract between stakeholders and developers.

- Requirement Validation.
  Goal: Make sure requirements correctly capture what stakeholders need and are realistic.

How it’s done:

- Requirement reviews & walkthroughs with stakeholders.
- Prototypes/mockups tested by users.
- Validation against business goals.

Output: Validated requirements ready for design and development.

## Types of Requirements.

- Functional Requirements:
  Functional requirements specify what the system should do. They describe tasks, services, and system behavior.

  Examples include:

  1. Hotel Management Service

  - Add or Update hot information
  - Upload changes propagated to downstream services via messaging queues and CDN — this supports real-time updates.

  2. Customer Service (Search & Booking)

  - Search hotels — using ElasticSearch to retrieve listings based on customer queries.
    Book hotels — the booking service handles reservations and interacts with payment processors.

  ## Non-functional requirements

  Definition: Non-functional requirements specify how the system should perform—its quality attributes like performance, scalability, security, etc.

  Examples Include:

  1. Performance & Low Latency
  2. Scalability & Reliability

  ## USE CASE DIAGRAMS

  They visually represent the interactions between users (called actors) and a system to achieve specific goals or tasks

  - Benefit of use case diagrams

  * Clarify requirements:
    They help identify and document functional requirements early in the development process

  * Define System Scope:
    By showing what’s inside and outside the system, they help teams understand boundaries and responsibilities.

  * Simplify Complexity:
    They break down large systems into manageable chunks of functionality, making it easier to design and develop.

Link to use case diagram ![Booking System Use Case](./alx-booking-uc.png)

## Acceptance Criteria.

- Importance of acceptance criterria

* Improve quality by setting clear expectations.
* Boost user satisfaction by delivering what was promised.
* Prevent misunderstandings between teams.
