# Definition of Done template, GitHub PR template, and new tech lead checklist

A **definition of done template**, **GitHub PR template**, and **new tech lead checklist** for small software teams (about 3–15 people). Copy them into the repo. Strike anything that is not true. Do not add process because it looks professional.

## What's in here

| File | What it is |
| --- | --- |
| [`docs/definition-of-done-template.md`](docs/definition-of-done-template.md) | Engineering definition of done template. The merge contract. Short on purpose. |
| [`docs/github-pr-template.md`](docs/github-pr-template.md) | GitHub PR template. Also installed at `.github/pull_request_template.md` so GitHub picks it up. |
| [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE/) | GitHub issue templates for bugs and work. |
| [`.github/workflows/ci.yml`](.github/workflows/ci.yml) | CI that only runs scripts you actually have. |
| [`docs/software-team-release-checklist.md`](docs/software-team-release-checklist.md) | Software team release checklist. Make releases boring. |
| [`docs/new-tech-lead-checklist.md`](docs/new-tech-lead-checklist.md) | New tech lead checklist for the first 90 days. |

## Use it

1. Copy the files into your repository.
2. Strike anything that is not true for you.
3. Keep the definition of done template in the GitHub PR template so it lives in the merge path, not a wiki.

If you cannot delete a line, it is too generic.

## Generate a version for *your* team

These files are a starting point. They will be wrong in places.

- [Definition of Done generator](https://getgroundwork.dev/tools/definition-of-done) - free
- [Tech lead readiness checklist](https://getgroundwork.dev/tools/tech-lead-readiness) - free
- [Engineering process health check](https://getgroundwork.dev/tools/health-check) - free
- [Tech Lead Starter Kit](https://getgroundwork.dev/starter-kit) - **£79**. A playbook, ownership model, 30/60/90, and a GitHub pack fitted to how you actually ship.

## Rule

Start lightweight. Measure whether it helps. Iterate. Automate what can be automated. Remove processes that don't earn their keep.
