# Contributing

Discuss substantial changes in the issue tracker before implementation. Keep each
pull request focused on one purpose and target the Kadupul repository.

## Changes and validation

Match the surrounding code and repository formatting rules. Preserve public
interfaces unless a change includes a documented migration. Avoid unrelated edits.

Reproduce a bug before fixing it, verify the changed behavior, and include the
validation commands and results in the pull request.

## Commits

Use Conventional Commits and sign off every commit with `git commit -s` under the
[Developer Certificate of Origin](https://developercertificate.org/).

## GitHub workflow

Use GitHub's documented workflow and each repository's own conventions for
issues, pull requests, reviews, discussions, releases, and project boards. Check
the repository's contribution guide, templates, labels, branch protections,
code-owner rules, and release guidance before creating or changing GitHub
records. Use GitHub's normal UI, CLI, or API paths so that changes retain their
review and audit trail.

Make issues and pull requests actionable and fully described. Use a specific
title, the repository's template, the affected repository and branch or release
where relevant, reproduction steps and expected versus actual behavior for bug
reports, verification evidence for code changes, and links to related issues
and pull requests. Apply existing labels that accurately describe type,
subsystem, security relevance, and target branch. Preserve valid metadata; do
not guess assignees, milestones, projects, or release commitments.

Review the current diff, head commit, checks, and review threads before acting
on a pull request. Address actionable feedback with evidence and request
re-review after changes. Merge only when current-head checks pass, actionable
threads are resolved, and required independent approvals and repository rules
are satisfied. Do not bypass protections or self-approve. Use least-privilege
permissions and never put secrets in GitHub records, logs, or commits.

Before handing off or merging a GitHub change, verify its title, description,
labels, issue links, head commit, checks, review state, and thread-resolution
state using GitHub's records.

## Documentation and security

Verify documentation against the implementation and use material whose license
permits its inclusion. Follow [SECURITY.md](SECURITY.md) for vulnerabilities.
