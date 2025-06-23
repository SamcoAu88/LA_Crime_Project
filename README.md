#  🕵🏻 🚔 🚨 👮🏻  LA Crime Data Analysis (2020 - December 2023)

![CRIME](images/crime.jpg)

This project analyzes a dataset of reported crime incidents in Los Angeles spanning from 2020 to December 2023. The dataset, containing 851,405 entries and 27 columns, provides a comprehensive view of crime within the city. The goal of this exploratory data analysis is to identify key trends, patterns, and insights related to crime occurrence, victim demographics, location, and reporting.

## Summary and Key Findings

This initial exploration of the Los Angeles Crime dataset has revealed several important trends and insights:

**Dataset Overview:**
- The dataset comprises 851,405 entries, offering a substantial foundation for analysis.
- Initial data cleaning involved handling missing values in certain columns and addressing inconsistencies, such as negative values in victim age.

**Temporal Crime Trends:**
- Crime incidents in Los Angeles generally increased until 2022, which marked a peak in reported cases.
- Following the peak in 2022, a slight decrease in crime incidents was observed in 2023.

**Crime Occurrence Rates:**
- **Vehicle Theft** is one of the most frequently reported crimes, averaging approximately 64 incidents per day.
- **Battery (Simple Assault)** is another common offense, occurring on average about 47 times per day.
- Other frequently occurring crimes include Theft of Identity, Burglary From Vehicle, and Burglary.

**Victim Demographics and Age Profiles:**
- The most common age group for crime victims is individuals in their early to mid-30s.
- Certain crime types show a tendency to affect older individuals, with average victim ages exceeding 50 for offenses like Dishonest Employee Attempted Theft and Grand Theft / Insurance Fraud.
- Crimes against children, including Child Abuse (Physical) and Child Neglect, have alarmingly low average victim ages, some as low as 8 years.

**Crime Reporting Timeliness:**
- A significant portion of crimes (approximately 49%) are reported on the same day they occur.
- Around 28% of crimes are reported within 1 to 2 days of the incident.
- Approximately 9% of crimes are reported between 3 to 6 days after occurrence.
- Certain less frequent crimes show very short average reporting times (e.g., Failure to Disperse, Disrupt School).

**Top 5 Nighttime Crime Hotspots (8 PM - 3 AM):**
1. Central
2. 77th Street
3. Hollywood
4. Pacific
5. Southwest

These areas exhibit a higher concentration of reported crime during nighttime hours.

**Location Analysis:**
- Analysis of the `location` column, after cleaning up extra whitespace, reveals the most frequently mentioned locations for crime incidents. However, the granularity of this data varies (specific addresses vs. broader streets or areas), which is a limitation to consider for precise spatial analysis.

**Victim Sex Analysis:**
- The distribution of crime victims by sex shows a higher number of male victims compared to female victims. A portion of the data also includes 'Other/Unspecified' and missing values for victim sex.

**Victim Descent Analysis:**
- The top victim descent categories are Hispanic, White, and Black, followed by a significant number of Unknown/Other and Asian individuals.

**Premise Description Analysis:**
- The most frequent premise types where crimes occur include Street, Residence, and various types of businesses.

**Case Status Distribution:**
- The distribution of crime case statuses indicates the progression and resolution stages of reported incidents.

**Relationship between Victim Sex and Crime Type:**
- Analysis of the relationship between victim sex and the top 10 crime types reveals variations in victimization across different sexes for specific offenses.

**Hourly Crime Distribution:**
- The hourly distribution of crime incidents initially showed a peak around noon. However, this peak is significantly influenced by the reporting patterns of 'THEFT OF IDENTITY' incidents, which tend to be reported at a consistent time.

**Overall Conclusion:**
- This exploratory analysis has provided a comprehensive initial understanding of crime patterns in Los Angeles between 2020 and December 2023. The findings highlight temporal trends, frequently occurring crimes, victim demographics, reporting behaviors, and spatial concentrations of crime. Further in-depth analysis can explore the relationships between these factors in more detail and inform potential strategies for crime prevention and community safety.

## Libraries Used

- pandas
- matplotlib
- seaborn
