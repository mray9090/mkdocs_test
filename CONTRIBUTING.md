# Contributing to the Docs

Edit documentation
- Modify or add .md files under docs/
Test locally
- mkdocs serve
Verify formatting, navigation, and content.

Commit & push changes
- git add docs/
- git commit -m "Update onboarding documentation"
- git push origin main

Publish updated site
- mkdocs gh-deploy
Site updates automatically
No manual HTML edits
gh-pages remains generated output only

---

## Key Rules

Do
- Edit .md files in docs/
- Test with mkdocs serve
- Commit and push to main
- Run mkdocs gh-deploy to publish
Do Not
- Edit files in gh-pages
- Commit generated HTML
- Skip committing source changes before deploy