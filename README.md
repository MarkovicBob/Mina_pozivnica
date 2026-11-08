# Mina – Digital Birthday Invitation with RSVP

Digital invitation with an RSVP system for family events. Guests look up their family by name, accept or decline for each family member, and an admin panel shows all responses and attendance stats.

**Live demo:** https://pozivnicamina.netlify.app · **Backend API:** [Mina_pozivnica_server](https://github.com/MarkovicBob/Mina_pozivnica_server) · **Portfolio:** https://portfoliobob.netlify.app/#projects

> Contact details, venue and photos in this repository are fictional placeholders.

## Features

- RSVP per family and per family member (accept / decline)
- Guest search with Serbian character normalization (č, ć, š, đ, ž)
- Admin dashboard with responses and attendance statistics (token-protected API)
- Add to calendar (ICS download + Google Calendar) and embedded Google Maps
- Photo gallery carousel, animated bubbles, confetti cursor and playful micro-interactions
- Fully responsive, mobile-first

**Stack:** React · Vite · Tailwind CSS · Framer Motion · Node.js/Express + MongoDB API

## Screenshots

<a href="https://portfoliobob.netlify.app/projects/mina/demo.mp4"><img src="https://portfoliobob.netlify.app/projects/mina/poster.webp" alt="Demo video" width="100%"></a>

<sub>▶ Click the image to watch the demo video</sub>

<table>
<tr><td width="50%"><img src="https://portfoliobob.netlify.app/projects/mina/2.webp" alt="Gallery" width="100%"></td><td width="50%"><img src="https://portfoliobob.netlify.app/projects/mina/3.webp" alt="RSVP" width="100%"></td></tr>
</table>

## Run locally

```bash
npm install
# .env: VITE_API_URL=<url of the Mina_pozivnica_server API>
npm run dev
```

Event details (date, venue, contact) live in `src/config.js`.

---

Built by [Boban Marković](https://portfoliobob.netlify.app) · [LinkedIn](https://www.linkedin.com/in/bobmardev) · [GitHub](https://github.com/MarkovicBob)
