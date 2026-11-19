# qikly-redirect

test.qikly.com moved to qikly.com. This GitHub Pages site keeps the old
address working: every page, at any path, forwards to the same path on
qikly.com and keeps the query, so `?ref=badge` links still count.

- `index.html` handles the root; `404.html` (the same page) handles every
  other path, because Pages serves it for anything it does not find.
- `images/` holds copies of the icons and the social card, because an image
  cannot be forwarded by a page. Released versions of qikly name these
  addresses in their MCP registry entry. Keep them until no supported
  release points at test.qikly.com.
- `CNAME` is `test.qikly.com`. Set it as this repo's custom domain only in
  the switch window, after gal-a/qikly's site has moved to qikly.com: a
  domain belongs to one Pages site at a time.
