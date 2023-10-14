# Data Cleansing

Data cleaning is the process of fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or incomplete data within a dataset. So, we would like to perform data cleansing from the netflix_title.csv dataset. There are several parts to do Data Cleansing:

### Remove duplicate or irrelevant observations
Remove unwanted observations from your dataset, including duplicate observations or irrelevant observations. Duplicate observations will happen most often during data collection. When you combine data sets from multiple places, scrape data, or receive data from clients or multiple departments, there are opportunities to create duplicate data. <br>
Example: <br>
![image](https://github.com/vinamaulina/Data-Cleansing/assets/114405502/39eb4b4c-99e5-4891-a5fd-e25a5025d5b1)

### Fix structural errors
Structural errors are when you measure or transfer data and notice strange naming conventions, typos, or incorrect capitalization. These inconsistencies can cause mislabeled categories or classes. For example, you may find “N/A” and “Not Applicable” both appear, but they should be analyzed as the same category. <br>
Example: <br>
![image](https://github.com/vinamaulina/Data-Cleansing/assets/114405502/2d850efd-f71e-49ac-9b95-f5ed0f08f7a0)

### Handle missing data
You can’t ignore missing data because many algorithms will not accept missing values. There are a couple of ways to deal with missing data. Neither is optimal, but both can be considered.
As a first option, you can drop observations that have missing values, but doing this will drop or lose information, so be mindful of this before you remove it.
As a second option, you can input missing values based on other observations; again, there is an opportunity to lose integrity of the data because you may be operating from assumptions and not actual observations.
As a third option, you might alter the way the data is used to effectively navigate null values. <br>
Example: <br>
![image](https://github.com/vinamaulina/Data-Cleansing/assets/114405502/f9315774-a4fc-4889-830a-6aaabb060f8d)

