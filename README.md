# smahato.com

Personal consulting site for SMahato Consulting, served via GitHub Pages at
[smahato.com](https://smahato.com). Built with Jekyll.

## How to publish a blog post

1. Create a file in `_posts/` named `YYYY-MM-DD-your-title.md` — the date and
   the title in the filename set the publish date and the URL.
2. Put this front matter at the top:

   ```yaml
   ---
   title: "Your post title"
   date: 2026-07-21
   description: "One or two sentences — shows on the blog list and in link previews."
   ---
   ```

3. Write the body in Markdown below the front matter.
4. Commit and push to `main`. GitHub rebuilds the site automatically; the post
   is live at `https://smahato.com/blog/your-title/` within a minute or so.

That's it — no HTML, no build step to run yourself.

### Markdown cheatsheet

```markdown
## Heading
**bold**  *italic*  [link text](https://example.com)

- bullet
1. numbered

> blockquote

`inline code`

![alt text](/assets/image.png)   <!-- put images in an /assets folder -->
```

## Site structure

| Path | What it is |
|------|------------|
| `index.html` | Homepage sections (front matter + verbatim markup) |
| `blog/index.html` | The blog listing page |
| `_posts/` | Your blog posts (Markdown) |
| `_layouts/default.html` | Shared shell: `<head>`, CSS, nav, footer, scripts |
| `_layouts/post.html` | Wrapper for a single blog post |
| `_includes/` | `nav.html`, `footer.html`, `scripts.html` |
| `_config.yml` | Site settings |
| `favicon.svg` | Browser tab icon (the mountain logo) |

## Preview locally (optional)

GitHub builds the site on push, so this is only if you want to see changes
before publishing:

```bash
bundle install
bundle exec jekyll serve
# open http://localhost:4000
```
