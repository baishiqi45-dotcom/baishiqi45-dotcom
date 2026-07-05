# Synthetic Sample: Script To Dispatchable AI Video Package

This is a fully invented public-safe sample. It demonstrates the control method
without using private scripts, private prompts, provider state, customer assets,
or final delivery claims.

## 1. Scene Intent

```text
Scene:
A late-night repair-shop owner hears a strange sound from the locked storage
room. He does not open it immediately. He first notices that the old red radio,
which was silent all day, has started playing a weather report from yesterday.

Viewer question:
Is the sound coming from the storage room, the radio, or the owner's memory?

Emotional transaction:
Curiosity should turn into unease without jumping to a monster reveal.
```

## 2. Visual Reference Roles

| Reference role | Binding? | What it controls | What it must not control |
| --- | --- | --- | --- |
| Repair shop layout | Binding | counter, storage-room door, back shelf, radio position | actor face, lighting style |
| Red radio | Binding | object identity, position, power light | whole color palette |
| Rainy street mood | Mood only | exterior reflection and night atmosphere | continuity facts inside the room |
| Owner wardrobe | Binding | oil-stained jacket, gray shirt | exact actor likeness |

## 3. Continuity Locks

| Lock | Must remain true | Fail signal | Retake target |
| --- | --- | --- | --- |
| Character | owner is tired, cautious, not panicked | he reacts like a horror victim too early | performance |
| Space | storage-room door is behind the counter on screen right | door jumps behind actor or changes shape | space lock |
| Prop | red radio is on the back shelf with a small power light | radio changes color, disappears, or moves to counter | prop lock |
| Action | owner pauses before crossing the room | he opens the door immediately | blocking |
| Emotion | curiosity becomes unease slowly | sudden scream, chase, or monster reveal | emotional lock |

## 4. Dispatchable Shot Package

### Shot 01

```text
Function:
Establish the repair shop and the silent storage-room door.

Performance:
Owner wipes his hands, tired but alert.

Blocking:
He stays behind the counter. The storage-room door remains visible on screen right.

Camera:
Static medium-wide. Let the viewer notice the red radio before it matters.

Asset roles:
Repair shop layout and red radio are binding. Rainy street is mood only.

Review rule:
Fail if the storage-room door is not readable or the radio is not visible.

Retake target:
Space lock or prop lock only.
```

### Shot 02

```text
Function:
The red radio turns on by itself.

Performance:
Owner freezes for one beat, then looks toward the radio before looking toward the door.

Blocking:
No one crosses the room yet.

Camera:
Slow push toward the shelf, but keep the owner partially in frame.

Asset roles:
Radio identity, shelf position, and power light are binding.

Review rule:
Fail if the owner reacts before the radio is clearly active.

Retake target:
Performance timing or prop lock.
```

### Shot 03

```text
Function:
Connect the radio to the locked storage-room door without revealing the source.

Performance:
Owner takes one step out from behind the counter, stops, listens.

Blocking:
He does not touch the door.

Camera:
Over-shoulder toward door. Radio light remains a small red point in background.

Asset roles:
Door position and radio light are binding. Exterior rain remains mood only.

Review rule:
Fail if the scene becomes a jump scare or reveals what is behind the door.

Retake target:
Emotional lock or camera.
```

## 5. QA Boundary

| Check | Admit | Retake | Rewrite |
| --- | --- | --- | --- |
| Door position stable | yes | if screen direction flips | if layout cannot be recovered |
| Radio identity stable | yes | if color/position drifts | if the object is not readable |
| Owner reaction restrained | yes | if panic appears too early | if scene function changes |
| No premature reveal | yes | if monster/shadow appears | if the story beat is lost |

## 6. Operator Handoff

Allowed local changes:

- adjust camera speed;
- reduce or increase rain mood;
- retake owner reaction timing;
- retake radio visibility.

Forbidden local changes:

- move the storage-room door;
- change the red radio identity;
- reveal the source of the sound;
- turn the scene into a jump scare;
- change owner wardrobe or role.

## 7. Admission Note

```text
This package is reviewable if the door, radio, owner position, and emotional
progression are visible. It is not final video acceptance. Human playback and
owner seal are still required before edit or delivery claims.
```

## 8. Reusable Lesson

The production question is not "can the model generate a creepy repair shop?"
The production question is:

```text
Which facts must survive across shots, and which failure can be retaken without
rewriting the whole package?
```
