# 🏭 Manufacturing Performance & Operational Intelligence

## 📌 Project Overview

This project presents a comprehensive Manufacturing Performance & Operational Intelligence solution designed to evaluate production performance, equipment effectiveness, capacity utilization, maintenance efficiency, quality outcomes, and operational risk across a manufacturing environment.

The analysis uncovers hidden production losses, downtime impacts, quality-related inefficiencies, and capacity recovery opportunities while providing visibility into the operational factors influencing overall manufacturing performance.

By combining operational performance monitoring, production loss analysis, downtime analysis, quality analysis, risk assessment, and predictive forecasting, the solution delivers actionable insights that support operational excellence and continuous improvement.

---

## 🎯 Business Problem

Manufacturing organizations often struggle with:

- Production losses despite high efficiency levels
- Equipment downtime reducing operational availability
- Hidden capacity constraints limiting output growth
- Quality losses through waste and defects
- Inconsistent shift performance
- Reactive maintenance practices
- Limited visibility into emerging operational risks

Without a centralized analytics solution, identifying the root causes of these issues becomes difficult, resulting in lost productivity, increased operating costs, and reduced profitability.

---

## 🎯 Project Objectives

This solution was developed to answer key operational questions:

- Are production targets being achieved efficiently?
- What factors are limiting Overall Equipment Effectiveness (OEE)?
- How much production capacity is being lost?
- Which production lines create the highest operational risk?
- Which machines require maintenance prioritization?
- Where are waste and quality losses occurring?
- Which shifts perform most effectively?
- What future operational risks are emerging?

---
## 🧮 Manufacturing KPI Framework

The following manufacturing KPIs were developed using DAX and industry-standard manufacturing methodologies.

| KPI | Formula |
|------|----------|
| OEE | Availability × Performance × Quality |
| Production Achievement % | Actual Output ÷ Planned Output |
| Capacity Utilization % | Actual Output ÷ Planned Output |
| Production Variance | Planned Output − Actual Output |
| Recoverable Capacity | Planned Output − Actual Output |
| Capacity Loss % | Recoverable Capacity ÷ Planned Output |
| Quality Pass Rate | Good Output ÷ Total Output |
| Rework Recovery Rate | Rework Units ÷ Defective Units |
| Machine Risk Score | Downtime + Frequency + Response Time + Production Impact |

---
### Overall Equipment Effectiveness (OEE)

```text
OEE = Availability × Performance × Quality
```

| KPI | Value |
|------|--------|
| OEE | 58% |
| Availability | 66% |
| Performance | 91% |
| Quality Pass Rate | 94% |

---
### Production Achievement

```text
Production Achievement % = Actual Output ÷ Planned Output
```
---
### Capacity Utilization

```text
Capacity Utilization % = Actual Output ÷ Planned Output × 100
```

**Result:** 91%

----
### Recoverable Capacity

```text
Recoverable Capacity = Planned Output − Actual Output
```

**Result:** 43,000 MT

----
### Capacity Loss %

```text
Capacity Loss % = Recoverable Capacity ÷ Planned Output × 100
```

**Result:** 9.33%

----
### Rework Recovery Rate

```text
Rework Recovery Rate = Rework Units ÷ Defective Units × 100
```

**Result:** 51%

----
### Machine Risk Score

A composite metric developed using:

- Downtime Duration
- Downtime Frequency
- Maintenance Response Time
- Production Impact

---

# 📊 Dashboard Architecture

The solution is structured into six analytical modules:

### 1️⃣ Manufacturing Operations & Overall Plant Performance Overview

![manufacturing-operations-performance-intelligence](https://github.com/AdekunleOjo/manufacturing-operations-performance-intelligence/blob/main/Dashboard_Overview.jpg)

The operation produced approximately 417,585 MT during the reporting period while achieving 91% production efficiency. However, equipment availability remained at 66%, limiting overall manufacturing performance and contributing to an estimated 43,000 MT production shortfall. The analysis indicates that improving equipment reliability and reducing downtime present the greatest opportunities for increasing output without additional capacity investment.

**Focus Areas**

- Production Output
- Production Efficiency
- OEE Performance
- Production Variance
- Quality Performance
- Operational Effectiveness

---

### 2️⃣ Capacity Recovery & Production Loss Analysis

![manufacturing-operations-performance-intelligence](https://github.com/AdekunleOjo/manufacturing-operations-performance-intelligence/blob/main/Dashboard_Production%20Loss.jpg)

The analysis identified approximately 43,000 MT of recoverable production capacity, representing 9.33% unrealized capacity during the reporting period. While overall capacity utilization remained high at 91%, production losses were concentrated within specific operations, indicating localized inefficiencies rather than plant-wide performance issues.

These findings highlight significant opportunities to increase output through downtime reduction, process optimization, and operational stability improvements before considering additional capital investment.

**Focus Areas**

- Capacity Utilization
- Capacity Loss
- Recoverable Capacity
- Production Variance
- Production Loss Drivers

---

### 3️⃣ Downtime & Maintenance Intelligence Analysis

![manufacturing-operations-performance-intelligence](https://github.com/AdekunleOjo/manufacturing-operations-performance-intelligence/blob/main/Dashboard_Downtime.jpg)

Downtime is the primary constraint on plant performance, with 4,101 hours of downtime across 5,314 incidents, indicating frequent and significant operational interruptions.

Key causes of downtime include power failures, mechanical breakdowns, material shortages, maintenance delays, and operator error, highlighting a mix of technical and process-related issues.

Asset-level analysis shows the Filler as the highest-risk machine, followed by the Conveyor and Deodorizer systems, due to higher downtime exposure and slower recovery times.

Additionally, downtime incidents have increased by approximately 15% over the reporting period, suggesting a declining reliability trend that could further impact equipment availability if not addressed.

**Focus Areas**

- Downtime Duration
- Downtime Incidents
- Downtime Causes
- Maintenance Response Time
- Machine Risk Assessment

---

### 4️⃣ Quality, Waste & Rework Analytics

![manufacturing-operations-performance-intelligence](https://github.com/AdekunleOjo/manufacturing-operations-performance-intelligence/blob/main/Dashboard_Quality%20%26%20Waste.jpg)

The operation maintained strong quality performance with a 94% pass rate, despite producing 7,569 defective units, 3,840 rework units, and 663.89 MT of waste.

Approximately 51% of defective output was recovered through rework, demonstrating effective recovery capability but also highlighting hidden costs in materials, energy, and production time.

The Extraction Line was identified as the highest contributor to waste, representing the primary opportunity for quality improvement, while the Packaging Line recorded the lowest waste and may serve as a performance benchmark.

Overall, the analysis indicates that reducing defects at source would deliver greater value than relying on rework-based recovery.

**Focus Areas**

- Quality Pass Rate
- Waste Generation
- Defective Units
- Rework Recovery
- Process Quality Performance

---

### 5️⃣ Shift Performance & Operational Risk Analysis

Shift-level analysis shows clear performance variation across production periods. The Morning Shift consistently delivered the strongest results across efficiency, waste, and downtime metrics, while the Afternoon Shift performed weakest and represents the main opportunity for improvement.

These differences suggest that operational performance is influenced not only by equipment reliability but also by workforce execution, supervision quality, and shift management practices.

Although overall operational risk remains relatively balanced, inconsistency during afternoon operations increases variability in output and performance.

Reducing shift-to-shift variation is a key priority for improving overall plant stability and achieving more consistent manufacturing performance.

**Focus Areas**

- Shift Efficiency
- Production Loss
- Waste
- Downtime
- Operational Risk

---

### 6️⃣ Predictive Manufacturing Analytics

![manufacturing-operations-performance-intelligence](https://github.com/AdekunleOjo/manufacturing-operations-performance-intelligence/blob/main/Dashboard_Predictive.jpg)

Forecasting analysis indicates that production efficiency will likely remain stable at ~90–91%, showing sustained production capability. However, emerging reliability risks are evident, with downtime incidents increasing by approximately 15% over the reporting period.

If current conditions persist, production losses are expected to remain between 3,000–4,000 MT per week, while waste and defect levels are likely to remain volatile due to ongoing process variability.

Overall, future performance will be driven more by equipment reliability and operational stability than by production efficiency, making downtime reduction and process consistency key priorities.

**Focus Areas**

- Production Loss Forecasting
- Downtime Forecasting
- Waste Forecasting
- Defect Forecasting
- Operational Risk Forecasting

---

# 💡 Strategic Recommendations

## Short-Term (0–3 Months)

- Conduct root-cause analysis on major downtime drivers
- Prioritize corrective actions on high-risk assets
- Standardize best practices from the Morning Shift
- Investigate waste drivers within the Extraction Line

## Medium-Term (3–12 Months)

- Strengthen preventive maintenance programs
- Improve downtime classification and tracking
- Standardize operating procedures across shifts
- Implement machine-level performance monitoring

## Long-Term (1–3 Years)

- Deploy predictive maintenance capabilities
- Implement reliability-centered maintenance programs
- Expand condition-monitoring technologies
- Develop an operational excellence framework

---

# 🚀 Expected Business Impact

Successful implementation of the recommendations could result in:

- Improved OEE
- Increased Production Output
- Reduced Downtime
- Higher Capacity Utilization
- Lower Waste Generation
- Improved Equipment Reliability
- Greater Operational Stability
- Enhanced Decision-Making

---

# 🛠️ Tools & Technologies

- Excel
- Power BI
- DAX
- Power Query
- Manufacturing KPI Frameworks
- Forecasting & Trend Analysis
- Operational Risk Analytics

---

# 📌 Conclusion

This project demonstrates how manufacturing analytics can move beyond descriptive reporting and become a strategic decision-support capability.

The analysis reveals that while production efficiency and quality performance remain strong, equipment availability, downtime management, and capacity recovery represent the most significant opportunities for operational improvement.

By focusing on reliability, loss elimination, and operational stability, the organization can unlock substantial productivity gains while maximizing the value of existing manufacturing assets.
