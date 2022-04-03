# Andrew's Blog Rocks

This repository hosts the code for Andrew Mitchell's personal blog (located at [andrewsblog.rocks](https://andrewsblog.rocks)).

Currently I have my blog deployed via Cloudflare Pages. If anyone is using this project as a base and doing something similar, remember to set the `HUGO_VERSION` env var to the version you're using as Cloudflare Pages by default uses a really old version of Hugo (see [Cloudflare Pages known issues](https://developers.cloudflare.com/pages/platform/known-issues/)).

* To build, simply type Hugo and the built directory will be named `public`.
* To run a local dev server type `hugo server` or with drafts enabled type `hugo server -D`.
* To create a new post type `hugo new posts/post-name.md` from the terminal.
