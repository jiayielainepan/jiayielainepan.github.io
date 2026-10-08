# Elaine Pan – personal website

A plain static site (HTML + CSS, no build step), migrated from
<https://sites.google.com/umich.edu/jiayi-pan>. It is served by GitHub Pages.

## Structure

| File | Page |
| --- | --- |
| `index.html` | Home: photo, bio, education, experience, contact |
| `research.html` | Research interests, projects, publications & presentations |
| `cv.html` | CV (embeds `assets/files/cv.pdf`) |
| `assets/css/style.css` | Styles (supports light and dark mode) |
| `assets/img/` | Images. Put your photo here as `profile.jpg`. |
| `assets/files/` | Downloads. Put your CV here as `cv.pdf`. |

To add a page, copy `research.html`, change its content, and add a link to it in the `<nav>` of every page.

## Preview locally

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Publish with GitHub Pages

1. Merge into the default branch (`main`).
2. On GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, and save.
4. The site goes live at `https://<username>.github.io/<repo>/` within a minute or two.
   If you rename the repo to `<username>.github.io`, it is served at `https://<username>.github.io/`.

## After the move

- On the Google Site, add a notice linking to the new URL, or unpublish the old site.
- Update the website link on Google Scholar, GitHub, LinkedIn, and your email signature.
