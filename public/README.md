Public folder for static assets (images)

Place images in `public/images/` and reference them from your site using absolute paths. Examples:

- Markdown: `![Alt text](/public/images/photo.jpg)`
- HTML: `<img src="/public/images/photo.jpg" alt="Alt text">`

Files under `public/` are served as static files at `/public/...` in most hosting setups. If you use Jekyll or another static site generator, ensure the folder is copied to the output (it usually is by default).