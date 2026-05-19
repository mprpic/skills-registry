---
title: autofix-skills
---

<!-- Auto-generated from registry.yaml. Do not edit directly. -->


# autofix-skills

Claude Code plugin for the Jira autofix pipeline. Provides orchestrator skills, agent prompt files, and deterministic Python scripts for automated bug fixing, CVE remediation, and ticket triage. Designed to run inside a Claude Code container as part of a CI pipeline.

!!! info "Plugin Details"

    - **Version**: 0.1.0
    - **Author**: opendatahub-io
    - **License**: Apache-2.0
    - **Category**: [Development Tools](../../categories/development-tools.md)
    - **Repository**: [opendatahub-io/autofix-skills](https://github.com/opendatahub-io/autofix-skills)
    - **Tags**: <span class="tag-pill">autofix</span> <span class="tag-pill">jira</span> <span class="tag-pill">cve</span> <span class="tag-pill">bug-fixing</span> <span class="tag-pill">triage</span> <span class="tag-pill">pipeline</span> <span class="tag-pill">ci-cd</span>

## Skills

| Skill | Description | Invocable |
|-------|-------------|-----------|
| [`/autofix-resolve`](autofix-resolve.md) | Orchestrate end-to-end bug fixing via implement and review agent loop (max 3 iterations) | :material-check: |
| [`/autofix-cve-resolve`](autofix-cve-resolve.md) | CVE remediation across multiple repos with state-machine dispatch | :material-check: |
| [`/autofix-triage`](autofix-triage.md) | Assess bug tickets for AI autofix readiness (ready/needs_info/not_fixable) | :material-check: |
| [`/autofix-research`](autofix-research.md) | Investigate spike tickets with no associated repository | :material-check: |

## Installation

```bash
/plugin install autofix-skills@opendatahub-skills
```
