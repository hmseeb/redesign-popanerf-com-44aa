# Pop-A-Nerf Entertainment — Website

A completely rebuilt, modern single-page site for **Pop-A-Nerf Entertainment**, a mobile Nerf war
experience that constructs a fully enclosed battle arena at the client's location.

## Stack

Vanilla HTML, CSS and JavaScript — no build step, no dependencies, no environment variables.

```
index.html    Entry point / full page markup
styles.css    Design system, layout and responsive rules
script.js     Sticky header, mobile nav, scroll reveal, FAQ accordion
favicon.svg   Site icon
```

## Running locally

Open `index.html` directly in a browser, or serve the directory:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Contents

- Hero with the business tagline and primary booking / call actions
- Experience section — enclosed arena, stocked armory, dedicated coordinator, zero downtime
- Where We Play — parks, back yards, corporate events, youth groups, front & side yards, arsenal
- Pricing — standard event package inclusions plus group-size pricing tiers
- Upgrades — all 13 add-ons with real pricing
- Google reviews call-to-action
- FAQ accordion built from the business's published event details
- Contact — phone (786-671-NERF / 786-671-6373), online booking, contact form, mobile service note

## Notes

- All photography is the business's own imagery from the original site.
- Semantic HTML, descriptive alt text, skip link, keyboard-accessible navigation and
  `prefers-reduced-motion` support.
- Open Graph / Twitter meta tags and `EntertainmentBusiness` JSON-LD structured data included.
