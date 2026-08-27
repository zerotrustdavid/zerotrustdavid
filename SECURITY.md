# Security record

Living record of the hardening state of this repository (the GitHub profile
README). Edited in place as settings change — it does not accumulate dated
entries. See [profileassets/SECURITY.md](https://github.com/zerotrustdavid/profileassets/blob/main/SECURITY.md)
for the record of the other profile repository.

- **Visibility:** public (verified via the GitHub API).
- **Purpose:** profile README only — no tooling, no workflows.
- **Collaborators:** owner only, no outside collaborators (verified via the GitHub API).
- **Branch protection on `main`:** a ruleset named "main protection" exists but,
  as last checked, had no branch targets configured — it applied to zero refs
  and was not enforcing anything. Once targeted at `main` it carries: require a
  pull request before merging, restrict deletions, block force pushes.
- **Secret scanning / push protection / Dependabot security updates:** not
  confirmed. The environment that verified this record has no route to the
  repository security-settings API — check directly under Settings → Code security.
- **Private vulnerability reporting:** not confirmed.
- **Actions default workflow permissions:** not confirmed (this repo carries no workflows).
- **Signed commits on `main`:** not required, as last checked.
- **`has_wiki` / `has_projects`:** on, as last confirmed live via the GitHub API — target is off.

## Outstanding

1. Open the "main protection" ruleset (Settings → Rulesets) and add a branch
   target — either "Include default branch" or the pattern `main` — so the
   rules already configured on it actually apply.
2. Turn off the wiki and Projects tab (Settings → General → Features).
3. Confirm secret scanning, push protection, Dependabot security updates, and
   private vulnerability reporting under Settings → Code security, and signed
   commits under the branch ruleset.
4. Re-verify with a live query (API or the Settings UI) and update this file
   to match — do not mark an item done without seeing the confirming state.
