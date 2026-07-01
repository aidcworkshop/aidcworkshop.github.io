# Jekyll Workshop Website Template

This is a GitHub Pages-ready Jekyll template for an academic workshop site.

## Local Preview

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000`.

## Customize

Most page content lives in `_data/workshop.yml`:

- workshop title, date, location, and intro
- navigation labels
- overview text
- speakers and agenda
- CFP dates and topics
- organizers

## Deploy On GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repository settings, enable GitHub Pages.
3. Use the included workflow, or set Pages to deploy from the `main` branch.

If your site is served from a repository path such as `https://username.github.io/repo-name/`, set `baseurl: "/repo-name"` in `_config.yml`.
