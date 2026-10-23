# rickeroberts

Code for my personal website: a one-page site in plain HTML, CSS and JavaScript. There is no build step: open `index.html` in a browser to see it.

## Files

```
index.html            the page (header, hero, about, highlights, contact, footer)
css/styles.css        colors, fonts and layout (edit the :root tokens at the top)
js/main.js            mobile menu and footer year (optional; the page works without it)
assets/images/        hero photo and Ultraman poster
assets/icons/         icons for the contact links
assets/resume.pdf     add your résumé here, or remove the Résumé button
favicon.svg           browser tab icon (change "YN" to your initials)
```

## Making it yours

1. Search `index.html` for `[` and `REPLACE` and fill in each placeholder.
2. To swap a photo, put the new file in `assets/images/` and update the matching `<img>` `src` and `alt` (and the `og:image` tag for the hero photo).
3. The 1960s Ultraman / Speed Racer palette and fonts live in the `:root` block at the top of `css/styles.css`.
4. Update the email, LinkedIn and GitHub links in the Contact section, and delete any you don't use.

## Publishing

Any static host works. Upload the folder as it is:

- **GitHub Pages**: push to a repository, then turn on Pages under Settings → Pages.
- **Netlify** or **Cloudflare Pages**: drag the folder onto the dashboard.
- **University or campus web space**: copy the files into your public web folder.
