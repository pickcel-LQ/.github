# .github

Organization-wide defaults for **pickcel-LQ**.

## Issue templates

`/.github/ISSUE_TEMPLATE/task.yml` is the default issue form for every repo that
does not define its own. It requires three fields on each new issue so the
Product board (Project #15) stays filterable:

- **Area** — Front End / Back End / Signage Player
- **Work Type** — Bug / Improvement / Feature / Migration / …
- **Customer Issue** — is a live customer/deployment affected?

`blank_issues_enabled: false` means these cannot be skipped. A repo can override
this by adding its own `.github/ISSUE_TEMPLATE/` folder.

The answers are synced into the project's single-select fields automatically.
