## Titanic Dataset Exploratory Data Analysis (EDA)
The dataset used is titanic.csv, which contains information about the passengers, including:

PassengerId: Unique identifier for each passenger.

Survived: Survival status (0 = No, 1 = Yes).

Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).

Name: Passenger's name.

Sex: Gender of the passenger.

Age: Age in years.

SibSp: Number of siblings/spouses aboard.

Parch: Number of parents/children aboard.

Ticket: Ticket number.

Fare: Passenger fare.

Cabin: Cabin number.

Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

Key Steps in the Analysis
Loading the Dataset: The dataset is loaded using pandas.

Initial Inspection:

Displaying the first and last few rows.

Checking the shape and data types.

Summarizing statistics.

Handling Missing Values: Identifying and summarizing missing values in the dataset.
Visualization: Creating plots to explore:
Survival counts.
Passenger class distribution.
Gender distribution.
Embarkation port counts.
Age distribution.
Key Findings
Survival Rate: More passengers did not survive than survived.
Passenger Class: The majority of passengers were in the 3rd class.
Gender Distribution: There were almost twice as many male passengers as female passengers.
Embarkation Port: Most passengers embarked from Southampton (S).
Age Distribution: The majority of passengers were between 20 and 40 years old.

Visualizations
Bar Plots: For categorical data (Survived, Pclass, Sex, Embarked).
Histogram: For the Age distribution.
