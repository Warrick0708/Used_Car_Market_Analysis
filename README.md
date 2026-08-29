# Used Car Market Analysis — Ontario / GTA
## About This Project

This is a personal data analysis project exploring used car prices in Ontario, mainly in the Greater Toronto Area.

I started this project because I was interested in buying a used car myself and wanted to understand how different cars compare in the real market instead of only looking at a few listings.

The project uses 202 real used-car listings from CarGurus Canada and covers 14 different models, including regular sedans, hybrids, sport-oriented cars, and entry-level luxury cars.

The analysis has two main parts:

1. **Used car market analysis**
   I use basic Python and statistical methods to compare used car prices and look at how factors such as vehicle age, mileage, and model are related to listing prices.

2. **Personal purchase decision**
   I compare the cars based on six factors that matter to me: purchase value, insurance cost, reliability, performance, energy cost, and comfort/practicality.

I also test several different weighting scenarios to see how changing my priorities affects the final ranking.

Under the current assumptions and weights, the **Hyundai Elantra N Line** ranks first overall, with the **Honda Civic Hybrid** and **Genesis G70 2.0T** close behind.

## Repository Structure

```text
├── Report/       # Full project report and methodology
├── Data/         # Raw and cleaned used-car listing data
├── Notebooks/    # Python analysis
│   ├── 01_used_car_market_analysis.ipynb
│   └── 02_personal_purchase_decision.ipynb
```

## What I Used

This project mainly uses:

* Python
* pandas
* NumPy
* matplotlib
* seaborn
* statsmodels

The analysis includes basic descriptive statistics, regression analysis, data visualization, and a scoring model for the final purchase comparison.

## Methodology

More details about the data sources, data cleaning, regression model, scoring system, assumptions, and sensitivity analysis can be found in:

`Report/Used-Car_Market_Analysis_Source_Methodology_Final.pdf`

## Scope and Limitations

This project is based on my own use case and preferences.

The main assumptions are:

* Budget of around CAD 25,000–30,000
* Around 7,000 km of driving per year
* Three-year ownership period

Because of this, the final ranking should not be treated as a general ranking of which car is the best. A different driver with a different budget, driving habits, or priorities could get a very different result.

The used-car listings also represent a sample of the market at the time the data was collected, so they do not represent every vehicle available in Ontario.

## Note

AI tools were used to help improve the formatting and presentation of some files in this project. All data collection, calculations, and analysis results were checked separately to make sure the original data and results were not changed by AI.

## Author

Warrick Wang
