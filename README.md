<p align="center">
  <a href="https://www.valisoft.net">
    <img alt="VALISOFT" src="https://www.valisoft.net/static/3db2e06a9b6a1199b4a018386ef35215/1b5b9/roundel.png" width="60" />
  </a>
</p>
<h1 align="center">Personal Gatsby Website Template</h1>

Jump into building your own personal static website with this GatsbyJS template.

Don't know React or GatsbyJS? That's fine! This template embraces Jamstack
principles, and is set up to allow you to customize your site quickly without
actually interacting with the core of the frontend implementation.

The only thing you need to do is edit some markdown files in `data/`.

## Metadata

Metadata is contained within `data/meta.json`; this centralizes key site
information.

### `siteTitle`

The title of your website (displayed as the tab title).

### `siteDescription`

Your site description (required for SEO, will be displayed in search engine
results).

### `siteUrl`

The URL of your site (required for SEO, used to generate `robots.txt` to allow
search engines to crawl your site more effectively). When in development, go
ahead and supply the URL you expect to host your website at.

### `avatarUrl`

The URL to your avatar resource of choice (must be a square image). If you do
not have an avatar hosted somewhere, you can supply your own via
`assets/profile.png` (square rule still applies).

**NOTE:** If supplying your own avatar, you must leave this field blank. Any
link supplied will override `assets/profile.png`.

### `name`

Your name (make it look neat!) which appears as the headline of your site and in
the Copyright notice in the footer.

### `location`

Displayed beneath your name as your current location.

### `links`

Links which will be displayed in a nav bar beneath your location. Go ahead and
put what you want here!

**NOTE:** `links` expects an array of `link` JSON objects, which have `title`
and `url` properties.

## Profile Content

Each markdown (`.md`) file in `data/` correlates to a section displayed on your
profile. The `title` frontmatter field of each file determines which profile tab
the content will be displayed in; possible values are: `Bio`, `Resume`, `CV`,
`Portfolio`, and `Contact` (these should be unique).

Remember, HTML is perfectly acceptable Markdown. You can copypasta some HTML
from an existing webpage or use an [online tool](https://word2md.com/) to
convert documents such as `.docx` files into HTML or Markdown.

## Deployment

This template is set up to deploy to GitHub Pages.

Enable GitHub Pages, edit `pathPrefix` in `gatsby-config.js` to be
`/<YOUR_REPO_NAME>`, then run `npm run deploy` to deploy this site at
`https://<YOUR_GITHUB_USERNAME>.github.io/<YOUR_REPO_NAME>`.

Consult
[Gatsby's deployment documentation](https://www.gatsbyjs.com/docs/deploying-and-hosting/)
on how to deploy sites built with this template.
