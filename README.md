# 白子烨 | AI 产品执行导演

Beijing Film Academy photography/directing background. I design AI-native
production control systems that help a non-engineer operator turn rough intent
into source selection, agent handoff, production packages, artifact review, and
lessons that can be reused.

> 我更关心一件事：把导演判断、影像生产、AI coding agent 和产物验收接成一条可审查的控制链，而不是把一堆 AI 工具包装成产品。

![AI production control loop](assets/aikb-control-loop.svg)

## Current Focus

| Line | What it means |
| --- | --- |
| **AI video production control** | From reviewed script to visual references, image evidence, shot packages, QA boundaries, retake notes, and low-context operator handoff. |
| **Director-style agent workflows** | Turning story intent into performance, blocking, camera, transition, asset roles, review rules, and field-level retake responsibility. |
| **Non-engineer AI product control** | Helping an operator move from intent to source/tool/research selection, owner-workspace handoff, artifact verification, and outcome-delta writeback. |
| **Video admission and verification** | Keeping weak video evidence, fake current state, fake human review, and overconfident model claims out of production decisions. |

## Public Case Directions

These are the public-safe case directions I am shaping from private and
project-owned work. They expose methods and boundaries, not private assets.

- **From script to dispatchable AI video packages**: a post-script production
  control chain for AI video work.
- **Turning one AI brain into a crew**: DirectorShotIR and role-based agent
  collaboration for performance, camera, assets, review, and retake.
- **Why AI short drama fails even when fields are complete**: watchability,
  failure patterns, and retake judgment.
- **Project Clinic for non-engineers**: turning a messy brief into a source
  bundle, startup packet, review checklist, and outcome-delta note.
- **From watching videos to reusable director knowledge**: a local, copyright
  cautious video-knowledge absorption protocol.

See [Public Packaging Playbook](PUBLIC_PACKAGING_PLAYBOOK.md) for the website
structure, case-study format, first content plan, and publishing boundaries.

## Building Blocks

These repositories are not the headline. They are small public slices behind the
larger control method.

| Repository | Role in the system | Status |
| --- | --- | --- |
| [`mmi-gateway`](https://github.com/baishiqi45-dotcom/mmi-gateway) | Intake pattern for turning messy material into review-required candidate evidence. | Reference slice |
| [`codex-sidecar-subagents`](https://github.com/baishiqi45-dotcom/codex-sidecar-subagents) | Read-only advisor pattern where Codex keeps file access, local verification, and final judgment. | Reference slice |
| [`epistemic-os`](https://github.com/baishiqi45-dotcom/epistemic-os) | Claim-scope guardrails so weak evidence does not become confident release language. | Guardrail slice |
| [`netfix`](https://github.com/baishiqi45-dotcom/netfix) | Mac network rescue utility for operator downtime when agent tools cannot connect. | Practical utility |

## How I Work

- **Case before tool**: a tool is only worth naming when it helped a real
  production, product, or verification problem.
- **Evidence before claim**: model output, sidecar advice, dry-runs, and fixtures
  stay candidate material until the right owner accepts them.
- **Director judgment into operator language**: taste, continuity, rhythm, and
  camera intent have to become inspectable instructions, not vague prompts.
- **Boundary first**: AIKB organizes knowledge, routing, capability selection,
  handoff, verification contracts, and lesson writeback. It does not own runtime
  execution, provider orchestration, private project assets, billing, or final
  artifact acceptance.

## Collaboration

Useful conversations usually start with one of these:

- an AI video or short-drama project that keeps failing at continuity, rhythm,
  asset control, or review;
- a non-engineer product idea that needs a source/tool/agent execution route
  before hiring engineers or opening a large build;
- an AI workflow that produces many artifacts but no reliable acceptance
  boundary.

If the question is about a public slice, open an issue in the relevant
repository. If it is about a private project, keep project material in its owner
workspace and discuss only the method, boundary, and review contract publicly.
