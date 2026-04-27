 Data Inspection
891 rows, 12 columns.

Missing values: Age (177), Cabin (687), Embarked (2).

Missing Values
Age filled with median (28).

Embarked filled with mode ('S').

Data Cleaning
No duplicates.

Converted Pclass, Sex, Embarked to category; Name, Ticket to string.

Exploratory Data (Summary Statistics)
Mean age: 29.7 years.

Survival rate: 38.4% (342 survived, 549 did not).

Histogram – Age Distribution
Most passengers 20–40 years old.

Few children under 5 or seniors over 70.

Histogram – Fare Distribution
Most fares under $50.

Long tail of high fares (max $512).

Right‑skewed.

Boxplot – Age & Fare Outliers
Age: few outliers above 65.

Fare: many high‑fare outliers (>$100).

Line Chart – Survival Rate by Passenger Class
1st class: ~63%

2nd class: ~47%

3rd class: ~24%

Bar Chart – Survival Count by Passenger Class
3rd class had the most passengers but the fewest survivors.

Heatmap – Correlation Analysis
Pclass vs Fare: -0.55 (strong negative).

Fare vs Survived: ~0.26 (weak positive).

Age vs Survived: ~0.08 (no correlation).

Summary
Majority young adults with low fares – economy‑class base.

Survival drops sharply with class – privilege matters.

Higher fare weakly linked to survival; age has almost no correlation.

Wealth (fare) determines class, which drives survival.

Class and wealth are stronger predictors than age or family size.
