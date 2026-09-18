Made some chanes to the html files which include:
- `index.html`: 8 `<section>` tags were opened but only 2 closed, leaving six homepage sections nested inside one another; all sections are now balanced and properly closed.

- `news.html`: 4 `<section>` tags opened, only 2 closed (Latest Reviews and Trending were left open); now balanced.
- `anime.html`: the `id="catalogue"` section was never closed, and a stray `</main>` tag was sitting inside `<header>` with no matching opening tag; both fixed, and the characte spotlight is now its own properly closed  section.
- `enquiry.html`: a duplicate `</main>` closing tag (closed twice in a row) was removed.

- `about.html`: the last nav `<li>` was missing its closing `>` (`</li` with no bracket); fixed.

- Removed a duplicate `<h1>` per page — the header brand name ("AniOrbit") is no longer marked up as a heading, so each page now has exactly one `<h1>` (the page title).

