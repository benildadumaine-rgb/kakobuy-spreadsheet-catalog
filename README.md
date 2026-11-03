# Kakobuy Spreadsheet Catalog

An independent, static index of Kakobuy and Taobao product listings. It is a browsable website, not a Google Sheet, and it is not affiliated with Kakobuy.

## Dataset at a glance

- Products: 1,148
- Style rows: 14,535
- Categories: 6
- Buying agents tracked: 34
- Displayed price range (USD): $1.07–$192.65
- Catalog refreshed: 2026-10-29
- Last full price check: 2026-08-16
- Maintained by: Alex Finds, since 2025-10-29

## What a row contains

Each row is one style variant of a product. A single product can have several style rows, which is why 1,148 products produce 14,535 rows.

| Field | Meaning |
|---|---|
| category | Clothing, Accessories, Shoes, Pants, Bags or Watches |
| product_name | Product name |
| style_name | Style variant label, may be empty |
| sizes | Available sizes, may be empty |
| price_usd | Displayed USD price, converted at display time |
| agents_count | Number of buying agents that can source the listing (1–35) |
| first_agent | First agent listed for the row, not a ranking |
| product_link | Product listing URL, affiliate parameters removed |
| image_url | Product photo from the original listing |
| style_id | Style row identifier |
| refreshed | Last refresh date for the row |

## Category counts

| Category | Style rows | Share |
|---|---|---|
| Clothing | 7,623 | 52.4% |
| Accessories | 2,919 | 20.1% |
| Shoes | 1,852 | 12.7% |
| Pants | 1,594 | 11.0% |
| Bags | 283 | 1.9% |
| Watches | 264 | 1.8% |
| Total | 14,535 | 100% |

Fragrance is excluded while sourcing is paused. Long sleeves is a shortcut inside Clothing, not a separate category.

## Notes on accuracy

- Prices are refreshed in batches, not live. Confirm the final price at checkout.
- Catalog photos are style references from listings, not QC photos. Warehouse QC photos are taken after the item arrives.
- Agent order is not a ranking or endorsement. The index does not recommend any agent.
- RIVORA Style Catalog is the browsing interface name for this catalog, not a separate apparel brand.

## Links

- Catalog: https://sites.google.com/view/kakobuy-spreadsheet-catalog
- Browsable tool: https://productsite-8wf.pages.dev/spreadsheet?view=styles
- CSV export: https://productsite-8wf.pages.dev/kakobuy-catalog.csv

## Disclaimer

This is an independent resource. It does not process orders, payments or shipping, and it is not operated by Kakobuy.
