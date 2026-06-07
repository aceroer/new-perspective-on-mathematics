# New Perspective on Mathematics

Questions Before Answers.

Exploring Mathematics Beyond Boundaries.

This repository hosts the static GitHub Pages site for **New Perspective on
Mathematics (NPM)**.

## Site Role

This repository is only for the journal/community website:

- home page;
- submission guide;
- editorial policies;
- issue pages;
- public article indexes.

Research workflows, branch cases, Lean files, verification scripts, and child
project audit records should live in their own repositories or in the main
workflow repository.

## Local Preview

Because the site is plain static HTML, it can be previewed by opening
`index.html` directly or by running:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## GitHub Pages Setup

Recommended repository name:

```text
new-perspective-on-mathematics
```

Recommended Pages setting:

```text
Deploy from branch
main
/
```

Expected Pages URL:

```text
https://aceroer.github.io/new-perspective-on-mathematics/
```

## Repository Boundary

This repository is the public web surface.

It should not contain restricted notes, local paths, nonpublic theory labels, API
tokens, or full research workspaces.

## Current Pages

- `index.html`
- `submissions.html`
- `policies.html`
- `issues/2026-06-branch-workflows.html`
