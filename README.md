# Project Performance Insights

Which marketing channels deliver positive ROI?

**Stakeholder:** Marketing Director

## Key Insights

- Paid social campaigns with low impression volume rarely break even on ROI.
- Email retains the highest conversion efficiency despite smaller reach.
- Display spend above $8k without A/B testing correlates with negative ROI.

## Dataset

Primary file: `data/campaign_performance.csv`  
Target variable: `roi_positive`

## Getting Started

```bash
pip install -r requirements.txt
jupyter notebook notebooks/01_exploration.ipynb
```


## Next Steps

**Done.** Class-weight tuning and SHAP explainability are implemented — see ### Implemented below.

---
*Analytics portfolio project — 2025-09*

<!-- build 7 -->

### Implemented

```bash
pip install -r requirements.txt
python src/train.py && python src/explain.py
```