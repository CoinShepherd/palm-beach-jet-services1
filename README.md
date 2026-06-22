# Palm Beach Jet Services — Website

A single-page site for Palm Beach Jet Services, built as plain HTML/CSS/JS
(no build step required) so it deploys on Vercel with zero configuration.

## Files

```
index.html                    ← the entire site (HTML + CSS + JS in one file)
assets/logo.png                ← your logo
assets/hero-coastal.jpg        ← hero background photo
assets/jet-clouds.jpg          ← "Fleet Access" banner photo
assets/jet-taxi-sunset.jpg     ← "Experience. Integrity. Results." band photo
vercel.json                    ← explicit Vercel settings (clean URLs, no build step)
.gitignore                     ← keeps OS/editor clutter out of the repo
```

`vercel.json` and `.gitignore` are optional helper files — the site
deploys fine without them, but they make the repo a little cleaner and
make Vercel's behavior explicit instead of relying purely on auto-detection.

## Photo credits

The three background photos are from Unsplash, used under the Unsplash
License (free for commercial use, no attribution legally required —
credited here anyway as good practice):

- `hero-coastal.jpg` — Ramon Kagie
- `jet-clouds.jpg` — Jacob McGowin
- `jet-taxi-sunset.jpg` — Ramon Kagie

Note: `jet-clouds.jpg` shows a Cirrus Vision Jet (visible "JetSuiteX"
livery), not a HondaJet — that's why it's used only as generic
atmosphere (the "Fleet Access" banner) and intentionally kept out of the
HondaJet Elite II spotlight section, which stays photo-free until you
have a real, rights-cleared Elite II image from Honda.


## Before you publish — please review

A few things were deliberately left as **placeholders** for you to update
in `index.html`:

1. **Physical address** — currently just "Palm Beach Gardens, Florida."
   Add a real street address only if you want one public (many charter
   brokers intentionally don't list one).
2. **Privacy Policy / Terms of Service** links — currently placeholders
   (`href="#"`) in the footer. Add real pages once you have them drafted
   (a lawyer should review these, especially the broker disclosure language).
3. **"Aircraft Management Coordination" wording** — phrased to reflect a
   broker/advisor coordinating with FAA-certificated Part 135 operators
   rather than claiming your own operating certificate. Adjust this language
   to match your actual operating authority and any DBA/LLC structure.
4. **HondaJet Elite II spotlight** — phrased as "a growing relationship,"
   not as an authorized dealer/distributor claim, since that wasn't
   specified. Tighten this language once the relationship with Honda
   Aircraft Company is formalized.
5. **Contact form** — the "Request a Quote" buttons currently link to a
   `mailto:charter@palmbeachjetservices.com` link, which works with zero
   setup. If you'd like a real on-page form later, that needs a small
   backend (e.g., Formspree, or a Vercel serverless function) — happy to
   add this when you're ready.

## Geographic/technical content

The airport list (SUA, F45, PBI, BCT, FLL, FXE, OPF) and F45's 4,300 ft
runway figure were verified against FAA/county/airport-authority sources
as of June 2026. Re-verify before publishing if time has passed, since
runway and ownership data can change.
