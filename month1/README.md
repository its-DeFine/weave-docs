# WEAVE Month 1 Overview

Month 1 is the runtime-first version of WEAVE. The goal is to get to a working application path quickly, using the agent as the main operator of the lifecycle and using existing Livepeer workloads as the substrate.

This is the low-hanging-fruit path. It keeps operating costs low, lets the first application become usable, and aligns the runtime with orchestrator benefit.

The current delivery target is **Friday 2026-05-01**. If needed, the delivery window can slip by one additional week to **Friday 2026-05-08**.

## What Month 1 delivers

### M1-D1. The WEAVE tool

The WEAVE tool is the open-source agentic capability layer. It should be able to support the application lifecycle end to end.

That means it should be able to:
- study existing Livepeer pipelines and understand what they can do
- synthesize available capabilities into reusable primitives where useful
- identify viable applications from those primitives
- engineer applications on top of existing Livepeer workloads
- QA those applications
- generate and run outreach workflows
- collect KPI and feedback data
- support iteration from the resulting evidence

In practical terms, Month 1 should leave behind a real open-source tool, not a placeholder shell, with tests or evidence that show the initial lifecycle capabilities actually work.

### M1-D2. The WEAVE runtime

The WEAVE runtime is the deployed realization of the tool. In Month 1, it is an operated runtime managed by the WEAVE team, not yet a mature third-party marketplace where external users submit intents and receive incentives.

Month 1 should deliver:
- a deployed runtime
- a website or hosted runtime surface
- at least one initial application that is usable and able to receive users
- authentic outreach run by the agent
- a payment or monetization path inside the runtime, where applicable

The first use of the incentive packets in Month 1 is to power the WEAVE runtime itself: hosting, agent operation, outreach, infrastructure, and the costs needed to keep the first application running. Broader third-party user incentives should be shaped after the first runtime proof is clearer.

### M1-D3. Public KPI reporting

Month 1 should also produce public reporting on what the runtime is actually doing.

That reporting should cover:
- what applications were researched and selected
- what was built
- what passed QA
- what outreach happened
- what initial usage, test usage, payment-path, or monetization-path evidence exists
- what changed based on the resulting evidence

Month 1 does not promise a specific usage volume. The commitment is that the runtime and initial application are live, able to receive users, actively marketed or distributed by the agent, and reported honestly.

## Success criteria

Month 1 review should be based on clear evidence, not implied demand volume.

The success criteria are:
- the open-source WEAVE tool repo is public and includes setup and architecture documentation
- the tool demonstrates an initial lifecycle path for the selected first application
- the hosted WEAVE runtime is live
- the initial application is accessible and able to receive users
- QA evidence exists for the initial application and runtime path
- outreach evidence exists for the agent-operated distribution path
- the public KPI/reporting surface is available
- reporting distinguishes measured evidence from plans or next steps
- an evidence pack is available for Rick and Mehrdad review

## Why this version of Month 1 is better

This version is better because it concentrates effort into a real runtime instead of splitting attention across a heavier structure.

It gives WEAVE:
- a faster path to a working application
- a lower operating cost because the agent can act as a lean operating team
- a direct path from a usable application and active outreach to orchestrator benefit
- a public story that is easier to understand and easier to verify

For the economics model behind that claim, see [Orchestrator Economics](orchestrator-economics.md).
For the public accountability boundary, see [Program Transparency](program-transparency.md).

## Governance and timing

WEAVE is maintained by Atumera LLC. Atumera does not extract profit from operating the runtime. The goal is to route value into the runtime and toward orchestrator benefit, not to create an Atumera profit-taking layer on top.

Month 2 is intentionally not fixed yet. Month 1 will be reviewed first, and Month 2 deliverables will be set after that review.

## Related document

- [Application Lifecycle Summary](app-lifecycle.md)
- [Orchestrator Economics](orchestrator-economics.md)
- [Program Transparency](program-transparency.md)
