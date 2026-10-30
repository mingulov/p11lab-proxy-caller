# p11lab-proxy-caller (test caller repo, M09 pilots)

Setup-only scaffold for M09 pilot (d) preparation. NOT an official caller;
SHAs from this repo never become upstream authority.

- `.github/workflows/proxy-diagnostic.yml`: byte-exact copy of the P11Lab
  caller template (`examples/proxy-consumer/workflow.yml` at control
  `10017b1`). Placeholders are intact: no runs are possible until a
  compatible workflow is published (ASK-9, deferred). Producer/mutant
  definitions, if any, arrive with reviewed pilot scope.

Trigger: `pull_request` only. No PRs have been opened from setup.
