# Project T5 Bootcamp
# Diamonds Dataset
## The resource https://www.kaggle.com/shivam2503/diamonds

### Problems:
Predict the price of diamonds

### Solutions:
### Dataset:
I will be using "diamonds.csv" data set that contains 10 columns and 53,940 rows.
#### Dataset Story:
The dataset has a story about diamonds, for each data has a story that is its price, its weight, its quality, its color, how it is clear, its dimensions, its total depth percentage, and width of the top of the diamond

#### Columns Stories:
- carat: weight of the diamond 
- price: in US dollars 
- cut: quality of the cut [Fair, Good, Very Good, Premium, Ideal]
- color: diamond color, from [D (best), E, F, G, H, I, J (worst)], [D, E, F] are Colorless and [G, H, I, J] are Near Colorless
- clarity: clarity a measurement of how clear the diamond is [IF (best), VVS1, VVS2, VS1, VS2, SI1, SI2, I1 (worst)] (by 10x microscope along with the trained naked eye)
- depth: total depth percentage is z / mean(x, y) = 2 * z / (x + y) 
- table:  width of the top of the diamond relative to widest point 
- x: length in mm 
- y: width in mm 
- z: depth in mm 

### Tools:
- Jupyter notebook<br>
- Programming language Python<br>
- Libraries: Numpy, Pandas, Matplotlip, train_test_split, LinearRegression, mean_squared_error
- https://en.wikipedia.org/wiki/Diamond_color ( to categorize colors )
