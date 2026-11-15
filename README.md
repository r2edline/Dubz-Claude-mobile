# Freelance Hourly Rate Calculator

A free, single-page calculator that tells freelancers what to charge. It is one
static file (`index.html`): no server, no build step, no running costs.

## How it can earn

- **Tips**: a "Support this tool" button, shown once you add a payment link.
- **A paid add-on**: an optional card that links to something you sell.

Both stay hidden until you fill them in, so the page is safe to publish as is.

## Put it online (free)

1. Merge this branch into your default branch (or keep it on this branch).
2. On GitHub: **Settings → Pages → Build and deployment → Deploy from a branch**,
   pick the branch and the `/ (root)` folder, then save.
3. Your page appears at `https://<your-username>.github.io/<repository-name>/`.

## Turn on payments

Open `index.html` and edit the `SETTINGS` block near the top:

```js
PAYMENT_LINK: "https://...",   // Stripe Payment Link, Ko-fi, Buy Me a Coffee, Gumroad
UPGRADE_LINK: "https://...",   // optional: a product you sell
```

Links must start with `https://`.

## Getting visitors

The page will not earn until people find it. It ships with a search-friendly
title, description and FAQ markup, but you still need to:

- Submit the page address to Google Search Console (free).
- Share it where freelancers ask "what should I charge?" (forums, communities),
  where that is welcome under each community's rules.
- The "Copy link to these numbers" button lets visitors share their own result,
  which brings others to the page.
