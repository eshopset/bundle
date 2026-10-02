# Catalog sync playbooks store-by-store

> **Primary keyword:** multi-store Google Sheets Shopify sync  
> **Related:** Data Sync, per-store catalog, sheet import

![EShopSet multi-store per-store apps](../../images/eshopset-screenshot-dashboard.png)

*EShopSet multi-store per-store apps — same product UI shown on [eshopset.com](https://eshopset.com).*

**multi-store Google Sheets Shopify sync** means each Shopify store keeps its own plan, app enables, and usage limits—not a shared multi-store control center. This use case shows how in-house teams, agencies, and freelancers run catalog sync playbooks store-by-store store by store with EShopSet.

_In-house ops: run Data Sync Google Sheets → Shopify imports on each store separately—map columns, preview, schedule—with row limits from that store’s plan._

## Outcomes

- One Google Sheet connection and mapping per Shopify store
- Preview before apply; never hard-delete—archive or zero inventory policies
- Row limits (1k / 5k) follow the plan on that store

## Why not one sync for every store

Catalogs, vendors, and SKU conventions differ by brand. A single shared apply would overwrite the wrong store. EShopSet keeps Data Sync scoped to the store you enabled—repeat the playbook deliberately.

## How it works in EShopSet

On store N: connect Google, pick spreadsheet/worksheet, map columns, choose match keys (SKU/handle/barcode/ID), set row policies, then manual preview/apply or schedule. Check Logs. Move to store N+1 with its own plan and sheet.

## Example: shared supplier, two brands

Ops maintained one supplier workbook with BrandA and BrandB tabs. They ran Data Sync on Brand A’s store against tab A (Growth, hourly), then repeated on Brand B’s store against tab B (Starter, daily)—no cross-store overwrite.

## Playbook

1. Document sheet URL + tab name per store.
2. Enable Data Sync; map and match keys.
3. Preview; fix sheet errors; apply.
4. Schedule only after a clean manual run.
5. Review Logs after the first scheduled job on each store.

## What to measure

- Preview vs apply error rate per store
- Rows processed vs plan row limit
- Time from sheet update to successful Logs run

## Proof points

- **1k / 5k** — Rows by plan
- **Preview** — Before apply on manual runs
- **Import only** — Sheet → Shopify

## Why this belongs in the EShopSet bundle

Instead of stacking a separate EShopSet bundle competitor, SEO suite, AI-visibility tracker, sheet importer, linker, and content tool, EShopSet includes **SEO Performance Monitor**, **AI Presence**, **Data Sync**, **Link Pilot**, and **CopilotPost** on one per-store plan (Starter from **$49/store/mo** at launch). Enable only what this store needs; usage never mixes across stores.

Operate the same apps from **Shopify Sidekick** or connect **EShopSet MCP** in Cursor, Claude, ChatGPT, Gemini, and Copilot.

## Get started

1. [Install EShopSet](https://apps.shopify.com/eshopset) from the Shopify App Store.
2. Enable **EShopSet bundle** and open Overview → Settings → Logs.
3. Follow this playbook, then compare limits on [pricing](https://eshopset.com/pricing/).
4. Optional: try the [live demo](https://demo.eshopset.com) or explore [AI Power](https://eshopset.com/ai-power/).

## Canonical & related

- Website use case: [https://eshopset.com/usecases/multi-store-management/in-house-data-sync-per-store/](https://eshopset.com/usecases/multi-store-management/in-house-data-sync-per-store/)
- App: [EShopSet bundle](https://eshopset.com/usecases/multi-store-management/)
- Category: [Multi-store Shopify management use cases](./README.md)
- Data Sync: https://eshopset.com/apps/data-sync/
- One-time sheet import: https://eshopset.com/usecases/one-time-sheet-import/
- Scheduled catalog sync: https://eshopset.com/usecases/scheduled-catalog-sync/
- Pricing: https://eshopset.com/pricing/

---

[Install Now](https://apps.shopify.com/eshopset) · [Pricing](https://eshopset.com/pricing/) · [Use cases on eshopset.com](https://eshopset.com/usecases/multi-store-management/)
