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
- **`has_wiki` / `has_projects`:** on, as last confirmed live via the GitHub API — target is off.

## Outstanding

Settings-page checklist (this environment has no tool that reaches any of
these endpoints, so they must be applied and confirmed directly):

1. **Settings → General → Features** — untick Wikis and Projects.
2. **Settings → General → Pull Requests** — tick "Automatically delete head
   branches"; untick "Allow merge commits" and "Allow rebase merging", leave
   "Allow squash merging" ticked.
3. **Settings → Advanced Security** — enable Secret scanning, its Push
   protection sub-toggle, and Dependabot security updates. Public repos
   sometimes ship with secret scanning already on — check current state first.
4. Same page — enable Private vulnerability reporting.
5. **Settings → Actions → General → Workflow permissions** — select "Read
   repository contents permission"; untick "Allow GitHub Actions to create
   and approve pull requests".
6. Re-verify with a live query (API or the Settings UI) and update this file
   to match — do not mark an item done without seeing the confirming state.
