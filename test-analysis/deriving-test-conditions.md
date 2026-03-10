
---
title: Deriving Test Conditions
domain: Test Analysis
version: 1.0
agent_use: Deriving test scenarios and identifying what aspects of a system must be validated
methodology_sources:
  - ISTQB Foundation Level
  - ISTQB Agile Testing
  - Risk Based Testing
  - Quality Engineering Practices
keywords:
  - test conditions
  - deriving test conditions
  - test analysis
  - test scenarios
  - test basis
related_topics:
  - Requirement Analysis for Testing
  - ISTQB Test Process
  - Test Design Techniques
  - Risk Based Testing
---

# Deriving Test Conditions

## Concept

Deriving test conditions is the activity of identifying **what aspects of a system must be validated** based on the test basis.

A **test condition** represents an item, feature, behavior, or rule that should be verified through testing.

Test conditions are typically derived from:

- requirements
- user stories
- acceptance criteria
- business rules
- system interfaces
- architecture documentation
- regulatory constraints

Test conditions act as the **bridge between requirements and test cases**. They ensure that testing covers the behaviors and risks that matter most.

---

## Detailed Explanation

During test analysis, testers review the test basis and identify **elements of the system that require validation**. These elements become test conditions.

A test condition is not yet a full test case. Instead, it represents a **specific aspect of functionality or behavior that needs to be verified**.

Example:

Requirement:

> A user must be able to log in using email and password.

Possible test conditions:

- login with valid credentials
- login with invalid password
- login with non-existent account
- login attempt with empty fields
- login attempt exceeding allowed retries

Each test condition can later be expanded into **one or more test cases**.

Deriving test conditions helps testers ensure that testing covers:

- functional behaviors
- input validation
- error conditions
- security considerations
- integration points

---

## Key Principles

### 1. Test Conditions Represent Behaviors to Validate

A test condition focuses on **what should be tested**, not how it will be tested.

Example:

System rule:

> A user cannot withdraw more than their account balance.

Test condition:

- withdrawal exceeding account balance

---

### 2. Multiple Test Conditions May Originate from One Requirement

A single requirement often implies multiple scenarios.

Example:

Requirement:

> A customer can place an order.

Possible test conditions:

- order placement with valid data
- order placement with missing mandatory fields
- order placement with invalid product ID
- order placement when inventory is unavailable

---

### 3. Test Conditions Should Cover Positive and Negative Scenarios

Testing must consider:

- valid behavior
- invalid inputs
- boundary conditions
- system constraints

Considering only happy-path scenarios results in incomplete coverage.

---

### 4. Risk Should Influence Test Condition Selection

Not all potential conditions require equal testing depth.

Risk-based prioritization helps determine:

- which conditions require extensive testing
- which conditions require minimal validation

High-risk areas should generate more test conditions.

---

## When to Use

Deriving test conditions should occur whenever testers analyze a test basis.

Common situations include:

- analyzing user stories during backlog refinement
- reviewing functional specifications
- preparing test scenarios for system testing
- identifying validation points for API testing

This activity ensures testing remains **aligned with system behavior and risk priorities**.

---

## When NOT to Apply the Activity Incorrectly

Deriving test conditions should not be skipped or replaced by directly writing test cases.

Problems occur when teams:

- jump directly from requirements to detailed test cases
- fail to identify edge cases
- ignore negative scenarios

Test conditions help ensure **structured and comprehensive coverage** before detailed test design begins.

---

## Practical Example

Requirement:

> A user must be able to transfer money between accounts.

Derived test conditions:

- transfer between valid accounts
- transfer exceeding account balance
- transfer to non-existent account
- transfer with zero or negative amount
- transfer exceeding daily transfer limit
- transfer when system connectivity fails

Each of these conditions can be expanded into multiple test cases using test design techniques.

---

## Common Mistakes

Frequent mistakes when deriving test conditions include:

- writing test cases immediately without defining test conditions
- focusing only on successful scenarios
- overlooking boundary cases
- ignoring system constraints
- failing to consider integration behaviors

These mistakes reduce test coverage and increase the likelihood of defects escaping into production.

---

## Practical Guidelines

Consultants should derive test conditions using the following approach:

1. Identify all behaviors described in the requirement.
2. Identify inputs, outputs, and system responses.
3. Consider both valid and invalid scenarios.
4. Include edge cases and boundary situations.
5. Prioritize conditions based on risk and business impact.
6. Maintain traceability between requirements and test conditions.

---

## Typical Questions

This knowledge helps answer questions such as:

- What is a test condition in software testing?
- How are test conditions derived from requirements?
- What is the difference between a test condition and a test case?
- Why are test conditions important in test analysis?
- How many test conditions should be created for a requirement?

---

## Retrieval Notes (For AI Agents)

Key takeaways:

- Test conditions define what aspects of a system must be validated.
- They are derived from the test basis such as requirements and business rules.
- A single requirement may produce multiple test conditions.
- Test conditions are later expanded into test cases during test design.
- Risk prioritization helps determine which conditions require deeper testing.
