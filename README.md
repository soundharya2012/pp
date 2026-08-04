# Power Platform guides

Interactive, single-file decision guides for Microsoft Power Platform, published with GitHub Pages.

**Live site:** https://soundharya2012.github.io/pp-guides/

| Guide | What it answers |
|---|---|
| [Developer vs Sandbox vs Production](power-platform-environments.html) | Which environment type to use, and the licensing, capacity, backup and copy/restore consequences of that choice |

## How these are built

Each guide is one self-contained `.html` file: inline CSS, inline JavaScript, no external
requests, no build step needed to view it. That means it renders identically from a web
server, a file share, or a local download, and it keeps working offline.

Content is compiled from Microsoft Learn and carries the verification date in the footer.

## Embedding in a blog

WordPress.com free and Personal plans strip `<script>` and `<iframe>`, so these guides can't
be embedded there. Link to them instead. Self-hosted WordPress and the WordPress.com
Business plan can embed them in an iframe.
