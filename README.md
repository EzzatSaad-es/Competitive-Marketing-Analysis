# Competitive Marketing Analysis Report

## Overview

A comprehensive competitive marketing analysis dashboard that provides detailed insights into sales performance across multiple channels, regions, and product lines. This project tracks key metrics including ROI, sales trends, and competitive positioning across online, social media, retail, and outlet channels.

---

## Key Features

### 📊 Five Main Dashboards:

1. **Detailed Info Dashboard**
   - Comprehensive product-level sales data
   - Manufacturer: VanArsdel
   - Track individual product performance (Maximus UM series)
   - Sales, units sold, and ROI metrics
   - Filter by channel (Online)

2. **Executive Overview**
   - Total Sales: $32K
   - Multi-channel performance tracking
   - Sales breakdown by channel, product, and time
   - ROI by channel (0% to 18%)

3. **Total Sales by City**
   - Geographic performance analysis
   - Top performing cities: San Diego CA ($70-87M), Los Angeles CA ($71M)
   - Multi-manufacturer comparison
   - City-level sales trends

4. **Sales by Region (Top 10)**
   - Regional sales breakdown: $11K total
   - State-level analysis with treemap visualization
   - Geographic heatmap with ROI distribution
   - Top regions: California ($1K+), Pennsylvania ($1K+), New York ($1K+)

5. **Return on Investment Analysis**
   - Overall ROI: 12%
   - ROI by state and product
   - Sales and ROI trends over time
   - Top performing products by ROI (Pomum UM-05 at 700%)
   - Channel-specific performance metrics

---

## Sales Channels

| Channel | Sales | ROI |
|---------|-------|-----|
| Online | $15K | 12% |
| Social Media | $9,262 | 0% |
| Stores | $6,746 | 5% |
| Outlet | $1,338 | 18% |

---

## Top Performing Cities

| City | State | Sales Range |
|------|-------|------------|
| San Diego | CA | $70M - $87M |
| Los Angeles | CA | $71M |
| Denver | CO | High |
| San Jose | CA | High |
| Colorado Springs | CO | Moderate |

---

## Top Products by ROI

| Product | ROI |
|---------|-----|
| Pomum UM-05 | 700% |
| Victoria UM-01 | 600% |
| Aliqui UM-04 | 300% |
| Currus UM-01 | 225% |
| Victoria UM-13 | 218% |
| Barba UM-05 | 138% |
| Aliqui UM-07 | 121% |
| Abbas UM-24 | 112% |

---

## Top Manufacturers

- **VanArsdel** (Primary focus)
- **Maximus** (UM series products)
- **Pirum** (Premium line)
- **Natura** (Eco-friendly)
- **Leo** (Standard line)
- **Abbas** (Budget line)

---

## Regional Performance Summary

**Total Regional Sales: $11K**

### Sales by Channel:
- Online Sales: $4,335 (39.4%)
- Social Media Sales: $3,103 (28.2%)
- Stores Sales: $2,886 (26.3%)
- Outlet Sales: $556 (5.1%)

### Top States:
- California: $1K+
- Pennsylvania: $1K+
- New York: $1K+
- Michigan, Georgia, Colorado, Washington, Louisiana, Kansas

---

## Key Insights

✅ **Channel Performance**: Online channel leads with 45.84% of total sales and 12% ROI

✅ **Seasonal Trends**: Sales peak from August to October, with secondary peaks in spring

✅ **Product Winners**: High-ROI products (Pomum, Victoria, Aliqui) drive profitability

✅ **Geographic Strength**: California dominates with San Diego leading city performance

✅ **Outlet Channel**: Despite lower volume, Outlet shows highest ROI at 18%

⚠️ **Social Media Concern**: 0% ROI indicates need for optimization

📈 **Growth Opportunity**: Store channel shows strong potential with 5% ROI

---

## System Requirements

- Microsoft Power BI Desktop or Power BI Service
- Excel 2016 or later
- SQL Server (optional, for large datasets)
- Minimum 4GB RAM for optimal performance

---

## Data Sources

- VanArsdel Sales Database
- Channel transaction records
- Regional sales systems
- Product performance metrics
- Geographic sales data

---

## Project Structure

```
Competitive-Marketing-Analysis/
├── dashboards/
│   ├── detailed-info.pbix
│   ├── executive-overview.pbix
│   ├── total-sales-by-city.pbix
│   ├── sales-by-region.pbix
│   └── roi-analysis.pbix
├── data/
│   ├── sales-data.xlsx
│   ├── product-data.xlsx
│   ├── regional-data.xlsx
│   └── roi-metrics.xlsx
├── reports/
│   ├── monthly-reports/
│   ├── quarterly-analysis/
│   └── annual-summary/
├── documentation/
│   └── data-dictionary.md
├── README.md
└── LICENSE
```

---

## How to Use

1. **View Dashboards**: Open .pbix files in Power BI
2. **Update Data**: Connect to your data source and refresh
3. **Filter Analysis**: Use interactive filters by channel, region, or product
4. **Export Reports**: Generate PDF or Excel reports for stakeholders
5. **Track Trends**: Monitor sales and ROI changes over time

---

## Key Metrics Explained

**Sales**: Total revenue generated from product sales

**Units Sold**: Quantity of products sold

**ROI (Return on Investment)**: Percentage return on marketing and sales investment

**Channel**: Distribution method (Online, Social Media, Stores, Outlet)

**Region**: Geographic area of sales activity

---

## Filters & Parameters

- **Channel**: Online, Social Media, Stores, Outlet
- **Manufacturer**: VanArsdel, Maximus, Pirum, Natura, Leo, Abbas, and others
- **Product**: All Maximus UM series and competitive products
- **Date Range**: Full year analysis with monthly granularity
- **Region**: All US states and major cities
- **ROI Range**: 0% to 700%+

---

## Performance Optimization Tips

- Filter by specific channels to reduce data load
- Use date range selectors for specific periods
- Archive historical data for faster queries
- Index frequently filtered columns
- Refresh data during off-peak hours

---

## Contributing

We welcome contributions! Please:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -m 'Add enhancement'`)
4. Push to branch (`git push origin feature/improvement`)
5. Open a Pull Request

---

## Troubleshooting

**Slow Dashboard Performance**
- Check data source connection
- Reduce time period filters
- Clear Power BI cache

**Missing Data**
- Verify data source is connected
- Check date filters are correct
- Confirm user has data access permissions

**ROI Calculation Issues**
- Verify all cost data is included
- Check for negative values affecting calculations
- Review formula definitions

---

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## Connect With Us

- 💼 **LinkedIn**: [Connect on LinkedIn](https://www.linkedin.com/in/your-profile/)
- 🐙 **GitHub**: [Follow on GitHub](https://github.com/your-username)
- 📊 **Portfolio**: [View My Work](https://your-portfolio.com)

---

## Notes

- Data includes competitive analysis from multiple manufacturers
- Analysis covers full calendar year with monthly breakdowns
- All figures in USD currency
- Regular updates maintained monthly
- Regional data covers all US states and major metropolitan areas

---

**Last Updated: October 17, 2025**
