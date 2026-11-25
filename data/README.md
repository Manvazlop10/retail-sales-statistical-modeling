# Data

Notebooks 01 and 03 use a 400-store retail dataset that was provided for a university course:

- `2nd_assignment.csv`: raw course file (with some missing values)
- `2nd_assignment_clean.csv`: cleaned version, written by `01_eda_hypothesis_testing.ipynb` and read by `03_ols_regression.ipynb`

Columns: `Sales` (thousands of units), `CompPrice`, `Income`, `Advertising`, `Population`, `Price`, `ShelveLoc` (Bad, Medium, Good), `Age`, `Education`, `Urban`, `US`.

The course file is not redistributed here. Its schema matches the Carseats dataset from *An Introduction to Statistical Learning* (James, Witten, Hastie, and Tibshirani), so the public Carseats CSV can be used to run the notebooks; results will be close to, but not exactly the same as, the course run.

Notebook 02 builds its data in code and needs no file.
