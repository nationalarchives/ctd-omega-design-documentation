# [ctd-omega-design-documentation](https://nationalarchives.github.io/ctd-omega-design-documentation/)

Design decisions and wireframe changes

## Sprint notes

Our sprint notes are hosted on [GitHub Pages](https://pages.github.com/).

- `_config.yml` is the [Jekyll](https://jekyllrb.com/) configuration.
- `index.md` is the contents of the site’s homepage.
- `_posts/` contains individual sprint notes, listed on the homepage from newest to oldest.

### Publishing notes

You can use the editor built into GitHub to maintain and preview the content of the site in [Markdown](https://guides.github.com/features/mastering-markdown/) files.

When creating a new post,

- The post’s filename needs to start with a date in the YYYY-MM-DD format: for example, `2021-11-24-sprint-1-notes.md`.
- The post title should be wrapped in quotes, for example: `title: "This week’s sprint"`

The [live site](https://nationalarchives.github.io/ctd-omega-design-documentation/) automatically updates whenever making changes in GitHub.

### Adding images

1. In GitHub, upload the image file in the `images/` folder.
2. Reference the image with the correct path and file name from your post, with appropriate alt text: `![Image alt text](/ctd-omega-design-documentation/images/my-file-name.png)`.

Or with a link over the image:

```markdown
[![Image alt text](/ctd-omega-design-documentation/images/my-file-name.png)](https://www.example.com/)
```

nb. Image does not display if you go directly to the linking file in the folder but does at https://nationalarchives.github.io/ctd-omega-design-documentation/
