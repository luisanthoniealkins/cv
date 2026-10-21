# Luis Anthonie Alkins — CV

Suggested GitHub repository name: `cv`.

This folder is the repository root. Upload its contents, rather than the entire Curriculum Vitae workspace or the enclosing github-pages folder.

## Structure

```text
index.html                         Homepage
backend/index.html                 Lead Backend CV
files/lead-backend-oct-2026.pdf     Downloadable application PDF
.nojekyll                          Serve as a plain static site
```

The HTML preserves the approved contact details, including the phone number. The downloadable PDF is the existing ReportLab version; replace it with your preferred browser-exported PDF when ready.

## Publish

Create a repository named `cv` and add the contents of this folder to its main branch. In the repository's Pages settings, configure publishing from the main branch, root directory.

Expected URLs:

- `https://YOUR_USERNAME.github.io/cv/`
- `https://YOUR_USERNAME.github.io/cv/backend/`

Nothing in this local folder publishes automatically until a remote repository and Pages deployment are configured.

## Add a CV variant

1. Create a folder such as `architect/`.
2. Put that variant's HTML in `architect/index.html`.
3. Place its PDF in `files/`.
4. Add a card linking to both files in the homepage.
5. Update that variant's download link.

Use relative links so the site works under the repository path. Only create navigation entries for variants that exist.

## Update this version

The site files are independent copies of the October 2026 artifacts. Updating the Markdown draft does not automatically update this folder. Copy or regenerate the corresponding HTML and PDF when the CV changes.

For a browser-generated PDF, choose A4, 100% scale, and disable browser headers and footers. The navigation controls are hidden during printing.
