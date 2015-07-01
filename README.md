# Getting Started
## Basics
**Workflow TBD**

Work in the branch gh-pages. That's the branch that is shown to public.

For simple edits, can just go to https://github.com/LoyalSphere/docs, change branch from master (default) to gh-pages, find the relevant file (index.md in appropriate folder), and edit it.

If you work more often, clone GIT to local using Clone in Desktop button at the above page.

## Jekyll
If you want to preview your changes before you commit to GIT, you need to use Jekyll locally.

1. bundle install (from docs directory)
2. bundle exec jekyll serve
3. http://localhost:4000/docs/


## Picnic
Stellar Docs repository was forked from Picnic.

[![Release](http://img.shields.io/github/release/kasperisager/picnic.svg?style=flat)](https://github.com/kasperisager/picnic/releases)

Picnic is a documentation template for Jekyll that came to life out of the need of having a simple and elegant way to write, view, and search documentation for projects of all sizes.

Picnic is heavily inspired by existing projects such as [Slate](https://github.com/tripit/slate), [Daux.io](https://github.com/justinwalsh/daux.io), and [Docco](https://github.com/jashkenas/docco). However, unlike these projects, Picnic is fully compatible with Jekyll-based GitHub Pages and can therefore be hosted without needing to be built beforehand.

Perhaps best of all, Picnic features full-text search using [lunr.js](http://lunrjs.com/). The search data is asynchronously streamed and indexed in chunks using [Oboe.js](http://oboejs.com/), so even if you have hundreds of pages it won't slow down your docs.

[__Watch Picnic in action__](https://kasperisager.github.io/picnic)

## Picnic in the wild

- [__Vanilla Forums__](https://vanillaforums.github.io/VanillaDocs)  
  API, developer, and end-user documentation for Vanilla Forums. This is where Picnic was born!

---
Copyright 2014 © [Kasper Kronborg Isager](http://kasperisager.github.io). Licensed under the terms of the [MIT License](LICENSE.md)
