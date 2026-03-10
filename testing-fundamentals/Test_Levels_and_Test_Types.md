---
title: Test Levels and Test Types
domain: Testing Fundamentals
version: 1.0
agent_use: Determining where and what to test within a software system
methodology_sources:
  - ISTQB Foundation Level
  - ISTQB Agile Testing
  - Quality Engineering Practices
keywords:
  - test levels
  - test types
  - unit testing
  - integration testing
  - system testing
  - acceptance testing
  - functional testing
  - non-functional testing
related_topics:
  - ISTQB Test Process
  - Requirement Analysis for Testing
  - Risk Based Testing
  - Test Strategy
---

# Test Levels and Test Types

## Concept

Software testing is organized along two key dimensions:

**Test Levels** define **where testing occurs in the system architecture or development lifecycle.**

**Test Types** define **what aspect of the system is being tested.**

Understanding the distinction between test levels and test types helps testers determine:

- the correct scope of testing
- the most efficient testing approach
- the appropriate tooling and environment
- where defects should be detected in the development lifecycle

Test levels structure testing across development stages, while test types ensure that different quality characteristics of the system are validated.

---

# Detailed Explanation

In professional testing practice, tests are organized so that defects are detected **as early and efficiently as possible**.

Different types of defects tend to appear at different layers of a system. For example:

- coding errors are typically detected at **unit level**
- interface defects appear at **integration level**
- workflow or business process defects appear at **system level**
- business validation occurs during **acceptance testing**

Test types, on the other hand, represent **different quality perspectives** from which a system can be evaluated.

Examples include:

- functional correctness
- performance
- security
- usability
- reliability

Test levels and test types work together. For example:

A **performance test** (test type) may be executed at **system level** (test level).

Understanding both dimensions allows testers to design **balanced and effective test strategies**.

---

# Test Levels

## Unit Testing

Unit testing focuses on verifying **individual components or functions of the software**.

Units typically include:

- individual functions
- classes
- modules
- microservices endpoints

Unit tests are usually created and executed by developers.

Characteristics:

- highly isolated tests
- fast execution
- automated execution
- often part of continuous integration pipelines

Purpose:

Detect defects in the smallest components before they propagate into higher levels.

Example:

Testing a function that calculates tax for a transaction.

---

## Integration Testing

Integration testing verifies **interactions between components or systems**.

The focus is on:

- data exchange
- interfaces
- communication protocols
- service interactions

Typical integration testing targets include:

- API communication
- database interactions
- message queues
- microservice communication

Purpose:

Detect defects in interactions between components.

Example:

Testing the interaction between an order service and a payment service.

---

## System Testing

System testing validates the **complete integrated system** against functional and non-functional requirements.

The entire system is tested as a whole.

Focus areas include:

- end-to-end workflows
- user interactions
- business processes
- system behavior under normal conditions

System testing is often performed by dedicated testing teams.

Example:

Testing the full checkout process in an e-commerce platform.

---

## Acceptance Testing

Acceptance testing validates whether the system **meets business needs and user expectations**.

This level often involves stakeholders such as:

- business users
- product owners
- customers

Acceptance testing focuses on:

- real-world usage scenarios
- business workflows
- operational readiness

Example:

Validating that a new banking feature meets regulatory and business requirements.

---

# Test Types

Test types represent **different quality attributes of a system**.

They are not tied to a specific development phase and can occur at multiple test levels.

---

## Functional Testing

Functional testing verifies that the system behaves according to its specified functionality.

Focus areas:

- user actions
- system responses
- business rules
- data processing

Example:

Testing whether a user can successfully place an order.

---

## Performance Testing

Performance testing evaluates how a system behaves under load or stress.

Key objectives:

- response time
- system throughput
- resource usage
- scalability

Example:

Testing whether an application can support 10,000 concurrent users.

---

## Security Testing

Security testing evaluates the system's resistance to threats and vulnerabilities.

Focus areas:

- authentication and authorization
- data protection
- vulnerability exploitation
- misuse scenarios

Example:

Testing whether unauthorized users can access restricted functionality.

---

## Usability Testing

Usability testing evaluates how easily users can interact with the system.

Focus areas:

- user experience
- interface clarity
- navigation
- accessibility

Example:

Assessing whether users can complete a purchase without confusion.

---

## Compatibility Testing

Compatibility testing evaluates how the system performs across different environments.

Focus areas:

- browsers
- operating systems
- devices
- network environments

Example:

Testing whether a web application works correctly across major browsers.

---

## Reliability Testing

Reliability testing evaluates system stability over time.

Focus areas:

- system uptime
- fault tolerance
- error recovery

Example:

Running long-duration tests to verify system stability.

---

# When to Use

Understanding test levels and types is essential when:

- defining a test strategy
- planning testing activities
- determining test responsibilities
- selecting automation scope
- designing risk-based testing approaches

Proper use ensures defects are detected **as early as possible**.

---

# When NOT to Misapply

Common misapplications include:

- executing all tests only at system level
- ignoring lower-level testing
- confusing test levels with test types
- performing performance testing only after release

Testing should be distributed across levels to maximize defect detection efficiency.

---

# Practical Example

Consider an online shopping platform.

Unit testing:

- validating price calculation logic

Integration testing:

- verifying communication between order and payment services

System testing:

- testing the entire purchase workflow

Acceptance testing:

- validating business approval of checkout functionality

Test types applied across levels:

- functional tests for workflows
- performance tests for checkout scalability
- security tests for payment handling

---

# Common Mistakes

Frequent mistakes include:

- over-reliance on UI/system testing
- lack of integration testing
- missing non-functional testing
- misunderstanding where defects originate
- failing to distribute testing across levels

These mistakes reduce testing efficiency and increase risk.

---

# Practical Guidelines

Consultants should follow these practices:

1. Detect defects as early as possible using lower test levels.
2. Use integration testing to validate system communication.
3. Reserve system testing for end-to-end validation.
4. Include both functional and non-functional test types.
5. Align test levels and types with system risks.

---

# Typical Questions

This knowledge helps answer questions such as:

- What are the different test levels in ISTQB?
- What is the difference between integration testing and system testing?
- What are examples of test types?
- Can performance testing occur at different test levels?
- When should acceptance testing occur?

---

# Retrieval Notes (For AI Agents)

Key takeaways:

- Test levels define where testing occurs in the system lifecycle.
- The main levels are unit, integration, system, and acceptance testing.
- Test types define what aspect of quality is evaluated.
- Test types include functional, performance, security, usability, compatibility, and reliability testing.
- Effective test strategies combine multiple test levels and test types.
