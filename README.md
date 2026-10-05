# .github (org defaults)

- **Scope:** Shared reusable CI workflows, PR/issue templates, CODEOWNERS defaults, security policy for every LogLens repo.
- **Not in scope:** Product code of any kind.
- **Owner:** @ParasRajput810 (founder).
- **Consumes:** Nothing.
- **Produces:** Reusable workflows (`reusable-ci.yml`) used by every repo; the org profile page.

## What's here
- `.github/workflows/reusable-ci.yml` — one CI workflow all repos call (`uses: LoglensAI/.github/.github/workflows/reusable-ci.yml@main`).
- `.github/workflows/PULL_REQUEST_TEMPLATE.md` — default PR checklist.
- `profile/README.md` — the public org landing page.
