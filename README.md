# quick grab ecommerce report

> 📊 a fully interactive Power BI solution for quick grab’s ecommerce data—letting you pivot across metrics, timeframes, and categories in real time.

---

## table of contents
1. [overview page](#overview-page)  
2. [over the days page](#over-the-days-page)  
3. [numbers game page](#numbers-game-page)  
4. [global how to use](#global-how-to-use)  
5. [tech stack](#tech-stack)  
6. [license](#license)  

---

## 1. overview page

> 🔍 your command center: toggle core metrics and watch every visual recalc instantly.

### features

- **kpi cards**  
  - large, bold display of:  
    - total sales  
    - total items sold  
    - average sale value  
  - mini sparklines underneath for trend context  
  - live updates driven by the metric slicer

- **metric slicer**  
  - custom slicer lets you pick:  
    - total sales  
    - average sale value  
    - total items sold  
    - average rating  
  - powers **every** visual—cards, charts, tables—on the page 🔥

- **top 10 categories**  
  - bar chart auto‑ranks the top 10 item categories by your chosen metric  
  - value labels on each bar for quick comparison  
  - dynamic reordering as you switch metrics

---

## 2. over the days page

> 🔎 drill into time-based trends by month and year, filtered by item type.

### features

- **line chart: total sales by month & outlet size**  
  - shows monthly sales for high‑, medium‑, and small‑tier outlets  
  - hover for exact values and labels  
  - respects both the metric slicer and item type filter

- **waterfall chart: total sales by year & item type**  
  - displays annual sales progression with “increase”/“decrease” segments around the total  
  - reveals years of significant growth or decline at a glance

- **item type filter**  
  - left‑pane checklist of categories (e.g., Bakery, Dairy, Snack Foods)  
  - selecting categories instantly updates both charts

---

## 3. numbers game page

> 🔢 break down outlet contributions, month‑to‑month shifts, and detailed time aggregates.

### features

- **treemap: total sales by outlet size**  
  - visualizes high, medium, and small outlet contributions  
  - block size and label show absolute dollar values

- **line chart: sales distribution – month difference**  
  - overlays total sales vs previous month’s sales  
  - spot jumps or dips; hover for exact figures

- **matrix: detailed time metrics**  
  - hierarchical rows: year → quarter → period  
  - columns: TotalSales, TotalYTD, TotalQTD, TotalMTD  
  - scrollable for drill‑down from summary to monthly details

- **item type slicer**  
  - same checklist as “Over the Days” page  
  - filters all visuals on this tab

---

## global how to use

1. download/open `QuickGrab – Ecommerce.pbix` in **Power BI Desktop**  
2. explore each tab:  
   - **Overview** for high‑level KPI & top 10 category insights  
   - **Over the Days** for monthly/yearly trends by outlet size & item type  
   - **Numbers Game** for outlet breakdowns, MTD/QTD/YTD metrics, and period‑over‑period shifts  
3. use the **metric slicer** (Overview) to pivot between sales, counts, and ratings  
4. use the **item type** filter (left pane on other tabs) to focus on specific product categories  
5. hover, expand, and drill down on visuals for more detail 🚀

---

## tech stack
- **Power BI Desktop** for report authoring  
- star‑schema data model with semantic measures  
- visuals: KPI cards, bar charts, sparklines, donut & waterfall charts, treemaps, matrices  

---

## license
this project is licensed under the [MIT License](LICENSE). feel free to fork, customize, and deploy!  
