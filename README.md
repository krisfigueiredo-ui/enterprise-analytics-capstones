# Enterprise Analytics Capstones

Case studies from two university capstones completed with enterprise partners:

- City National Bank of Florida, University of Miami M.S. in Business Analytics
- Tractor Beverage Company, West Virginia University B.S.B.A. in Supply Chain Management

## City National Bank of Florida: IT Asset Lifecycle and Risk

Kristofor's documented contribution:

- Contributed to a cross-functional KPI audit across approximately 4,200 IT hardware assets in ServiceNow.
- Modeled lifecycle and end-of-life fields to predict at-risk units and surface legacy dependencies within internal systems.
- Supported development of a unified performance framework to standardize risk metrics and align reporting with strategic technology priorities.
- Built executive-ready Power BI dashboards with four interactive report pages and 19 custom DAX measures, translating system risk indicators into actionable leadership reporting.
- Delivered the reporting layer with DAX and CSS to meet a no-JavaScript security constraint.

[Open the public IT asset lifecycle and risk case study](https://krisfigueiredo-ui.github.io/cnb-synthetic-dashboard.html)

### DAX examples

[`dax/it_asset_risk_measures.dax`](dax/it_asset_risk_measures.dax) contains 19 newly written, generic portfolio examples covering lifecycle status, data completeness, dependency exposure, risk weighting, remediation candidates, and priority ranking.

These are not the original client measures. They use generic table and field names and do not encode internal thresholds or business rules.

## Tractor Beverage Company: Inventory Planning

**West Virginia University capstone · Project Team Leader · January-April 2025**

Kristofor led a seven-person team that developed a reusable SKU-level safety-stock strategy for a 27-product portfolio. The analytical approach included:

- ABC segmentation
- Service-level targets
- Safety-stock and reorder-point logic
- Forecast error monitoring
- Bootstrap and Monte Carlo scenario analysis

The team set SKU-level service targets of 85-95%. Backtesting indicated the model could have prevented approximately 80% of prior stockouts on key items while improving return on inventory investment by more than 20%.

[Open the public synthetic inventory-planning demonstration](https://krisfigueiredo-ui.github.io/tractor-synthetic-inventory.html)

Dashboard and DAX examples use demonstration data and newly written portfolio measures.

## Portfolio

[View Kristofor Figueiredo's full analytics portfolio](https://krisfigueiredo-ui.github.io/)
