# Glassbro Blog

Code for Glassbro Blog.

## Publish

To publish changes to the blog, run:

``` sh
quarto render posts/path/to/index.qmd --to html
git add --all .
git commit -m "New post: etc"
quarto publish
```
