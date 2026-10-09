# Stop Victim Blaming — Statement Studio

A responsive browser-based statement and campaign design studio for the Stop Victim Blaming community.

## Separate design templates
- Reference statement: burgundy framed quote layout inspired by the supplied reference.
- Awareness poster: high-contrast solid-colour campaign poster.
- Public statement: formal centered heading and editorial body layout.
- Social media square: square card layout for social posts.
- Wide banner: horizontal 16:9 campaign banner.
- Custom editorial: alternate typography and asymmetric background.

Each template has its own visual structure, not just replacement text. Users can edit headline, body, community header, footer, logo URL, theme colour, headline size, and canvas size.

## Export
PNG and PDF export use a fixed-size off-screen canvas independent of the phone preview dimensions:
- A4 portrait: 1240 × 1754 pixels
- Social square: 1200 × 1200 pixels
- Wide banner: 1600 × 900 pixels

The export routine waits for fonts and images and reduces text sizing when necessary to prevent content from being clipped.

## Use
Open `index.html` in a modern browser with an internet connection. Export depends on html2canvas and jsPDF loaded from CDN-hosted libraries. The community logo is loaded from its supplied public Google image URL; if it does not appear, check the URL's public access settings.

## Editorial note
Review all Burmese copy carefully before publishing, particularly formal community announcements. The tool runs in the browser and does not send the text to a backend service.
