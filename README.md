# Statistical-Analysis-and-Visualization-in-R
First Project 
SUMMARY STATISTICS

Crop Yield Summary:
# A tibble: 3 × 3
  Crop  Mean_Yield SD_Yield
  <chr>      <dbl>    <dbl>
1 Maize       5.01    0.522
2 Rice        4.29    0.418
3 Wheat       3.48    0.392

Shapiro-Wilk Normality Test (Crop Yield):

	Shapiro-Wilk normality test

data:  crop_yield$Yield_ton_per_hectare
W = 0.98579, p-value = 0.4365


Soil Properties Correlation Matrix:
                           Soil_pH Nitrogen_mg_kg Phosphorus_mg_kg
Soil_pH                 1.00000000    -0.08157270       0.02560003
Nitrogen_mg_kg         -0.08157270     1.00000000       0.06192303
Phosphorus_mg_kg        0.02560003     0.06192303       1.00000000
Organic_Matter_percent -0.14805862    -0.01718599       0.03745695
                       Organic_Matter_percent
Soil_pH                           -0.14805862
Nitrogen_mg_kg                    -0.01718599
Phosphorus_mg_kg                   0.03745695
Organic_Matter_percent             1.00000000
