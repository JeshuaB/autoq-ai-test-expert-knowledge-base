---
agent_use: Testing workflow guidance, reasoning about testing tasks,
  test planning and execution support
domain: Testing Fundamentals
keywords:
- test process
- istqb test process
- test planning
- test analysis
- test design
- test execution
- defect reporting
methodology_sources:
- ISTQB Foundation Level
- ISTQB Agile Testing
- Risk Based Testing Practices
- Quality Engineering Principles
related_topics:
- ISTQB Testing Principles
- Requirement Analysis for Testing
- Deriving Test Conditions
- Risk Based Testing
title: ISTQB Test Process
version: 1
---

# ISTQB Test Process

## Concept

The ISTQB Test Process defines the structured workflow used to plan,
design, implement, execute, and evaluate testing activities. It provides
a systematic approach that helps testing teams ensure that testing is
organized, traceable, and aligned with project risks.

The process ensures that testing activities are not performed randomly
but follow a logical sequence that supports software quality and risk
reduction.

The standard ISTQB test process consists of the following activities:

1.  Test Planning
2.  Test Monitoring and Control
3.  Test Analysis
4.  Test Design
5.  Test Implementation
6.  Test Execution
7.  Test Completion

These activities may overlap and iterate during development, especially
in Agile environments.

The test process forms the **operational backbone of professional
software testing** and guides how testers move from requirements to
executed tests and reported defects.

------------------------------------------------------------------------

## Detailed Explanation

Testing is not a single activity but a series of coordinated steps that
transform requirements into executed tests and quality insights.

The ISTQB test process provides a structured framework for organizing
these steps.

Each activity within the process serves a specific purpose:

-   **Test Planning** defines scope, strategy, and resources.
-   **Test Monitoring and Control** ensures testing stays on track.
-   **Test Analysis** identifies what should be tested.
-   **Test Design** determines how testing should be performed.
-   **Test Implementation** prepares test cases and environments.
-   **Test Execution** runs tests and records results.
-   **Test Completion** evaluates testing outcomes and documents lessons
    learned.

In modern Agile environments, these activities may occur continuously
and iteratively rather than sequentially.

For example:

-   test analysis often occurs during backlog refinement
-   test design may happen during sprint planning
-   test execution occurs continuously during development

Despite these variations, the conceptual structure of the test process
remains valid.

Understanding the test process enables consultants to organize testing
activities efficiently and maintain clear traceability between
requirements, tests, and defects.

------------------------------------------------------------------------

## Key Process Activities

### 1. Test Planning

Test planning defines the overall testing approach for a project or
iteration.

Typical planning decisions include:

-   testing scope
-   testing objectives
-   test strategy
-   required environments
-   resource allocation
-   schedule and milestones
-   risk assessment

**Outputs**

-   Test strategy or test plan
-   Risk analysis
-   Testing schedule

**Implications**

Good planning ensures that testing focuses on areas that matter most to
the business.

------------------------------------------------------------------------

### 2. Test Monitoring and Control

Test monitoring tracks the progress of testing activities, while test
control adjusts the plan when deviations occur.

Examples of monitoring metrics:

-   test case execution progress
-   defect discovery rates
-   test coverage
-   test pass/fail rates

Test control may involve:

-   adjusting priorities
-   adding additional tests
-   reallocating resources
-   modifying schedules

Monitoring and control ensure that testing remains aligned with project
goals and risk priorities.

------------------------------------------------------------------------

### 3. Test Analysis

Test analysis determines **what needs to be tested**.

This activity identifies test conditions based on the test basis.

Common test bases include:

-   requirements
-   user stories
-   architecture documentation
-   business rules
-   system interfaces

Test analysis results in the identification of **test conditions**,
which describe specific aspects of the system that require validation.

Example:

Requirement: A user must be able to reset their password.

Possible test conditions:

-   password reset with valid email
-   password reset with invalid email
-   expired reset link
-   multiple reset requests

------------------------------------------------------------------------

### 4. Test Design

Test design determines **how testing will be performed**.

During this phase, testers convert test conditions into structured test
cases using test design techniques.

Examples of techniques:

-   equivalence partitioning
-   boundary value analysis
-   decision tables
-   state transition testing

Outputs of test design include:

-   detailed test cases
-   expected results
-   traceability to requirements

------------------------------------------------------------------------

### 5. Test Implementation

Test implementation prepares tests for execution.

Activities include:

-   organizing test cases into test suites
-   preparing test data
-   configuring test environments
-   developing automated test scripts
-   preparing test execution schedules

Outputs:

-   executable test suites
-   automated test scripts
-   prepared environments

------------------------------------------------------------------------

### 6. Test Execution

Test execution involves running the prepared tests and recording
results.

During execution:

-   tests are executed manually or automatically
-   results are compared against expected outcomes
-   defects are logged when discrepancies occur

Defect reports typically include:

-   reproduction steps
-   observed behavior
-   expected behavior
-   severity and priority

Execution also generates valuable information about system quality and
defect trends.

------------------------------------------------------------------------

### 7. Test Completion

Test completion evaluates whether testing objectives have been achieved.

Activities include:

-   verifying exit criteria
-   summarizing test results
-   documenting defects and unresolved issues
-   capturing lessons learned

Typical outputs:

-   test summary reports
-   quality assessments
-   improvement recommendations

Test completion ensures knowledge gained during testing contributes to
future projects.

------------------------------------------------------------------------

## When to Use the Test Process

The test process should be applied in most software development
projects, including:

-   Agile development environments
-   enterprise software projects
-   system integration programs
-   digital product development
-   platform modernization initiatives

Even in Agile environments where documentation is lighter, the
underlying activities of the test process still occur.

Applying the process helps ensure:

-   testing activities remain structured
-   requirements are traceable to tests
-   testing effort focuses on business risk

------------------------------------------------------------------------

## When NOT to Apply the Process Rigidly

The test process should not be applied as a rigid waterfall sequence in
every context.

Examples where flexibility is required:

-   Agile development cycles
-   exploratory testing sessions
-   rapid prototyping
-   continuous integration environments

In these contexts, activities still exist but occur more iteratively.

For example:

Test analysis and design may occur simultaneously during backlog
refinement.

------------------------------------------------------------------------

## Practical Example

Consider an e-commerce checkout system.

Applying the test process:

**Test Planning**

The team identifies critical risk areas:

-   payment processing
-   order calculation
-   shipping logic

These areas receive deeper testing.

**Test Analysis**

Test conditions are derived from requirements such as:

-   successful payment processing
-   invalid payment details
-   network interruption during checkout

**Test Design**

Test cases are created using boundary value analysis and decision
tables.

**Test Implementation**

Test suites are created and automated API tests are implemented.

**Test Execution**

Tests are executed in staging environments and defects are reported.

**Test Completion**

Testing results are summarized and quality risks are documented before
release.

------------------------------------------------------------------------

## Common Mistakes

Typical mistakes when applying the test process include:

-   skipping test analysis and designing tests directly from
    requirements
-   insufficient traceability between tests and requirements
-   inadequate test planning
-   poor defect documentation
-   ignoring test monitoring metrics
-   delaying test design until late development stages

These mistakes often lead to inefficient testing and increased project
risk.

------------------------------------------------------------------------

## Practical Guidelines

Consultants can apply the test process effectively by following these
practices:

1.  Start testing activities early in the development lifecycle.
2.  Maintain traceability between requirements, test conditions, and
    test cases.
3.  Use risk-based prioritization to guide testing effort.
4.  Continuously monitor testing progress using meaningful metrics.
5.  Adapt the process to Agile workflows rather than enforcing rigid
    phases.
6.  Capture lessons learned during test completion activities.

------------------------------------------------------------------------

## Typical Questions

This knowledge helps answer questions such as:

-   What is the ISTQB test process?
-   What are the phases of the testing lifecycle?
-   What is the difference between test analysis and test design?
-   What happens during test execution?
-   What is test completion in ISTQB?

------------------------------------------------------------------------

## Retrieval Notes (For AI Agents)

Key takeaways:

-   The ISTQB test process organizes testing activities into structured
    phases.
-   The process includes planning, monitoring, analysis, design,
    implementation, execution, and completion.
-   Test analysis identifies what to test; test design defines how to
    test it.
-   Test implementation prepares environments and test suites.
-   Test execution runs tests and records results.
-   Test completion evaluates outcomes and captures lessons learned.
