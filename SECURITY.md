# Security record

Living record of the hardening state of this repository (the GitHub profile
README). Edited in place as settings change — it does not accumulate dated
entries. See [profileassets/SECURITY.md](https://github.com/zerotrustdavid/profileassets/blob/main/SECURITY.md)
for the record of the other profile repository.

- **Visibility:** public (verified via the GitHub API).
- **Purpose:** profile README only — no tooling, no workflows.
- **Collaborators:** owner only, no outside collaborators (verified via the GitHub API).
- **Branch protection on `main`:** none. The owner created a ruleset then
  deleted it (owner decision — this repo is a static, single-owner README with
  no CI, so the risk it would have covered is low). No tool available to this
  record's verifying environment can read rulesets, so this line is taken on
  the owner's word, not independently confirmed.
- **Secret scanning / push protection / Dependabot security updates:** enabled (owner-confirmed).
- **Private vulnerability reporting:** enabled (owner-confirmed).
- **Actions default workflow permissions:** read-only, and Actions cannot create
  or approve pull requests (owner-confirmed; this repo carries no workflows).
- **Merge settings:** squash-only merges with automatic head-branch deletion
  (owner-confirmed).
- **Signed commits on `main`:** not required — no ruleset exists to carry that setting.
- **`has_wiki` / `has_projects`:** off (verified via the GitHub API).

## Provenance

Two levels of confidence are used above, deliberately:

- **verified via the GitHub API** — read back live from GitHub by the
  environment maintaining this record.
- **owner-confirmed** — applied and checked by the owner in the GitHub
  Settings UI. The environment maintaining this record has no tool that
  reaches the repository security-settings, Actions-permissions, or ruleset
  endpoints, so it cannot independently confirm these.

Anything re-checked later should be updated in place, and promoted to
"verified" only once actually read back.
