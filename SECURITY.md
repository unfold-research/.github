# Security policy

Thank you for helping keep Unfold's open projects and their users safe.

## Report a vulnerability

Please **do not open a public issue**. Use GitHub's private vulnerability reporting instead:

1. Open the repository, for example [bioswarm-plugin](https://github.com/unfold-research/bioswarm-plugin/security) or
   [bioswarm](https://github.com/unfold-research/bioswarm/security).
2. Choose **Report a vulnerability** and describe the issue, how to reproduce it and its impact.

We acknowledge reports within five working days and keep you informed until a fix is released. We credit reporters
who want to be credited.

## Scope

- **In scope:** the BioSwarm plugin (code that runs inside agent hosts), the SDK, the protocol and the scripts in these
  repositories. A policy or message that makes the plugin read files, run commands or send data beyond what
  [`bioswarm.v1`](https://github.com/unfold-research/bioswarm/blob/main/protocol/bioswarm.v1.md) allows is a
  vulnerability.
- **Out of scope:** findings in third-party agent hosts or model providers (report them upstream), and research results
  you disagree with (open a research question instead).

## Supported versions

BioSwarm is pre-release. Security fixes go to the latest release of each package.
