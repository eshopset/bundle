# Map sheet columns to Shopify fields

> **Primary keyword:** map Google Sheet to Shopify fields  
> **Related:** SKU, handle, Data Sync

![EShopSet Data Sync Overview](../../images/eshopset-screenshot-datasync.png)

*EShopSet Data Sync Overview — same product UI shown on [eshopset.com](https://eshopset.com).*

**map Google Sheet to Shopify fields** keeps supplier sheets and Shopify catalogs aligned without CSV upload roulette. [Data Sync](https://eshopset.com/apps/data-sync/) maps columns, previews creates vs updates, then applies—once or on a schedule—inside the same EShopSet plan as SEO and AI Presence.

_Map Google Sheet columns to Shopify handle, title, SKU, price, inventory, and images in Data Sync before the first sync to avoid mismatched products._

## Outcomes

- Map handle, title, SKU, price, inventory, images deliberately
- Prevent duplicate products from weak identity keys
- Document the mapping so agencies and freelancers don’t drift

## Why mapping is pillar setup

Sheets are flexible; Shopify is strict. Ambiguous identity (title-only matching) creates duplicates. Over-mapping description columns can overwrite carefully written PDP copy on every sync. Treat mapping as a published internal standard.

## How it works in EShopSet

In Data Sync Settings, map each sheet column to a Shopify field. Prefer stable keys (handle or SKU). Leave rich merchandising fields unmapped if Shopify remains the source of truth—combine with price/inventory-only policy when needed.

## Example: multi-warehouse sheet

A brand maintained warehouse_A_qty and warehouse_B_qty columns. They mapped a computed inventory column (SUM) to Shopify inventory and kept warehouse columns unmapped. Preview then showed clean updates without creating phantom products from warehouse codes mistaken as SKUs.

## Playbook

1. Define the identity column (handle recommended for existing catalogs).
2. Map price and inventory next; validate types (numbers, not text).
3. Decide which content fields Shopify owns vs sheet owns.
4. Save mapping; run preview on a 50-row sample tab first.
5. Document mapping in the sheet header row comments for the team.

## What to measure

- Duplicate product creates after first mapped sync (target 0)
- Fields unexpectedly overwritten (audit 10 PDPs)

## Proof points

- **1 identity key** — Handle or SKU discipline
- **6+ fields** — Common mapped set
- **Once** — Then reuse across runs

## Why this belongs in the EShopSet bundle

Instead of stacking a separate Data Sync competitor, SEO suite, AI-visibility tracker, sheet importer, linker, and content tool, EShopSet includes **SEO Performance Monitor**, **AI Presence**, **Data Sync**, **Link Pilot**, and **CopilotPost** on one per-store plan (Starter from **$49/store/mo** at launch). Enable only what this store needs; usage never mixes across stores.

Operate the same apps from **Shopify Sidekick** or connect **EShopSet MCP** in Cursor, Claude, ChatGPT, Gemini, and Copilot.

## Get started

1. [Install EShopSet](https://apps.shopify.com/eshopset) from the Shopify App Store.
2. Enable **Data Sync** and open Overview → Settings → Logs.
3. Follow this playbook, then compare limits on [pricing](https://eshopset.com/pricing/).
4. Optional: try the [live demo](https://demo.eshopset.com) or explore [AI Power](https://eshopset.com/ai-power/).

## Canonical & related

- Website use case: [https://eshopset.com/usecases/catalog-sync/map-sheet-columns-to-shopify/](https://eshopset.com/usecases/catalog-sync/map-sheet-columns-to-shopify/)
- App: [Data Sync](https://eshopset.com/apps/data-sync/)
- Category: [Shopify Google Sheets catalog sync use cases](./README.md)
- Data Sync: https://eshopset.com/apps/data-sync/
- Price & inventory-only updates: https://eshopset.com/usecases/price-inventory-only-updates/
- Preview before apply: https://eshopset.com/usecases/preview-before-apply-catalog/
- Pricing: https://eshopset.com/pricing/

---

[Install Now](https://apps.shopify.com/eshopset) · [Pricing](https://eshopset.com/pricing/) · [Use cases on eshopset.com](https://eshopset.com/usecases/catalog-sync/)
