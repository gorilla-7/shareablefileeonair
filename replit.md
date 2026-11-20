# Running this project on Replit

This is a static HTML redirect page. The Replit preview is served with:

```sh
python3 -m http.server 5000 --bind 0.0.0.0
```

Publishing is configured as a static site with the project root as its public
directory; no build step or secrets are required. The page redirects visitors
to `https://nataleereed.com/quotation/index.html` and appends the browser URL
fragment to that destination.
