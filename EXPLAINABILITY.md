## Decision and Reasoning

IssueMedic decides whether the project exposes recognizable issue-management or template artifacts. If none are found, it reports a readiness gap and recommends adding issue templates or guidance.

## Inputs and Data Sources

It uses filenames containing issue or template signals in the inspected repository. The decision is based on repository-visible evidence only.

## Limits and Constraints

It cannot assess the quality of existing issue templates or prove that GitHub issue forms are configured outside the submitted files. Platform settings not present in the repository are not observed.
