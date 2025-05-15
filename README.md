# The College Scorecard dataset

## Summary

For the final project, we are analyzing the U.S. Department of Education's *College Scorecard* dataset.

## About the Dataset

The *College Scorecard* dataset started by The Obama Administration in September 2015. Each row in this dataset contains information about a college in the USA.

Each row in the *data dictionary tab* of the spreadsheet describes a column in the original dataset (i.e. the name of the column and a desciption of the data contained in that column).

The `college` dataset includes data on a huge range of issues, including:

* location
* demographics
* admission standards
* tuition rates
* graduation rates
* student loans
* outcomes after graduation
* ... and many more (almost 2000 different variables!)


**This is a large dataset that that contains millions of individual cells.**
**As such, there is no one right way to approach this project.**

## The final project report

The final project is built around asking an interesting question about the dataset.

The project report should contain the following sections:

* Introduction
* Preprocessing
* Visualization
* Summary Statistics
* Data Analysis
* Conclusions

## Checklist

* **General**
  * Answers are written in full sentences and paragraphs.
  * Answers are clear and not garbled.
  * Tone is professional.
  * Correct spelling and grammar.
  * All graphs appropriately labelled (title and axes).
  * Code should be accompanied by written descriptions and interpretations (ask yourself "Would a random reader understand why I created this code chunk and what its code is doing?").
  * Formatting:
    * Use `head()` to show first 6 rows only.
    * Tables do not overrun right margin.
    * Code does not overrun right margin.
* **Introduction section**
  * Question of interest is stated.
  * Explanation of why this question is interesting.
  * State the columns you will be using to answer this question, and describe what data each variable contains.
  * State whether you will be using modeling or inference to answer your question.
* **Preprocessing section**
  * Extract the columns that is needed.
  * Rename columns more descriptively.
  * Recode any integer categorical variables.
  * Do *not* remove missing data at this stage.
  * Steps are documented with written descriptions of what each code chunk is doing.
* **Visualization section**
  * At least 3 graphs (relevant to question, and showing distinctly different information).
  * One graph must use faceting to show multiple sub-plots.
  * Each graph introduced by sentence(s) explaining why it has been created.
  * Each graph followed by an interpretation.
  * (Optional) A brief conclusion summarizing any overall patterns that are most relevant to the question of interest.
* **Summary Statistics section**
  * Summary stats calculated for each of the variables identified in the Introduction section.
  * Written interpretations of the numbers you have just calculated.
* **Data Analysis section**
  * Code is accompanied by written descriptions and interpretations.
  * Using modeling:
    * Create a linear model.
    * Report coefficients (slope(s) and intercept) and R<sup>2</sup>, and discuss what these numbers mean for your model.
    * Create 3 graphs to check the model assumptions:
      * Observed vs. predicted plot
      * Residuals vs predicted plot
      * Q-Q plot.
    * Interpret the above plots.
* **Conclusions section**
  * Integrate the results from *all* previous sections in this project.



