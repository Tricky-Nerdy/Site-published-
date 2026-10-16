# Obsidian and publication guide

These are newly written practical notes for this repository.

## Import into Obsidian

1. Clone or download this repository. Keep a copy of existing vault files before importing.
2. Copy the selected publication folder into the vault's designated public site folder, retaining the Markdown and PDF together. Alternatively, open a separate copy of this repository as a dedicated public-content vault.
3. Open `The Bodies We Borrow.md` in Obsidian. The chapter headings provide navigation. The PDF is a separate print reference.
4. If copying only a publication folder, also copy this guide where appropriate or update its relative link in that folder's README.

## Keep private notes out of GitHub

- Treat this entire repository and its Git history as public.
- Sync or copy only the explicitly selected site/publication folder. Do not initialize this public repository at the root of a mixed private/public vault.
- Keep private journals, unrelated folders, credentials, and `.obsidian` settings out of the public copy. A separate public-only checkout is the simplest boundary.
- Before each commit, review the changed-file list and diff. Add only the intended publication files; avoid bulk-adding a mixed vault.
- Pull current repository changes before publishing edits and resolve conflicts deliberately. Do not overwrite newer edits blindly.
- Ignore rules alone do not remove already tracked files or erase Git history. Review what is actually tracked before pushing.

This repository does not configure a phone sync service, Obsidian plugin, or website deployment. Set up folder selection in the chosen sync tool before enabling it, then test with one non-private file and verify the destination contains only intended content.

## Publish to a website

Use the Markdown as editable source and the PDF as an optional download. The website's import/build process determines how Markdown becomes a page. Keep relative asset links valid when moving files. Review the published preview before making a site update live.

## Print

Use `publications/the-bodies-we-borrow/The_Bodies_We_Borrow_Office_Print_Edition.pdf` for the existing print layout: 34 pages, US Letter. Select the matching paper size, inspect print preview, and test a page before printing the full document. Printer margins and duplex settings vary. Changes to the Markdown require a fresh export if they should appear in a new PDF.
