# Agent Development Guide

## Issue and PR Guidelines

Create issues or pull requests only when the user explicitly requests that
action. Follow the requested scope and preserve unrelated work.

For development verification, use `pnpm testTsc && pnpm lint` for the quick
loop. `pnpm test` runs the full standalone build, TypeScript, ESLint, Stylelint
and plugin-list gate; verify the current package scripts for the touched scope.
