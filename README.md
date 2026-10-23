# Home by Kish website demos

Two clickable demos for Home by Kish, Cagayan de Oro. Nothing entered is saved.

- `/` (`index.html`): Version 1, the showcase website (₱1,500 a year)
- `/booking/` (`booking/index.html`): Version 2, the booking website (₱800 a month)
- `img/`: full-size photos (WebP), `img/t/`: small versions for thumbnails
- `vercel.json`: photo caching, basic security headers, hidden from Google while these are demos
- `robots.txt`: tells search engines not to crawl the demos

Each version opens with a "Two versions to choose from" box that links to the other.

## Run it on your computer

    npx serve .

Then open http://localhost:3000 and http://localhost:3000/booking/
(Opening the HTML files directly won't show the photos, because they load from /img/.)

## Change the colours

In each `index.html`, find `/* ===== Colour scheme: change these to re-theme the whole site ===== */`.

## Going live

See the `launch-kit` folder that came in the same zip.
