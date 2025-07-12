# Data visualization

data visualization is typically the final step in your analysis. To have a figure that is easily readable, conveys information succinctly, and is not too overwhelming is the goal. In order to accomplish that task, your data must be cleaned, your data must be structured how you wish to present it, and your analysis must be complete. This guide will for the most part assume that those three steps are complete, though we will include a bit of all three at times. 

## Tables
Tables are not always included in data visualization guides or documents, but I find it to be just as important as plots. There are many uses where tables convery the information more clearly than a plot. Just as with plots, tables can become very difficult to parse if you are not clear in what information you want to convey and how you want to convey it. Many of you will have seen landscape regression tables with tiny text and every single covariate listed that become an endevor just to see if they allign with the author's interpretation of their test. A few tips for creating readable tables. 
- Do not make them more than a page or the standard margins (or very rarely break this rule)
- For summary statistics, consider what information the reader needs to know and be sure to include all of it, and nothing extra
- For regression tables, if you are testing a relationship between x and y and you have many covariates, you can include checklists in your table rows insteead of each indivudal covaraite. You should not interpretting coefficients and p-values for variables not included in your hypothesis.
- A key for most visualization is clean data, take your time and make sure you have properly prepared your data for the work you want to do
- Make sure you have variables measured at the correct unit of analysis. This is more of a data preparation tip, but visualization will make it blatant if you are presenting variables measured at different units of analysis together

When making tables for presenting, avoid using too many separation lines, but also try to avoid huge chunks of white space. This can be a tricky balance when you are starting out. One way to help you hone this skill is to take note of tables you come across whether in your job, university posts, or articles you are reading. If you are not able to immediately tell what the information they are presenting is and what they are trying to convey with that information, see if you can find out why. Are there too many variables without clear labels? Does the table have too much use of contrast and bold? Are the margins within the table consisten? Does the table have clear headers and labels? Those are a few questions to ask yourself. 

## Plots
Picking the right plot type can be difficult for new analysts. There are use cases for just about any kind of relationship you want to visualize. You can also choose multiple types of plots for each type of relationship. That being said, there are some plots that make the relationships you wish to present more convoluted or are excessive for your needs. Below is a basic table that I hope you find helpful. 

| Data type     | Plot type |
| ------------- | ------------- |
|Univariate, contionuous  | Box-whisker, density |
|Univariate, categorical  | Barplots |
|Bivaraite, categorical,continuous | Line plot, histogram, stacked/grouped barplot|
|Bivaraite, continuous,continuous | Scatterplot|
|Multivariate| Grouping|

There are obviously many types of plots and charts not mentioned here and there are use cases for all of them. These will be the most commonly used charts in social sciences. 
