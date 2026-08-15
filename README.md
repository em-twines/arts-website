# Emily Delbridge — Portfolio

Source for [em-twines.github.io/arts-website](https://em-twines.github.io/arts-website/), a Jekyll portfolio site for Emily Delbridge (Twines) — interdisciplinary performance and technology artist, writer, and software engineer.

----------

## Local development

Requires [Ruby](https://www.ruby-lang.org/) and [Bundler](https://bundler.io/) (`gem install bundler`).

1. Install dependencies:
   ```
   bundle install
   ```
2. Start the local server:
   ```
   bundle exec jekyll serve
   ```
3. Visit `http://localhost:4000/arts-website/` in your browser (the `/arts-website/` path comes from `baseurl` in `_config.yml`). Jekyll rebuilds automatically as you edit files — refresh the page to see changes.

Site config (title, description, nav links, social usernames) lives in `_config.yml`.

## Deploying

This is a GitHub Pages **project site**, served directly from the `gh-pages` branch — there is no separate build/deploy step. Commit and push to `gh-pages` and GitHub Pages republishes automatically within a minute or two:

```
git push origin gh-pages
```

## Structure

- `_layouts/` and `_includes/` — shared page chrome (head/meta, nav, footer)
- `interactive/`, `film/`, `criticism/`, `tech/`, `about/` — the site's main sections, each with its own `index.html` gallery/listing page and per-work subpages
- `img/`, `css/`, `js/` — static assets

----------

## Credits

Originally built on the [Photorama](https://github.com/sunbliss/photorama) Jekyll theme by Filippo Oretti and Dario Andrei, itself based on [Clean Blog](https://github.com/BlackrockDigital/startbootstrap-clean-blog-jekyll).

## License

The MIT License (MIT)

Copyright (c) 2014 Filippo Oretti, Dario Andrei

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
