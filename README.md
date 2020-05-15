# lancevadla.com

A markdown-powered blog built with [Sapper](https://github.com/sveltejs/sapper) and [Svelte](https://github.com/sveltejs/svelte).

Consult [sapper.svelte.dev](https://sapper.svelte.dev) and [svelte.dev](https://svelte.dev) for help getting started.

## 🏗 Structure

The base structure of this template is the same as Sapper's [default template](https://github.com/sveltejs/sapper-template/). These are some of the new things you'll find here:

### src/routes/blog

- `_posts.js`: this module contains the logic for loading and parsing markdown posts.
- `[slug].svelte`: this is the template of a blog post.
- `index.svelte`: this is the template of the blog list page.

### src/routes/blog/posts

This is where markdown posts live. All `.md` files in this directory are treated as blog posts and parsed automatically by the `_posts.js` module.

- The markdown file name becomes the post slug. For example `hello-world.md` becomes `http://localhost:3000/blog/hello-world`.
- Everything between the start of the post and the `<!-- more -->` tag becomes the article's "excerpt".
- Frontmatter properties supported are `title` and `date`.

## 🐛 Bugs

Sapper is in early development, so check the [Sapper issue tracker](https://github.com/sveltejs/sapper/issues) if you have any problems.
