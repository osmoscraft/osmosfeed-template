# About

This is repository hosts the UI and content of an RSS feed reader.

## How does it work

- The site is statically hosted by GitHub Pages. There is no server to fetch content on the fly.
- The content is updated periodically by GitHub Actions, configured in `/.github/workflows/update-feed.yaml`.
- The source of the content can be any RSS feed URL, configured in `/osmosfeed.yaml`.
- The content fetching and static site generation is powered by [osmosfeed](https://github.com/osmoscraft/osmosfeed).
- The repository is generated from a [template](https://github.com/osmoscraft/osmosfeed-template).

## References

- [File an issue about the template](https://github.com/osmoscraft/osmosfeed-template).
- [File an issue about the tool](https://github.com/osmoscraft/osmosfeed).
- [The lastest documentation](https://github.com/osmoscraft/osmosfeed).
