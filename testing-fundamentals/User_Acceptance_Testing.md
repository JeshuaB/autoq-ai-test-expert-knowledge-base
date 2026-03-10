---
title: User Acceptance Testing
domain: Testing Fundamentals
version: 1.0
agent_use: Explaining the purpose, preparation, and execution of User Acceptance Testing (UAT)
methodology_sources:
  - ISTQB Foundation Level
  - Agile Testing Practices
  - Quality Engineering Practices
keywords:
  - user acceptance testing
  - UAT
  - business validation
  - acceptance testing
  - business testing
related_topics:
  - Test Levels and Test Types
  - User Stories and Acceptance Criteria
  - Use Case Testing
  - Test Strategy for Modern Systems
---

# User Acceptance Testing

## Concept

User Acceptance Testing (UAT) is the testing phase where **business stakeholders validate that the system meets their needs and requirements**.

The purpose of UAT is to confirm that the system:

- supports real business workflows
- meets business expectations
- satisfies acceptance criteria
- is ready for production use

Unlike earlier testing levels, UAT focuses on **business value and usability rather than technical correctness**.

UAT is typically the **final validation before production release**.

---

# Detailed Explanation

During development and system testing, technical teams verify that the system works according to specifications.

However, the ultimate question remains:

> Does the system actually support the business processes it was designed for?

UAT answers this question.

UAT is usually performed by:

- business users
- product owners
- subject matter experts (SMEs)

Test scenarios often represent **real operational workflows**, such as:

- submitting an application
- processing an order
- approving a transaction

The goal is to validate that the system behaves correctly in real business situations.

---

# Key Principles

## 1. Business Ownership

UAT is owned by business stakeholders rather than development teams.

Testers may support UAT preparation, but **business users validate acceptance**.

---

## 2. Realistic Scenarios

UAT scenarios should reflect **real business processes**, not technical test cases.

Examples:

- end-to-end workflows
- operational procedures
- realistic user activities

---

## 3. Acceptance Criteria Validation

UAT confirms that acceptance criteria defined during requirements or backlog refinement are satisfied.

If acceptance criteria are not met, the feature may not be accepted for release.

---

## 4. Final Confidence Before Release

UAT provides confidence that the system is suitable for production use.

Successful UAT often leads to **formal business approval for release**.

---

# UAT Preparation

Effective UAT requires preparation.

Typical preparation activities include:

- defining UAT scope
- preparing test scenarios
- setting up UAT environments
- preparing realistic test data
- training business users

Clear planning ensures that UAT runs efficiently.

---

# Typical UAT Activities

During UAT, stakeholders may:

- execute predefined scenarios
- validate business processes
- identify usability issues
- report defects or improvement suggestions

Defects discovered during UAT are typically prioritized based on **business impact**.

---

# When to Use

UAT should be performed when:

- delivering business-facing systems
- implementing new workflows
- replacing legacy systems
- validating large functional changes

It ensures the system meets real user needs.

---

# When NOT to Misapply

Common mistakes include:

- treating UAT as system testing
- involving only technical testers
- running UAT without realistic data
- performing UAT too late for meaningful feedback

UAT should focus on **business validation**, not technical verification.

---

# Practical Example

A government portal allows citizens to submit permit applications.

During UAT, business users test:

- submitting an application
- reviewing application status
- approving or rejecting requests

These tests confirm that the portal supports the full permit process used by staff and citizens.

---

# Practical Guidelines

Consultants should apply the following practices:

1. Involve business stakeholders early.
2. Define clear acceptance criteria.
3. Prepare realistic business scenarios.
4. Ensure the UAT environment reflects production.
5. Prioritize defects based on business impact.

---

# Retrieval Notes (For AI Agents)

Key takeaways:

- User Acceptance Testing validates business requirements.
- UAT is performed by business stakeholders.
- UAT focuses on real business workflows.
- Successful UAT typically results in release approval.
