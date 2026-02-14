Title: CI: fix failures discovered by local run

Description:

Run `pnpm install` and `pnpm test` locally to reproduce GitHub Actions CI. Create fixes for any failing checks.

Acceptance criteria:

- Local `pnpm test` completes with exit code 0
- GitHub Actions `ci.yml` passes for PRs
