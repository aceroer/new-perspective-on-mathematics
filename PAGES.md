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

## Article Pages

Each article has its own HTML abstract page and a searchable PDF in `papers/`.
Link articles from `papers/index.html` and their issue page. Keep the title,
author, publication date, issue, and absolute `citation_pdf_url` consistent with
the visible article details. Do not invent an ISSN, volume, pagination, or DOI.

The initial Collatz entry reproduces manuscript version 0.2 from Zenodo record
20535479 (publication date 2026-06-04, creator Wangyue). Its PDF is unchanged:

- Source: https://zenodo.org/api/records/20535479/files/eulerian_collatz_method.pdf/content
- Size: 218404 bytes
- MD5 recorded by Zenodo: `725244c6bd0fb0d53834e6cf49de8a03`
- PDF license: CC BY 4.0, retained from that record rather than replaced by the site license.

For new versions, retain the existing version URL or introduce a distinct URL;
do not replace a PDF while retaining another version's DOI and metadata.
The HTML carries author and date metadata because the archived PDF omits them
on its title page. Search indexing and timing are controlled by Google Scholar,
not by successful Pages deployment.

## Site Edits

For ordinary site edits:

```bash
git status --short
git add .
git commit -m "Update NPM site"
git push
```

## Boundary Scan

Before publishing, run the public hygiene scan used by the main workflow
repository.  The scan should check for unfinished placeholders, restricted labels,
local machine paths, and credential-like strings.

Keep the command text outside this public Pages repository to avoid matching
the scan pattern inside the operations note itself.
