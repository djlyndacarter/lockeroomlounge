# The Lockeroom Lounge website

Static site for lockeroomlounge.com, hosted on Netlify. Every push to `main` goes live automatically.

- Pages are plain HTML: `index.html` (home) and one folder per page (`about/`, `menu/`, `events/`, `employment/`, `booking/`, `contact/`, `terms/`, `privacy/`, `thanks/`).
- Shared look: `styles.css`. Header and footer are repeated in each page, so change them everywhere.
- Photos and logos: `images/`. Menu PDF: `menu/lockeroom-menu.pdf` (replace the file to update the menu).
- Forms (employment, booking, contact) use Netlify Forms. Submissions appear in the Netlify dashboard under Forms, and can be emailed under Project configuration > Notifications.
- `netlify.toml` redirects the old WordPress addresses to the new pages.
