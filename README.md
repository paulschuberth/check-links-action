# Check Links Action

This is a very basic composite action that uses `wget` to check recursively if links
on a page a reachable.

## Usage:

```yaml
      - name: Check Links
        uses: paulschuberth/check-links-action@v1
        with:
          # Required: The Url from which wget starts to crawl the website
          start-url: 'http://localhost:1313'

          # Optional:
          broken-link-message: 'broken link!'
```
