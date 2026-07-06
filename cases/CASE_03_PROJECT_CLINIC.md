# Case 03: 一句需求如何变成启动包、审阅清单和经验写回

## Original Intent

A non-engineer operator has an AI product, content, or workflow idea. The idea
is not ready for engineering or agent execution because source truth, tool
choice, first action, and acceptance are unclear.

## Where The Project Was Losing Control

- The request jumped from idea to tool before source evidence was clear.
- Agents could start working without knowing the owner truth boundary.
- The operator had many possible first actions but no way to choose.
- Outputs could not be reviewed because no acceptance checklist existed.
- Lessons from one attempt could not be safely reused.

## Control Method Used

Project Clinic creates a startup packet:

```text
original intent
known sources
missing sources
candidate tool route
owner truth boundary
first safe action
review checklist
outcome-delta note
```

## What Was Handed Off

Public-safe handoff shape:

- source bundle;
- capability route;
- first agent task;
- review checklist;
- outcome-delta stub;
- non-claims.

## Synthetic Teardown: Messy Request To First Safe Action

Messy request:

```text
I want an AI dashboard that turns my short-drama ideas into video tasks. Can an
agent build it?
```

Why this is not ready for coding:

- "dashboard" jumps to UI before source and acceptance are clear;
- the real first question is whether one scene can become a usable task packet;
- private scripts, screenshots, and provider state must not enter a public
  example;
- the operator needs a review checklist before asking for implementation.

Project Clinic route:

| Clinic field | Public-safe answer |
| --- | --- |
| Original intent | Reduce prompt rewrites by turning one scene into a repeatable task packet. |
| Known sources | Public templates and one invented scene. |
| Missing sources | Owner acceptance criteria and self-owned examples. |
| Candidate route | Markdown packet first; UI prototype later. |
| First safe action | Fill one Project Clinic startup packet using synthetic material. |
| Stop condition | If the packet needs private assets to make sense, do not publish it. |

The filled public-safe packet is here:
[Project Clinic creator workflow dashboard example](../examples/filled-project-clinic-creator-dashboard.md).

## How The Artifact Was Reviewed

Review asks:

1. Did the first action use the right source?
2. Did the agent stay inside the owner boundary?
3. What artifact exists now?
4. What evidence supports it?
5. What should be reused, revised, or blocked next time?

## What Became Reusable

- A non-engineer first-action decision template.
- A startup packet format.
- A writeback discipline that prevents one-off outputs from becoming fake
  system knowledge.

## Public Boundary

Do not publish:

- private owner workspace paths;
- client acceptance truth;
- runtime implementation details;
- account/provider state;
- private project assets.

Safe public material:

- blank startup packet;
- synthetic example;
- decision checklist;
- writeback note template.

## Current Public Artifacts

- [Project Clinic startup packet](../templates/project-clinic-startup-packet.md)
- [Project Clinic filled synthetic example](../examples/filled-project-clinic-creator-dashboard.md)
