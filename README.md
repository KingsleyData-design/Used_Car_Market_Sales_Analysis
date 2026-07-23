# USED CAR PRICE PREDICTION ANALYSIS DASHBOARD 

## PROJECT OVERVIEW
  This project Analyzed used car market price prediction to identify price trend, kms driven, fuel type and price patterns across multiple car companies across India. By the end of this analysis, i was able to uncover the full story of What actually drives a used car's price — the brand, the age, how far it's been driven? This one digs into 716 used car listings to find out. Same Four-tool build as the rest of this portfolio: Excel, Power BI, SQL, and Python, same questions asked four different ways

  ## KEY METRICS 
  | METRICS | VALUE |
|--------|-------|
| AVERAGE CAR PRICE | ₹402.06 |
| HIGHEST AVG PRICE | Mahindra (₹626.25k) |
| LOWEST AVG PRICE | Tata (₹190.71k) | 
| TOTAL CARS LISTED | 716 |
| TOTAL COMPANIES | 25 |
| FUEL TYPE AVAILABLE | 3 |

## INSIGHTS — What the data actually says
- **Mahindra has the highest average price in this dataset**, sitting well above Toyota and Ford, which are tied close behind. Volkswagen, Honda, Hyundai, and Maruti follow, with Maruti at the lower end of the average price range.
- **Petrol and Diesel make up almost the entire market**  — 53.77% Petrol, 45.95% Diesel, and LPG barely registering at 0.28%. If you're pricing a used car in this dataset, it's almost certainly one of the first two fuel types.
- **Mileage and price have a clear inverse relationship**. Cars driven 0-20K km hold the highest average price, and it drops steadily through the 20K-40K, 40K-60K, and 60K+ brackets — pretty much exactly what you'd expect, but it's satisfying to see it actually hold up in the numbers.
- **Price by year isn't a simple "newer is always more expensive" story**. Average price actually dips through the 2000s before climbing back up, with a sharp jump for the most recent years — meaning some older cars are holding value better than the mid-range years, likely due to specific models or brands skewing those numbers.
- **Maruti has by far the most listings in the "Year by Company" breakdown**, meaning it's the most common brand showing up on the resale market, even though it's not the highest-priced.
  
## RECOMMENDATIONS — So what would this mean for someone buying or selling?
- **If you're buying, low-mileage cars in the 20K-40K bracket are probably the sweet spot** — you avoid the premium on near-new cars while mileage-related depreciation hasn't hit hard yet.
- **Brand matters more than raw mileage in some cases** Since Mahindra sits well above other brands on average price regardless of the general mileage trend, brand reputation and resale demand are clearly doing some of the pricing work here, not just condition.
- **Don't assume older automatically means cheaper** The price-by-year dip-then-rise pattern means some older cars are genuinely still valuable — worth checking a specific model's trend rather than assuming age alone drives price down.
- **Petrol and Diesel dominate for a reason** — LPG has almost no resale market in this dataset, so anyone selling an LPG vehicle should expect a much smaller buyer pool and price accordingly.

## TOOLS — What I built it in, and why four times?
- **Excel** — cleaned the data, first pass at average price by company, year, and fuel type. 
- **Power BI** — the main dashboard. Fuel Type and Year Range as slicers, with charts covering average price by company, year by company, price vs. mileage (bucketed), price by fuel type, and average price by year and of course, DAX and KPIs showing price trend and measures.
- **SQL** — same KPIs rebuilt as queries against the dataset.
- **Python** — same analysis again in a notebook, pandas and matplotlib doing the work.

Same reasoning as the rest of this portfolio — four tools, same questions, because the point is proving the logic holds up no matter which one's doing the calculating.

- **Files**
- `used-car-price-cleaned.xlsx — cleaned data + Excel dashboard`
- `Used-Car-Price-Prediction-Analysis.pbix — Power BI dashboard`
- `used-car-price-queries.sql — all the SQL, commented`
- `used-car-price-analysis.ipynb — Python notebook`
