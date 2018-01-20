# Hyperdoc

A distributed documentation and blogging tool powered by the [Dat protocol](https://www.datproject.org/).

It inherits most functionalities from [the Dat client](https://github.com/datproject/dat). To init a blog, just add `--type=blog` option when creating the Dat, which will generate extra files and metadata for blogging. In the same way, you could add `--type=doc` option to generate a documentation repository.

## Installation

> npm install -g hyperdoc

## Blog App

Create your blog:

> dx create --type=blog

Edit the blog post in the `_posts` directory with markdown format with name like `_posts/2018-01-01-first-blog.md`

Generate index.json for the blog:

> dx index

Serve the blog:

> dx serve

Then open `http://localhost:3300/` to see the blog.

## Doc App

Create your doc app:

> dx create --type=doc

Just edit any markdowns in the repository, and `README.md` would be the home page.

Serve the doc:

> dx serve

Then open `http://localhost:3300/` to see it.


## Acknowledgement and License

The documentation app is inspired from and based on [docsify](https://docsify.js.org/), which is a lean and beautiful alternative to gitbook. The blog theme is based on [scribble](https://github.com/muan/scribble).

MIT License

