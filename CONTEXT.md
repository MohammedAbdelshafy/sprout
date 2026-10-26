---
type: repository
status: candidate
owner_repo: MohammedAbdelshafy/sprout
product_name: Sprout Task Assistant
source_of_truth: https://github.com/MohammedAbdelshafy/sprout
---

# Sprout Task Assistant CONTEXT

One job: explore a task-running assistant that can break work into steps, call configured tools, and check its results. Treat it as experimental until current tests and runtime show otherwise.

## Inputs
- Capabilities and caveats: [README](README.md)
- Agent definitions and runtime: inspect the paths linked from the README.
- Project status: current repository default branch and tests.

## Process
1. Describe the requested task and its permitted scope.
2. Inspect the available tools and configured execution limits.
3. Plan the work in small steps.
4. Run a step only after its inputs and permissions are clear.
5. Verify the result and keep failures visible.
6. Record lessons only when there is evidence the proposed improvement worked.

## Output
A proposed plan, task result and verification evidence for the configured workflow.

## Check
Run the project's actual test suite before claiming an improvement. Do not describe recursive delegation, automatic learning or autonomous execution as reliable production behavior without current, reproducible evidence.
