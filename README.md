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

<!-- DUAL-LICENSE-START -->
## License

Copyright (c) 2026 Wangyue.

This repository uses a dual-license framework:

- Code, scripts, Lean files, formalization files, and software components are
  licensed under the GNU Affero General Public License v3.0 (AGPL-3.0-only).
  See [LICENSE](LICENSE).
- Research text, papers, manuscripts, documentation, templates, policies,
  examples, and explanatory materials are licensed under the Creative Commons
  Attribution-NonCommercial-ShareAlike 4.0 International License
  (CC BY-NC-SA 4.0). See [LICENSE-DOCS](LICENSE-DOCS).

Commercial or institutional use outside these license terms requires separate
written permission from the author.

Attribution must remain clear. Redistribution, adaptation, citation, or reuse
must preserve attribution to the original author and repository. No derivative
work may imply original authorship, endorsement, or official affiliation
without explicit written permission.
<!-- DUAL-LICENSE-END -->
