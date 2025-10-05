# Mini Supply Chain Portfolio — Abhijit Kapse

> **Data notice:** Datasets are **synthetic/anonymized** for learning/demo.  
> S&OP horizon: **Apr-2024 → Mar-2025**. Ops KPI timestamps: **Apr–Jul 2024**.

## Preview

![Adjusted Demand vs Constrained Plan](https://raw.githubusercontent.com/AbhijitKapse369/ops-portfolio-abhi/main/sop_chart.png)
![Projected Inventory vs Safety Stock](https://raw.githubusercontent.com/AbhijitKapse369/ops-portfolio-abhi/main/inventory_vs_safetystock.png)
![On-time Dispatch % by DC](https://raw.githubusercontent.com/AbhijitKapse369/ops-portfolio-abhi/main/otd_by_dc.png)

---

## 1) S&OP Planning Workbook (Excel)
- Aligns monthly **demand**, **capacity**, and **safety stock** into a feasible plan.
- What-if inputs: **Demand Uplift %**, **Capacity Change %**, **Safety Stock (days)**.
- Outputs: **Constrained Plan**, **Projected Inventory**, **Stockout Flags**.
- File: `SOP_Workbook.xlsx` (usage guide on the **README** sheet inside the file).

## 2) Operations KPI Dashboard (Excel)
- KPIs: **On-time Dispatch % (OTD)**, **OTIF %**, **Pick/Pack TAT (min)**, **Fill Rate**.
- Monthly comparison by DC (Pune, Mumbai, Bangalore).
- File: `Ops_KPI_Dashboard.xlsx` (usage guide on the **README** sheet inside the file).

---

### How I’d use this in your team (DHL / Maersk / Delhivery)
- **Morning huddle:** yesterday’s OTD%, top exceptions, pick/pack bottlenecks.
- **Weekly S&OP:** run demand/capacity what-ifs, tune safety-stock policy, publish a constrained plan.

### Repo contents
- `SOP_Workbook.xlsx` — S&OP model.
- `Ops_KPI_Dashboard.xlsx` — KPI model.
- `sop_chart.png`, `inventory_vs_safetystock.png`, `otd_by_dc.png` — charts used in this README.
