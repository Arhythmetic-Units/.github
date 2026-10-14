# Public repository instructions

This repository is public. Every file, commit message, issue, and pull request
must be safe for public disclosure.

## Scope

- Maintain the organization profile in `profile/README.md` and public community
  guidance in the root Markdown files.
- Use the live company website, <https://arhythmetic-units.com/>, as the source
  for company copy, published product claims, availability, and contact details.
- Keep released products distinct from products in development. Do not infer
  release dates, prices, platform support, or licensing terms.
- Link to published assets and documents instead of copying files from private
  repositories. Do not import repositories, submodules, or Git history.

## Publication boundaries

- Never add proprietary source, algorithms, implementation details, internal
  documentation, private repository references, unannounced plans, credentials,
  personal data, or customer information.
- Do not copy website source, design files, builds, installers, archives,
  datasets, or development artifacts into this repository.
- Keep local paths and private working notes out of all public content.
- Do not add a product or software license here. Product repositories own their
  respective licensing; public visibility is not a license grant.
- The `.gitignore` allows specific files only. Update it deliberately for an
  authorized addition; never use forced staging to bypass it.
- Root community health files can apply across the organization. Keep them
  general and avoid promises about response times or product support lifetimes.

## Verification

- Inspect Git status and preserve existing user changes before editing.
- Check every changed file for confidential content, including links, hidden
  files, image metadata, and attachments if any are introduced.
- Verify local links and public destinations, and review `git diff --check`.
- Review untracked files explicitly: ordinary `git diff` does not show them.
- Review the exact staged file list and diff before any commit. Ignore rules
  are not a content scanner and do not protect already tracked files.
- Commit or push only when requested. Report what changed, what was verified,
  and whether the changes remain local.
