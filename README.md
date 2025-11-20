# 💰 Pricing Optimization Strategy: Data-Driven Revenue Growth

## Executive Summary
Using real e-commerce transaction data, I developed a tiered pricing strategy that could increase annual revenue by **$2.38M (13.9%)** without acquiring a single new customer.

## The Business Problem
Most retailers use one-size-fits-all pricing, leaving money on the table in two ways:
- **Premium customers** would pay more for enhanced value, but aren't given the option
- **Price-sensitive customers** churn because there's no budget-friendly alternative

Current state: Single pricing tier generating $17.1M from 5,843 customers.

## My Approach

### 1. Price Elasticity Analysis
Analyzed 20 top-revenue products to understand price sensitivity:
- **13 products elastic** (|E| > 1): Demand is highly sensitive to price changes
- **5 products inelastic** (|E| < 1): Customers buy regardless of small price changes

**Key Insight:** Different products respond differently to pricing—one-size-fits-all leaves opportunity on the table.

### 2. Customer Segmentation (RFM Analysis)
Segmented 5,843 customers by Recency, Frequency, and Monetary value:

| Segment  | Customers | Avg Spend | Total Revenue | Behavior |
|----------|-----------|-----------|---------------|----------|
| Premium  | 1,729 (30%) | $8,052 | $13.9M (81%) | Frequent buyers, high value |
| Standard | 1,774 (30%) | $1,317 | $2.3M (14%) | Moderate engagement |
| Budget   | 2,340 (40%) | $378 | $885K (5%) | Price-sensitive, low frequency |

**Critical Finding:** 30% of customers (Premium) generate 81% of revenue but receive the same pricing as everyone else.

### 3. Revenue Trend Analysis
Identified strong seasonality:
- **November spike:** Revenue jumps before holidays (highest sales period)
- **January crash:** Sharp decline post-holidays
- **Insight:** Seasonal pricing adjustments could capture additional demand during peak periods

## Recommended Pricing Strategy

### Three-Tier Model:

**TIER 1 - VALUE ($):**
- **Target:** Budget-conscious customers (40% of base)
- **Pricing:** 15% below current average
- **Strategy:** Capture price-sensitive segment, reduce churn
- **Expected:** 2,808 customers × $321 avg = **$902K revenue**

**TIER 2 - STANDARD ($$):**
- **Target:** Mainstream customers (30% of base)
- **Pricing:** Current average pricing maintained
- **Strategy:** Core offering for typical customers
- **Expected:** 1,774 customers × $1,317 avg = **$2.3M revenue**

**TIER 3 - PREMIUM ($$$):**
- **Target:** High-value customers (30% of base)
- **Pricing:** 30% premium for exclusive perks
- **Strategy:** Capture willingness to pay more for an enhanced experience
- **Expected:** 1,556 customers × $10,468 avg = **$16.3M revenue**

## Projected Business Impact

| Metric | Current State | Proposed State | Change |
|--------|---------------|----------------|--------|
| Revenue | $17.1M | $19.5M | **+$2.38M (+13.9%)** |
| Customer Retention | Baseline | Improved via Value tier | Est. +20% in Budget segment |
| Premium Capture | $0 | $16.3M | New revenue stream |

### ROI Breakdown:
- **Implementation cost:** Minimal (pricing structure changes only)
- **Revenue uplift:** $2.38M annually
- **Margin improvement:** Premium tier likely has higher margins
- **Customer satisfaction:** Options for every budget level

## Technical Implementation

### Tools & Technologies:
- **Python:** pandas, numpy, scikit-learn, matplotlib, seaborn
- **Statistical Analysis:** Price elasticity (log-log regression), RFM segmentation
- **Data:** 798K+ transactions from UK e-commerce retailer

### Key Metrics Calculated:
- Price elasticity of demand
- Customer lifetime value by segment
- Revenue optimization scenarios
- Seasonal trend analysis

### Files:
```
pricing-optimization/
├── notebooks/
│   └── pricing_analysis.ipynb    # Complete analysis
├── data/
│   └── online_retail.csv          # Source data
├── visualizations/
│   ├── price_elasticity.png
│   ├── customer_segments.png
│   ├── pricing_recommendations.png
│   └── monthly_revenue.png
└── README.md
```

## Key Insights

1. **Premium customers are undermonetized:** They spend 21x more than Budget customers but pay the same prices
2. **Elasticity varies widely:** Some products can handle 30%+ price increases without demand loss
3. **Segmentation matters:** 40% of customers contribute only 5% of revenue—they need different pricing
4. **Seasonality opportunity:** November revenue spike suggests dynamic pricing could capture additional $$$

## Business Recommendations

### Immediate Actions:
1. **Launch Premium tier** with exclusive benefits (priority support, early access, premium packaging)
2. **Introduce Value tier** to reduce churn in price-sensitive segment
3. **A/B test pricing** on elastic products to validate elasticity calculations
4. **Implement seasonal pricing** for November holiday surge

### Expected Outcomes:
- 13.9% revenue increase = **$2.38M additional annual revenue**
- Improved customer satisfaction (options match willingness to pay)
- Better resource allocation (focus on high-value Premium customers)
- Data foundation for ongoing price optimization

## Learnings

This project taught me that pricing isn't just about covering costs; it's about understanding customer psychology, willingness to pay, and value perception. The biggest opportunity wasn't finding new customers; it was better monetizing existing ones.

*Built with Python, business acumen, and a lot of coffee ☕*
```
