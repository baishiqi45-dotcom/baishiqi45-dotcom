# Filled Example: DirectorShotIR

This is an invented public-safe example for turning one vague directing note
into agent-readable work.

## Shot Intent

```text
Scene function: The character realizes the corridor is not just empty; it is watching her.
Audience question: Will she step forward or turn back?
Emotional transaction: Curiosity should tighten into pressure without a monster reveal.
```

## Director Note

```text
Make this corridor feel oppressive.
```

## Fields

| Field | Instruction | Binding evidence | Review rule | Retake target |
| --- | --- | --- | --- | --- |
| Performance | She slows down, holds breath, keeps shoulders tight. | Actor action note | Fail if she runs or overacts fear. | Performance intensity. |
| Blocking | She stays close to the wall and stops before the final door. | Corridor layout | Fail if she crosses the full corridor too early. | Blocking distance. |
| Camera | Low, slightly compressed lens feel; door line dominates frame. | Camera note | Fail if the shot becomes a neutral hallway wide. | Camera height/framing. |
| Transition | End on her hand almost touching the handle, not opening it. | Next-shot relation | Fail if the door opens in this shot. | Transition boundary. |
| Asset roles | Corridor geometry is binding; cold color is mood only. | Reference role map | Fail if mood reference changes the hallway layout. | Asset role clarification. |

## Role Split

```text
Writer analyst: confirm the beat is hesitation, not reveal.
Director: set performance, blocking, and transition boundary.
Art director: keep corridor geometry stable.
Cinematographer: translate camera pressure into framing.
Film critic: check whether pressure is visible, not just described.
QA: name the smallest failed field for retake.
```

## Boundary

This does not prove automated directing ability. It shows how a director-style
judgment can become bounded AI work and field-level retake language.
