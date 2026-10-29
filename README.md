# Good Drinks

A one-page drinks collection website: alcohol, alcohol-free drinks, a shop with cart, and a scroll-driven hero. Built as a single `index.html` file with no build step.

**Live site:** https://sameer-sankaria.github.io/GoodDrinks/

> All products, prices and details on this site are demo examples, not real offers. The cart does not place orders or take payments.

## Features

- **Scroll hero:** the "Good drinks. Great stories." opening with an amber disc, a beer glass and orbiting photos. On scroll the disc floods the screen and the text reveals.
- **Shop:** search, sort, category filters, product detail dialog, quantity controls and a cart drawer.
- **Demo checkout:** "Place order" collects details and shows a confirmation. Nothing is sent or charged.
- **Flight picker:** choose four drinks into round slots, then save the list.
- **Age notice:** a dismissible "Please enjoy responsibly" banner, remembered in `localStorage` when the browser allows it.
- **Contact and newsletter forms:** validated in the browser. They do not send anything until connected to a form service.
- **Accessible:** keyboard navigation, focus handling in dialogs, `prefers-reduced-motion` support, and the page reads fully without JavaScript.

## Tech

- HTML, CSS and vanilla JavaScript in one file: `index.html`
- [GSAP](https://gsap.com/) with ScrollTrigger for scroll animation
- [Lenis](https://github.com/darkroomengineering/lenis) for smooth scrolling
- Fonts: Bricolage Grotesque and Onest (Google Fonts)
- Photos: Unsplash (see [CREDITS.md](CREDITS.md))

## Run locally

No build is needed. Open the file in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy on GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`.
4. Wait a minute, then open the Pages URL.

## Before going live

Replace these placeholders and demo facts in `index.html`:

- [ ] Brand name, favicon letter and colours
- [ ] Real contact details: email, phone, address and map link
- [ ] Social media links in the footer
- [ ] Product names, descriptions, prices and images in the shop
- [ ] Opening hours and any other claims
- [ ] Booking/contact form: connect Formspree, Netlify Forms or similar, or remove the form
- [ ] Social preview image (`og:image`), or remove the tag
- [ ] Check local alcohol-sale and age-verification rules before taking real orders

## Project files

| File | Purpose |
|---|---|
| `index.html` | The whole site: markup, CSS and JavaScript |
| `AGENTS.md` | Notes for AI coding assistants: what to keep, what to replace |
| `CREDITS.md` | Photo, font and library credits |
| `LICENSE` | License for the template code |

## Credits

Built on a free brewery website template by [8B](https://8b.com) (MIT License). Photos from [Unsplash](https://unsplash.com) under the Unsplash License. See [CREDITS.md](CREDITS.md).

## License

Code: MIT, see [LICENSE](LICENSE). Photos and fonts keep their own licences, listed in [CREDITS.md](CREDITS.md).
