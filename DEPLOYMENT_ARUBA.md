# Aruba deployment checklist

1. Back up the current Aruba document root.
2. Upload the reviewed static snapshot, including route folders, `assets/`, `.htaccess`, `robots.txt`, `sitemap.xml`, and `404.html`.
3. Confirm HTTPS and the canonical host redirect.
4. Check representative route status codes, trailing slashes, legacy redirects, 404 behavior, CSS, JS, and images.
5. Verify `robots.txt`, sitemap URLs, and canonical metadata on the production host.
6. Do not change DNS, WordPress, or cut over traffic as part of this repository workflow.

The original generator and redirect source map were not included, so do not regenerate `.htaccess` until those sources are restored.
