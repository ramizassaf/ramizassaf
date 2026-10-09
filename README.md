# Ramiz Assaf | Interactive CV

Personal CV website of Ramiz Assaf, Data Professional and Industrial Engineer based in Nablus, Palestine.

**Live site:** https://ramizassaf.github.io/cv

![Preview](og.png)

## Features

- **Live demos.** A break-even calculator and a normal CDF approximation demo run in the browser.
- **English and Arabic.** One click switches language and right-to-left layout.
- **Dark mode.** Follows the system setting, with a manual toggle.
- **Print to PDF.** The Download CV button prints a clean CV without demos or navigation.
- **Link preview.** `og.png` shows as a card when the link is shared on LinkedIn, WhatsApp, or X.
- **No build step.** One HTML file. No frameworks, no dependencies.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole site: content, styles, and scripts |
| `og.png` | 1200 × 630 link preview image |
| `LICENSE` | MIT license for the code |

## Edit the content

All content lives in `index.html`.

- **Experience and education:** edit the `.t-item` blocks in the `#experience` section. Add one block per role, newest first.
- **Projects:** edit the `<article class="card proj">` blocks in the `#projects` section.
- **Arabic text:** each element with `data-i18n="key"` has an Arabic version under the same key in the `AR` object inside the script.
- **Contact form:** create a free form at [formspree.io](https://formspree.io) and paste its ID into `FORMSPREE_ID` near the top of the script. While the ID stays empty, the form opens the visitor's email app.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy

GitHub Pages serves the site from the `main` branch root. Every push to `main` updates the live site within 1 to 2 minutes.

## Related projects

- [Normal CDF Piecewise-Linear Approximation](https://github.com/ramizassaf/normal-cdf-piecewise-linear)
- [Break-Even Location Finder](https://github.com/ramizassaf/break-even-location-finder)
- [Engineering Economy Analysis](https://github.com/ramizassaf/Engineering-Economy)

## Contact

- Email: ramizassaf@gmail.com
- GitHub: [@ramizassaf](https://github.com/ramizassaf)

## License

Code released under the [MIT License](LICENSE). CV content and photo © Ramiz Assaf.
