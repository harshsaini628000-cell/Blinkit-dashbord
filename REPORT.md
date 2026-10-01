# Blinkit Sales Analysis – Report

## 1. Business Requirement
Conduct a comprehensive analysis of Blinkit's sales performance, customer satisfaction and inventory distribution, and identify opportunities for optimisation using KPIs and visualisations in Power BI.

## 2. Data Overview
- 8,523 records, 12 columns (item, outlet and sales attributes)
- Outlet establishment years: 2011–2022 (no records for 2013, 2019, 2021)
- Data quality fix: `Item Fat Content` standardised from 5 labels to 2 (Low Fat, Regular)
- Currency is shown as `$` in the dashboard; the dataset has no currency label

## 3. Headline KPIs (full dataset)
| KPI | Value |
|---|---|
| Total Sales | $1.20M |
| Average Sales | $141 |
| Average Rating | 3.97 |
| Records (items) | 8,523 |

## 4. Findings

### 4.1 Fat content
| Fat Content | Sales | Share |
|---|---|---|
| Low Fat | $776K | 64.6% |
| Regular | $425K | 35.4% |

Low Fat items sell nearly twice as much as Regular items.

### 4.2 Item type
Top 5 by sales: Fruits & Vegetables ($178K), Snack Foods ($175K), Household ($136K), Frozen Foods ($119K), Dairy ($101K). Seafood, Breakfast and Others sit at the bottom.

### 4.3 Outlet size
| Size | Sales |
|---|---|
| Medium | $508K |
| Small | $445K |
| High | $249K |

Medium outlets contribute ~42% of sales.

### 4.4 Outlet location
| Tier | Sales |
|---|---|
| Tier 3 | $472K |
| Tier 2 | $393K |
| Tier 1 | $336K |

Tier 3 leads, and Tier 1 is the smallest contributor.

### 4.5 Outlet type
| Outlet Type | Sales | Avg Sales | Avg Rating | Records |
|---|---|---|---|---|
| Supermarket Type1 | $788K | $141 | 3.96 | 5,577 |
| Grocery Store | $152K | $140 | 3.99 | 1,083 |
| Supermarket Type2 | $131K | $142 | 3.97 | 928 |
| Supermarket Type3 | $131K | $140 | 3.95 | 935 |

Supermarket Type1 drives ~65% of sales mainly through volume. Average sale and rating barely differ between outlet types.

### 4.6 Outlet establishment year
Sales per establishment year sit around $130K, with 2011 lower ($78K) and 2018 the peak ($205K).

## 5. Recommendations
1. Prioritise stock and promotions for Fruits & Vegetables, Snack Foods and Household.
2. Expand the Low Fat range, since it is the stronger seller.
3. Study Tier 1 outlets for under-performance (footfall, assortment, pricing).
4. Review the weakest categories (Seafood, Breakfast, Others) for range rationalisation or targeted campaigns.
5. Since ratings are flat (~3.9–4.0) across all segments, improving satisfaction needs a service/quality initiative rather than a segment-specific fix.

## 6. Limitations
- Single snapshot dataset with no date-level sales, so no true trend or seasonality analysis
- "Number of Items" counts item records, not distinct products
- Establishment-year results compare outlet cohorts, not sales over time
