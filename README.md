# Tesla DCF Valuation Model

This project builds a discounted cash flow valuation model for Tesla using historical financial inputs, revenue growth assumptions, operating margin forecasts, reinvestment estimates, cost of capital, terminal value, and equity value calculations.

The goal of the model is to estimate Tesla's implied equity value and value per share under a DCF-based operating asset valuation framework.

## Project Overview

Tesla is a high-growth company with valuation heavily driven by future revenue growth, operating margin improvement, reinvestment needs, and long-term terminal assumptions. This model uses a structured DCF approach to forecast free cash flow to the firm and estimate the value of Tesla's operating assets.

The model includes:

* Historical inputs from Tesla's 10-K
* Revenue growth assumptions
* EBIT operating margin projections
* Tax assumptions
* Reinvestment calculations
* Free cash flow to firm forecast
* Cost of capital and discount factor calculations
* Terminal value estimation
* Equity value bridge
* Estimated value per share

## Model Structure

The workbook includes the following key sheets:

| Sheet                             | Description                                                                                                                              |
| --------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| `Tesla Valuation`                 | Main valuation output sheet with revenue forecast, EBIT, FCFF, discounting, terminal value, equity value, and estimated value per share. |
| `Inputs From 10k`                 | Historical inputs such as revenue, operating margin, tax rate, debt, and cash.                                                           |
| `Assumptions>>>`                  | Growth rate assumptions including most likely, worst case, and best case scenarios.                                                      |
| `Unadjusted Growth Rate (Calc)`   | Supporting calculation sheet for historical growth rates.                                                                                |
| `Adjusted Growth Rate (G&R Calc)` | Supporting calculation sheet for adjusted growth and risk assumptions.                                                                   |
| `EBIT OP Margin (Calc)>`          | Supporting calculation sheet for operating margin assumptions.                                                                           |
| `Cost of Sales Ratio (Calc)`      | Supporting calculation sheet for cost of sales assumptions.                                                                              |
| `OPEX Ratio (Calc)`               | Supporting calculation sheet for operating expense assumptions.                                                                          |
| `Risks`                           | Risk and sensitivity considerations that may affect Tesla's growth and valuation.                                                        |

## Key Valuation Inputs

| Input                      | Value / Approach                            |
| -------------------------- | ------------------------------------------- |
| Base Year Revenue          | $97.7 billion                               |
| Base Year Operating Margin | 7.2%                                        |
| Tax Rate                   | 20.0% in base year, 25.0% in forecast years |
| Forecast Period            | 10 years                                    |
| Terminal Growth Rate       | 4.0%                                        |
| Terminal Cost of Capital   | 8.0%                                        |
| Debt                       | $7.9 billion                                |
| Cash                       | $36.6 billion                               |
| Shares Outstanding         | 3.2 billion                                 |

## Valuation Methodology

The model follows a DCF valuation process:

1. Forecast future revenue using projected growth rates.
2. Estimate EBIT using operating margin assumptions.
3. Calculate after-tax operating income.
4. Estimate reinvestment needs using sales-to-capital assumptions.
5. Calculate free cash flow to the firm.
6. Discount projected FCFF using the cost of capital.
7. Estimate terminal value using terminal cash flow and terminal cost of capital.
8. Add present value of forecast cash flows and terminal value.
9. Adjust for debt and cash to calculate equity value.
10. Divide equity value by shares outstanding to estimate implied value per share.

## Valuation Output

The model estimates:

| Output                    |         Result |
| ------------------------- | -------------: |
| Value of Operating Assets | $116.1 billion |
| Value of Equity           | $144.8 billion |
| Estimated Value per Share |         $45.25 |

## Scenario Assumptions

The model includes multiple growth scenarios:

| Scenario         | Description                                                                   |
| ---------------- | ----------------------------------------------------------------------------- |
| Most Likely Case | Uses adjusted growth assumptions based on historical growth and risk factors. |
| Worst Case       | Reflects downside growth assumptions that account for business risks.         |
| Best Case        | Reflects upside growth assumptions based on stronger future performance.      |

## Risk Considerations

The model considers risks that could affect Tesla's valuation, including:

* Increased competition in the electric vehicle market
* Delays in vehicle design and production
* Reduction of tax credits or EV subsidies
* Market share pressure
* Revenue growth uncertainty
* Margin and cost structure volatility

## Tools Used

* Microsoft Excel
* Financial modeling
* Discounted cash flow analysis
* Scenario analysis
* Valuation analysis

## Files

* `Tesla Valuation Model.xlsx` - Excel workbook containing the full DCF model, assumptions, calculations, and valuation output.
* `README.md` - Project overview and documentation.

## Conclusion

This Tesla DCF valuation model estimates implied value per share by forecasting Tesla's future free cash flows and discounting them back to present value. The model shows how key assumptions such as revenue growth, operating margins, reinvestment, cost of capital, and terminal value can significantly influence Tesla's estimated valuation.

The model is intended as an educational finance project and should not be interpreted as investment advice.
