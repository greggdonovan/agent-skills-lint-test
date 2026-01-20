# agent-skills-lint-test

Sample repo that exercises the `agent-skills-lint` pre-commit/prek hooks.

## Setup

Install the linter binary:

```bash
cargo install --git https://github.com/greggdonovan/agent-skills-lint
```

Run the hook manually:

```bash
prek run agent-skills-lint
prek run agent-skills-lint-fix --hook-stage manual --all-files
```
