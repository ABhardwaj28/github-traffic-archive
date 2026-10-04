# Sharing Diagnostics Safely

When sharing traffic archive data in a bug report, review the data first to make sure it does not contain information that should remain private.

## Fields to review

### Repository names

Repository names and slugs can reveal private or internal projects. Replace real private repository names with fictional examples when they are not necessary to reproduce the problem.

### Paths

Popular paths may contain project names, usernames, internal endpoints, or other information that should not be shared publicly.

Review paths before including them in an issue or attaching an archive.

### Referrers

Referrer data can reveal where traffic originated and may contain private URLs or other identifying information.

Review referrers before sharing an archive publicly.

### Page titles

Page titles may contain internal project names or other information that should not be published.

Review page titles before including traffic data in a bug report.

## Creating a minimal reproduction

When possible, create a small fictional example that demonstrates the problem without using real private data.

Prefer:

- fictional repository names
- synthetic URLs
- fictional paths
- fictional page titles
- small datasets containing only the values needed to reproduce the problem

Do not include:

- GitHub tokens or other credentials
- private traffic archives
- private repository information
- unrelated production data

For the bug-report process, see [the bug report form](https://github.com/HafidIdrissi/github-traffic-archive/issues/54) and the [synthetic example](https://github.com/HafidIdrissi/github-traffic-archive/issues/33).

## Before posting a bug report

Check that:

- [ ] Repository names are safe to share
- [ ] Paths have been reviewed for private information
- [ ] Referrers have been reviewed
- [ ] Page titles have been reviewed
- [ ] No tokens or credentials are included
- [ ] The reproduction uses fictional data where possible
- [ ] Only the data needed to demonstrate the problem is included