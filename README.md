# Multi-Brand QSR Franchise P&L Model

A dynamic monthly P&L model for a 10-location quick-service restaurant portfolio
across three brands: Little Caesars, Arby's, and Wingstop.

## What This Model Does

- Models **monthly revenue, COGS, and operating expenses** for each location
- Applies **brand-specific seasonal indices** to reflect real-world traffic patterns
  (Super Bowl, NFL season, summer peaks, drive-thru consistency)
- Separates **variable vs. fixed labor** for more accurate cost structure
- Adjusts **food costs monthly** to reflect commodity price swings (e.g. wing prices in February)
- Rolls up all 10 locations into a **Portfolio Summary tab** with brand-level subtotals

## Portfolio Overview

| Brand | Locations | Key Driver |
|---|---|---|
| Little Caesars | 4 | Summer family nights, Halloween, Super Bowl |
| Arby's | 3 | Drive-thru consistency, lower labor % |
| Wingstop | 3 | NFL season, Super Bowl (+35% revenue in February) |

**Total Portfolio: ~$8.5M annual revenue | ~$2.5M EBITDA**

## How to Use It

1. Open the Excel file
2. Navigate to any unit tab (e.g. "Little Caesars Location 1")
3. Edit the **yellow assumption cells** (base revenue, cost %, rent, utilities)
4. Edit the **amber seasonal index rows** to model different scenarios
5. The Portfolio Summary tab updates automatically

## Tools Used

Excel (openpyxl) | Financial modeling | QSR operations | Seasonal demand planning

## Background

Built to demonstrate P&L modeling and operations analytics skills
developed across fintech, franchise operations, and program management roles.
