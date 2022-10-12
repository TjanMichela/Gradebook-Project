
<br/> The project involves:
- Data exploration
- Loading the data with Pandas
- Calculating the final grade
- Plotting the grade distribution

<br/> Datasets — CSV files:
- Information of the class rosterHomework and exam scoresQuiz grades

<br/>Complications:
- Students’ names are represented differently in each file
- Some students use nicknames and preferred names instead of what was recorded in the class roster
- Students with the same name have uniquely modified emails; therefore, each email address does not have the same elements
- Missing data
- Each data sources sorts the data differently
- Columns with the same data are labeled differently in each file

<br/>Process:
- Libraries used are pathlib, pandas, numpy, scipy, and matplotlib.

- Load and clean files
- Merge DataFrames
- Calculate students’ grades per category
- Calculate final letter gradeGroup and sort final_data
- Plot summary statistics
