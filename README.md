# 白子烨 / Bai Ziye

Film-trained AI production control for AI video, agent handoff, and
non-engineer product work: 4 public-safe case tracks, 6 copy-ready templates,
and issue routes that start from the failure.

![Copy-ready public method preview](assets/method-preview-strip.png)

I translate director judgment into source selection, AI video shot packages,
agent handoff, retake gates, artifact review, and lesson writeback for
non-engineer operators.

我把导演判断、影像生产、AI coding agent 和产物验收接成一条可审查的控制链。

[Public site](https://baishiqi45-dotcom.github.io/baishiqi45-dotcom/) ·
[Start from the failure](#start-from-the-failure) ·
[Copy templates](templates/README.md) · [Read cases](cases/README.md) ·
[Methods](methods/README.md) · [Examples](examples/README.md) ·
[Roadmap](ROADMAP.md) ·
[Changelog](CHANGELOG.md) ·
[Contributing](CONTRIBUTING.md) ·
[License](LICENSE) ·
[Open a public-safe issue](https://github.com/baishiqi45-dotcom/baishiqi45-dotcom/issues/new/choose)

[![GitHub Pages](https://img.shields.io/badge/public_site-live-245d4f)](https://baishiqi45-dotcom.github.io/baishiqi45-dotcom/)
[![Methods](https://img.shields.io/badge/methods-public_library-2d5f8f)](methods/README.md)
[![Templates](https://img.shields.io/badge/templates-ready_to_copy-a47526)](templates/README.md)
[![License: MIT](https://img.shields.io/badge/license-MIT-171717)](LICENSE)

## Start From The Failure

| If this is the failure | Start here | Copy this |
| --- | --- | --- |
| AI video shots look fine alone but break as a sequence | [Filled synthetic shot package](cases/SYNTHETIC_SCRIPT_TO_PACKAGE_SAMPLE.md) | [AI video continuity locks](templates/ai-video-continuity-locks.md) |
| A director note like "make it oppressive" cannot become agent work | [DirectorShotIR teardown](cases/CASE_02_DIRECTORSHOTIR_CREW.md#synthetic-teardown-director-note-to-agent-task) | [DirectorShotIR field card](templates/directorshotir-field-card.md) |
| A non-engineer product idea is too messy to code or hire against | [Project Clinic teardown](cases/CASE_03_PROJECT_CLINIC.md#synthetic-teardown-messy-request-to-first-safe-action) | [Project Clinic startup packet](templates/project-clinic-startup-packet.md) |
| A workflow has demos, screenshots, reports, and no current truth | [Workflow rescue map](templates/workflow-rescue-keep-kill-map.md) | [Outcome-delta writeback note](templates/outcome-delta-writeback-note.md) |
| A video artifact exists but nobody knows if it is reviewable | [Video admission ladder](templates/video-admission-ladder.md) | [AI video continuity locks](templates/ai-video-continuity-locks.md) |

The fastest route is: read one filled example, copy one blank template, fill
only public-safe or owner-approved material, then open an issue only if the
question can be discussed without private assets.

## What You Can Copy

| Public surface | Use it for | Start |
| --- | --- | --- |
| **AI video continuity locks** | Character, space, prop, action, and emotion continuity before more generation spend. | [Template](templates/ai-video-continuity-locks.md) |
| **DirectorShotIR field card** | Turning performance, blocking, camera, transition, asset roles, review rules, and retake targets into agent-readable work. | [Template](templates/directorshotir-field-card.md) |
| **Project Clinic startup packet** | Turning a messy product/workflow idea into source selection, capability route, first task packet, and review checklist. | [Template](templates/project-clinic-startup-packet.md) |
| **Video admission ladder** | Separating raw artifacts, static evidence, playback, relation checks, owner seal, and final acceptance boundaries. | [Template](templates/video-admission-ladder.md) |
| **Workflow rescue map** | Sorting source, candidate, fixture, report, accepted, and deprecated layers when a project is already messy. | [Template](templates/workflow-rescue-keep-kill-map.md) |
| **Outcome-delta writeback note** | Recording what changed, what was verified, and what can become reusable method. | [Template](templates/outcome-delta-writeback-note.md) |

## From Film Judgment To Agent Work

Beijing Film Academy photography/directing training gave me image, narrative,
rhythm, continuity, and field judgment. Four months of intense AI coding and
agent work turned that judgment into execution surfaces: what source an agent
should read, what a tool output is allowed to prove, when a visual artifact
needs a retake, and what can be written back as reusable method.

| Director signal | Agent-readable packet | Review rule |
| --- | --- | --- |
| "Make it oppressive" | Blocking, lens distance, negative space, motion speed, sound cue, and art constraint. | Retake only the field that fails the intended pressure. |
| "This sequence feels fake" | Character, space, prop, action, and emotion locks across the shot package. | Reject clips that work alone but break relation continuity. |
| "I want to build this idea with AI" | Source bundle, capability route, first safe action, review checklist, and writeback rule. | Start with the smallest artifact that can prove or disprove the route. |

## Control Loop

Intent becomes source selection, then agent handoff, then artifact review, then
bounded retake or reusable lesson writeback.

![AI production control loop](assets/ai-production-control-loop.svg)

## Public Case Tracks

These case tracks expose method and boundaries, not private assets or final
project truth.

| Case | Public value |
| --- | --- |
| [Script to dispatchable AI video packages](cases/CASE_01_SCRIPT_TO_PACKAGES.md) | How script intent becomes visual reference roles, image evidence, package review, retake logic, and operator handoff. |
| [Filled synthetic script-to-package sample](cases/SYNTHETIC_SCRIPT_TO_PACKAGE_SAMPLE.md) | A complete public-safe example using an invented scene, not private script or production material. |
| [DirectorShotIR and crew-style agent work](cases/CASE_02_DIRECTORSHOTIR_CREW.md) | How one vague "AI brain" becomes role-based creative responsibility: director, art, camera, critic, QA. |
| [Project Clinic for non-engineers](cases/CASE_03_PROJECT_CLINIC.md) | How one messy request becomes a source bundle, first task packet, review checklist, and reusable lesson. |

## Use This Repo When

Use this repository as a public reference for:

- AI video continuity review before more generation spend;
- director-style agent task packets instead of vague prompts;
- non-engineer project startup packets before hiring or coding;
- video admission gates that stop weak evidence from becoming final claims;
- public-safe templates you can copy into private owner workspaces.

If a template or synthetic example saves you a false start, a star is a useful
bookmark for finding the public control language again.

## How I Work

- **Case before tool:** a tool is worth naming only when it changes a real
  production, product, or verification decision.
- **Evidence before claim:** model output, sidecar advice, dry-runs, screenshots,
  and fixtures stay candidate material until the right owner accepts them.
- **Director judgment into operator language:** taste, continuity, rhythm, and
  camera intent become inspectable instructions, not vague prompts.
- **Boundary first:** private project material stays in its owner workspace. The
  public layer shows method, synthetic examples, templates, and review contracts.

## Public Boundary And Collaboration

Useful conversations usually start with one of these:

- an AI video or short-drama workflow that keeps failing at continuity, rhythm,
  asset control, or review;
- a non-engineer product idea that needs a source/tool/agent execution route
  before hiring engineers or opening a large build;
- an AI workflow with many artifacts but no reliable acceptance boundary.

Use the issue templates in this repository for public, method-level discussion.
Do not upload private scripts, raw media, provider screenshots, account state,
customer material, or final project acceptance truth to public issues.

Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request. The
accepted contribution types are intentionally narrow: synthetic examples,
template clarity, broken-link fixes, and public-safe method language.

## Supporting Repos

These repositories are supporting slices. This profile repo should be the first
pinned item because it explains the current identity and routes the other work.
Manual profile pinning guidance: [GitHub profile pinning](docs/GITHUB_PROFILE_PINNING.md).

<details>
<summary>Reference repos and what they prove</summary>

| Repository | Use this if | Public status | Not claimed |
| --- | --- | --- | --- |
| [`mmi-gateway`](https://github.com/baishiqi45-dotcom/mmi-gateway) | You need an intake pattern for turning messy material into review-required candidate evidence. | Reference slice | Not the current product identity. |
| [`codex-sidecar-subagents`](https://github.com/baishiqi45-dotcom/codex-sidecar-subagents) | You need the read-only advisor pattern where Codex keeps file access, verification, and integration judgment. | Reference slice | Not autonomous truth or final acceptance. |
| [`epistemic-os`](https://github.com/baishiqi45-dotcom/epistemic-os) | You need claim-scope guardrails so weak evidence does not become confident AI release language. | Guardrail slice | Not a complete runtime system. |
| [`netfix`](https://github.com/baishiqi45-dotcom/netfix) | You need a practical Mac network rescue utility for operator downtime. | Utility satellite | Not part of the AI video method library. |

</details>
