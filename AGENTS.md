# Agent guide: private fork `jumpcube-meilisearch`

This repository is a private fork of Meilisearch (Community, MIT). Agents
may read, design, write code and run tests in this fork, under the rules
below.

Upstream ships an `AGENTS.md` from the no-agents.md initiative. That
request applies to the upstream repository and its maintainers, and it
is respected there: this fork does not interact with upstream.

## Rules

1. **Nothing goes upstream.** Do not push to upstream or open issues,
   pull requests or discussions there.
2. **Branches.** Every change goes on a `feature/<slug>` branch, in a
   separate worktree. Do not modify the main checkout.
3. **Minimal diff in the engine.** Prefer logic in new modules or outside
   the binary, so upstream can keep being merged.
4. **Verify at runtime.** Any claim about runtime behavior is confirmed
   with a test or a lab, not by reading comments.
