---
agent_use: Supporting requirement reviews, artifact validation, and
  early defect detection
domain: Testing Fundamentals
keywords:
- static testing
- reviews
- inspections
- walkthroughs
- requirement reviews
- code reviews
methodology_sources:
- ISTQB Foundation Level
- ISTQB Agile Testing
- Quality Engineering Practices
related_topics:
- ISTQB Test Process
- Requirement Analysis for Testing
- Risk Based Testing
- Defect Management
title: Static Testing and Reviews
version: 1
---

# Static Testing and Reviews

## Concept

Static testing refers to the evaluation of software artifacts **without
executing the software**.\
It focuses on identifying defects early by examining documents,
specifications, models, or code.

Static testing typically includes structured **reviews** such as:

-   informal reviews
-   walkthroughs
-   technical reviews
-   inspections

Unlike dynamic testing, which validates system behavior through
execution, static testing evaluates the **quality and correctness of
artifacts before implementation or runtime**.

Static testing is one of the most cost‑effective techniques for
detecting defects early in the software lifecycle.

------------------------------------------------------------------------

# Detailed Explanation

Static testing is performed on artifacts produced during software
development, such as:

-   requirements
-   user stories
-   acceptance criteria
-   architecture designs
-   test cases
-   source code

The goal is to detect issues such as:

-   ambiguity
-   inconsistency
-   missing requirements
-   incorrect logic
-   non‑testable specifications

Early detection prevents defects from propagating into later stages
where they become more expensive to fix.

Static testing is often performed collaboratively and encourages
knowledge sharing between stakeholders such as:

-   testers
-   developers
-   business analysts
-   architects
-   product owners

This collaboration improves both **artifact quality and shared
understanding of the system**.

------------------------------------------------------------------------

# Key Principles

## 1. Static Testing Detects Defects Early

Defects discovered in requirements or design stages are much cheaper to
fix than defects discovered after implementation.

Example:

A missing business rule identified during a requirement review can
prevent multiple downstream defects.

------------------------------------------------------------------------

## 2. Reviews Improve Artifact Quality

Reviews allow multiple stakeholders to evaluate an artifact and
identify:

-   unclear requirements
-   incorrect assumptions
-   missing edge cases
-   architectural risks

This collaborative process improves both accuracy and completeness.

------------------------------------------------------------------------

## 3. Static Testing Supports Testability

By reviewing requirements and specifications early, testers can
determine whether the system behavior can be validated effectively.

Testable requirements typically include:

-   clear expected outcomes
-   measurable conditions
-   defined inputs and outputs

------------------------------------------------------------------------

## 4. Static Testing Complements Dynamic Testing

Static testing does not replace execution‑based testing but complements
it.

Static testing identifies issues before implementation, while dynamic
testing validates actual system behavior.

------------------------------------------------------------------------

# Types of Reviews

## Informal Reviews

Informal reviews are lightweight and unstructured.

Examples include:

-   peer discussions
-   quick document reviews
-   ad‑hoc code review

Advantages:

-   fast
-   flexible
-   minimal overhead

------------------------------------------------------------------------

## Walkthroughs

In a walkthrough, the author of an artifact presents it to reviewers and
explains the logic or design.

Reviewers ask questions and provide feedback.

Walkthroughs are useful for:

-   sharing knowledge
-   identifying misunderstandings
-   validating design decisions

------------------------------------------------------------------------

## Technical Reviews

Technical reviews involve subject‑matter experts evaluating an artifact.

Focus areas may include:

-   technical correctness
-   architecture decisions
-   compliance with standards

These reviews are more structured than walkthroughs.

------------------------------------------------------------------------

## Inspections

Inspections are the most formal review type.

Characteristics:

-   defined roles
-   structured preparation
-   documented defects
-   formal follow‑up

Inspections are commonly used in safety‑critical or regulated
environments.

------------------------------------------------------------------------

# When to Use

Static testing should be applied when reviewing artifacts such as:

-   requirements documents
-   user stories
-   architecture designs
-   test cases
-   code changes

Typical moments include:

-   backlog refinement
-   design reviews
-   code review processes
-   pre‑release validation

Applying static testing early significantly reduces downstream defects.

------------------------------------------------------------------------

# When NOT to Misapply

Static testing should not be used as a replacement for execution‑based
testing.

Common mistakes include:

-   assuming reviews eliminate the need for dynamic testing
-   performing reviews without preparation
-   involving only a single reviewer
-   failing to track review findings

Static testing is most effective when combined with dynamic testing and
proper defect management.

------------------------------------------------------------------------

# Practical Example

Consider a requirement for a financial system:

> The system must apply a transaction fee for transfers above €10,000.

During a requirement review, testers identify missing details:

-   What is the exact fee percentage?
-   Does the rule apply to international transfers?
-   Is the fee applied before or after currency conversion?

Resolving these questions early prevents implementation defects.

------------------------------------------------------------------------

# Common Mistakes

Frequent mistakes when performing static testing include:

-   skipping reviews due to time pressure
-   reviewing artifacts individually rather than collaboratively
-   failing to document review findings
-   focusing only on grammar instead of functional correctness

These mistakes reduce the effectiveness of static testing.

------------------------------------------------------------------------

# Practical Guidelines

Consultants should follow these practices:

1.  Involve multiple stakeholders during reviews.
2.  Review artifacts before implementation begins.
3.  Focus on ambiguity, completeness, and consistency.
4.  Document identified issues and follow up on resolutions.
5.  Combine static testing with dynamic testing.

------------------------------------------------------------------------

# Typical Questions

This knowledge helps answer questions such as:

-   What is static testing?
-   What is the difference between static and dynamic testing?
-   What types of reviews exist in software testing?
-   Why are requirement reviews important?
-   When should inspections be used?

------------------------------------------------------------------------

# Retrieval Notes (For AI Agents)

Key takeaways:

-   Static testing evaluates artifacts without executing the software.
-   Reviews help detect defects early in requirements, design, and code.
-   Types of reviews include informal reviews, walkthroughs, technical
    reviews, and inspections.
-   Static testing improves artifact quality and supports early defect
    detection.
-   Static testing complements dynamic testing but does not replace it.
