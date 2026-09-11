# Contributing to the Official Course Repository

This repository is the **public, student-facing** source of course material. Contributions from course staff should preserve correctness, release discipline, and a clean public history.

## 1. What belongs here

Public, instructor-approved material such as:

- lecture slides and public lecture supplements;
- released assignment statements, starter notebooks, datasets, and helper files;
- released quiz/exam material when publication is appropriate;
- final-project phase descriptions and public starter material;
- TA-session/tutorial resources;
- approved course description, calendar, and policies.

## 2. What must never be committed here

- unreleased assessment material;
- private solutions or answer keys;
- internal grading rubrics;
- gradebooks or individual grades;
- student submissions or student personal data;
- staff-only notes, private meeting notes, credentials, API keys, or `.env` files.

Use a separate **private staff repository/workspace** for drafts and sensitive material.

## 3. Branch naming

Use short, scoped branch names:

- `docs/<topic>`
- `lecture/<topic>`
- `hw/<number>-<topic>`
- `quiz/<number>`
- `project/<phase>`
- `exam/<midterm|final>`
- `fix/<short-description>`

## 4. Pull requests

Substantive public changes should be made through a pull request. A PR should:

1. have one clear purpose;
2. list the student-facing files that change;
3. confirm that no private material is included;
4. confirm that links and filenames are correct;
5. be reviewed by at least one course Supervisor before release.

High-impact releases (assignment/project/exam material) should receive a final content review before merging.

## 5. File naming

Prefer stable, descriptive names:

- `ML-HW1.pdf`
- `ML-HW1-Starter.ipynb`
- `ML-Quiz1.pdf`
- `ML-Midterm.pdf`
- `ML-Project-Phase1.pdf`
- `Lecture-01-Introduction.pdf`

Avoid `final-final-v2`, dates embedded in filenames unless essential, and spaces when a stable kebab-case name is clearer.

## 6. Release checklist

Before merging a release PR:

- [ ] content is instructor/supervisor approved;
- [ ] release date/deadline matches the official calendar;
- [ ] PDFs/notebooks open correctly;
- [ ] notebooks run from top to bottom when applicable;
- [ ] datasets/starter files are complete;
- [ ] no solution, rubric, grade, or student data is present;
- [ ] README/navigation links are updated;
- [ ] eLearn announcement text is ready or already published.

## 7. Authority

The official eLearn announcements and instructor-approved course description/calendar override repository text in case of a conflict.
