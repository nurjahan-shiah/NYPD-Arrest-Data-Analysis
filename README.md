# NYPD-Arrest-Data-Analysis
For the seasonal trend analysis,  I used Python in the NYPD Arrest Data. 

Libraries used: Pandas, Matplotlib
Tools: Jupyter Notebook 

The dataset has been collected from: data.gov (https://catalog.data.gov/dataset/nypd-arrest-data-year-to-date)

Goal: Investigate any seasonal trends in the dataset, such as increases in certain types of offences during specific times of the year.

# To clean up the dataset, I'll focus on common data-cleaning tasks such as:
1. Removing duplicate rows.
2. Handling missing values, by filling them with a placeholder (e.g. "Unknown" for categorical data) or dropping rows/columns with missing values.
3. Ensuring consistent formatting for categorical data, such as capitalization and whitespace.

Clean dataset: 

## Result

# Top 10 Specific Offense Descriptions Leading to Arrests
1. Assault 3: 24,744 arrests
2. Larceny, Petit from Open Areas: 23,820 arrests
3. Assault 2,1, Unclassified: 15,496 arrests
4. Traffic, Unclassified Misdemeanor: 11,925 arrests
5. Robbery, Open Area Unclassified: 11,003 arrests
6. Public Administration, Unclassified: 9,325 arrests
7. Larceny, Grand from Open Areas, Unattended: 9,003 arrests
8. Controlled Substance, Possession: 7,966 arrests
9. Menacing, Unclassified: 5,784 arrests
10. Theft of Services, Unclassified: 5,703 arrests

# Top 10 Offense Categories Leading to Arrests
1. Assault 3 & Related Offenses: 33,839 arrests
2. Petit Larceny: 23,888 arrests
3. Felony Assault: 21,121 arrests
4. Dangerous Drugs: 15,701 arrests
5. Miscellaneous Penal Law: 14,862 arrests
6. Vehicle and Traffic Laws: 12,443 arrests
7. Robbery: 11,071 arrests
8. Criminal Mischief & Related Offenses: 11,012 arrests
9. Grand Larceny: 10,666 arrests
10. Dangerous Weapons: 9,613 arrests

# Heatmap for the top 5 offences, showing their frequency by month. This visualization will help to identify any seasonal patterns in the occurrence of these offenses.

<img width="461" alt="image" src="https://github.com/nurjahan-shiah/NYPD-Arrest-Data-Analysis/assets/70992112/a16fe94f-455a-43f1-a8b7-f9ed826f44a2">

Colours: The intensity of the blue colour indicates the relative frequency of each offense within a given month. Darker shades represent higher frequencies relative to the maximum occurrence of that offense throughout the year.

Patterns: Spotting which months show a higher occurrence rate for each offense. For example, if a specific offense has a notably darker column in certain months, it suggests a seasonal increase during those times.

Normalization: The data is normalized (scaled between 0 and 1 for each offense) to facilitate comparison across offenses that might vary widely in absolute numbers. A value of 1.00 indicates a month where the offence reached its peak frequency for the year, while lower values indicate lower frequencies relative to that peak.

