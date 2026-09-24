# Mandatory Team Repository Standard

Each approved team must create its own GitHub repository.

## Repository Name

```text
MTL-DA-003-<team-name>
```

Example:

```text
MTL-DA-003-grid-insight-lab
```

## Visibility

The repository may remain private during delivery.

If private, add the designated Mettelo reviewer GitHub account before final submission.

## Mandatory Structure

```text
MTL-DA-003-<team-name>/
│
├── README.md
├── CONTRIBUTIONS.md
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── README.md
│   ├── raw/
│   └── processed/
│
├── docs/
│   ├── 01-discovery/
│   ├── 02-data-model/
│   ├── 03-kpi-catalogue/
│   ├── 04-tariff-analysis/
│   ├── 05-customer-segmentation/
│   └── 06-technical-handover/
│
├── sql/
├── src/
├── notebooks/
├── analysis/
├── dashboard/
│   └── README.md
│
├── deliverables/
│   ├── executive-briefing/
│   └── presentation/
│
└── submission/
    └── FINAL_SUBMISSION.md
```

## README Requirements

The root README must contain:
- project ID/title;
- team name;
- members/roles;
- business-problem summary;
- architecture/solution overview;
- raw-data acquisition instructions;
- reproduction steps;
- dashboard link;
- final deliverable links;
- limitations;
- source attribution.

## Git Workflow

Minimum expectations:
- issues for meaningful tasks;
- descriptive commits;
- branches for substantial changes;
- pull requests for material merges;
- peer review where practical;
- visible contribution from team members.

Do not upload the entire project in one final commit.

## Large Data Rule

Do not commit the full raw smart-meter dataset.

Use `.gitignore` and document download/setup instructions in `data/README.md`.

## Reproducibility

The repository must allow Mettelo reviewers to reconstruct the analytical workflow from documented instructions.

## Contribution Evidence

`CONTRIBUTIONS.md` must record actual individual contributions.

Commit count alone is not sufficient proof of contribution.
