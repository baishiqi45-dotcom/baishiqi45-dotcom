# Public Method Library

These are public-safe method cards for AI-native production control. They are
meant to start better work, not to prove final project truth.

The methods come from film and directing judgment first: image continuity,
performance rhythm, camera attention, field handoff, and review pressure. The AI
part is the execution layer. The useful work is turning taste and operator
judgment into instructions an agent, engineer, reviewer, or production tool can
act on.

## Five Continuity Locks

Use when AI video clips look acceptable one by one but fail as a sequence.

What this catches: sequence-level failures that prompt tweaks miss, especially
identity drift, prop state drift, space confusion, action mismatch, and emotional
reset between clips.

| Lock | Review question | Retake target |
| --- | --- | --- |
| Character | What must stay recognizable? | face, wardrobe, silhouette, voice, behavior |
| Space | What spatial fact must not drift? | room layout, entrance, position, screen direction |
| Prop | What object state must carry forward? | item presence, handoff, damage, count |
| Action | What physical cause continues? | gesture, movement, collision, gaze |
| Emotion | What performance state is inherited or broken? | fear, refusal, intimacy, suspicion, release |

Template: [AI video continuity locks](../templates/ai-video-continuity-locks.md)
Filled example: [repair-shop continuity locks](../examples/filled-ai-video-continuity-locks-repair-shop.md)

## Failure-Layer Debug Table

Use when a team says "the AI output is bad" but cannot name the failing layer.

What this catches: wrong fixes. A generation failure, a source failure, a review
failure, and an edit failure need different next actions.

| Layer | Question | Evidence to inspect |
| --- | --- | --- |
| Intent | Was the scene function clear? | brief, beat, viewer question |
| Source | Did references contain the needed evidence? | reference role map |
| Asset | Did identity, prop, or space drift? | contact sheet, frames |
| Prompt | Did instruction omit a hard constraint? | shot/package card |
| Generation | Did the provider fail despite clear constraints? | raw output, manifest |
| Review | Did the reviewer accept weak evidence too early? | checklist, admission note |
| Edit | Did ordering or rhythm create the failure later? | timeline relation |

## DirectorShotIR

Use when creative judgment needs to become agent-readable work.

What this catches: vague director language that sounds right to humans but gives
agents no inspectable shot responsibility.

| Field | Plain-language meaning |
| --- | --- |
| Performance | What the body should do and feel. |
| Blocking | Where bodies move and how they relate to space. |
| Camera | What the viewer is forced to notice. |
| Transition | How this shot hands energy to the next shot. |
| Asset roles | Which references are binding and which are mood only. |
| Review rule | What would make the shot fail. |
| Retake target | The smallest field to change if it fails. |

Template: [DirectorShotIR field card](../templates/directorshotir-field-card.md)
Filled example: [oppressive corridor note](../examples/filled-directorshotir-oppressive-corridor.md)

## Project Clinic Startup Packet

Use when a non-engineer has a product/workflow idea but the first safe action is
unclear.

What this catches: premature coding. The packet forces source selection,
capability route, first action, review checklist, and writeback before the work
turns into a large uncontrolled build.

Template: [Project Clinic startup packet](../templates/project-clinic-startup-packet.md)
Filled example: [creator workflow dashboard](../examples/filled-project-clinic-creator-dashboard.md)

## Video Admission Ladder

Use when a video artifact exists but nobody knows whether it can enter edit,
story, or acceptance review.

What this catches: treating screenshots, raw outputs, or one good-looking clip as
accepted video truth before playback, relation checks, and owner review exist.

Template: [Video admission ladder](../templates/video-admission-ladder.md)

## Outcome-Delta Writeback

Use after a project attempt so the next run learns the right lesson without
promoting candidate output into fake system truth.

What this catches: noisy learning. A failed run should produce a specific method
delta, not a vague "we learned to prompt better" note.

Template: [Outcome-delta writeback note](../templates/outcome-delta-writeback-note.md)
