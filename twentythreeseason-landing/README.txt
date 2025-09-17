TWENTY THREE SEASON — Landing Page (One-file deploy)

Files:
- index.html (single page app)
- README.txt (this file)

How to deploy (choose ONE):

A) Netlify (drag & drop)
1) Go to https://app.netlify.com/drop
2) Drag index.html onto the page.
3) Netlify gives you a live URL instantly. Copy it to your Instagram bio.

B) GitHub Pages
1) Create a new GitHub repo (public is fine).
2) Upload index.html to the repo root.
3) Repo Settings -> Pages -> Source: 'Deploy from a branch' -> Branch: main, Folder: / (root), Save.
4) Wait a minute -> Site appears at https://<yourname>.github.io/<repo-name>/

C) Cloudflare Pages
1) Go to https://pages.cloudflare.com/ -> Create a project -> Direct Upload.
2) Upload index.html.
3) You'll get a URL like https://<project>.pages.dev

Custom Domain (optional)
- Buy a domain from a registrar (Namecheap/GoDaddy/etc).
- In your host (Netlify/Cloudflare/GitHub), add the domain under "Domains".
- Copy the DNS records they show you into your registrar's DNS settings.
- Wait up to 30 minutes for DNS to update.
