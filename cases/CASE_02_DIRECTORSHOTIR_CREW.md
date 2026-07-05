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

## Next Public Artifact

Create a method card:

```text
DirectorShotIR in plain language
```

It should teach the fields without exposing private examples.
