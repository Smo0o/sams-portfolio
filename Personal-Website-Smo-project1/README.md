# Personal Website — Starter Portfolio (Sams Portfolio)

This is a simple, modernized starter portfolio built with Bootstrap 5 and a small custom stylesheet. It includes a polished main page and a separate Projects page.

Files added/updated:
- `main.html` — Main page with a hero titled "Sams Portfolio", About, Skills, Contact, and links to Projects.
- `projects.html` — Dedicated Projects page with project cards.
- `Website/styles.css` — Modernized custom styles (hero, updated palette, LinkedIn button styles).

How to open locally:
1. Open `main.html` in your browser (double-click or right-click -> Open with).
2. Or serve it with a simple HTTP server. For example, with Python 3 installed:

```powershell
# from the repository root
python -m http.server 8000; Start-Process http://localhost:8000/main.html
```

Notes & next steps:
- Update placeholder images, project descriptions, and links to your real work.
- Replace the LinkedIn `href` values with your profile URL.
- Add interactivity (contact form handling, project detail pages, filters) in the next unit.

If you want, I can:
- Replace the placeholder content with your real name/bio and links.
- Wire the contact form to a free form backend (Formspree, Netlify Forms) so it actually sends messages.
- Add icons or extra accessibility improvements.
