# My Setup

A practical, version-controlled reference for my personal computer and development environment.

This repository documents how my workspace is configured, which tools I use, and how to rebuild the environment without relying on memory or scattered notes.

## Scope

- **Hardware** — computer specifications and peripherals.
- **Windows** — installation notes, system configuration, drivers, and recovery.
- **Development** — programming languages, editors, terminals, Git, and project tooling.
- **AI** — local AI tools, models, and safe configuration notes.
- **Automation** — PowerShell scripts for repeatable setup tasks.
- **Maintenance** — backup, updates, troubleshooting, and change history.

## Principles

1. Document the current, working setup — not every tool ever tested.
2. Prefer repeatable scripts for tasks that are safe to automate.
3. Keep machine-specific details separate from reusable instructions.
4. Never commit passwords, API keys, tokens, private keys, personal access tokens, or other secrets.
5. Explain what a script changes before asking someone to run it.
6. Keep instructions useful for a future computer, not only the current device.

## Repository structure

```text
my-setup/
├── README.md
├── docs/
│   ├── hardware/
│   ├── windows/
│   ├── development/
│   ├── ai/
│   └── maintenance/
├── scripts/
│   ├── windows/
│   └── development/
├── config/
│   └── examples/
└── .gitignore
```

The structure will grow only when there is real content to put in it.

## Status

<sub>Initial structure — documentation and scripts are being added incrementally.</sub>
