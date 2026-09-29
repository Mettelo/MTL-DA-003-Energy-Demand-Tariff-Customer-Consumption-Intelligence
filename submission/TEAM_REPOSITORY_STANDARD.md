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

## Mandatory Mettelo Access

Every team delivery repository **must grant Mettelo access** for review, verification and project-quality assurance.

### If the repository is owned by a team member or another organisation

The Team Lead must invite the **designated Mettelo reviewer GitHub account** as a collaborator.

### If the repository is created inside the Mettelo GitHub organisation

The required Mettelo reviewer/team access must be retained.

### Submission rule

A repository will **not be treated as a complete Mettelo submission until Mettelo access has been granted and verified**.

The Team Lead is responsible for ensuring that:

- the invitation has been sent;
- the designated Mettelo reviewer can open the repository;
- the reviewer can inspect code, documentation, issues, pull requests and contribution history;
- access remains available throughout review and verification.

Do not remove Mettelo access until the project review and verification process is complete.

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
