# apps.memair.com

The Memair app directory is closed for now. This repo serves one page at [apps.memair.com](https://apps.memair.com) that says so and links to the [developer docs](https://docs.memair.com).

Apps can still connect to Memair through OAuth and the GraphQL API. The docs explain how.

## Keep the `CNAME` file

The `apps.memair.com` DNS record points at GitHub Pages. While this repo publishes a site with that `CNAME`, the subdomain shows a page Memair owns. A DNS record that points at GitHub Pages with no site behind it is open to a domain takeover ([GitHub Docs, "Securing your custom domain"](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#securing-your-custom-domain)). To retire the subdomain, remove the DNS record first.

## Bringing the directory back

The listings, the gallery layout and its assets are in the git history. Commit `ade2a81` is the last one with the directory in place.
