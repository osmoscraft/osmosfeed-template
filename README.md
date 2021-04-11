This is a self-hosted RSS feed. Please refer to the [latest documentation](https://github.com/osmoscraft/osmosfeed).

- The site is statically hosted by GitHub Pages. There is no server to fetch content on the fly.
- The content is updated periodically by GitHub Actions, configured in `/.github/workflows/update-feed.yaml`.
- The source of the content can be any RSS feed URL, configured in `/osmosfeed.yaml`.
- The content fetching and static site generation is powered by [osmosfeed](https://github.com/osmoscraft/osmosfeed).
