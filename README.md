# Madeline Carlton Portfolio Site

A simple static portfolio site for GitHub Pages.

## Files

- `index.html` — page content
- `styles.css` — visual design
- `images/` — put artwork photos here

## How to add artwork

Put image files inside `images/`, then replace a placeholder like:

```html
<div class="placeholder clay">Add image</div>
```

with:

```html
<img class="art-image" src="images/my-artwork.jpg" alt="Short description of the artwork">
```

Then edit the title, medium, year, and description in the `figcaption`.

## Custom domain

After buying a domain, add it in GitHub:

Repository → Settings → Pages → Custom domain

GitHub will create or use a `CNAME` file. If you add it manually, the file should contain only the domain name, for example:

```txt
madelinecarlton.com
```
