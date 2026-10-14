# NIW Case Workspace Template

This directory is a **generic template only**. Do not store personal case data here.

For an actual matter, copy this template into the gitignored workspace:

```bash
cp -R templates/niw-case workspace/<matter-name>
```

Example:

```bash
cp -R templates/niw-case workspace/amber-niw-2026
```

The repository already ignores `workspace/`.

## Working Order

```text
00 Dashboard
  ↓
01 Evidence Inventory
  ↓
02–05 contribution/method/research
  ↓
06 Proposed Endeavor
  ↓
07 Prong 1 map
  ↓
08–11 track record / dissemination / recommenders / Prongs 2–3
  ↓
12 Narrative
  ↓
13 RFE audit
  ↓
14 Attorney review package
```

## ID Convention

- `E-###` — Evidence
- `C-P1-###` — Prong 1 claim
- `C-P2-###` — Prong 2 claim
- `C-P3-###` — Prong 3 claim

## Status Values

Use:
- `NOT_STARTED`
- `IN_PROGRESS`
- `BLOCKED`
- `READY_FOR_REVIEW`
- `COMPLETE`

## Evidence Status

Use:
- `VERIFIED`
- `PARTIAL`
- `PLANNED`
- `UNSUPPORTED`

## Sensitivity

Use:
- `PUBLIC`
- `EMPLOYER_APPROVED`
- `PRIVATE`
- `CONFIDENTIAL_DO_NOT_SHARE`

## Rule

Do not draft the final petition until `06_Proposed_Endeavor_One_Pager.md` is stable enough to pass the Employer Removal Test and Generic Engineer Test.
