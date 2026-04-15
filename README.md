# Infrastructure Documentation

This repository hosts Infrastructure team documentation using a
**Markdown + MkDocs + GitHub Pages** approach.

Documentation is treated as code and maintained in this repository.
All published content is generated from the Markdown files stored here.

---

## How This Works

- Documentation is written in **Markdown**
- **MkDocs** builds a static site from the Markdown files
- **GitHub Pages** hosts the generated static site

The `main` branch contains the documentation source.
The `gh-pages` branch contains generated site output and should not be edited manually.

---

## Repository Structure

```text
docs/          # All documentation content (Markdown)
mkdocs.yml     # MkDocs site configuration
README.md      # This file