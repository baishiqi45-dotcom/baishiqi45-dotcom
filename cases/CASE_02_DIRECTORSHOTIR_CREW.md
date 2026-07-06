# Case 02: 把一个 AI 脑子拆成剧组：DirectorShotIR 与 AI 导演控制

## Original Intent

An AI video or short-drama workflow needs more than one model producing a long
answer. It needs director-like roles: story analysis, shot design, art
continuity, prompt compilation, review, and QA.

## Where The Project Was Losing Control

- One agent had to think like writer, director, art director, cinematographer,
  reviewer, and QA at the same time.
- "Make it better" retakes changed too many fields.
- The team could not identify whether a failure was performance, camera, asset,
  transition, or review.
- Prompts described mood but did not encode production responsibility.

## Control Method Used

The method splits creative control into role-specific work:

| Role | Responsibility |
| --- | --- |
| Writer analyst | scene function, event logic, audience question |
| Director | performance, blocking, camera, transition |
| Art director | space, props, visual continuity |
| Cinematographer | production-language prompt and shot execution |
| Film critic | review against rubric |
| QA | failure classification and retake boundary |

DirectorShotIR translates creative judgment into fields:

```text
performance
blocking
camera
transition
asset_reference_roles
review_rule
retake_target
```

## What Was Handed Off

Public-safe handoff shape:

- role map;
- field definitions;
- retake target examples;
- synthetic before/after critique;
- no-private-script demonstration.

## Synthetic Teardown: Director Note To Agent Task

Vague director note:

```text
Make this corridor feel oppressive.
```

Why that fails as an agent task:

- it names a feeling but not the visible behavior;
- it does not say whether pressure comes from performance, blocking, camera, or
  art direction;
- it gives no review rule, so a retake becomes "make it better";
- it risks changing layout, mood, and performance at the same time.

DirectorShotIR translation:

| Field | Agent-readable instruction | Review rule | Retake target |
| --- | --- | --- | --- |
| Performance | Character slows down, holds breath, shoulders tight. | Fail if she runs or overacts fear. | Performance intensity. |
| Blocking | Stay close to the wall; stop before the final door. | Fail if she crosses the full corridor too early. | Blocking distance. |
| Camera | Low, slightly compressed framing; door line dominates. | Fail if the shot becomes a neutral hallway wide. | Camera height/framing. |
| Transition | End before the door opens. | Fail if the reveal happens in this shot. | Transition boundary. |
| Asset roles | Corridor geometry is binding; cold color is mood only. | Fail if mood reference changes the layout. | Asset role clarification. |

The filled public-safe field card is here:
[DirectorShotIR oppressive corridor example](../examples/filled-directorshotir-oppressive-corridor.md).

## How The Artifact Was Reviewed

Review asks:

1. Which role owns the decision?
2. Which DirectorShotIR field failed?
3. Does the retake need new source evidence or only a field-level correction?
4. Is the failure local to the shot or caused by previous sequence logic?

## What Became Reusable

- Director-style agent division of labor.
- Field-level retake language.
- A public explanation of how film direction becomes AI operator language.

## Public Boundary

Do not publish:

- real sample scripts;
- project-specific agent prompts;
- copyrighted reference plots;
- private material from production workspaces;
- claims that simulated runs prove full production readiness.

Safe public material:

- role diagrams;
- field glossary;
- synthetic scene cards;
- anonymized metrics only with clear scope labels.

## Current Public Artifacts

- [DirectorShotIR field card](../templates/directorshotir-field-card.md)
- [DirectorShotIR filled synthetic example](../examples/filled-directorshotir-oppressive-corridor.md)
