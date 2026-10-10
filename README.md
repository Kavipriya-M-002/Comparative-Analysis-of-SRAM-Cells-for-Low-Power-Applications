# Comparative Analysis of SRAM Cells for Low-Power Applications

## 🔍 Overview
This project focuses on comparing different leakage-power reduction techniques for a conventional 6T SRAM cell using 90 nm CMOS technology. The study evaluates stacking, PMOS clamping, standard MTCMOS, and a modified MTCMOS technique to analyze their impact on power consumption.

## 🛠️ Tools & Technology Stack

| Category | Tools / Technology |
|---|---|
| Circuit Design | Cadence Virtuoso |
| Technology | 90 nm CMOS |
| Physical Verification | DRC, LVS |
| Parasitic Extraction | RCX |
| Design Focus | Low-Power SRAM, Leakage Reduction |

## ⚙️ Methodology
- Designed and simulated a conventional 6T SRAM cell as the baseline.
- Evaluated stacking, PMOS clamping, and standard MTCMOS techniques.
- Implemented and evaluated a modified MTCMOS approach.
- Compared the power consumption of the different SRAM configurations.
- Analyzed DC response characteristics to compare the conventional and modified MTCMOS SRAM cells.
- Performed layout and parasitic extraction where applicable.

## 📊 Key Results

| SRAM Configuration | Reported Power (µW) |
|---|---:|
| Conventional 6T SRAM | 147.598 |
| Stacking Technique | 83.6443 |
| PMOS Clamping | 60.4218 |
| Standard MTCMOS | 21.1461 |
| Modified MTCMOS | 2.28509 |

The modified MTCMOS design achieved approximately **98.45% lower reported power** than the conventional 6T SRAM baseline under the evaluated simulation conditions.

## 📈 DC Response Comparison

- **Conventional 6T SRAM:** The butterfly curve represents the baseline static characteristics and is used for comparison.
- **Modified MTCMOS SRAM:** Exhibits a different butterfly-curve shape, indicating changes in its static characteristics due to the modified MTCMOS configuration.
- **Key Observation:** The results demonstrate approximately **98.45% lower reported power**. Quantitative static noise margin (SNM) analysis is required to confirm the impact on data-retention stability.

## 🎯 Key Takeaway
This project demonstrates the impact of different leakage-power reduction techniques on SRAM design and explores modified MTCMOS as a potential approach for low-power memory applications.
