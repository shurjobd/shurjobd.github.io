# Shurjo

The Shurjo website. Live at https://shurjo.github.io

Two pages:

- `index.html` is the main site. Problem, solution, process, impact, contact.
- `products.html` is the collection page, linked from the second QR code.
- `images/` holds every photo. Filenames must stay exactly as they are.

## Editing things

**Contact details** are near the bottom of `index.html`, in the section marked `id="contact"`. The Facebook URL appears three times: twice in `index.html` and once in the footer of `products.html`. Find and replace all three when the new page is ready.

**Products** are in `products.html`, grouped into five collections. Each one is a single `<article class="card">` block. Copy a block to add a product, delete one to remove it. Prices sit in the line marked `class="price"`.

**Impact numbers** on `index.html` are labelled as year one targets, not results. Change the figures in the `data-count` attributes if the team agrees different ones.

## Photos

Every image slot expects a specific filename, listed in small grey text on any placeholder that is still empty. Names are lowercase and end in `.jpg`. GitHub is case sensitive even though your computer is not, so `Tote.JPG` will work on a laptop and fail once live.

## Updating the live site

Edit a file on GitHub with the pencil icon and commit, or upload a replacement with the same name. Changes appear in about a minute.

## On pitch day

Fonts load from Google, so with no internet they fall back to Georgia and a system sans. Still looks fine, just less distinctive. Open the site once beforehand so it caches, and keep a screen recording as a backup in case the venue wifi fails.
