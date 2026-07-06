# Filled Example: AI Video Continuity Locks

This is an invented public-safe example based on the repair-shop scene from the
synthetic script-to-package sample.

## Sequence

```text
Project: Synthetic repair-shop scene
Scene: Late-night storage-room sound
Shot range: 01-03
Owner: Public method library example
Review date: 2026-07-06
```

## Locks

| Lock | Must remain true | Evidence source | Fail signal | Retake target |
| --- | --- | --- | --- | --- |
| Character | Owner is tired, cautious, not panicked. | Shot package performance field | He screams, runs, or acts like the reveal already happened. | Performance timing only. |
| Space | Storage-room door stays behind the counter on screen right. | Repair shop layout reference | Door moves behind actor or swaps side. | Space lock only. |
| Prop | Red radio stays on the back shelf with a small power light. | Prop reference role | Radio changes color, disappears, or jumps to the counter. | Prop lock only. |
| Action | Owner pauses before crossing the room. | Blocking field | He opens the door immediately. | Blocking. |
| Emotion | Curiosity turns into unease slowly. | Scene intent | Jump scare or monster reveal arrives too early. | Emotional lock. |

## Review Decision

```text
Admit to next review: yes, if door/radio/owner position are visible.
Needs local retake: yes, if one lock fails while scene function survives.
Needs package rewrite: yes, if the scene becomes a reveal or chase.
Blocked because: no owner seal; this is synthetic method evidence only.
```

## Boundary

This filled example is not final video acceptance. It only shows how continuity
constraints and retake scope can be recorded before more generation spend.
