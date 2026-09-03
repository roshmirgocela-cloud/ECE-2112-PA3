# ECE-2112-PA3
Made by: Roshmir Janylin C. Gocela
__
## PROBLEMS: PYTHON DATA ANALYSIS (PANDAS)
### A. Positional and Label-based Slicing

After loading cars, complete the following operations.
    a. Display the shape and complete list of column names of cars.
    b. Using positional slicing, create cars 6 to 10 containing rows 6 through 10 of the dataset, where
    the first data row is row 1.
    c. From cars 6 to 10, display only the columns Model, mpg, cyl, hp, and gear, in that order.
Requirement: The row selection in part (b) must use iloc; the column selection in part (c) must
use column labels.

### B. Model Lookup

Use Boolean indexing on the Model column to answer both requests.
  a. Display the complete row for Toyota Corolla.
  b. For Pontiac Firebird, display only Model, mpg, hp, and wt.
Store the two results in toyota and pontiac, respectively. Do not use a hard-coded row number to
locate either model.

### C. Multi-model Subsetting

Create a DataFrame named selected cars containing only the records for three models: Datsun 710,
Lotus Europa, and Ferrari Dino.
For these records, retain only Model, mpg, cyl, hp, and gear. Select the rows by their model values
rather than by row numbers. Display selected cars and its shape.
Required check: The final DataFrame must contain exactly three rows and five columns.

__

