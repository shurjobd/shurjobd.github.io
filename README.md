# Shurjo website

Two pages. `index.html` is the main site. `products.html` is the collection page with prices and stories.

## Before the pitch, edit these

**Contact details** are in `index.html`, in the section marked `<!-- REPLACE these with your real details -->`. Right now the phone number and emails are placeholders.

**The numbers** in the Impact section are labelled as year one targets, not results. Judges tend to trust a target more than an invented statistic, but change them to whatever your team actually decided.

**Prices and products** are all in `products.html`. Each product is one `<article class="item">` block. Copy a block to add a seventh product, delete one to have five.

## Adding your photos

Make a folder called `images` next to the HTML files. Then find any block that looks like this:

```html
<div class="ph">
  <b>Photo: Signature Tote</b><small>images/tote.jpg</small>
</div>
```

Replace the whole `<div class="ph">...</div>` with:

```html
<img src="images/tote.jpg" alt="Shurjo Signature Tote">
```

The photo will crop and fill the frame automatically. The small grey text in each placeholder tells you the filename it expects.

If you leave a placeholder in, it still looks intentional rather than broken, so there is no rush to fill all of them.

## Getting it online for the QR codes

The fastest option is Netlify Drop at app.netlify.com/drop. Drag the whole folder onto the page and it gives you a live link in about ten seconds, no account needed to start. Point QR code one at that link, and QR code two at the same link with `/products.html` on the end.

GitHub Pages works too if you already have an account and want a nicer address.

## If the venue has no wifi

The fonts load from Google. Without internet they fall back to Georgia and a system sans, which still looks fine, just less distinctive. If you want to be safe, open the site once on the laptop beforehand so it is cached, and keep a screen recording as backup.
