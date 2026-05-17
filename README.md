# Past Drops Archive — Free Shopify Section

**Built by [shopifycraft.dev](https://shopifycraft.dev)**

A free, zero-dependency Shopify section for drop-based brands. Display your full release history in a filterable timeline or grid — with live countdowns, product thumbnails, and status badges.

---

## Features

- Timeline & grid layout toggle
- Filter by All / Sold Out / Available / Upcoming
- Live countdown timer for upcoming drops
- Product thumbnails auto-pulled from linked collection
- Status badges — Sold Out · Available · Upcoming
- Year grouping with large ghost year text
- Stats row — total drops, total pieces, sold out count
- Configurable fonts via Theme Editor
- Dawn compatible · any Online Store 2.0 theme
- **One file · no apps · no dependencies**

---

## Installation

### Option A — Shopify Admin (no CLI needed)

1. Go to **Online Store → Themes → ⋯ → Edit code**
2. Open the `sections/` folder → **Add a new section**
3. Name it `past-drops`
4. Delete the placeholder and paste the contents of `sections/past-drops.liquid`
5. Click **Save**

### Option B — Shopify CLI

```bash
shopify theme pull --store your-store.myshopify.com
cp sections/past-drops.liquid path/to/your-theme/sections/
shopify theme push --store your-store.myshopify.com
```

---

## Setup

1. Open **Theme Editor** → navigate to any page
2. Click **Add section → Past Drops**
3. Click **Add block → Drop** for each release

### Drop block fields

| Field | Example | Notes |
|-------|---------|-------|
| Drop number | `DROP 001` | Label shown above the name |
| Drop name | `Origin` | Main card heading |
| Release date | `2025-04-15` | Format: `YYYY-MM-DD` |
| Status | `Sold Out` | Sold Out / Available / Upcoming |
| Collection | — | Products auto-load as thumbnails |
| CTA URL override | `/collections/drop-001` | Leave blank to use collection URL |
| Notify Me URL | `/pages/notify` | Upcoming drops only |

### Section settings

| Setting | Description |
|---------|-------------|
| Label | Eyebrow text above the heading |
| Heading | Main title — default: "Past Drops" |
| Subheading | Italic subtitle |
| Show stats row | Toggle drop/pieces/sold-out counters |
| Show filter bar | Toggle status filters |
| Show layout toggle | Toggle Timeline / Grid switcher |
| Default layout | Timeline or Grid |
| Heading font | For title, names, countdown numbers |
| Label font | For badges, metadata, buttons |
| Footer note | Small text at the section bottom |
| Color scheme | Inherits Dawn color schemes |
| Padding top / bottom | Section spacing |

---

## Compatibility

- Shopify Dawn (all versions)
- Any Online Store 2.0 theme
- Light and dark color schemes
- Mobile responsive

---

## File structure

```
sections/
└── past-drops.liquid   ← everything in one file, drop & go
```

---

## Hire Us

Need this customized for your store? We build bespoke Shopify sections, themes, and full storefronts for drop-based brands.

**→ [shopifycraft.dev/hire](https://shopifycraft.dev/hire)**
**→ [hello@shopifycraft.dev](mailto:hello@shopifycraft.dev)**

From a single custom section to a full theme build — get in touch.

---

## License

Free to use on any Shopify store. Attribution appreciated but not required.

Made with care by [shopifycraft.dev](https://shopifycraft.dev)
