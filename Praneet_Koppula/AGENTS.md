# Public Portfolio Agent Contract

This repository is the working surface for privacy-cleared portfolio pages,
public-safe visuals, site components, and discovery surfaces. Build that work
directly in its final site path on a non-main branch. Private evidence,
research corpora, claim ledgers, and unredacted case material belong only in
`/Users/praneet/PortfolioEvidence`.

## Intake boundary

- Accept portfolio assets only from a committed, unchanged file under
  `/Users/praneet/PortfolioEvidence/cases/03-public-safe/<case-slug>/`.
- Use the vault's `scripts/publish_public_safe.py` handoff so every copied asset
  records the vault commit, source path, checksum, and destination.
- Privacy-cleared page work may remain in progress on a local non-main branch.
  Keep prose, layout, navigation, and responsive behavior in their final public
  paths throughout development.
- Do not treat `.codex/portfolio-evidence/`, PraneetIdeas case-study folders, or
  an uncommitted vault file as a publication source.
- Never copy raw, company-private, personnel, customer, secret, or personally
  identifying evidence into this repository.

## Production safety

- Branch before changing portfolio content. Never hand off directly on `main`
  or `master`.
- Inspect the complete staged diff and provenance before a public commit.
- Do not push, merge, or deploy unless the user explicitly requests it.
- Keep unrelated local work intact and stage only the intended public-safe
  files.
