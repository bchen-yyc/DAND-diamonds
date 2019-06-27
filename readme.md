# Diamond Dataset Exploration
## by Liangbin Chen


## Diamond Dataset

It is a dataset regarding the prices and attributes of approximately 54,000 round-cut diamonds. All the data is stored in the `diamonds.csv` file.
In this project, I went through the steps of an explanatory data visualization, systematically starting from univariate visualizations, moving through bivariate visualizations, and finally multivariate visualizations. 
Here is a list of all the attributes

- price: Price in dollars. Data was collected in 2008.
- carat: Diamond weight. 1 carat is equal to 0.2 grams.
- cut: Quality of diamond cut, affects its shine. Grades go from (low) Fair, Good, Very Good, Premium, Ideal (best).
- color: Measure of diamond coloration. Increasing grades go from (some color) J, I, H, G, F, E, D (colorless).
- clarity: Measure of diamond inclusions. Increasing grades go from (inclusions) I, SI2, SI1, VS2, VS1, VVS2, VVS1, IF (internally flawless).
- x, y, z: Diamond length, width, and depth, respectively, in mm.
- table: Ratio of width of top face of diamond to its overall width, as a percentage.
- depth: Proportional depth of diamond, as a percentage. This is computed as 2 * z / (x + y), or the ratio of the depth to the average of length and width.

## How to run

Libraries needed: numpy, pandas, seaborn, matplotlib
Running environment: Jupyter Notebook
Executable files: Univariate_Exploration.ipynb, Bivariate_Exploration.ipynb, 
Explanatory_Polishing.ipynb, Multivariate_Exploration.ipynb.

## Summary of Findings

- The log of price was approximately linearly related to the cube root of carat weight
- It appears that price has negtive relation the categorical quality measures of cut, color, and clarity, that the median price decreased with increasing quality. However, after map the color the scatter plot of price VS. carat with clarity, we can clearly see with the same carat, higher clarity grade diamonds always have a higher price than lower grade ones.

