# Android-PlayStore-Data-Analysis
Analysing the bugs identified by topic modelling the reviews of different apps of Android Play Store.
Steps followed in the process
* Data of 30 different Educational Apps is collected using google scrapper [data_csv](Data_Educational_Apps.csv)
* For these 30 apps, reviews are being scraped using python [Scrapper_Code](Educational_Apps_Data_Scraped.ipynb)
* The reviews data[Reviews_Data](EducationalAppsDataScraped.xlsx) for all these 30 apps is being explored by EDA [EDA_Code](Exploratory_Data_Analysis.ipynb)
* The reviews are topic modelled [Topic_Modelling_Code](https://github.com/DivyaMeghana7686/Android-PlayStore-Data-Analysis/blob/main/Educational_Apps_Reviews_Topic_Modelling(main).ipynb) and the main topics/bugs from the reviews are obtained.
* The obtained bugs are analysed using the issues in  Common Weakness Enumeration [CWE](https://cwe.mitre.org/data/definitions/699.html) 
* The final report contains all the data about the issues occuring in educational apps [Report](https://github.com/DivyaMeghana7686/Android-PlayStore-Data-Analysis/blob/main/Final%20Report_Android%20PlayStore%20Data%20Analysis.pdf).
