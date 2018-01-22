# Hyperdoc

A distributed blogging and documentation tool powered by the [Dat](https://www.datproject.org/) protocol.

It extends the functionality of the [Dat client](https://github.com/datproject/dat), and allows you to create a blog or wiki that could be synchronized over the p2p network and served by webbrowser.

## Installation

> npm install -g hyperdoc

## Blog App

Create your blog:

> hyperdoc create --type=blog

Edit the blog post in the `_posts` directory in markdown format with name like `_posts/2018-01-01-first-blog.md`

Commit new files to dat:

> hyperdoc commit

Generate index.json for the blog:

> hyperdoc index

Serve the blog:

> hyperdoc serve

Then open `http://localhost:3300/` to see the blog.

## Doc App

Create your doc app:

> hyperdoc create --type=doc

Just edit any markdowns in the repository, and `README.md` would be the home page.

Commit new files to dat:

> hyperdoc commit

Serve the doc:

> hyperdoc serve

Then open `http://localhost:3300/` to see it.


## Acknowledgement and License

The documentation app is inspired from and based on [docsify](https://docsify.js.org/), which is a lean and beautiful alternative to gitbook. The blog theme is based on [scribble](https://github.com/muan/scribble).

MIT License

