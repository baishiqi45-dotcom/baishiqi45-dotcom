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

## Next Public Artifact

Create a downloadable template:

```text
project_clinic_startup_packet_public_template.md
```
