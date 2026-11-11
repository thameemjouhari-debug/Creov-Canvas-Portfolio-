# Creov Canvas portfolio

Static portfolio site, no build step. Everything is controlled from the Admin page.

## 1. Publish on GitHub Pages
1. Create a repository and upload everything in this folder (index.html, projects.json, images/).
2. Settings -> Pages -> Deploy from a branch -> `main` and `/ (root)`.
3. Your site appears at `https://<username>.github.io/<repository>/`.

## 2. Open Admin
Scroll to the Contact page and click **Admin** at the bottom, or add `#admin` to the web address.

First time on each device:
1. Create a GitHub token: GitHub -> Settings -> Developer settings -> Personal access tokens -> Fine-grained tokens. Choose only your portfolio repository and set **Contents: Read and write**.
2. In Admin enter `username/repository`, the branch (`main`), the token, and a new admin password (8+ characters).
3. The token stays only in that browser, locked by your password. Afterwards you only type the password.

## 3. What Admin controls
- **Brand, home and menu:** site name, tab title, logo, portrait, About, skills, scroll hint, footer text, menu labels.
- **Contact and links:** email, Behance, Instagram, LinkedIn, WhatsApp, plus any extra links.
- **Pages and sections:** reorder, hide or show every page; add new Text, Image or Big-statement pages (optionally in the menu); edit or delete them.
- **Categories:** add, rename, delete (when empty).
- **Works:** add projects, move between categories, reorder, delete.
- **Look and limits:** theme, colours, font, scroll speed, max categories, max projects per category.
- **Admin password:** change it.

Each save is committed to your repository; the live site updates about a minute later. Visitors never see Admin controls, and GitHub refuses changes from anyone without your token.

## Navigation
Mouse wheel, swipe, arrow keys, or the dots on the right.
