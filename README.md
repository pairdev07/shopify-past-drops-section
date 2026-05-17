# Free Shopify Sections — shopifycraft.dev

> Free, copy-paste Liquid sections for Shopify stores. No app needed. No monthly fees. Just clean code that works.

Built and maintained by [shopifycraft.dev](https://shopifycraft.dev) — open for Shopify projects.

---

## Sections

| # | Section | What it replaces | Article | Status |
|---|---------|-----------------|---------|--------|
| 01 | [Past Drops Archive](#past-drops-archive) | Drop archive apps ($19–$49/mo) | [Read guide →](https://shopifycraft.dev) | ✅ Available |
| 02 | [FAQ Accordion](#faq-accordion) | FAQ apps ($9–$20/mo) | Coming soon | 🔜 Soon |
| 03 | [Sticky Add-to-Cart](#sticky-add-to-cart) | Sticky cart apps ($9–$29/mo) | Coming soon | 🔜 Soon |
| 04 | [Before / After Slider](#before--after-slider) | Image comparison apps ($9–$29/mo) | Coming soon | 🔜 Soon |
| 05 | [Size Guide Popup](#size-guide-popup) | Size chart apps ($7–$25/mo) | Coming soon | 🔜 Soon |
| 06 | [Countdown Timer](#countdown-timer) | Timer apps ($5–$19/mo) | Coming soon | 🔜 Soon |
| 07 | [Trust Badges](#trust-badges) | Badge apps ($5–$15/mo) | Coming soon | 🔜 Soon |
| 08 | [Product Tabs](#product-tabs) | Tab apps ($9–$19/mo) | Coming soon | 🔜 Soon |
| 09 | [Bundle Display](#bundle-display) | Bundle apps ($15–$29/mo) | Coming soon | 🔜 Soon |
| 10 | [Recently Viewed Products](#recently-viewed-products) | App dependent | Coming soon | 🔜 Soon |

---

## How to Install Any Section

Every section in this repo is a single `.liquid` file. Installation takes under 5 minutes.

**Method 1 — Theme code editor (recommended)**

```
1. Open the section folder
2. Download the .liquid file
3. Shopify Admin → Online Store → Themes
4. Click "Edit code" on your active theme
5. Open the "Sections" folder
6. Click "Add a new section"
7. Paste the code
8. Save
9. Go to theme editor → Add section → find it by name
```

**Method 2 — Shopify CLI**

```bash
# Copy the section file into your local theme
cp sections/past-drops-archive/past-drops-archive.liquid your-theme/sections/

# Push to your store
shopify theme push
```

---

## Compatibility

Every section is built to work across all major Shopify 2.0 themes:

| Theme | Compatible |
|-------|-----------|
| Dawn | ✅ |
| Horizon | ✅ |
| Sense | ✅ |
| Impulse | ✅ |
| Prestige | ✅ |
| Custom themes (OS 2.0) | ✅ |

> **Requirements:** Shopify Online Store 2.0. Any theme that supports sections and blocks will work.

---

## Sections

---

### Past Drops Archive

**`/sections/past-drops-archive/`**

Display all your past product drops in a clean archive with status badges, product thumbnails, and a live countdown for upcoming releases. Two layout modes — Timeline and Grid.

**Replaces:** Drop archive apps charging $19–$49/month for features that should be native.

**Features:**
- Timeline layout and grid layout — merchant picks in theme editor
- Status badges — Sold Out / Available / Upcoming
- Live countdown timer for upcoming drops
- Product thumbnails pulled automatically from collections
- Filter by status — All / Sold Out / Available / Upcoming
- Notify Me button for upcoming drops
- Year grouping — drops organized chronologically
- Zero JavaScript dependencies — vanilla JS only
- No app required — fully native Shopify section

[→ Read the full install guide](sections/past-drops-archive/README.md)

---

### FAQ Accordion

**`/sections/faq-accordion/`** — *Coming soon*

---

### Sticky Add-to-Cart

**`/sections/sticky-add-to-cart/`** — *Coming soon*

---

### Before / After Slider

**`/sections/before-after-slider/`** — *Coming soon*

---

### Size Guide Popup

**`/sections/size-guide-popup/`** — *Coming soon*

---

### Countdown Timer

**`/sections/countdown-timer/`** — *Coming soon*

---

### Trust Badges

**`/sections/trust-badges/`** — *Coming soon*

---

### Product Tabs

**`/sections/product-tabs/`** — *Coming soon*

---

### Bundle Display

**`/sections/bundle-display/`** — *Coming soon*

---

### Recently Viewed Products

**`/sections/recently-viewed-products/`** — *Coming soon*

---

## Need This Customized?

Every section here is a starting point. If you need it modified for your store — different layout, additional features, or integration with your theme's design system — we are available for Shopify projects.

**What we build:**
- Custom sections built from scratch to your spec
- Full theme customizations
- Shopify integrations with external APIs and systems
- Performance optimization

**Get in touch:**

📩 [hello@shopifycraft.dev](mailto:hello@shopifycraft.dev)

→ [See services and pricing at shopifycraft.dev/hire](https://shopifycraft.dev/hire)

We respond within 24 hours. No charge for scoping or quotes.

---

## Contributing

Found a bug? Have a suggestion? Open an issue and we will look at it.

If you want to contribute a section — open an issue first to discuss before submitting a pull request.

---

## License

MIT — free to use, modify, and distribute in personal and commercial projects.

Attribution appreciated but not required.

---

*Built by [shopifycraft.dev](https://shopifycraft.dev)*
