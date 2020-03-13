# jekyll-theme-console

## Usage

-   Create a new post in the _posts directory and fill out the relevant YAML fields
-   Make a 250x200 thumbnail and drop it in the thumbnails directory. List its filename in the post's markdown file.

In addition to jekyll's default configuration options, you can provide:
- `header_pages` to specify which pages should be displayed in navbar
- `footer` string, which will be inserted on the end of the page (doesn't support markup, but html)
- `google_analytics` tracking id (tracking will be enabled only in production environments)
- `listen_for_clients_preferred_style` boolean, used to allow users to choose theme based on their preferences (mostly affected by OS dark or light theme, details see https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme)

```yaml
header_pages:
  - index.md
  - about.md

style: dark # dark (default) or light
listen_for_clients_preferred_style: true # true or false (default)

footer: 'follow us on <a href="https://twitter.com/xxx">twitter</a>'

google_analytics: UA-NNNNNNNN-N
```


## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
