# Real Life Ready

A fast, accessible, single-page website for Real Life Ready executive function coaching.

## Configure the site

Open `index.html` and update the `window.siteConfig` block near the top of the file:

```js
window.siteConfig = {
  bookingLink: "https://calendly.com/your-business/free-parent-call",
  businessEmail: "hello@example.com",
  serviceArea: "Serving families locally and online",
  domainName: "https://example.com"
};
```

Also update the canonical URL, Open Graph URL, Open Graph image URL, and JSON-LD values in the `<head>` if you have a production domain.

## Run locally

Because this is a static site, you can open `index.html` directly in a browser or run a small local server:

```bash
python3 -m http.server 4173
```

Then visit <http://localhost:4173>.

## Deploy

### Vercel

1. Create a new Vercel project from this repository.
2. Keep the framework preset as **Other** or **Static**.
3. Leave build command empty.
4. Set the output directory to `.`.
5. Deploy.

### Netlify

1. Create a new Netlify site from this repository.
2. Leave build command empty.
3. Set publish directory to `.`.
4. Deploy.

### GitHub Pages

1. Go to repository **Settings → Pages**.
2. Choose **Deploy from a branch**.
3. Select your main branch and `/root`.
4. Save and wait for the Pages URL to publish.
