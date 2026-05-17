# Metadata Specification

Every `.md` file in this knowledge base includes YAML frontmatter with the following fields:

## Required Fields

| Field | Type | Description |
|-------|------|-------------|
| `domain` | string | Top-level category (e.g., `natural-sciences`) |
| `subdomain` | string | Specific field name (e.g., `physics`) |
| `title` | string | Human-readable title |
| `description` | string | One-line summary of the field |
| `created` | date | Date created (YYYY-MM-DD) |
| `updated` | date | Last updated (YYYY-MM-DD) |

## Optional Fields

| Field | Type | Description |
|-------|------|-------------|
| `tags` | list[string] | Keywords for cross-domain search |
| `prerequisites` | list[string] | Related domains that help understanding |
| `related` | list[string] | Paths to related knowledge files |
| `difficulty` | string | `introductory`, `intermediate`, `advanced` |
| `completeness` | string | `draft`, `developing`, `comprehensive` |

## Example

```yaml
---
domain: natural-sciences
subdomain: physics
title: "Physics"
description: "The fundamental science of matter, energy, and their interactions"
created: 2026-05-15
updated: 2026-05-15
tags: [matter, energy, forces, spacetime, quantum, relativity]
prerequisites: [mathematics]
related: [natural-sciences/chemistry, engineering-technology/electrical-engineering]
difficulty: introductory
completeness: comprehensive
---
```

## Cross-Reference Format

Links between knowledge files use relative paths:
```markdown
See also: [Chemistry](../natural-sciences/chemistry.md)
```
