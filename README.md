# BlueLine Home Services — Austin, TX

A single-page, mobile-first marketing site for a fictional family-owned HVAC and plumbing company serving Austin, Texas. Built as a self-contained HTML file with no build step, no dependencies, and no external JavaScript.

## 🌐 Live Site

Once GitHub Pages is enabled: `https://<your-username>.github.io/<repo-name>/`

## ✨ Features

- **Fully responsive** — mobile-first layout with a sticky "Call Now" bar on small screens
- **Hero call-to-action** with a `?mode=schedule` URL toggle that swaps the primary CTA from "Call" to "Book"
- **Scrollable service marquee** with `prefers-reduced-motion` support
- **Services grid** — AC, heating, and plumbing
- **Transparent pricing** cards (free service call, maintenance plan, seasonal check)
- **Customer reviews** section with aggregate rating
- **Owner bio** with license credentials
- **Step-by-step** "what happens next" process
- **FAQ** using native `<details>`/`<summary>` (no JS)
- **Lead capture form** with honeypot spam protection and inline validation
- **Schema.org `HVACBusiness` structured data** for SEO
- **Accessibility** — skip-friendly landmarks, ARIA labels, focus outlines, `sr-only` helpers

## 🛠️ Tech Stack

| Layer | Choice |
|---|---|
| Markup | HTML5 |
| Styling | Vanilla CSS (custom properties, clamp, grid, flexbox) |
| Scripts | ~30 lines of vanilla JS (mobile nav, URL mode toggle, form validation) |
| Icons | Inline SVG |
| Fonts | System fallbacks (`Barlow Condensed`, `Source Sans 3` via OS) |

No frameworks, no bundler, no npm install.

## 🚀 Deploying to GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select **Deploy from a branch**.
4. Choose `main` and `/ (root)`, then **Save**.
5. Wait ~1 minute. Your site is live at `https://<username>.github.io/<repo>/`.

## ⚙️ Configuration Notes

- **Contact mode toggle:** Append `?mode=schedule` to the URL to make "Book Now" the primary hero CTA; default is `?mode=call`.
- **Imagery:** The hero background and owner photo currently point to external CDN URLs (Adobe Stock / Unsplash). Replace with your own licensed assets before going live.
- **Form backend:** The lead form posts to `action="#"`. Wire it up to Formspree, Netlify Forms, or your CRM endpoint.
- **Business details:** Phone `(512) 555-0147`, address `4200 Burnet Rd, Suite 210`, and license numbers are **placeholders** — update them everywhere (meta tags, JSON-LD, header, footer) before deploying for a real client.

## 📁 Project Structure

## ⚠️ Disclaimer

This is a **demonstration template**. The business name, phone number, address, license numbers, reviews, and owner identity are fictional. Do not deploy it as-is for a real company without replacing all placeholder content and confirming you have rights to the images used.

## 📄 License

MIT — free to use, modify, and adapt.