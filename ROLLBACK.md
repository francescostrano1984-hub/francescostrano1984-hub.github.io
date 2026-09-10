# Rollback

Before upload, archive the existing Aruba document root and record the deployment timestamp. To roll back, restore that archive, verify HTTPS/host redirects, then check the home page, contact route, one service route, one guide route, `robots.txt`, sitemap, and `404.html`.

If only a bad redirect is introduced, restore the previous `.htaccess` first and verify Apache syntax before restoring content.
