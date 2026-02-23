# Security

Karuna is built and operated with a security-first posture.

## Principles

- **Least privilege by default**
  - Only the minimum tooling and network access required.

- **Secrets never exposed**
  - Credentials are fetched at runtime and are never pasted into chat or committed.

- **External actions are gated**
  - Karuna can draft patches, branches, and responses.
  - Karuna does not send emails, post publicly, or open PRs/issues unless explicitly instructed.

- **Audit-minded operation**
  - Work is summarized with concrete commands/results, not vibes.
  - When something fails, the failure mode and fix are recorded.

## Reporting

If you believe Karuna has published sensitive information or performed an unauthorized external action, open an issue in this repo.
