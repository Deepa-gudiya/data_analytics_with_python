project_2
-fundamentals_central_tendency.ipynb
-IBM-313 Marks.xlsx

📌 Implementation Strategy – Project 1

(Fundamentals & Central Tendency Analysis)

🔹 Step 1: Import Required Libraries

Imported pandas

Imported numpy (if required)

Used statistics module (optional)

🔹 Step 2: Load Excel Dataset

Loaded IBM-313 Marks.xlsx using:

pd.read_excel("IBM-313 Marks.xlsx")


Stored dataset in a DataFrame

🔹 Step 3: Data Inspection

Viewed first rows using head()

Checked dataset structure using info()

Verified number of rows & columns using shape

Identified column names

🔹 Step 4: Central Tendency Calculations

Performed statistical analysis on marks column:

Mean → df['column'].mean()

Median → df['column'].median()

Mode → df['column'].mode()

Also:

Compared manual formula calculation with built-in functions

Interpreted what each measure indicates about student performance

🔹 Step 5: Measures of Dispersion (if included)

Range → max - min

Variance → df['column'].var()

Standard Deviation → df['column'].std()

Analyzed data spread and consistency of marks.

🔹 Step 6: Interpretation of Results

Identified overall class performance trend

Checked whether marks are uniformly distributed

Observed variability in scores
