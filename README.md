# Rakesh Wedding Card Maker

A one-page, personalized Hindi wedding invitation for Rakesh and Pooja.

## Included

- Guest name, groom, bride, wedding date, venue name and RSVP phone fields
- Live floral invitation preview with a subtle floating animation
- User-supplied Ganesh artwork, cleaned to transparent gold linework
- Hindu wedding wording and programme for 01, 02 and 03 December 2026
- Standard PNG export: 1135 × 1600 px
- Print-ready PNG export: 3405 × 4800 px
- No Canva account or client-side JavaScript package required

## Run on the homeserver

```bash
cd /home/aditya/projects/rakesh-wedding
python3 -m http.server 4177 --bind 0.0.0.0
```

Open `http://100.119.192.17:4177/` over Tailscale, or `http://192.168.1.6:4177/` on the same Wi-Fi/LAN.

## Project files

- `index.html`: editable card maker and SVG/PNG export logic
- `assets/ganesh.jpg`: original image downloaded from the supplied link
- `assets/ganesh-card.png`: transparent, gold linework version embedded in the card
- `index.html.before-review-20261109.bak`: backup of the design before this review pass

The demo invitee is `Ramesh with Family`. Change the name in the first input and export a separate PNG for each invitee.
