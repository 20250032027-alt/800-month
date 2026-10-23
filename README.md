# Home by Kish website demos

Two clickable demos for Home by Kish, Cagayan de Oro. Nothing entered is saved.

- `/` (`index.html`): Version 1, the showcase website (₱1,500 a year)
- `/booking/` (`booking/index.html`): Version 2, the booking website (₱800 a month)
- `img/`: photos used by both, watermarks already cropped
- `vercel.json`: photo caching, and hidden from Google while these are demos

Each version opens with a "Two versions to choose from" box that links to the other.

## Run it on your computer

    npx serve .

Then open http://localhost:3000 and http://localhost:3000/booking/
(Opening the HTML files directly won't show the photos, because they load from /img/.)

## Change the colours

In each `index.html`, find `/* ===== Colour scheme: change these to re-theme the whole site ===== */`.

## When a demo becomes the real site

1. Remove `<meta name="robots" content="noindex, nofollow">` from the HTML.
2. Remove the `X-Robots-Tag` block from `vercel.json`.
3. Replace the [bracketed] placeholders (mobile number, email, GCash and bank details, building name).
4. Remove the preview strip at the top and the versions box.
