# Global Health Insights Dashboard
PowerBi

An advanced analytics project using Power BI to explore key global health indicators from 1999 to 2022 across 180+ countries. This dashboard provides a data-driven lens into life expectancy, child mortality, and HIV prevalence, three of the most critical metrics used to measure health system performance globally.

---

## Objective

To model and visualize long-term trends in core global health indicators using only Power BI, enabling actionable insights across regions and time. This project demonstrates how data storytelling can support epidemiological analysis, health equity tracking, and evidence-based decision-making in the public health sector.

---

## Tools & Technologies

| Task                          | Tool         |
|-------------------------------|--------------|
| Data Analysis & Visualization | Power BI     |
| Custom Metrics & Trends       | DAX          |
| Dataset Source                | Open Global Health Data (1999–2022) |

---

## Data Processing

The dataset included approximately 4,000+ records over a 24-year span with data from 180+ countries. Processing was done entirely in Power BI:

- Removed duplicate country-year entries  
- Cleaned inconsistent naming (e.g. spacing in country names)  
- Verified temporal coverage per country (some had missing years)  
- Parsed mortality fields into neonatal, post-neonatal, and under-5 segments  
- Applied proper data types to support DAX calculations and visuals  

---

## Feature Engineering

Custom DAX logic and calculated columns were created to derive:

- Year-over-Year (YoY) % changes in:
  - Life Expectancy
  - Infant Mortality
  - Under-5 Mortality
  - HIV Prevalence
- Trend indicators (▲▼) with conditional color formatting  
- Mortality Gap = Under-5 Mortality – Neonatal Mortality  
- Highest Life Expectancy Flag (used to highlight countries in visuals)  

These measures helped show directional movement, not just static values which are critical for policy interpretation.

---

## Dashboard Highlights

The dashboard was designed for ease of insight, especially for analysts and policymakers. Key visuals include:

- KPI cards with YoY changes and arrows (colored based on improvement/decline)  
- Line chart comparing Life Expectancy and HIV rate over time  
- Filled map with color intensity for average life expectancy, enriched with tooltips  
- Stacked bar chart comparing neonatal vs post-neonatal mortality trends  

Interactive slicers include Year and Country, supporting focused exploration.

---

## Key Insights

1. Life expectancy has steadily improved in many countries post-2010, although some nations show signs of plateauing or slower progress in recent years.  
2. A notable decline in life expectancy occurred between 2020 and 2022, coinciding with the global COVID-19 pandemic. This trend reflects:
   - Elevated COVID-related deaths
   - Disruption in essential healthcare services
   - Strain on public health systems
3. HIV prevalence spiked in 2000, 2002, and 2022, potentially linked to regional reporting changes or public health system shifts.  
4. Infant and under-5 mortality increased between 2020 and 2022, reversing prior improvements. This may relate to disrupted maternal care, immunization programs, or healthcare funding.  
5. Neonatal mortality remains the largest component of under-5 deaths in most countries, highlighting a persistent challenge in early-life care.  
6. Countries like Australia, Belgium, and Latvia consistently report the highest life expectancy, while several others show more variable progress over time.  
7. The global trend in infant mortality shows improvement, but large differences remain across countries.

---

## Dashbord



---

## Recommendations

1. **Support Countries Facing Life Expectancy Decline (2020–2022):**  
   Countries with recent declines should focus on restoring essential health services and strengthening preparedness for future health emergencies.

2. **Prioritize Neonatal Care in Health Programs:**  
   As neonatal mortality contributes the most to under-5 deaths, national health strategies should reinforce skilled birth care, newborn services, and follow-up care.

3. **Improve HIV Data Monitoring and Treatment Continuity:**  
   For countries showing rising HIV prevalence, strengthen annual data reporting and expand access to testing and antiretroviral therapy (ART).

4. **Enable Better Comparison Through Regional Grouping:**  
   To improve equity-focused analysis, consider organizing countries into regions or groups (e.g. WHO regions) to detect geographic patterns in health performance.

5. **Protect Maternal and Child Health During Crises:**  
   The increase in infant and child mortality during the pandemic reveals the need for resilient systems that can maintain these services even during emergencies.

---

## Conclusion

This project transforms multi-year global health data into structured, insight-driven visuals that reveal long-term trends in life expectancy, child mortality, and HIV prevalence. The dashboard supports public health understanding through:

- Outcome monitoring – by surfacing progress and setbacks in health indicators across countries  
- Regional benchmarking – through comparative visuals that highlight disparities and high performers  
- Policy direction – by helping decision-makers spot where to focus maternal, child, and infectious disease interventions  
- Crisis detection – by flagging reversals or disruptions in health outcomes over time  

By using Power BI to drive exploratory insight, trend detection, and user-friendly design, this analysis bridges the gap between technical analytics and real-world public health impact and reflects how I approach solving problems through data in the global health space.


