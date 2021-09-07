# Content Guide

This content guide is for Crunchy Data employees to use as a general reference for creating technical content (user guides, READMEs, etc.). The repository contains a collection of Markdown files:

- [index.md](content/_index.md) is for the homepage
- [01-tldr.md](content/01-tldr/_index.md) is intended to highlight the most important points throughout the guide
- [06-writing-technical-content.md](content/06-writing-technical-content/_index.md) is a collection of *writing* guidelines that apply to any kind of technical content
- There are specific sections for user guides, READMEs, blog posts, and learn.crunchydata.com (Katacoda) - more may be added later if necessary 

## Update, Build, and Deploy

The content guide site can be acessed at https://crunchydata.github.io/doc-content-guide/

The site is built with Hugo and is hosted on GitHub Pages. It uses the [Crunchy Hugo theme](https://github.com/CrunchyData/crunchy-hugo-theme) which has been added to this project as a git submodule.

Add new content under the `content/` directory. Run `hugo new` to add a new page, e.g.:

    hugo new general/new_page.md

To create a new top-level section, create a new subdirectory that contains an `_index.md`. This creates a [branch bundle](https://gohugo.io/content-management/page-bundles/) which allows a section to have multiple subsections (even nested ones if desired). Even if the section currently contains only one page, this makes it easier to expand the section in the future.

    hugo new <name-of-section>/_index.md

To deploy, first run Hugo to build:

    hugo

The site pages will be generated under `docs/`. This folder has been configured as the [publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages#publishing-sources-for-github-pages-sites) for the site. 

## Credits

The content guide was adapted from Mailchimp's [Content Style Guide](https://github.com/mailchimp/content-style-guide), under the CC [Attribution-NonCommercial 4.0 International](https://github.com/mailchimp/content-style-guide/blob/master/LICENSE.md) license.
