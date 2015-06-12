# Getting Started Working on Stellar Documentation
## Basics
Work in the branch gh-pages. That's the branch that is shown to public.

For simple edits, can just go to https://github.com/LoyalSphere/docs, change branch from master (default) to gh-pages, find the relevant file (index.md in appropriate folder), and edit it.

If you work more often, clone GIT to local using Clone in Desktop button at the above page.

## Jekyll
If you want to preview your changes before you commit to GIT, you need to use Jekyll locally.

a. bundle install (from docs directory)
b. bundle exec jekyll serve
c. http://localhost:4000/docs/


## Picnic
Stellar Docs repository was forked from Picnic.

Picnic is a documentation template for Jekyll that came to life out of the need of having a simple and elegant way to write, view, and search documentation for projects of all sizes.

Picnic is heavily inspired by existing projects such as [Slate](https://github.com/tripit/slate), [Daux.io](https://github.com/justinwalsh/daux.io), and [Docco](https://github.com/jashkenas/docco). However, unlike these projects, Picnic is fully compatible with Jekyll-based GitHub Pages and can therefore be hosted without needing to be built beforehand.

Perhaps best of all, Picnic features full-text search using [lunr.js](http://lunrjs.com/). The search data is asynchronously streamed and indexed in chunks using [Oboe.js](http://oboejs.com/), so even if you have hundreds of pages it won't slow down your docs.

[__Watch Picnic in action__](http://kasperisager.github.io/picnic)

---
Copyright 2014 © [Kasper Kronborg Isager](http://kasperisager.github.io). Licensed under the terms of the [MIT License](LICENSE.md)
