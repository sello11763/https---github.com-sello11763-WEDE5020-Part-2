Made some chanes to the html files which include:
- `index.html`: 8 `<section>` tags were opened but only 2 closed, leaving six homepage sections nested inside one another; all sections are now balanced and properly closed.

- `news.html`: 4 `<section>` tags opened, only 2 closed (Latest Reviews and Trending were left open); now balanced.
- `anime.html`: the `id="catalogue"` section was never closed, and a stray `</main>` tag was sitting inside `<header>` with no matching opening tag; both fixed, and the characte spotlight is now its own properly closed  section.
- `enquiry.html`: a duplicate `</main>` closing tag (closed twice in a row) was removed.

- `about.html`: the last nav `<li>` was missing its closing `>` (`</li` with no bracket); fixed.

- Removed a duplicate `<h1>` per page — the header brand name ("AniOrbit") is no longer marked up as a heading, so each page now has exactly one `<h1>` (the page title).

What i added for the CSS style sheet:
- External stylesheet (`css/style.css`) linked from every page, replacing all inline `style` attributes.
- `js/main.js` placeholder, reserved for Part 3 functionality work.

- Horizontal navigation menu with a pure-CSS mobile toggle , consistent across all six pages.
- `<meta charset="UTF-8">`, `<meta name="viewport">`, and a meta description added to every page (previously missing on all of them).

- Descriptive `alt` text on every image site-wide (previously missing on `index.html`, `about.html`, `news.html`, `contact.html`, and `enquiry.html`).

- A contact form (name, email, subject, message) on `contact.html`, which previously had contact details only.

 References:  

Canva (2026) Canva: Visual Suite for everyone. Available at: 
https://www.canva.com/ (Accessed: 14 August 2026). 

Crunchyroll (2026) Crunchyroll: Watch popular anime, play games and shop online. 
Available at: https://www.crunchyroll.com/ (Accessed: 14 August 2026). 

MyAnimeList (2026) MyAnimeList.net. Available at: https://myanimelist.net/ 
(Accessed: 14 August 2026). 

Pinterest (2026) Pinterest. Available at: https://www.pinterest.com/ (Accessed: 14 
August 2026). 

World Wide Web Consortium (W3C) (2026) Web Content Accessibility Guidelines 
(WCAG). Available at: https://www.w3.org/WAI/standards-guidelines/wcag/ 
(Accessed: 14 August 2026).