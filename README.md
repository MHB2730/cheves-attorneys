# Cheves Attorneys — concept website

A concept single-page website for **Cheves Attorneys** (Bob Cheves), a specialist
environmental, planning and development law practice in Westville, KwaZulu-Natal.

This is a **draft concept** for presentation. Some details are placeholders
(notably the contact email address) pending sign-off.

## What's here

- `index.html` — the entire site (self-contained HTML/CSS/JS)
- `assets/` — colour-graded photography (hero, portrait, and field gallery)

## Features

- Responsive single-page layout (desktop / tablet / mobile)
- Hero with a slow Ken Burns drift over the Drakensberg Amphitheatre
- "From the field" gallery of the attorney's own wildlife and botany photography,
  with images that wipe in on scroll
- A slow drifting green "mist" ambient underlay (pure CSS), disabled under
  `prefers-reduced-motion`
- Scroll-reveal and parallax transitions; enquiry form that opens a pre-filled email

## Running locally

It's a static site — open `index.html` in a browser, or serve the folder:

```
python -m http.server 5050
```

then visit <http://localhost:5050/>.

---

© 2026 M.H. Bremner. All rights reserved. See `LICENSE`.
