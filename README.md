# Requirement Analysis in Software Development

## What is Requirement Analysis?
Requrement analysis is all the requirements needed in creating or accomplishing the project at hand

## Why is Requirement Analysis Important?
These are the seven reasons as to why the Requirement Analysis is important
### 1. Ensures Alignment with User Needs:
Requirement analysis helps developers understand the actual needs and expectations of various stakeholders, ensuring the final product is valuable and usable. 
### 2. Minimizes Costly Changes:
Identifying and clarifying requirements early in the development process helps to prevent issues and conflicts that would be expensive and time-consuming to fix later. 
### 3. Prevents Scope Creep:
By clearly defining what the software should and should not do, requirement analysis helps manage project scope and prevents unnecessary additions to the project. 
### 4. Provides a Clear Basis for Design:
The analysis creates clear, actionable, and testable requirements, which serve as the foundation for the subsequent design and development phases. 
### 5. Improves Communication and Collaboration:
It facilitates a shared understanding among all stakeholders, including developers, designers, and clients, fostering collaboration and a common vision. 
### 6. Reduces Project Risks:
A thorough requirement analysis lowers the risk of project failure by ensuring the project's objectives are well-understood and feasible. 
### 7. Supports Verification and Validation:
It provides the basis for verification (ensuring the software is built correctly to the specifications) and validation (ensuring the software meets the user's actual needs). 

## Key Activities in Requirement Analysis.
Requirement analysis ensures that software solutions align with business objectives and user expectations. The process involves five key activities:
- Requirement Gathering
Collecting raw requirements from stakeholders, clients, and end-users.
Sources include interviews, surveys, existing system documentation, and direct observation.
Focus is on capturing all potential needs without filtering or judgment at this stage.
- Requirement Elicitation
Engaging with stakeholders to clarify and refine gathered requirements.
Techniques include workshops, brainstorming sessions, prototyping, and questionnaires.
The goal is to uncover implicit needs, constraints, and expectations that may not be immediately obvious.
- Requirement Documentation
Structuring requirements into clear, concise, and accessible formats.
Common outputs include Software Requirement Specifications (SRS), user stories, and use cases.
Documentation ensures all parties share a consistent understanding of system needs.
- Requirement Analysis and Modeling
Reviewing and breaking down requirements to identify conflicts, overlaps, or gaps.
Applying modeling techniques such as data flow diagrams, UML diagrams, or process models.
Helps visualize system behavior, dependencies, and business workflows.
- Requirement Validation
Ensuring requirements are complete, consistent, feasible, and testable.
Stakeholder reviews, walkthroughs, and prototyping are common validation methods.
Confirms alignment with business goals before moving into design and development.

## Types of Requirements
### 1. Functional Requirements
#### Definition:
These specify what the system must do—the behaviors, features, or services the system offers. They describe system functions, interactions, and business rules.
#### Examples (Booking Management Project):
- The system shall allow users to create a new booking by selecting a date, time, and service type.
- The system shall check availability of resources (e.g., rooms, staff, equipment) before confirming a booking.
- The system shall allow users to modify or cancel bookings up to 24 hours before the scheduled time.
- The system shall send confirmation emails (and/or SMS) to users once a booking is created or modified.
- The system shall generate daily and monthly booking reports for administrators.
- The system shall support user authentication (login/logout) and role-based access (e.g., user, admin, manager).

### 2. Non-Functional Requirements
#### Definition:
These specify how the system performs the functions—the quality attributes such as performance, usability, reliability, security, etc.
#### Examples (Booking Management Project):
- Performance: The system shall process booking confirmations within 2 seconds of user request under normal load.
- Scalability: The system should handle at least 1,000 concurrent booking requests without degradation.
- Reliability / Availability: The system shall maintain 99.9% uptime, excluding scheduled maintenance.
- Security: All user data must be stored encrypted. The system shall enforce strong password policies and use HTTPS for all data transactions.
- Usability: The user interface shall be intuitive, providing clear error messages and guidance. Non-technical users should be able to make a booking in no more than 3 steps.
- Maintainability: Code should follow modular design principles; the system shall allow updates to booking rules without major code rewrites.
- Localization / Internationalization: The system shall support local date/time formats and multiple currencies (if applicable) for users from different regions.

## Use Case Diagrams
Use Case Diagrams are a type of Unified Modeling Language (UML) diagram used in requirement analysis.  
They illustrate the interactions between system users (actors) and the system itself through different use cases.  

**Benefits of Use Case Diagrams:**
- Provide a clear visualization of system functionality from the user’s perspective.  
- Help identify actors (users, admins, external systems) and their goals.  
- Support communication between stakeholders and developers.  
- Serve as a foundation for writing detailed requirements and test cases.

**Use Case Diagram for the Booking System:**
<img width="631" height="182" alt="alx-booking-uc" src="https://github.com/user-attachments/assets/87ab06aa-bcca-4b69-8f0a-5548c2579f27" />
" />

## Acceptance Criteria
#### Definition and Importance:
Acceptance criteria are a set of conditions that a software product must satisfy to be accepted by stakeholders, typically the client or end-user. They define what “done” means for a feature, ensuring clear expectations between developers, testers, and stakeholders.

#### Why Acceptance Criteria Matter:
- Provide clarity on what a feature must achieve.
- Serve as a reference for writing test cases and verifying functionality.
- Reduce misunderstandings and scope creep during development.
- Ensure features meet user needs and business requirements before release.

#### Example: Checkout Feature in the Booking Management System
- Users must be able to select available bookings and proceed to checkout.
- Payment options should include credit/debit card, mobile money, and online wallets.
- Users must receive a confirmation email or SMS once payment is successful.
- If payment fails, users should see an error message explaining the issue.
- The system must prevent double-booking of the same slot.
- Checkout process should be completed within 3 minutes under normal load.
