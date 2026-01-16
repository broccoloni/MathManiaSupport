# Math Mania — Support Site (GitHub Pages)

This is a tiny static support + privacy site you can host for free on GitHub Pages.

## 1) Create a repo

Create a new GitHub repository, e.g. `math-mania-support`.

## 2) Add these files

Commit the files in this folder to the repo root:

- `index.html` (Support + contact)
- `privacy.html`

## 3) Enable GitHub Pages

In the repo:

- **Settings → Pages**
- **Build and deployment → Source**: *Deploy from a branch*
- **Branch**: `main` and folder `/ (root)`

After saving, your site will be available at:

`https://<your-username>.github.io/<repo-name>/`

## 4) Add a contact form (Formspree)

GitHub Pages is static, so forms need a third-party handler.

1. Create a free Formspree form
2. Copy the form endpoint (looks like `https://formspree.io/f/xxxxxx`)
3. Paste it into `index.html` (replace `REPLACE_ME`)

## 5) Link it from your app

Use the same URL in:

- App About screen “Support” link
- Google Play “Support URL” (if you choose to provide one)
- Privacy policy link fields
