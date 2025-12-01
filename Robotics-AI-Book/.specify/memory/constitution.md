<!--
---
version_change: "0.0.0 -> 1.0.0"
modified_principles: []
added_sections:
  - "Core Principles"
  - "Additional Constraints"
  - "Development Workflow"
  - "Governance"
removed_sections: []
templates_updated:
  - "`.specify/templates/plan-template.md` (pending)"
  - "`.specify/templates/spec-template.md` (pending)"
  - "`.specify/templates/tasks-template.md` (pending)"
follow_up_todos:
  - "TODO(RATIFICATION_DATE): Please provide the date this constitution was initially ratified."
---
-->
# Robotics AI Book Constitution

## Core Principles

### I. Library-First
Every feature starts as a standalone library. Libraries must be self-contained, independently testable, and have a clear purpose.

### II. CLI Interface
Every library exposes functionality via a CLI. The interface should follow a text-in/text-out protocol (stdin/args -> stdout, stderr for errors) and support both JSON and human-readable formats.

### III. Test-First (NON-NEGOTIABLE)
TDD is mandatory. The Red-Green-Refactor cycle is strictly enforced.

### IV. Integration Testing
Integration tests are required for new library contracts, contract changes, inter-service communication, and shared schemas.

### V. Observability
All components must provide structured logging for debuggability.

### VI. Versioning & Breaking Changes
All components must follow `MAJOR.MINOR.PATCH` semantic versioning.

## Additional Constraints

[SECTION_2_CONTENT]

## Development Workflow

[SECTION_3_CONTENT]

## Governance

All PRs/reviews must verify compliance with this constitution. Complexity must be justified.

**Version**: 1.0.0 | **Ratified**: 2025-12-01 | **Last Amended**: 2025-12-01