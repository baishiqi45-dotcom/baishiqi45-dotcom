# Public Packaging Execution Plan 2026-07-05

> **For agentic workers:** this plan is the execution contract for the public
> packaging lane. Execute task-by-task, keep private project truth out of public
> files, and verify each public claim before publishing.

**Goal:** turn the GitHub profile and public packaging surface into a mature,
useful public identity around AI video production control, non-engineer AI
product control, Project Clinic/DSC, and video admission/verification methods.

**Architecture:** GitHub is the proof appendix, not the main conversion surface.
The public profile points to method/case packaging; old repositories remain
small supporting slices. Website/case/content drafts live in this profile repo
until a dedicated personal-site repo exists.

**Tech Stack:** Markdown, SVG, GitHub profile repo, GitHub CLI, native Codex
subagents for independent checks, Claude Opus cold review for high-risk wording.

---

## 0. Current State

### Completed Before This Plan

- [x] Profile repo headline changed from generic AI control systems to
      `白子烨 | AI 产品执行导演`.
- [x] Profile README foregrounds AI video production control, director-style
      agent workflows, non-engineer AI product control, and video
      admission/verification.
- [x] `PUBLIC_PACKAGING_PLAYBOOK.md` exists with positioning, website structure,
      case format, service offers, content plan, GitHub rules, and publish
      checklist.
- [x] `assets/ai-production-control-loop.svg` says
      `AI production control loop`.
- [x] Public repo descriptions have been updated:
      `baishiqi45-dotcom`, `mmi-gateway`, `codex-sidecar-subagents`,
      `epistemic-os`, `netfix`.
- [x] Old public repos have been downgraded in README first screens:
      `mmi-gateway` as reference slice, `codex-sidecar-subagents` as reference
      slice, `epistemic-os` as guardrail slice, `netfix` as utility satellite.
- [x] Star-growth wording was removed from the public profile and checked old
      repo first screens.

### Public Execution Scope

- This profile repository is the active public packaging workspace.
- Supporting public repositories are adjusted only through their public README
  and public repository description.
- Local controller state, private workspaces, and internal writeback mechanics
  must not be published as part of this plan.
- The internal knowledge/routing/capability layer remains private. Public
  packaging outputs stay in public packaging repositories unless the user
  explicitly asks for private writeback.

## 1. Owner, Truth, And Non-Claims

### Owner

Public packaging owner:

```text
this GitHub profile repository
```

Supporting public repo owners:

`mmi-gateway`, `codex-sidecar-subagents`, `epistemic-os`, and `netfix`.

### Truth Boundary

This lane owns public-facing language, structure, method packaging, synthetic
case templates, and content calendars.

This lane does not own:

- private project truth;
- raw scripts, prompts, source media, subtitles, screenshots, or customer
  materials;
- provider job, account, credit, key, or download state;
- final artifact acceptance;
- production runtime implementation;
- billing, Stripe, Supabase, RAG, OCR, or app backend changes.

### Non-Claims

Do not claim:

- the private control layer is a public product runtime;
- any dry-run, fixture, prompt package, sidecar review, or checker pass proves a
  final artifact;
- old public repos are the main product;
- GitHub stars are the goal;
- the user replaces engineers or owns all final execution.

## 2. Public Identity Stack

### One-Line Identity

```text
白子烨是 AI 产品执行导演：把非工程师的商业意图、影像判断和创意素材，翻译成可被 AI coding agent、外部工程师、影像工具执行和验证的工作系统。
```

### English Identity

```text
AI-native creative operator for intent-to-artifact systems: film/directing judgment, agent handoff, production control, artifact verification, and lesson writeback.
```

### Four Public Pillars

1. **AI video production control**
   - Reviewed script to visual references, image evidence, shot packages, QA,
     retake, and operator handoff.
2. **Director-style agent workflows**
   - Story intent to performance, blocking, camera, transition, asset roles,
     review rules, and field-level retake.
3. **Non-engineer AI product control**
   - Intent to source/tool/research route, owner-workspace handoff, artifact
     verification, and outcome-delta writeback.
4. **Video admission and verification**
   - Evidence ladder, human playback boundary, weak-claim blocking, and retake
     decision language.

## 3. File Map To Create Or Maintain

### Existing Files

| File | Responsibility |
| --- | --- |
| `README.md` | GitHub profile surface and first-screen identity. |
| `PUBLIC_PACKAGING_PLAYBOOK.md` | Public strategy, website structure, case format, service offers, content plan, publishing rules. |
| `assets/ai-production-control-loop.svg` | Visual shorthand for public control-loop positioning. |

### Files To Add In This Execution Goal

| File | Responsibility |
| --- | --- |
| `PACKAGING_EXECUTION_PLAN_2026-07-05.md` | This execution contract. |
| `website/HOME.md` | Copy deck for the future personal website home page. |
| `website/METHODS.md` | Public method-library page outline and copy. |
| `website/SERVICES.md` | Service offers, scope, outputs, non-claims, CTA copy. |
| `cases/CASE_01_SCRIPT_TO_PACKAGES.md` | Public-safe case skeleton for AI video production control. |
| `cases/CASE_02_DIRECTORSHOTIR_CREW.md` | Public-safe case skeleton for director-style agent workflows. |
| `cases/CASE_03_PROJECT_CLINIC.md` | Public-safe case skeleton for non-engineer AI product control. |
| `content/FIRST_10_POSTS.md` | First 10 content drafts across 小红书/即刻/LinkedIn/X. |
| `verification/PUBLIC_PACKAGING_VERIFICATION_2026-07-05.md` | Evidence of what was changed, checked, pushed, and not claimed. |

## 4. Execution Rules

### Main-Thread Duties

- Codex main thread owns edits, integration, commits, pushes, and final user
  summary.
- Subagents and Claude are advisory unless given a specific read-only or path
  lease.
- No helper output can become public wording without Codex reading the actual
  file diff and checking publish boundaries.

### Native Subagent Triggers

Use a native subagent when:

- a public file needs independent boundary review;
- a content/case draft needs a second reader for overclaim, privacy leakage, or
  incoherent positioning;
- a verification checklist needs raw path inspection independent of the writer.

Default subagent lane:

```text
role: public-packaging-boundary-review
allowed_sources:
  - GITHUB_PROFILE_baishiqi45-dotcom public packaging files
  - public README snippets from old public repos
forbidden:
  - editing files
  - reading private project raw assets
  - promoting candidate reports to validation
expected_output:
  - findings ordered by severity
  - exact file/line references where possible
  - accepted/rejected risk summary
```

### Claude Opus Triggers

Use Claude Opus cold review when:

- public homepage/profile language risks sounding inflated, generic, or
  unbelievable;
- a service offer risks overpromising runtime/provider/final delivery;
- case copy needs harsh external-market skepticism.

Claude packet must be narrow and read-only:

```text
task: cold-review public packaging language for overclaim, credibility, and conversion clarity
scope: README.md + PUBLIC_PACKAGING_PLAYBOOK.md + new website/case drafts
forbidden: private project assets, provider state, account details, edits, commits, pushes
expected output: top risks, exact wording concerns, replacement direction
```

## 5. Task Plan

### Task 1: Preserve Current Public Profile State

**Files:**

- Maintain: `README.md`
- Maintain: `assets/ai-production-control-loop.svg`
- Reference: GitHub repo descriptions

Steps:

- [x] Verify `README.md` foregrounds `AI 产品执行导演`.
- [x] Verify old repos are under `Building Blocks`, not `Selected public work`.
- [x] Verify no star-request wording in the checked public first screens.
- [x] Verify remote repo descriptions match the tool-satellite role.

Verification command:

```bash
gh repo list baishiqi45-dotcom --limit 20 --json name,isPrivate,description,updatedAt \
  | jq -r '.[] | select(.isPrivate==false) | [.name,.description] | @tsv'
```

Expected public descriptions:

```text
baishiqi45-dotcom  AI product execution director: AI video production control, non-engineer operator workflows, and verification methods.
mmi-gateway        Reference slice: multimodal intake for review-required candidate evidence, not project truth.
codex-sidecar-subagents Reference slice: bounded read-only sidecar advisors for Codex-owned verification.
epistemic-os       Guardrail slice: claim-scope checks that keep candidate evidence from becoming overconfident AI claims.
netfix             Utility satellite: Mac network rescue for operator downtime when agent tools cannot connect.
```

### Task 2: Write Website Copy Deck

**Files:**

- Create: `website/HOME.md`
- Create: `website/METHODS.md`
- Create: `website/SERVICES.md`

Steps:

- [x] Create `website/HOME.md` with:
  - hero headline;
  - bilingual one-line identity;
  - three primary entry points;
  - one featured case slot;
  - boundary note;
  - CTA copy.
- [x] Create `website/METHODS.md` with:
  - five method cards;
  - what each card helps decide;
  - what it does not prove.
- [x] Create `website/SERVICES.md` with:
  - four service offers;
  - scope, output, timeline, not-in-scope;
  - CTA copy that does not imply final artifact acceptance.

Verification:

Run the sensitive scan from Task 5 against `website/`.

Expected: no matches.

### Task 3: Write First Three Case Skeletons

**Files:**

- Create: `cases/CASE_01_SCRIPT_TO_PACKAGES.md`
- Create: `cases/CASE_02_DIRECTORSHOTIR_CREW.md`
- Create: `cases/CASE_03_PROJECT_CLINIC.md`

Steps:

- [x] Create Case 01 with title `从剧本到可派发抽卡包：AI 影像生产总控链`.
- [x] Create Case 02 with title `把一个 AI 脑子拆成剧组：DirectorShotIR 与 AI 导演控制`.
- [x] Create Case 03 with title `一句需求如何变成启动包、审阅清单和经验写回`.
- [x] Use the case-card format:

```text
Title
Original intent
Where the project was losing control
Control method used
What was handed off
How the artifact was reviewed
What became reusable
Public boundary
Next public artifact
```

Verification:

Run the sensitive scan from Task 5 against `cases/`.

Expected: either no matches, or only explicit boundary warnings.

### Task 4: Draft First 10 Posts

**Files:**

- Create: `content/FIRST_10_POSTS.md`

Steps:

- [x] Write 10 post drafts, not only titles.
- [x] Each draft must name:
  - platform;
  - hook;
  - body;
  - visual suggestion;
  - CTA;
  - boundary note.
- [x] Cover at least:
  - AI video continuity;
  - DirectorShotIR / crew;
  - Project Clinic;
  - video admission;
  - why GitHub star is not the target.

Verification:

Run the sensitive scan from Task 5 against `content/`.

Expected: no promotional star-growth or private-asset claims.

### Task 5: Independent Review

**Files:**

- Review: `README.md`
- Review: `PUBLIC_PACKAGING_PLAYBOOK.md`
- Review: `PACKAGING_EXECUTION_PLAN_2026-07-05.md`
- Review: `website/*.md`
- Review: `cases/*.md`
- Review: `content/*.md`

Steps:

- [x] Spawn one native subagent for boundary and privacy review.
- [x] Run Claude Opus cold review if public copy feels overclaimed or too soft.
- [x] Integrate accepted findings.
- [x] Record rejected findings briefly in the verification file.

Verification:

```bash
git diff --check
python3 - <<'PY'
from pathlib import Path

roots = [
    Path("README.md"),
    Path("PUBLIC_PACKAGING_PLAYBOOK.md"),
    Path("PACKAGING_EXECUTION_PLAN_2026-07-05.md"),
    Path("website"),
    Path("cases"),
    Path("content"),
    Path("assets"),
]

patterns = {
    "absolute local path": "/" + "Users" + "/",
    "workspace path": "AI_" + "PROJECT_WORKSPACE",
    "private knowledge repo path": "AI_" + "KNOWLEDGE_BASE_NON_RUNTIME",
    "provider secret": "provider " + "key",
    "api key": "api_" + "key",
    "auth credential A": "to" + "ken",
    "auth credential B": "coo" + "kie",
    "auth credential C": "pass" + "word",
    "raw private script": "真实" + "剧本",
    "supplier package": "供应" + "商包",
    "private asset": "私有" + "素材",
    "star request": "please " + "star",
    "star CTA": "Star " + "it",
}

files = []
for root in roots:
    if root.is_file():
        files.append(root)
    elif root.is_dir():
        files.extend(p for p in root.rglob("*") if p.is_file())

hits = []
for path in files:
    text = path.read_text(encoding="utf-8", errors="ignore")
    for label, pattern in patterns.items():
        if pattern in text:
            hits.append((str(path), label))

if hits:
    for path, label in hits:
        print(f"{path}: {label}")
    raise SystemExit(1)
print("sensitive scan passed")
PY
```

Expected: `git diff --check` exits 0; sensitive scan has no unsafe matches.

### Task 6: Verification Record

**Files:**

- Create: `verification/PUBLIC_PACKAGING_VERIFICATION_2026-07-05.md`

Steps:

- [x] Record commits, pushed refs, and local status.
- [x] Record remote profile README evidence.
- [x] Record repo description evidence.
- [x] Record old repo first-screen status.
- [x] Record sensitive scan results.
- [x] Record non-claims and remaining work.

Verification:

```bash
sed -n '1,220p' verification/PUBLIC_PACKAGING_VERIFICATION_2026-07-05.md
```

Expected: the file is readable without private internal context.

### Task 7: Commit And Push Public Packaging Package

**Files:**

- Add all files created by Tasks 2-6.

Steps:

- [ ] Run `git status --short`.
- [ ] Run `git diff --check`.
- [ ] Run the sensitive scan from Task 5.
- [ ] Commit with message:

```text
Add public packaging execution package
```

- [ ] Push `main`.
- [ ] Re-read remote `PACKAGING_EXECUTION_PLAN_2026-07-05.md` and
      `website/HOME.md` from GitHub API.

Verification:

```bash
git rev-parse HEAD
git ls-remote origin refs/heads/main
```

Expected: local HEAD equals remote `main`.

## 6. Execution Stop Conditions

Stop and re-admit before:

- creating a full website app or deploying a site;
- publishing private case screenshots or raw production artifacts;
- changing private repositories;
- adding provider, account, billing, install, or runtime automation;
- deleting, moving, or cleaning unrelated local files;
- staging unrelated dirty work;
- claiming final goal completion without remote evidence.

## 7. Completion Criteria For This Goal

The goal is complete only when all are true:

- [ ] `PACKAGING_EXECUTION_PLAN_2026-07-05.md` exists and is pushed.
- [ ] `website/HOME.md`, `website/METHODS.md`, and `website/SERVICES.md` exist.
- [ ] Three public-safe case skeletons exist.
- [ ] `content/FIRST_10_POSTS.md` exists with 10 usable drafts.
- [ ] At least one independent review route was used or explicitly recorded as
      unnecessary with evidence.
- [ ] `verification/PUBLIC_PACKAGING_VERIFICATION_2026-07-05.md` exists.
- [ ] Sensitive scan passes.
- [ ] Remote GitHub state proves the files are published.
- [ ] Old repo satellite positioning remains intact.

## 8. Next Phase After This Goal

Do not start these until the current goal is complete:

- Build the actual personal website in a separate site repo.
- Create downloadable PDF/Notion method cards.
- Publish the first 小红书/即刻/LinkedIn/X posts manually.
- Create a synthetic template repo for one method card.
