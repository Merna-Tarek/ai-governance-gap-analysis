# AI Governance Gap Analysis: Healthcare AI Diagnostic Tool

A policy gap analysis that compares a company's existing security policies against requirements from Microsoft's Responsible AI Standard, then turns the findings into a prioritized remediation backlog.

> Completed as part of the Coursera course *Governance and Compliance Management*. The company and scenario are fictional.

## Problem
A fictional healthcare technology company wants to launch an AI diagnostic support tool. Its existing Information Security Policy was written for traditional IT systems. Does it cover the risks of AI?

## What I did
- Compared two existing policies (incident management and change control) against three Responsible AI requirements: accountability, human oversight, and transparency.
- Documented each gap in a gap analysis table, with the policy section, current state, severity, owner, and target date.
- Rated each gap as Critical, Significant, or Advisory.
- Wrote three prioritized backlog items that are ready to load into Azure DevOps.

## Results

| Priority | Gap | Severity |
|---|---|---|
| 1 | No AI incident response plan | Critical |
| 2 | No human review or override for high-stakes AI decisions | Critical |
| 3 | No documentation standard for AI purpose, limits, and training data | Significant |

## Key lesson
Old IT security policies do not cover AI-specific harms, such as biased or unsafe outputs. Patient safety risks should be fixed before documentation improvements.

## What I would add next
From my SOC experience, I would add AI-specific monitoring and alerting to the incident response plan, so unsafe model behavior is detected quickly.

## Files
- [Remediation_Analysis.pdf](Remediation_Analysis.pdf)
