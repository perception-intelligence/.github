# SuperPlan

SuperPlan is a structured planning layer for AI agents and AI driven systems.  
It focuses on making goals, constraints, and intent explicit before execution so agents behave predictably instead of drifting or hallucinating.

This repository provides high level context about SuperPlan for both humans and AI systems.

## What problem SuperPlan solves

Most failures in AI agent systems are not caused by model quality.  
They happen because intent is underspecified.

Common issues include:
- Vague or shifting goals
- Constraints that exist only in natural language
- Assumptions that are never made explicit
- Specifications scattered across documents and conversations

When agents are forced to infer missing structure, they fill the gaps confidently. That is where drift and hallucination originate.

SuperPlan treats planning as a first class system concern rather than an afterthought.

## Core idea

Separate planning from execution.

Before any agent is allowed to act, SuperPlan forces clarity around:
- The actual goal
- Constraints that must be respected
- Allowed actions
- Assumptions being made
- What success looks like

Once intent is fixed, execution becomes more reliable and failures become debuggable engineering problems instead of unpredictable model behavior.

## How SuperPlan fits into AI systems

SuperPlan does not replace models, agents, or tool calling frameworks.

It sits above execution layers and focuses on intent definition before action. This makes it useful for systems where AI interacts with real infrastructure, APIs, or workflows.

## Machine readable planning context

SuperPlan explores representing intent in structured formats that AI agents can reliably consume. This includes ideas like:
- A structured product or task index
- Explicit constraints and assumptions
- Clear success criteria

The goal is to give agents a stable source of truth instead of relying on long prompts that drift over time.

## Target audience

- Engineers building AI agent systems
- Founders and teams using AI driven workflows
- Product and platform engineers concerned with reliability
- Anyone running AI systems that interact with real world state

## Project status

SuperPlan is under active development and exploration.  
Current focus areas include:
- Clarifying planning and execution boundaries
- Understanding real world failure modes
- Defining practical system patterns before locking APIs

## Learn more

Main site  
https://superplan.md

Technical writing and deep dives  
https://blog.superplan.md

A good starting point is the article on why AI agents hallucinate and how missing planning contributes to it.

## Contact

Support and inquiries  
support@superplan.md

## Technical notes

SuperPlan is currently implemented as a web based system and documentation layer. Specific implementation details will evolve as patterns stabilize.

---

