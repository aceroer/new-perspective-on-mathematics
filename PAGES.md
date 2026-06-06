# Pages Operations

## Publish

After creating the GitHub repository, push `main` and enable GitHub Pages:

```bash
gh repo create aceroer/new-perspective-on-mathematics --public --source . --remote origin --push
```

Then in GitHub:

```text
Settings -> Pages -> Build and deployment -> Deploy from branch -> main -> /
```

## Update

For ordinary site edits:

```bash
git status --short
git add .
git commit -m "Update NPM site"
git push
```

## Boundary Scan

Before publishing, run the public hygiene scan used by the main workflow
repository.  The scan should check for unfinished placeholders, private labels,
local machine paths, and secret-looking tokens.

Keep the command text outside this public Pages repository to avoid matching
the scan pattern inside the operations note itself.
