# My website

A plain HTML + CSS personal site: no build step, no frameworks, nothing to install.

| File | What it is |
|---|---|
| `index.html` | Home page |
| `ideas.html` | Ideas and planned projects (each has a page in `projects/`) |
| `blog.html` | List of blog posts |
| `blog/*.html` | One file per post |
| `shelf.html` | Books, films and shows |
| `resume.html` | Resume |
| `style.css` | All colors, fonts and layout |
| `script.js` | Dark-mode toggle, phone menu, scroll animations |

**Add your photo:** put `me.jpg` in this folder and replace `<div class="initials">VP</div>` in `index.html` with `<img src="me.jpg" alt="Varun Pritham">`.

Search the files for `EDIT:` to find every spot to fill in.

**Adding a blog post:** copy `blog/hello-world.html`, rename it (e.g. `blog/my-new-post.html`), write the post, then add a line for it in `blog.html` (and on the home page under "Latest writing").

---

## Hosting it online for free: GitHub Pages ($0)

You get an address like `https://YOUR-USERNAME.github.io`, with no ads and no time limit.

1. Create a free account at <https://github.com/signup>.
2. Create a new repository at <https://github.com/new>:
   - **Repository name:** `YOUR-USERNAME.github.io` (use your exact username; this gives you the short address)
   - Set it to **Public**, then click **Create repository**.
3. On the new repo page, click **"uploading an existing file"**. Drag in **everything inside this folder** (`index.html`, `style.css`, the `blog` folder, etc.; not the folder itself). Click **Commit changes**.
4. Go to **Settings → Pages**. Under "Branch", choose `main` and `/ (root)`, then click **Save**.
5. Wait about a minute, then visit `https://YOUR-USERNAME.github.io`. That's it.

**To update the site later:** edit the files here, then upload the changed files to the repo the same way. The site refreshes within a minute.

### Adding your own domain later (optional, about $10–12/year)
Buy a domain (Cloudflare Registrar and Porkbun sell at cost). In the repo, go to **Settings → Pages → Custom domain**, enter it, and follow GitHub's DNS instructions. Hosting stays free.

### Alternative: Netlify Drop (also free, even quicker)
Go to <https://app.netlify.com/drop> and drag this whole folder onto the page. You get a link instantly; create a free account to keep it permanently.
