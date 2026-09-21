# IssueMedic

> Portable agent for diagnosing missing or unclear issue-management guidance in repositories.

## What it does

IssueMedic inspects repository structure for recognizable issue-management templates or guidance. It helps projects expose a clearer path for reporting bugs, requests, and other maintenance work.

### Diagnostic fingerprint

**Issue workflow evidence → maintainability signal → finding → recommendation**

## Why this agent is distinct

IssueMedic focuses on the interface between a codebase and the humans maintaining it. It does not evaluate whether individual issues are good or bad. It asks whether the repository provides visible structure for issue reporting.

## Workflow

```text
Repository
    ↓
Template / guidance detector
    ↓
Issue-workflow rule
    ↓
Evidence-backed finding
    ↓
Maintenance improvement plan
```

## Verification

Includes:
- passport metadata for OpenGAP
- issue-focused fixture
- SOUL and explainability contracts
- OpenAI / CrewAI / Claude Code / Lyzr adapters
- adapter verification tests

OpenGAP validation and all four exports have been exercised successfully.

## Design principle

**A repository is also a collaboration surface.** IssueMedic looks for evidence that this surface has a usable entry point for contributors and maintainers.

## Medic family

IssueMedic is a focused member of the Medic series, sharing a portable contract while preserving a distinct repository-maintenance concern.