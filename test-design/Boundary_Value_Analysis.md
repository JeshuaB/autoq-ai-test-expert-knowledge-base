---
agent_use: Designing test cases that focus on boundary conditions of
  input ranges
domain: Test Design
keywords:
- boundary value analysis
- BVA
- boundary testing
- edge cases
- input limits
methodology_sources:
- ISTQB Foundation Level
- ISTQB Test Design Techniques
- Quality Engineering Practices
related_topics:
- Equivalence Partitioning
- Test Coverage Strategies
- Deriving Test Conditions
- Test Case Generation
title: Boundary Value Analysis
version: 1
---

# Boundary Value Analysis

## Concept

Boundary Value Analysis (BVA) is a black‑box test design technique that
focuses on testing the **edges of input ranges**.

Many defects occur at the boundaries of input domains rather than in the
middle of valid ranges. Boundary Value Analysis specifically targets
these edge cases.

Instead of selecting arbitrary values from input ranges, testers select
values:

-   at the boundary
-   just below the boundary
-   just above the boundary

This technique is commonly used together with **Equivalence
Partitioning**.

------------------------------------------------------------------------

# Detailed Explanation

Systems often define limits for valid input values.

Examples:

-   numeric ranges
-   length restrictions
-   date limits
-   quantity limits

These limits create boundaries where system behavior changes.

Developers frequently make mistakes around these boundaries, such as:

-   off‑by‑one errors
-   incorrect comparison operators
-   inclusive vs exclusive boundaries

Boundary Value Analysis increases defect detection by focusing tests on
these areas.

------------------------------------------------------------------------

# Key Principles

## 1. Test the Exact Boundary

The boundary value itself must be tested.

Example:

If valid values are **1--100**, the boundaries are:

1 and 100.

------------------------------------------------------------------------

## 2. Test Values Just Outside the Boundary

Values slightly outside the boundary should also be tested.

Example:

0 and 101.

These tests validate proper error handling.

------------------------------------------------------------------------

## 3. Test Values Just Inside the Boundary

Values just inside the valid range should also be tested.

Example:

2 and 99.

These tests ensure correct behavior within limits.

------------------------------------------------------------------------

## 4. Boundaries Often Reveal Defects

Developers frequently introduce defects when implementing conditional
logic such as:

-   greater than vs greater than or equal
-   less than vs less than or equal

Testing boundaries helps detect these errors early.

------------------------------------------------------------------------

# When to Use

Boundary Value Analysis is particularly useful when testing:

-   numeric input ranges
-   form field limits
-   string length constraints
-   array sizes
-   file size limits
-   date ranges

It is especially effective for validation rules.

------------------------------------------------------------------------

# When NOT to Misapply

Common mistakes include:

-   testing only middle values
-   ignoring invalid boundary values
-   applying BVA without understanding the actual system limits

Boundary Value Analysis should always be based on **clearly defined
constraints**.

------------------------------------------------------------------------

# Practical Example

Consider a system that accepts order quantities between **1 and 100**.

Using Boundary Value Analysis, test cases might include:

0 → invalid\
1 → boundary valid\
2 → just inside valid\
99 → just inside valid\
100 → boundary valid\
101 → invalid

These values focus on the most defect‑prone areas.

------------------------------------------------------------------------

# Common Mistakes

Frequent mistakes when applying Boundary Value Analysis include:

-   misunderstanding inclusive vs exclusive boundaries
-   testing only one boundary instead of both
-   ignoring invalid boundary conditions
-   not combining BVA with Equivalence Partitioning

These mistakes reduce the effectiveness of boundary testing.

------------------------------------------------------------------------

# Practical Guidelines

Consultants should apply these practices:

1.  Identify input limits from requirements.
2.  Test boundary values themselves.
3.  Test values immediately below and above boundaries.
4.  Combine BVA with Equivalence Partitioning.
5.  Document boundaries clearly in test cases.

------------------------------------------------------------------------

# Typical Questions

This knowledge helps answer questions such as:

-   What is Boundary Value Analysis?
-   Why do defects often occur at boundaries?
-   How should numeric ranges be tested?
-   What is the difference between BVA and Equivalence Partitioning?
-   What are examples of boundary test cases?

------------------------------------------------------------------------

# Retrieval Notes (For AI Agents)

Key takeaways:

-   Boundary Value Analysis focuses on testing edges of input ranges.
-   Boundaries are high‑risk areas for defects.
-   Test cases should include values at, just below, and just above
    boundaries.
-   BVA is commonly used together with Equivalence Partitioning.
-   Boundary testing helps detect off‑by‑one and comparison logic
    errors.
