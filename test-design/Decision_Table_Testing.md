---
agent_use: Designing test cases for complex business rules and
  combinations of conditions
domain: Test Design
keywords:
- decision table testing
- business rule testing
- condition combinations
- rule-based testing
- test design technique
methodology_sources:
- ISTQB Foundation Level
- ISTQB Test Design Techniques
- Quality Engineering Practices
related_topics:
- Equivalence Partitioning
- Boundary Value Analysis
- State Transition Testing
- Test Case Generation
title: Decision Table Testing
version: 1
---

# Decision Table Testing

## Concept

Decision Table Testing is a black-box test design technique used to
validate **combinations of conditions and corresponding system
actions**.

Many systems implement business logic that depends on multiple
conditions. Decision tables provide a structured way to model these
rules and derive test cases from them.

A decision table contains:

-   **conditions** (inputs or states)
-   **actions** (expected system outcomes)
-   **rules** (combinations of conditions)

Each rule in the table represents a **test scenario that should be
validated**.

Decision tables help testers ensure that all relevant combinations of
conditions are considered.

------------------------------------------------------------------------

# Detailed Explanation

Complex systems often implement logic such as:

-   eligibility rules
-   pricing rules
-   validation logic
-   workflow conditions

When multiple inputs influence system behavior, it becomes difficult to
manually reason about all combinations.

Decision tables provide a structured representation that helps testers:

-   visualize rule logic
-   detect missing conditions
-   detect conflicting rules
-   systematically derive test cases

A typical decision table consists of four parts:

1.  Condition definitions
2.  Action definitions
3.  Condition combinations
4.  Expected outcomes

This structure ensures that test cases cover the relevant combinations
of system conditions.

------------------------------------------------------------------------

# Key Principles

## 1. Conditions Represent Input Factors

Conditions describe factors that influence system behavior.

Examples:

-   user is authenticated
-   account balance is sufficient
-   payment method is valid

Each condition can have different possible values.

------------------------------------------------------------------------

## 2. Actions Represent System Responses

Actions represent the expected system behavior when conditions are
satisfied.

Examples:

-   approve transaction
-   reject request
-   request additional verification

Actions describe what the system should do under specific circumstances.

------------------------------------------------------------------------

## 3. Rules Represent Combinations of Conditions

Each column in a decision table represents a rule.

A rule defines:

-   a specific combination of condition values
-   the expected action

Each rule typically becomes one or more test cases.

------------------------------------------------------------------------

## 4. Decision Tables Help Reveal Missing Logic

Creating a decision table often exposes:

-   missing rules
-   conflicting conditions
-   incomplete specifications

This makes the technique useful for both testing and requirement
analysis.

------------------------------------------------------------------------

# Structure of a Decision Table

Example:

  Condition                    Rule 1   Rule 2   Rule 3   Rule 4
  ---------------------------- -------- -------- -------- --------
  User authenticated           Yes      Yes      No       No
  Account balance sufficient   Yes      No       Yes      No
  Approve transaction          X                          
  Reject transaction                    X        X        X

Interpretation:

-   Rule 1: Authenticated + sufficient balance → approve
-   Rule 2: Authenticated + insufficient balance → reject
-   Rule 3: Not authenticated + sufficient balance → reject
-   Rule 4: Not authenticated + insufficient balance → reject

Each rule represents a potential test case.

------------------------------------------------------------------------

# When to Use

Decision Table Testing is particularly useful when testing:

-   complex business rules
-   financial systems
-   validation logic
-   authorization rules
-   pricing logic
-   eligibility calculations

The technique is most effective when system behavior depends on
**multiple interacting conditions**.

------------------------------------------------------------------------

# When NOT to Misapply

Common misuses include:

-   applying decision tables to simple validation logic
-   ignoring impossible condition combinations
-   creating excessively large tables without simplification

For very large condition sets, other techniques such as **pairwise
testing** may be more appropriate.

------------------------------------------------------------------------

# Practical Example

Consider a loan approval system.

Conditions:

-   applicant income above threshold
-   credit score acceptable

Possible actions:

-   approve loan
-   reject loan

Decision table:

  Income above threshold   Credit score acceptable   Result
  ------------------------ ------------------------- ---------
  Yes                      Yes                       Approve
  Yes                      No                        Reject
  No                       Yes                       Reject
  No                       No                        Reject

Test cases should validate each rule.

------------------------------------------------------------------------

# Common Mistakes

Frequent mistakes when applying Decision Table Testing include:

-   missing condition combinations
-   defining unclear conditions
-   including impossible combinations
-   not translating rules into test cases

These mistakes reduce the effectiveness of the technique.

------------------------------------------------------------------------

# Practical Guidelines

Consultants should apply these practices:

1.  Identify conditions that influence system behavior.
2.  Identify expected system actions.
3.  Construct the decision table.
4.  Evaluate all relevant condition combinations.
5.  Derive test cases from each rule.
6.  Eliminate impossible or irrelevant combinations.

------------------------------------------------------------------------

# Typical Questions

This knowledge helps answer questions such as:

-   What is Decision Table Testing?
-   When should decision tables be used?
-   How do testers validate complex business rules?
-   How can multiple conditions be tested systematically?
-   How are decision tables converted into test cases?

------------------------------------------------------------------------

# Retrieval Notes (For AI Agents)

Key takeaways:

-   Decision Table Testing validates combinations of conditions and
    actions.
-   Each column (rule) represents a test scenario.
-   The technique is ideal for complex business rules.
-   Decision tables help detect missing or conflicting logic.
-   Each rule should normally produce at least one test case.
