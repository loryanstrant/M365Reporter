# Copilot instructions — M365Reporter

> Canonical standards live in the `dev-standards` repo on SOUNDWAVE/Gitea.

## What this repo is

A **Microsoft 365 reporting** project. The migrated repo currently contains only
a `README.md` — the implementation isn't tracked here as source. Not a Home
Assistant component.

## Important limitation

There's no code in version control yet (README only), so agents can't read or
edit an implementation in place. If this becomes active, add the source as
tracked files first.

## Conventions

- M365 tooling: no HA component scaffolding applies.
- Never commit tenant IDs, app secrets, or credentials.

## Never

- Don't commit secrets or tenant-specific identifiers.
