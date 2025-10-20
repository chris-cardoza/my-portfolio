1. Checked the integrity and reliability of the data and source.
2. Read notes to understand how data was collected so that I am aware of any biases.
3. Categorized dataset features/ column names into broader categories to understand what the data communicates and plan how it can be used to answer the client’s questions if possible.
4. Read data schema to understand data types and units of measurement.
5. Viewed data on Excel for data exploration since it’s a small dataset (SQL not required).
6. Fixed formatting errors where column type did not match data schema (2 numeric features were incorrectly formatted as text in the data export).
7. Looked for any nulls (none were found).
8. Since all numerical data, searched for any exceptionally small/ large values using conditional formatting (none were found).
9. Plotted quick scatterplots and 100% stacked column charts of selected features to get an overview of what to expect in terms of how income, employment, and commuting duration compare across all neighbourhoods.
10. Determined KPIs through investigative research to establish thresholds for the purpose of evaluating Kingston’s performance on income, employment generation and occupational diversity.
11. Exported data to R for advanced programming, detailed analysis and higher quality visualizations.
12. Performed data cleaning to ready data for analysis: (1) viewed the data structure to check and correct for any feature type errors; (2) checked for any nulls in the dataset to either remove or substitute with proxy data; (3) converted counts to percentages because it would not be reasonable to compare counts across neighbourhoods that are variably sized; (4) removed columns that were irrelevant to the study to reduce computing time and dimensional complexity; (5) encode feature names to produce sizeable and cleaner visuals.
13. Proceeded with data analysis.
14. Produced a correlation matrix of all relevant numerical features and visualized the result as a heat map to easily spot any strong correlations within all possible variable pairs. But to create a more sizeable, intuitive and user-friendly heat map, some additional work needed to be done: (1) dropped the lower triangle of the matrix to eliminate unnecessary clutter because of duplicates; (2) dropped the middle diagonal of the matrix to eliminate misleading perfect correlations because they represent correlations with self; (3) selected a threshold of significance of 0.5 and dropped any correlations less than that so that only relevant features get mapped to further reduce size and complexity of visual, and, only significant correlations are coloured by the gradient scale so that weak correlations get filtered out for more user friendly visualization.
15. Studied resulting correlation matrix to identify feature relationships that may be answering the questions laid out in the problem statement regarding prevalence of low income using scatter plots, trend lines, R^2, and confidence intervals, and identify opportunities for growth if any.
16. Produced a density distribution ridgeline visualization to effectively compare the occupation distributions across all Kingston neighbourhoods and, once again, identify opportunities for growth if any.
17. Structured the analysis into a comprehensive narrative with key takeaways for the client.
18. Edited and finalized R markdown document and compiled it into an html report.
