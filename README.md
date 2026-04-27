Titanic Data Set Overview:

Data Overview:
891 rows, 12 columns

Missing values: Age (177), Cabin (687), Embarked (2)

Data Cleaning
Age → filled with median (28)

Embarked → filled with mode ('S')

No duplicates

Converted types: Pclass, Sex, Embarked to category; Name, Ticket to string

Summary Statistics
Mean age: 29.7 years

Survival rate: 38.4% (342 survived, 549 died)

Age Distribution
Most passengers: 20–40 years

Few children under 5 or seniors over 70

Fare Distribution
Most fares under $50

Right‑skewed, max fare $512

Outliers
Age: few above 65

Fare: many above $100

Survival by Passenger Class
1st class: ~63%

2nd class: ~47%

3rd class: ~24%

Higher class → better survival

Survival Count by Class
3rd class had most passengers but fewest survivors

Correlation Highlights
Pclass vs Fare: -0.55 (strong negative)

Fare vs Survived: ~0.26 (weak positive)

Age vs Survived: ~0.08 (no correlation)

Conclusion
Majority were young adults with low fares (economy class)

Class and wealth are the strongest predictors of survival

Age and family size have almost no correlation with survival

