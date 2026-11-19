# Zlign — landing page

Marketing site for **Zlign Parking App** (`com.zlign.app`), a parking marketplace for India.

- Space owners list a driveway, garage or bay and set a weekly or monthly rate.
- Vehicle owners book by the week or month and pay the owner at the spot, in cash or UPI.
- The app never takes card or UPI credentials and does not process payments.

## Stack

Single static page — `index.html` with inline CSS, no build step, no dependencies.
Deployed on Vercel as a static site (zero config).

## Local preview

Open `index.html` in a browser, or:

```bash
npx serve .
```

## Deploy

```bash
vercel --prod
```

Vercel serves `index.html` at the domain root; no `vercel.json` is needed for a static page.

## Content rules

Copy on this page comes from the Zlign project record. When updating it:

- Keep release status accurate — v1.6.4 is live for closed testers, v1.6.5 is in Google review, v1.6.6 is built but not uploaded.
- Do not publish prices, city lists, iOS availability or payment claims that are not shipped.
- The only call to action is the Google Play closed-test link:
  https://play.google.com/apps/testing/com.zlign.app

## Contact

zlign9@gmail.com
