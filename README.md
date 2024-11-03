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

You may need to go to the GitHub repo > Settings > Pages menu, then reenter the custom domain for DNS checking.
