# WEAVE Application Lifecycle Summary

WEAVE is built around a six-stage application lifecycle.

The important point is that this lifecycle is primarily operated by the agent. Humans can remain in the loop for steering, review, and approval-gated actions, but the runtime is meant to perform the actual work of researching, building, QAing, distributing, reading feedback, and iterating.

## Stage 1. Research and analysis

Purpose: understand the Livepeer capability surface and the market opportunity surface well enough to identify viable applications.

This includes:
- mapping existing pipelines and what they can do
- assessing quality, uptime, pricing, operators, and operational reliability
- synthesizing available capabilities into reusable primitives where useful
- identifying what applications become possible from those primitives
- running competitor analysis and pricing analysis once a serious concept exists

Primitive note:
- a stacked primitive layers multiple pipelines in the same path or modality
- a coordinated primitive uses multiple pipelines together across different paths or modalities inside the same application behavior
- one example is a real-time media pipeline combined with an LLM such as Gemma, where the LLM interprets user intent and turns it into prompts or parameters for the media pipeline
- another example is an LLM router that combines multiple LLM pipelines and sends a request to the most appropriate model based on request type, cost, quality, or availability

Synthesis of two or more pipelines is part of the broader WEAVE direction, but it is not necessarily a Month 1 completion requirement. Month 1 focuses on proving the runtime and first application path from available capability.

## Stage 2. Engineering and commercial integration

Purpose: compose the chosen capabilities into a working application and wire the runtime, payment, monetization, or orchestrator flow where applicable.

This includes:
- using the relevant existing pipelines correctly
- implementing runtime behavior and application assembly
- implementing user payment, monetization, or orchestrator routing where applicable
- connecting the runtime to the hosted or documented product surface as needed

## Stage 3. QA and readiness

Purpose: test the built application, identify issues, and determine whether it is ready for user exposure.

This includes:
- functional QA
- integration QA
- payment-flow QA
- failure-case QA
- readiness judgment

## Stage 4. Outreach and distribution

Purpose: put the application in front of potential users through a repeatable workflow.

This includes:
- creating the outreach workflow
- having the agent operate that workflow as the primary actor
- advertising or distributing to target consumers in a controlled way
- keeping human review or approval only where a boundary is intentionally retained

## Stage 5. KPI, feedback, and interpretation

Purpose: read market truth from initial usage, test usage, public KPIs, analytics, and customer responses.

This includes:
- tracking public KPIs
- collecting analytics and customer feedback
- interpreting whether the problem is product, market, pricing, onboarding, quality, or positioning

## Stage 6. Iteration

Purpose: improve or redirect the product based on real-world evidence.

This includes:
- making engineering changes
- re-QAing the changed system
- returning to outreach or earlier stages as needed
- rejecting, pausing, or reframing when evidence justifies

## Tool versus runtime

This distinction matters:
- the WEAVE tool is the open-source agentic operating layer for Livepeer applications and runs the agents that take a product through the lifecycle stages
- the WEAVE runtime is the hosted deployment of that tool, where those agents operate one initial usable application, produce evidence, and expose public reporting

The tool and the runtime are not two unrelated products. The runtime is the live expression of the tool.
