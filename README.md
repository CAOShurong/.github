# Account-wide GitHub community defaults

This special public repository holds the default contribution, support,
security, issue, and pull-request guidance for repositories owned by
[CAOShurong](https://github.com/CAOShurong).

GitHub applies a file from here only when a repository does not provide its own
file of that type. Project-specific instructions therefore take precedence.
In particular, a repository with any local `.github/ISSUE_TEMPLATE` content
uses that whole local template set instead of the defaults here.

The defaults are deliberately evidence-oriented:

- bug reports ask for a minimal reproduction, environment, and observed
  result rather than a conclusion without evidence;
- pull requests separate what changed from what was actually verified;
- security reports are routed to GitHub's private vulnerability-reporting
  channel instead of public Issues;
- AI-assisted contributions are allowed, but the contributor remains
  responsible for understanding and validating the submitted result.

This repository does not provide a default license. GitHub does not inherit
licenses from `.github`, and every project must make its own licensing status
explicit in the files that users actually clone or download.

See GitHub's documentation on
[default community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
for the inheritance rules.
