# 🌍 Global CO2 Emissions Analysis (1750–2021)
### A Data-Driven Exploration of Climate Change Through Carbon Data

---

## 📋 Project Overview

This project analyzes **global CO2 emissions** spanning over 270 years (1750–2021),
using country-level data paired with population figures to uncover trends, patterns,
and insights about humanity's carbon footprint.

The dataset is sourced from **Our World in Data** and covers fossil fuel emissions,
land-use change, per-capita figures, and temperature change contributions across
hundreds of countries and regions.

---

## 🗂️ Dataset Information

| Property | Detail |
|---|---|
| **Source** | Our World in Data — CO2 and GHG Emissions |
| **File** | `visualizing_global_co2_data.csv` |
| **Time Range** | 1750 – 2021 |
| **Rows** | 50,598 entries |
| **Columns** | 79 features |
| **Granularity** | Country × Year |
| **Countries / Regions** | 278 |

---

## 📁 Project Structure

```
CO2+Emissions/
│
├── CO2+Emissions.ipynb          # Main Jupyter Notebook
│
├── Raw_Datasets/
│   └── visualizing_global_co2_data.csv   # Source dataset
│
├── Visualizations/
│   ├── 00_EDA_Overview.png
│   ├── 01_Global_CO2_Trend.png
│   ├── 02_Top_Emitters_Three_Eras.png
│   ├── 02_Emissions_Share_2021.png
│   ├── 03_CO2_Per_Capita.png
│   ├── 04_Fossil_vs_LandUse.png
│   └── 05_Executive_Summary_Dashboard.png
│
├── Presentations/
│   └── CO2_Emissions_Presentation.pptx
│
└── README.md
```

---

## 🎯 Analysis Questions

### Q1 — How Have Global CO2 Emissions Changed Over Time?
Tracing the full journey from 1750 to 2021 using world-level data,
identifying key historical turning points including the Industrial Revolution,
Post-WW2 boom, Oil Crisis, and COVID-19.

### Q2 — Who Emits the Most CO2 Each Year?
Identifying top emitting countries across three historical eras (1900, 1970, 2021)
and analyzing their share of global emissions.

### Q3 — Where Does the Average Person Emit the Most CO2?
Per-capita analysis revealing the lifestyle and energy intensity of each nation,
comparing Gulf states, Western nations, and emerging economies.

### Q4 — How Have Fossil Fuel & Land Use Emissions Changed Over Time?
Breaking down emissions by source — coal, oil, gas, cement, and land use change —
to understand the energy mix evolution over 270 years.

---

## 🔧 Technical Stack

| Tool | Purpose |
|---|---|
| **Python 3** | Core programming language |## 📝 Phase 6 — Final Conclusion & Non-Technical Summary

---

### 🌍 The Story of Carbon: A 270-Year Journey

Imagine the Earth's atmosphere as a bank account.

For thousands of years, that account was perfectly balanced —
nature absorbed exactly as much CO2 as it released.

Then, around 1760, humanity made its first large "withdrawal" —
burning coal to power the Industrial Revolution in Britain.
The balance began to tip.

By 1900, the world was emitting **1,952 million tonnes** of CO2 per year.
A large number — but nothing compared to what came next.

The post-World War II economic boom unleashed an unprecedented
appetite for energy. Factories multiplied. Cars filled the roads.
Cities expanded overnight. By 2021, annual emissions had reached
**37,124 million tonnes** — a **1,802% increase** in just 120 years.

---

### 🏭 Who Is Responsible?

The burden is not shared equally.

Just **10 countries** are responsible for **68.3%** of all CO2 emitted today.

At the top stands **China** — now emitting 11,472 million tonnes per year,
nearly **one third of the entire planet's emissions**.
Behind it, the **United States** at 5,007 Mt, and **India** rising fast at 2,710 Mt.

But here is where the story gets more nuanced.

China has **1.4 billion people**. Its emissions per person?
Just **8 tonnes** annually.

Compare that to **Qatar** — a nation of 3 million —
where every single person emits **35.6 tonnes per year**.
That is **7.5 times the world average**.

The Gulf states, powered by oil wealth and energy-intensive lifestyles,
top the per-capita rankings by a wide margin.

---

### ⚡ What Are We Actually Burning?

In 2021, the breakdown was stark:

- 🪨 **Coal** — 14,980 Mt — *still* the largest single source at 41%
- 🛢️ **Oil** — 11,837 Mt — powering our cars and planes at 32%
- 💨 **Gas** — 7,922 Mt — the so-called "clean" fossil fuel at 22%
- 🏗️ **Cement** — 1,673 Mt — building our cities at 5%
- 🌳 **Deforestation** — 3,939 Mt — a silent, persistent contributor

Coal's share has fallen from 95% in 1900 to 41% today —
but its **absolute volume has never stopped growing**.
We have not replaced coal. We have simply added oil and gas on top of it.

---

### 🎯 What Must Change?

The data points to three urgent priorities:

**1. Target the giants.**
China, the USA, and India together produce over half of global emissions.
No climate strategy succeeds without their full commitment.

**2. End coal — truly.**
Coal remains the dirtiest and largest source.
Every coal plant still operating is a direct threat to climate targets.

**3. Rethink "natural gas."**
Gas is cleaner than coal — but it is still a fossil fuel.
At 7,922 Mt per year, it cannot be called a climate solution.

---

### 💬 Closing Thought

> *"The atmosphere does not negotiate.*
> *It does not care about economic growth, political cycles, or quarterly profits.*
> *It only responds to the total amount of carbon we release.*
> *The data is clear. The question now is whether our decisions will match it."*

---
*Analysis by Dr. Bahaa | Python & Jupyter Notebook | June 2026*
*Data Source: Our World in Data — Global CO2 and GHG Emissions Dataset*
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computations |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical plotting |
| **Jupyter Notebook** | Interactive development environment |

---

## 📊 Key Findings

### Q1 — Global Trend
- CO2 emissions in 1750: **9.35 million tonnes**
- CO2 emissions in 2021: **37,124 million tonnes**
- Growth from 1900 to 2021: **+1,802%**
- No sustained global decline has ever been recorded

### Q2 — Top Emitters (2021)
| Rank | Country | CO2 (Mt) | Global Share |
|---|---|---|---|
| 🥇 | China | 11,472 | 30.9% |
| 🥈 | United States | 5,007 | 13.5% |
| 🥉 | India | 2,710 | 7.3% |
| — | Top 10 Combined | — | 68.3% |

### Q3 — Per Capita Emissions (2021)
| Rank | Country | Tonnes / Person |
|---|---|---|
| 🥇 | Qatar | 35.6 |
| 🥈 | Bahrain | 26.7 |
| 🥉 | Kuwait | 25.0 |
| 🌍 | World Average | 4.7 |
| — | India | 1.9 |

### Q4 — Fuel Mix (2021)
| Source | CO2 (Mt) | Share |
|---|---|---|
| 🪨 Coal | 14,980 | 41.1% |
| 🛢️ Oil | 11,837 | 32.5% |
| 💨 Gas | 7,922 | 21.8% |
| 🏗️ Cement | 1,673 | 4.6% |
| 🌳 Land Use | 3,939 | — |

---

## 🎯 Recommendations

| Priority | Recommendation | Target |
|---|---|---|
| 🔴 Critical | Accelerate coal phase-out globally | China, India, USA |
| 🔴 Critical | Hold top 3 emitters accountable for 51.7% of emissions | Policy & diplomacy |
| 🟠 High | Address Gulf states' extreme per-capita footprints | Qatar, Bahrain, Kuwait |
| 🟠 High | Stop treating gas as a green transition fuel | All nations |
| 🟡 Medium | Halt deforestation — land use adds ~3,939 Mt annually | Tropical nations |
| 🟡 Medium | Support India's clean development path | India |
| 🟢 Ongoing | Replicate USA & Germany's per-capita decline model | Developing nations |

---

## 💬 Closing Thought

> *"The atmosphere does not negotiate.*
> *It does not care about economic growth, political cycles, or quarterly profits.*
> *It only responds to the total amount of carbon we release.*
> *The data is clear. The question now is whether our decisions will match it."*

---

## 👨‍💻 About the Analyst

**Dr. Bahaa** — Pharmacist & Data Analyst  
Bahaa Pharmacy, Dirout, Egypt  
Combining domain expertise with Python data science skills.

---

*Analysis completed: June 2026*
*Tool: Python 3 / Jupyter Notebook*
*Data Source: Our World in Data — Global CO2 and GHG Emissions Dataset*
