# Contributing

Contributions are welcome when they make a repository more useful, reliable,
understandable, or honest about its limits.

## Start with the repository's own instructions

Read the target repository's README and any local `CONTRIBUTING.md`,
`AGENTS.md`, or development documentation first. Local instructions override
this account-wide fallback and normally contain the correct setup and test
commands.

Before opening an issue, search existing Issues and current pull requests. A
good bug report includes:

1. the smallest input or sequence that reproduces the problem;
2. what you observed and what you expected instead;
3. the project version, operating system, runtime, and installation method;
4. relevant logs or screenshots with secrets and personal data removed.

## Pull requests

Keep a pull request focused on one problem. Explain why the change is needed,
what it changes, and which checks you actually ran. Include tests for behavior
changes when the repository has a test suite, and update documentation or
generated artifacts when user-visible behavior changes.

Please avoid unrelated formatting, dependency, or refactoring changes. Do not
replace licensing or attribution files unless the change is explicitly in
scope and legally justified.

AI-assisted contributions are allowed. The submitting author is still
responsible for understanding every change, checking licenses and sources,
running the stated verification, and correcting the work during review. If AI
materially shaped the implementation or evidence, a short disclosure in the
pull request helps reviewers calibrate their checks.

## Claims and evidence

Do not report a test, build, hardware run, publication, benchmark, or user
outcome as successful unless it actually happened. Synthetic examples and
demos are useful when they are labelled as such. If an important check could
not be run, say what was not verified and why.

For a suspected security vulnerability, do not open a public issue. Follow
the instructions in [SECURITY.md](SECURITY.md).
