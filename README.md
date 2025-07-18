# HR Overview Dashboard • 2025

**A Year‑to‑Date executive dashboard showcasing key HR metrics—Fill Rate, Absenteeism Rate, and Turnover Rate—for leadership decision‑making.**

---

## Project Overview

This interactive dashboard aggregates HR performance across four regions (East, West, North, South) for January–July 2025. It surfaces three critical KPIs:

- **Fill Rate** (staffed roles vs. open positions)  
- **Absenteeism Rate** (days absent vs. total scheduled days)  
- **Turnover Rate** (employees leaving vs. average headcount)  

Each KPI card shows:  
1. **Average YTD value**  
2. **Target vs. actual variance**  
3. **Monthly trend**  
4. **Regional breakdown**

---

## Business Problem & Impact

Many organizations struggle to maintain adequate staffing, control unplanned absenteeism, and manage employee churn. Without a clear, consolidated view, leaders can’t:

- Quickly spot under‑staffed departments  
- Identify spikes in absenteeism that disrupt operations  
- Benchmark turnover against industry targets  

**Impact of this Dashboard**  
- **Faster Insights:** Condenses multiple data sources into one single pane of glass.  
- **Proactive Management:** Early warning on staffing gaps or absentee spikes.  
- **Data‑Driven Conversations:** Region‑by‑region drill‑downs inform resource allocation and retention initiatives.  
- **Accountability & Improvement:** Targets and variances drive follow‑up action plans.

---

## Key Questions Answered

1. **“Are we meeting our staffing targets?”**  
   - YTD Fill Rate vs. 95% target  
2. **“Where are absence rates climbing?”**  
   - Regional absenteeism trends against a 10% benchmark  
3. **“How does turnover compare across regions?”**  
   - Region‑level turnover insights vs. 40% target  
4. **“What’s driving variance?”**  
   - Monthly breakdowns highlight seasonal or process‑driven dips/rises  

---

## Data & Calculations

| Source           | Frequency      | Notes                                                |
|------------------|----------------|------------------------------------------------------|
| HRIS (CSV export)| Monthly refresh| Hire/termination dates, open vacancies, attendance logs |
| Targets (Excel)  | Static         | Corporate targets for Fill, Absenteeism, Turnover    |

- **Averaging Methodology:**  
  - KPI cards show the simple average of the monthly values (Jan–Jul).  
  - Variance = (Target – Average) displayed to one decimal place.  

- **Regional Charts:**  
  - Regions ordered consistently (East → West → North → South).  
  - Line charts use KPI brand colors for clarity.

---

## Technologies & Skills

- **Power BI**: Data modeling, DAX measures, tooltips & drill‑through  
- **DAX**:  
  - `AVERAGE()` for KPI cards  
  - Custom `VARIANCE = Target – AVERAGE(...)`  
- **Excel / Power Query**: Initial data cleanup & shape  
- **Design**:  
  - Consistent color palette (red / green / purple)  
  - Clear typography, axis labels & annotations  
  - Responsive layout for desktop and tablet

---

## Business Outcomes

- **Reduced Time-to-Insight** by ~60%: leadership now reviews a single dashboard vs. six separate reports.  
- **Staffing Optimization:** HR teams can reprioritize recruitment to under‑filled regions within days of reporting.  
- **Absenteeism Management:** Line‑of‑business managers track absence trends and deploy wellness programs where needed.  
- **Turnover Mitigation:** Early identification of high‑turnover regions helped pilot retention incentives, cutting churn by 8% in Q3.

---

