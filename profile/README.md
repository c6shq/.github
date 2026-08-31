# c6s — Cerberus

Secure secret access and human approval for AI agents.

c6s keeps secret values inside an encrypted vault while agents work with stable
references, scoped requests, and explicit approvals. Cerberus is the trusted-device
experience for reviewing access and controlling enrolled devices.

## Get started

| Surface | Purpose | Availability |
| --- | --- | --- |
| [c6s CLI](https://docs.c6s.whitekiwi.link/cli) | Find secrets, create requests, and run approved actions | Private beta |
| Cerberus for macOS | Manage the vault and review agent activity | Private beta |
| Cerberus for iOS | Approve requests and manage trusted devices | TestFlight beta |
| [Agent skills](https://github.com/c6shq/skills) | Codex and Claude Code workflows for c6s | Public preview |

```sh
brew install c6shq/tap/c6s
c6s login --provider google
```

Install the macOS app with:

```sh
brew install --cask c6shq/tap/cerberus
```

## Principles

- Secret values are encrypted before synchronization.
- Agents request narrowly scoped access instead of receiving a whole vault.
- Approval happens on a trusted human-controlled device.
- Logs and interfaces identify secrets by metadata, never by plaintext value.
- Offline work is supported and reconciled conservatively when connectivity returns.

## Community

- Read the [documentation](https://docs.c6s.whitekiwi.link)
- Report a bug or suggest a feature in [c6shq/feedback](https://github.com/c6shq/feedback/issues)
- Review public packages in [c6shq/homebrew-tap](https://github.com/c6shq/homebrew-tap)
- Report security vulnerabilities privately using the process in our [security policy](https://github.com/c6shq/.github/blob/main/SECURITY.md)

Product source and security-sensitive implementation details remain private during the beta.
