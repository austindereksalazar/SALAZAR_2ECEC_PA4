# SALAZAR_2ECEC_PA4
#Experiment 4 - Data Wrangling and Data Visualization

##I. Intended Learning Outcomes:

* Filter tabular data using categorical and numerical conditions.
* Construct focused DataFrames with specific features.
* Summarize relationships between categorical features and numerical variables.
* Create clear, correctly labeled data comparison plots.

##II. Instructions & Problems:
Analyze the ECE Board Exam 2 dataset using Pandas and Matplotlib in a Jupyter Notebook.

##Problem A: VISAYAS COMMUNICATION DATAFRAME
Filter for Hometown 'Visayas' and Track 'Communication'. Retain specific columns.
Documentation for Problem A:

* Used `pd.read_csv()` to load data.
* Computed the missing 'Average' column using `.mean(axis=1)` on a DataFrame copy to preserve the original data.
* Applied explicit filtering conditions before selecting required columns.

##Problem B: VISAYAS FEMALE DATAFRAME
Filter for Hometown 'Visayas' and Gender 'Female'. Display rows where Average >= 60.
Documentation for Problem B:

* Applied strict filtering to create the `VisFemale` DataFrame.
* Used conditional masking (`VisFemale[VisFemale['Average'] >= 60]`) in the display function to show filtered rows without overwriting the variable.

##Problem C: CATEGORY-AVERAGE VISUALIZATION
Compute and plot the mean Average for Track, Gender, and Hometown.
Documentation for Problem C:

* Used `.groupby().mean()` to compute summary tables for each category.
* Used `plt.subplots(1, 3, sharey=True)` to generate three side-by-side bar charts with a consistent y-axis scale.
* Applied proper titles, axis labels, and tick rotations for clear readability.

##Author
Salazar, Austin Derek A.

##Date of Submission
17/09/2026

##Section
2ECE-C
