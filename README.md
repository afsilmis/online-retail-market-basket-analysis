# Market Basket Analysis: Retail Intelligence System

A Data Science project utilizing Association Rule Mining to uncover product purchase patterns and generate merchandising strategies to increase revenue for a UK-based online retailer.

## Highlights

- **10.2× Average Lift** — 3-10× stronger than industry standard (1.5-3.3×)
- **98.5% Model Stability** — Validated on 76K test transactions
- **147 High-Quality Rules** — Covering 27% of total transactions
- **£7.14M Dataset** — 379K transactions from 4,265 customers across 39 countries

## Key Findings

### Product Association Patterns Discovered

| Pattern | Avg Lift | Avg Confidence | Business Action |
|---------|----------|----------------|-----------------|
| **Color/Design Variants** | 21.8× | 65.4% | Bundle discount for multi-variant purchases |
| **Theme Collections** | 30.0× | 74.7% | Dedicated display & gift packaging |
| **Complementary Products** | 18.5× | 61.2% | Cross-sell recommendations |

### Business Impact
- **27% Transaction Coverage** — Discovered patterns explain more than 1 in 4 customer purchases
- **3 Actionable Strategies** — Ready for implementation to boost cross-selling and bundling

## Tech Stack

- **Algorithm**: FP-Growth (tested 150+ parameter combinations)
- **Libraries**: pandas, numpy, mlxtend, matplotlib, seaborn, networkx
- **Validation**: Train-test split (80-20), stability testing

## Methodology

1. **Data Cleaning** — Removed 27% noise from 522K raw records
2. **Basket Creation** — Transform to transaction matrix (17K × 1.6K)
3. **FP-Growth Mining** — Extract frequent itemsets (min support 2%)
4. **Rule Generation** — Generate IF-THEN rules (min confidence 30%, min lift 2.0×)
5. **Validation** — Train-test split validation to ensure stability

## Documentation

For complete analysis, business insights, and detailed visualizations, please refer to the [presentation slides](https://github.com/afsilmis/online-retail-market-basket-analysis/blob/main/Market%20Basket%20Analysis%20Retail%20Intelligence%20System.pdf) in the PDF file.

## Author

**Az-Zukhrufu Fi Silmi Suwondo**  
- Email: afsilmis@gmail.com
- LinkedIn: [az-zukhrufu-fi-silmi-suwondo](https://linkedin.com/in/az-zukhrufu-fi-silmi-suwondo/)
- GitHub: [@afsilmis](https://github.com/afsilmis/)
