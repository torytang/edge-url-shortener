## Edge URL Shortener

The edge URL shortener uses Workers and Workers KV.

Slugs and redirection URLs can be added and modified from the Cloudflare KV
Dashboard dynamically.

The slug is case-insensitive. For instance, https://{your_domain}/SLUG and
https://{your_domain}/slug will be redirected to the same destination.

The redirected URL can be any URLs, including external domains and different
protocols.

