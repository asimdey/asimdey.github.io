# Asim Kumer Dey — Academic Website

This Quarto project is configured for the GitHub Pages user site:

https://asimdey.github.io

## Repository name

Create the GitHub repository exactly as:

`asimdey.github.io`

## Preview locally

1. Install Quarto from https://quarto.org/docs/get-started/
2. Open a terminal in this folder.
3. Run `quarto preview`.

## Publish

From this project folder, run:

```bash
git init
git add .
git commit -m "Create academic website"
git branch -M main
git remote add origin https://github.com/asimdey/asimdey.github.io.git
git push -u origin main
quarto publish gh-pages
```

When prompted by Quarto, confirm GitHub Pages publishing. The public website will be available at https://asimdey.github.io.

## Updating the website later

Edit the `.qmd` files, then run:

```bash
git add .
git commit -m "Update website"
git push
quarto publish gh-pages
```

The CV is stored in `files/Asim_Dey_CV.pdf`.
