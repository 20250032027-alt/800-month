# Home by Kish (booking website demo)

A clickable demo of the booking website for Home by Kish, Cagayan de Oro.
Nothing you enter is saved: it's for showing the owner how the real site will work.

## What's in here

- `index.html`: the whole site (pages, styles and scripts in one file)
- `img/`: the photos, watermark already cropped out
- `vercel.json`: hosting settings (photo caching, and "don't show in Google" while it's a demo)

## Run it on your computer

Just open `index.html` in a browser. Or, to test it like a real server:

    npx serve .

## Change the colours

Open `index.html` and find the block that starts with
`/* ===== Colour scheme: change these to re-theme the whole site ===== */`.
Every colour on the site comes from there.

## When the demo becomes the real site

1. Remove `<meta name="robots" content="noindex, nofollow">` from `index.html`.
2. Remove the `X-Robots-Tag` block from `vercel.json`.
3. Replace the [bracketed] placeholders (mobile number, email, bank details, building name).
