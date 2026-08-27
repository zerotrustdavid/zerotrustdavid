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
- **Secret scanning / push protection / Dependabot security updates:** not
  confirmed. The environment that verified this record has no route to the
  repository security-settings API — check directly under Settings → Advanced Security.
- **Private vulnerability reporting:** not confirmed.
- **Actions default workflow permissions:** not confirmed (this repo carries no workflows).
- **Signed commits on `main`:** not required — no ruleset exists to carry that setting.
- **`has_wiki` / `has_projects`:** off (confirmed live via the GitHub API).

## Outstanding

Still not independently confirmed (this environment has no tool that reaches
these endpoints, so they can only be taken on the owner's word or checked
directly): secret scanning, push protection, Dependabot security updates,
private vulnerability reporting, Actions default workflow permissions,
delete-branch-on-merge and merge-method restrictions. Confirm each under
Settings → Advanced Security / General / Actions, and update the relevant
line above once seen — not on the strength of a toggle having been clicked.
