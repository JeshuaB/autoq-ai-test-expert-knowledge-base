---
agent_use: Supporting defect reporting, defect lifecycle explanation,
  and defect analysis
domain: Testing Fundamentals
keywords:
- defect management
- defect lifecycle
- bug tracking
- defect reporting
- defect prioritization
methodology_sources:
- ISTQB Foundation Level
- ISTQB Agile Testing
- Quality Engineering Practices
related_topics:
- ISTQB Test Process
- Static Testing and Reviews
- Risk Based Testing
- Test Strategy
title: Defect Management
version: 1
---

# Defect Management

## Concept

Defect management is the structured process used to **identify,
document, track, prioritize, and resolve defects** discovered during
testing or other quality assurance activities.

A defect represents a flaw in the software that causes it to behave
differently from expected behavior.

Effective defect management ensures that:

-   defects are documented clearly
-   issues are tracked throughout their lifecycle
-   development teams can reproduce and fix defects
-   stakeholders understand the impact of defects on quality and risk

Defect management is a critical part of the overall **test process and
quality assurance strategy**.

------------------------------------------------------------------------

# Detailed Explanation

During dynamic testing, when the actual system behavior differs from the
expected result, a **defect report** is created.

Defect management systems help teams track issues and coordinate
resolution activities.

Typical defect tracking tools include:

-   issue trackers
-   test management tools
-   project management systems

Defect management is not only about logging issues but also about:

-   prioritizing fixes
-   monitoring defect trends
-   identifying root causes
-   improving development processes

Proper defect management enables teams to understand the **health of a
product and the risks associated with releasing it**.

------------------------------------------------------------------------

# Key Principles

## 1. Defects Must Be Clearly Documented

A defect report must contain enough information for developers to
reproduce the issue.

Typical information includes:

-   defect ID
-   description
-   steps to reproduce
-   expected result
-   actual result
-   environment information
-   screenshots or logs

Clear documentation speeds up defect resolution.

------------------------------------------------------------------------

## 2. Defects Have a Lifecycle

Defects move through a series of states as they are investigated and
resolved.

Typical lifecycle states include:

-   New
-   Assigned
-   In Progress
-   Resolved
-   Verified
-   Closed

Additional states may include:

-   Rejected
-   Duplicate
-   Deferred

The exact workflow may vary depending on the organization.

------------------------------------------------------------------------

## 3. Severity and Priority Are Different

Defects are typically classified by:

**Severity** -- the technical impact of the defect.

Example severity levels:

-   Critical
-   High
-   Medium
-   Low

**Priority** -- the urgency with which the defect should be fixed.

A low-severity defect may still have high priority if it affects key
business functionality.

------------------------------------------------------------------------

## 4. Defect Trends Provide Quality Insights

Monitoring defect metrics helps teams understand product quality.

Examples of useful metrics:

-   defect density
-   defect discovery rate
-   defect leakage to production
-   defect resolution time

Analyzing these trends can reveal underlying development or testing
issues.

------------------------------------------------------------------------

# When to Use

Defect management should be applied whenever issues are discovered
during:

-   system testing
-   integration testing
-   acceptance testing
-   exploratory testing
-   production monitoring

Effective defect management ensures that defects are tracked and
resolved systematically.

------------------------------------------------------------------------

# When NOT to Misapply

Common mistakes include:

-   logging incomplete defect reports
-   failing to reproduce defects before reporting
-   misclassifying severity or priority
-   reporting duplicates without checking existing issues

These mistakes create confusion and reduce efficiency in defect
resolution.

------------------------------------------------------------------------

# Practical Example

Consider an online banking system.

Test case:

User transfers money between accounts.

Expected result:

Transfer completes successfully.

Actual result:

System returns an error when transferring amounts above €5,000.

Defect report should include:

-   exact steps taken
-   transfer amount used
-   account types involved
-   screenshots or logs

This information helps developers reproduce the issue and identify the
root cause.

------------------------------------------------------------------------

# Common Mistakes

Frequent mistakes in defect management include:

-   vague defect descriptions
-   missing reproduction steps
-   reporting environment-specific issues without context
-   excessive duplicate defects
-   not verifying fixes after resolution

These mistakes slow down the development process.

------------------------------------------------------------------------

# Practical Guidelines

Consultants should apply these practices:

1.  Ensure defects are reproducible before logging them.
2.  Write clear and concise defect descriptions.
3.  Include steps, expected results, and actual results.
4.  Attach logs, screenshots, or test data when possible.
5.  Verify fixes after defects are resolved.
6.  Track defect trends to identify quality risks.

------------------------------------------------------------------------

# Typical Questions

This knowledge helps answer questions such as:

-   What is defect management in software testing?
-   What is the defect lifecycle?
-   What information should be included in a defect report?
-   What is the difference between defect severity and priority?
-   How should defects be prioritized?

------------------------------------------------------------------------

# Retrieval Notes (For AI Agents)

Key takeaways:

-   Defect management tracks issues discovered during testing.
-   Defects move through a lifecycle from discovery to closure.
-   Clear documentation is essential for reproducibility.
-   Severity measures impact, while priority determines urgency.
-   Monitoring defect trends helps assess product quality and risk.
