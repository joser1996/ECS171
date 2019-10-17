# ECS 171 Report

## Jose Torres Vargas

### Problem 1

Data was divided into four bins by sorting, by mpg, and then dividing by four.
Each bin contains 98 samples each. Cut off indicies were... 

(Rows are 0-indexed)
* Low: 97 (mpg < 17)
* Med: 195 (mpg < 23)
* High: 293 (mpg < 29)
* Very High: 391 (mpg > 30)

### Problem 2

**Scatter Plot Matrix of features**

![Scatter Plot Matrix](https://github.com/joser1996/ECS171/blob/master/ScatterPlotMat.PNG "Scatter Matrix")

In this particular case I would say that the *weight* and *model_year* pair
give me the most information. In this plot I can clearly see each of the
four classes(Low, Med, High, and Very High) clustered together. I can
easily imagine multiple lines being drawn through the plot in order to divide
all four of the classes.

### Problem 3
Implemented OLS solver. See code.

### Problem 4

| Features | MSE 0th | MSE 1st | MSE 2nd | MSE 3rd | Data Set |
|:--------:|:-------:|:-------:|:-------:|:-------:|:--------:|
|Cylinder | 56.15 | 21.22 | 20.93 | 20.46 | Training Set|
|-| 73.18 | 32.29 | 32.50 | 26.33 | Testing Set |
|Displacement| 56.52 | 19.28 | 17.12 | 17.06 | Training Set|
|-| 73.18 | 27.67 | 24.16 | 24.13 | Testing Set|
|Horse Power| 56.51 | 23.19 | 20.52 | 20.48 | Training Set|
|-|73.18 | 26.64 | 15.30 | 15.84 | Testing Set|
|Weight | 56.52 | 17.39 | 16.39 | 16.38 | Training Set|
|-| 73.18 | 22.54 | 20.21 | 20.30 | Testing Set|
|Acceleration| 56.52 | 50.38 | 49.11 | 49.01 | Training Set|
|-| 73.18 | 50.38 | 50.26 | 50.11 | Testing Set|
|Model Year| 56.52 | 38.66 | 36.62 | 36.50 | Training Set|
|-| 73.18 | 45.44 | 44.22 |44.36 | Testing Set|
|Origin| 56.52 | 39.11 | 38.79 | 1067.01 |Training Set|
|-| 73.18 | 48.05 | 46.43 | 1447.08 | Testing Set|
*MSE Table*

**Cylinder** 

![Cylinder Plot](https://github.com/joser1996/ECS171/blob/master/cylinders_plot.PNG)

**Displacement** 

![Displacement Plot](https://github.com/joser1996/ECS171/blob/master/displacement_plot.PNG)

**Horse Power** 

![Horse Power Plot](https://github.com/joser1996/ECS171/blob/master/HP_plot.PNG)

**Weight** 

![Weight Plot](https://github.com/joser1996/ECS171/blob/master/weight_plot.PNG)

**Acceleration** 

![Acceleration Plot](https://github.com/joser1996/ECS171/blob/master/acc_plot.PNG)

**Model Year** 

![Model Year Plot](https://github.com/joser1996/ECS171/blob/master/year_plot.PNG)

**Origin** 

![Origin Plot](https://github.com/joser1996/ECS171/blob/master/origin_plot.PNG)
