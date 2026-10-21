# Mobile Mechanic Website

A clean, fully responsive multi-page site for a mobile mechanic business.

## What’s Included

- **Homepage** (`index.html`) — brand grid + contact form
- **15 brand pages** under `/brands/`
  - Ford, Chevrolet, GMC, Ram, Toyota, Honda, Nissan, Hyundai, Kia, Jeep, Subaru, BMW, Mercedes-Benz, Audi, Volkswagen
- Each brand page has the **same services list** + a **contact form** pre-filled with that brand
- Shared CSS (`css/styles.css`) — mobile-first, works on iPhone, Samsung, iPad, and desktop

## Services Listed (on every brand page)

- Oil Change & Oil Filter
- Transmission Fluid Change (drain & fill only)
- Brake Pads & Rotors + Brake Fluid Flush
- Suspension (shocks, struts, bushings)
- Alternator & Starter Replacement
- Serpentine / Drive Belt
- Battery Replacement
- Spark Plugs (when accessible)
- Engine Air Filter & Cabin Air Filter
- Tire Rotation & Inspection
- Diagnostic Scan / Check Engine Light
- Wiper Blades
- Exterior Lighting

**Not included** (as requested): internal engine work, transmission rebuilds, or pulling motors/transmissions.

## How to View

1. Open `index.html` in any browser (Chrome, Safari, Edge, Firefox).
2. Or double-click the file / drag it into a browser window.
3. Test mobile view: right-click → Inspect → toggle device toolbar (iPhone, Pixel, iPad, etc.).

## Customization Tips

- **Business name / phone / email**: Search and replace `MobileMechanic`, `service@yourmobilemechanic.com`, and the footer text.
- **Form**: Currently uses `mailto:`. For a real site, connect to Formspree, Netlify Forms, or your own backend.
- **Colors**: Edit the CSS variables at the top of `css/styles.css` (`--accent`, `--primary`, etc.).
- **Add more brands**: Copy any brand page and update the name/models text, then add a card on the homepage.

## File Structure

```
mobile-mechanic/
├── index.html
├── css/
│   └── styles.css
├── brands/
│   ├── ford.html
│   ├── chevrolet.html
│   ├── ... (15 total)
│   └── volkswagen.html
└── README.md
```
