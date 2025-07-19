# quick grab ecommerce report overview



## table of contents
- [introduction](#introduction)  
- [features](#features)  
  - [kpi cards](#kpi-cards)  
  - [metric slicer](#metric-slicer)  
  - [top 10 categories](#top-10-categories)  
- [how to use](#how-to-use)  
- [tech stack](#tech-stack)  
- [license](#license)  

---

## introduction  
this overview page aggregates your core ecommerce metrics into one place. by wiring everything to a custom **metric slicer**, you can toggle between total sales, average sale value, total items sold, or average rating—and see every visual recalc instantly.

---

## features

### kpi cards  
- display three primary metrics in **large, bold** font:  
  - **total sales**  
  - **total items sold**  
  - **average sale value**  
- mini sparklines below each card to show recent trend movement  
- live updates based on the chosen metric  

### metric slicer  
- a custom “metric” slicer drives **every** visual on the page  
- pick your measure and watch:  
  - kpi cards  
  - bar charts  
  - donut/stacked charts  
  - tables  
  all recalc on the fly 🔥

### top 10 categories  
- auto‑ranks the top 10 item categories by whichever metric you select  
- value labels on each bar for immediate comparison  
- dynamic reordering so category leaders shift as you toggle metrics  

---

## how to use  
1. open the `QuickGrab – Ecommerce.pbix` file in **Power BI Desktop**.  
2. locate the **metric slicer** in the top nav bar.  
3. select one of the four metrics:  
   - total sales  
   - average sale value  
   - total items sold  
   - average rating  
4. explore:  
   - kpi cards will update  
   - top 10 categories chart will reorder  
   - all other visuals adapt in real time 🚀  

---

## tech stack  
- **power bi desktop** for report authoring  
- data modeled on **star schema** with semantic measures  
- visuals: bar charts, donut charts, sparklines, tables  


## over the days page

> 🔎 this page dives into daily and yearly sales trends, letting you slice by item type and see how performance evolves over time.

---

### features

- **line chart: total sales by month & outlet size**  
  - displays monthly sales broken down by outlet size (high, medium, small)  
  - hover to inspect exact values and compare outlet tiers  
  - dynamic: respects both the **metric slicer** (from the overview page) and the **item type** filter  

- **waterfall chart: total sales by year & item type**  
  - shows annual sales progression, stacking “increase” and “decrease” segments around the total  
  - highlights how each year’s change contributes to the overall sales trend  
  - useful for spotting years of significant growth or decline across all item categories  

- **item type filter**  
  - located in the left pane as a checklist  
  - select one or more categories (e.g., Bakery, Dairy, Snack Foods)  
  - both charts instantly update to reflect only the chosen item types, revealing focused trends  

---

### how to use

1. open the `QuickGrab – Ecommerce.pbix` file in **Power BI Desktop**.  
2. navigate to the **“Over the Days”** tab (▶️ Over the Days).  
3. use the **item type** slicer on the left to pick one or multiple categories.  
4. watch the **line chart** redraw to show monthly sales across outlet sizes.  
5. check the **waterfall chart** below to see year‑over‑year sales changes for those same categories.  
6. combine this with your metric slicer (overview page) to pivot between sales, item counts, and ratings across time.

---

### why it matters

this page transforms raw time‑series data into clear stories:  
- spot seasonal peaks and troughs at a glance  
- understand which outlet sizes drive growth each month  
- identify years of rapid expansion or contraction across product lines  

with interactive filters and drill‑down visuals, you get a truly modular toolkit for uncovering hidden trends—day by day and year by year.  

---

## license  
this project is licensed under the [mit license](LICENSE). feel free to fork, tweak, and make it your own!  
