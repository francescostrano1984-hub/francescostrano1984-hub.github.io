# STR Sgomberi static site

Static HTML site for STR Sgomberi, serving Catania and provincia. The repository currently contains the published snapshot: route folders, shared CSS/JS, images, `.htaccess`, `robots.txt`, `sitemap.xml`, and `404.html`.

## Local preview

Serve this directory with any static HTTP server. Do not open HTML files directly when checking canonical URLs, redirects, or asset paths.

## Important scope note

The original generator, source data, migration maps, and Lighthouse evidence were not present in the cloned branch. This snapshot can be maintained safely, but a deterministic rebuild pipeline must be restored before generated output is regenerated.

Production domain: `https://www.sgomberocatania.it/`

See `OPEN_DECISIONS.md` for unresolved source/build decisions.

## Publishing

Review the generated HTML and run the validation checks before uploading to Aruba or changing DNS. No deployment or cutover is performed by this repository workflow.

## License and content

Business copy, contact details, and media belong to the site owner. Verify claims and image rights before publication.

## Staging

Use a separate host or directory-level environment for staging. Staging must be protected from indexing with HTTP authentication and a `noindex` response/meta directive; never change production canonicals or sitemap files for staging.
