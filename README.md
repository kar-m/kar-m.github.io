# Karen Mosoyan

Research portfolio and writing: <https://kar-m.github.io/>

The site uses GitHub Pages and Jekyll. GitHub builds and publishes updates to
the `main` branch from the repository root. The home page is `index.html`,
and its styles are in `style.css`.

## Add a post

1. Create `_posts/YYYY-MM-DD-your-title.md` with the actual publication date.
2. Start with the following front matter, then write the post in Markdown:

   ```markdown
   ---
   title: "Your post title"
   ---

   Your Markdown content goes here.
   ```

3. Commit the file to `main`. Once GitHub Pages finishes deploying, the post
   appears in the home page's Writing section, newest first, with its own URL
   at `/blog/YYYY/MM/DD/your-title/`.

The post layout is set automatically. Optional front matter includes
`description: "A short summary"` and `published: false` to hide a draft from
the generated site. This is a public repository: draft source committed here
is still public. Keep private drafts outside this repository.

Store public post images in `assets/` and reference them as
`![Descriptive alt text](/assets/filename.png)`. No posts are included yet.

## Preview locally

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

Open <http://127.0.0.1:4000>. To build without serving, run
`bundle exec jekyll build --safe`. Generated output goes to `_site/`, which is
ignored by Git. Repository instructions and build dependency files are excluded
from the generated website.
