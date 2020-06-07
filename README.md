# Setup

- [Jekyll 4.1.0](https://jekyllrb.com/)
- [Minima theme](https://github.com/jekyll/minima) inlined and customised
- [GoatCounter](https://chirag.goatcounter.com)
- [Netlify](https://app.netlify.com/sites/chatty-kikwi-42/deploys)

  - Build command: `jekyll build`
  - Publish directory: `_site/`
  - Environment variables: `JEKYLL_ENV=production`

## Running locally

`bundle exec jekyll serve --host 0.0.0.0 --drafts`

- Serves the website on `localhost:4000`
- `--host 0.0.0.0`: Allows other devices on your network to access
- `--drafts`: Displays posts in `__drafts` folder as if they were published today
