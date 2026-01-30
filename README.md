# Quantifying Shade Inclusivity in Global Beauty Brands

This project analyzes foundation shade offerings across global beauty brands to evaluate how well different brands serve diverse skin tones.

Using exploratory data analysis and a custom Shade Inclusivity Index (SII), the project compares shade coverage and distribution across markets to identify inclusivity gaps in product offerings.

---

## Project Overview

Foundation shade availability varies widely across brands and regions. This project applies data analysis techniques to quantitatively measure how inclusive shade offerings are across global markets.

The analysis evaluates:

- Shade distribution across lightness values
- Coverage range of available shades
- Bias toward lighter or darker tones
- Overall inclusivity performance using a custom metric

---

## Key Findings

- Shade inclusivity varies significantly across brand groups, with some providing broader and more balanced coverage than others.
- Brands founded by BIPOC entrepreneurs and several US best sellers demonstrate the strongest overall shade inclusivity.
- Some markets still concentrate offerings in lighter shade ranges, suggesting limited availability for darker complexions.
- Inclusivity depends not only on the number of shades offered but also on how evenly shades cover the full skin tone spectrum.

---

## Methodology

The analysis combines exploratory data analysis with custom metrics:

1. **Shade Distribution Analysis**  
   Compare how shades are distributed across lightness values.

2. **Coverage Range Measurement**  
   Measure how much of the skin tone spectrum brands cover.

3. **Shade Bias Evaluation**  
   Compare average shade lightness across groups.

4. **Shade Inclusivity Index (SII)**  
   Composite metric combining:
   - Coverage range
   - Distribution evenness
   - Dark shade representation

This index enables quantitative comparison across brand groups.

## Repository Structure

```
shade-inclusivity-analysis/
├── data/
│   └── shades.csv
├── outputs/
│   ├── avg_shade_lightness.png
│   ├── shade_coverage_range.png
│   ├── shade_lightness_distribution_bygroup.png
│   └── sii.png
├── shade_inclusivity_analysis.ipynb
└── README.md
```


## Dataset

The dataset contains foundation shade offerings collected from beauty brands across several global markets. Shade colors were converted into lightness values using the CIE Lab color model to allow quantitative comparison.

Brand groups include:

- US best sellers
- Nigerian best sellers
- Japanese best sellers
- Indian best sellers
- BIPOC-founded brands
- BIPOC-recommended brands
- Fenty Beauty
- Make Up For Ever

Dataset source: Kaggle Makeup Shades Dataset (https://www.kaggle.com/datasets/shivamb/makeup-shades-dataset?resource=download)

---

## Business & Product Applications

This analysis shows how data science can support product strategy, including:

- Identifying shade coverage gaps
- Guiding shade expansion decisions
- Supporting inclusive product development
- Informing regional market strategy

---

## Future Work

Possible extensions include:

- Comparing shade offerings with population skin tone distributions
- Incorporating product sales data
- Tracking inclusivity trends over time
- Expanding analysis to other complexion products

---

## Tools Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

---
