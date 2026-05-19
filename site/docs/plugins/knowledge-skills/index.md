---
title: knowledge-skills
---

<!-- Auto-generated from registry.yaml. Do not edit directly. -->


# knowledge-skills

Autonomous knowledge management skills for keeping AI context files (CLAUDE.md, AGENTS.md) up to date. Scans merged PRs, extracts relevant knowledge using parallel agents, and proposes updates as a git-apply-able patch for human review. Supports GitHub and GitLab.

!!! info "Plugin Details"

    - **Version**: 0.1.0
    - **Author**: opendatahub-io
    - **License**: Apache-2.0
    - **Category**: [Documentation](../../categories/documentation.md)
    - **Repository**: [opendatahub-io/knowledge-skills](https://github.com/opendatahub-io/knowledge-skills)
    - **Tags**: <span class="tag-pill">knowledge</span> <span class="tag-pill">context</span> <span class="tag-pill">claude-md</span> <span class="tag-pill">agents-md</span> <span class="tag-pill">pr-analysis</span> <span class="tag-pill">automation</span>

## Skills

| Skill | Description | Invocable |
|-------|-------------|-----------|
| [`/knowledge.repo`](knowledge.repo.md) | Scan merged PRs and propose updates to AI context files (CLAUDE.md, AGENTS.md) as a git-apply-able patch | :material-check: |

## Installation

```bash
/plugin install knowledge-skills@opendatahub-skills
```
