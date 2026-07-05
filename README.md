# 白子烨 | AI Product Execution Director

I work at the intersection of film direction, AI video production, agent
workflow, and non-engineer product control.

My public work is about one missing layer: turning creative intent and product
intent into work that AI coding agents, external engineers, video tools, and
human reviewers can actually execute, inspect, retake, and learn from.

> 我把导演判断、影像生产、AI coding agent 和产物验收接成一条可审查的控制链。

[Public site](https://baishiqi45-dotcom.github.io/baishiqi45-dotcom/) ·
[Methods](methods/README.md) · [Templates](templates/README.md) ·
[Cases](cases/README.md) ·
[Open a public-safe issue](https://github.com/baishiqi45-dotcom/baishiqi45-dotcom/issues/new/choose)

![AI production control loop](assets/ai-production-control-loop.svg)

## What I Am Packaging Publicly

| Public pillar | What I make concrete |
| --- | --- |
| **AI video production control** | Script intent, visual reference roles, shot/package logic, continuity locks, QA boundaries, retake notes, and low-context operator handoff. |
| **Director-style agent workflows** | Turning performance, blocking, camera, transition, asset roles, review rules, and retake targets into agent-readable work. |
| **Project Clinic for non-engineers** | Turning a messy product/workflow idea into source selection, capability route, first task packet, review checklist, and outcome-delta note. |
| **Video admission and verification** | Separating raw artifacts, static evidence, human playback, relation checks, owner seal, and final acceptance boundaries. |

## Why This Is Not A Generic Engineering Profile

I started from Beijing Film Academy photography/directing. My advantage is not
pretending to be a conventional full-stack engineer. It is translating image,
narrative, rhythm, continuity, taste, and operator reality into AI-native work
systems.

Many people can use an AI coding agent casually. The harder layer is knowing:

- what source the agent should read first;
- what a tool output is allowed to prove;
- when a generated artifact is only candidate evidence;
- how to turn a creative failure into a field-level retake;
- what should be written back as reusable method rather than fake project truth.

That is the public lane here.

## Start Here

| Need | Best first artifact |
| --- | --- |
| AI video keeps breaking continuity or taste | [AI video continuity locks](templates/ai-video-continuity-locks.md) |
| A team says "the AI output is bad" but cannot name why | [Failure-layer debug table](methods/README.md#failure-layer-debug-table) |
| A non-engineer product idea needs the right first action | [Project Clinic startup packet](templates/project-clinic-startup-packet.md) |
| A repo/workflow has many demos but no acceptance boundary | [Workflow rescue keep/kill map](templates/workflow-rescue-keep-kill-map.md) |
| A video artifact exists but nobody knows whether it is reviewable | [Video admission ladder](templates/video-admission-ladder.md) |

## Public Case Tracks

These case tracks expose method and boundaries, not private assets or final
project truth.

| Case | Public value |
| --- | --- |
| [Script to dispatchable AI video packages](cases/CASE_01_SCRIPT_TO_PACKAGES.md) | How script intent becomes visual reference roles, image evidence, package review, retake logic, and operator handoff. |
| [Synthetic script-to-package sample](cases/SYNTHETIC_SCRIPT_TO_PACKAGE_SAMPLE.md) | A complete public-safe example using an invented scene, not private script or production material. |
| [DirectorShotIR and crew-style agent work](cases/CASE_02_DIRECTORSHOTIR_CREW.md) | How one vague "AI brain" becomes role-based creative responsibility: director, art, camera, critic, QA. |
| [Project Clinic for non-engineers](cases/CASE_03_PROJECT_CLINIC.md) | How one messy request becomes a source bundle, first task packet, review checklist, and reusable lesson. |

## Public Building Blocks

These repositories are supporting slices. They are not the headline.

| Repository | Role | Public status |
| --- | --- | --- |
| [`mmi-gateway`](https://github.com/baishiqi45-dotcom/mmi-gateway) | Intake pattern for turning messy material into review-required candidate evidence. | Reference slice |
| [`codex-sidecar-subagents`](https://github.com/baishiqi45-dotcom/codex-sidecar-subagents) | Read-only advisor pattern where Codex keeps file access, local verification, and integration judgment over sidecar advice. | Reference slice |
| [`epistemic-os`](https://github.com/baishiqi45-dotcom/epistemic-os) | Claim-scope guardrails so weak evidence does not become confident release language. | Guardrail slice |
| [`netfix`](https://github.com/baishiqi45-dotcom/netfix) | Mac network rescue utility for operator downtime when agent tools cannot connect. | Practical utility |

## How I Work

- **Case before tool:** a tool is worth naming only when it changes a real
  production, product, or verification decision.
- **Evidence before claim:** model output, sidecar advice, dry-runs, screenshots,
  and fixtures stay candidate material until the right owner accepts them.
- **Director judgment into operator language:** taste, continuity, rhythm, and
  camera intent become inspectable instructions, not vague prompts.
- **Boundary first:** private project material stays in its owner workspace. The
  public layer shows method, synthetic examples, templates, and review contracts.

## Collaboration

Useful conversations usually start with one of these:

- an AI video or short-drama workflow that keeps failing at continuity, rhythm,
  asset control, or review;
- a non-engineer product idea that needs a source/tool/agent execution route
  before hiring engineers or opening a large build;
- an AI workflow with many artifacts but no reliable acceptance boundary.

Use the issue templates in this repository for public, method-level discussion.
Do not upload private scripts, raw media, provider screenshots, account state,
customer material, or final project acceptance truth to public issues.
