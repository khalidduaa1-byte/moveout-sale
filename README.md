# Bilal & Duaa — Move-Out Sale (website)

This folder is a ready-to-deploy static site (just `index.html`).

## Easiest way to publish (no command line)
1. Go to https://vercel.com  and log in (you already have an account).
2. Click **Add New… > Project**, then the **deploy a template / drag-and-drop** option,
   OR go to https://vercel.com/new and **drag this whole `moveout-sale-site` folder** onto the page.
3. Vercel gives you a public link like `moveout-sale-xxxx.vercel.app` — share that anywhere.

## Or with the command line
    cd "moveout-sale-site"
    npx vercel        # first run asks you to log in, then deploys
    npx vercel --prod # promote to your public URL

## To update later
Replace `index.html` (I regenerate it) and drag the folder in again, or run `npx vercel --prod`.

NOTE: edit the WhatsApp number — open index.html and change WA="971500000000" to your real number.
