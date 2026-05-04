# MIST-4610-Group5-Project2

## Team Members
- Caleb Rivers – (https://github.com/CRivers2805/MIST_4610_21482_G5_CMR_2)
- Catherine Lusick - (https://github.com/cl95728/GroupProject2_MIST4610)
- Emmy Nguyen – (https://github.com/emmyn1/MIST-4610-Group5-Project2)  
- Diyaa Patel - (https://github.com/Diyaa-P13/MIST4610-Group5-Project2.git)

## Dataset Description 
Our dataset focuses on drug overdose rates in the United States from 2000 to 2018. The data was obtained from https://catalog.data.gov/ and includes a variety of dimensions that allow for detailed analysis of trends related to the opioid epidemic. The dataset contains variables such as the year, which is a whole number, data type, along with demographic categories including gender, race, and age group, which are all stored as string data types. It also includes information on the type of drug involved in each case, such as heroin or methadone, which is another categorical variable. A key measure in the dataset is the age-adjusted overdose death rate, which is a decimal data type and allows for accurate comparisons across different populations. These dimensions work together to show how overdose rates change over time and how different groups are affected. Overall, the dataset includes a mix of categorical and numeral variables that provide enough depth and variation to analyze patterns, identify trends, and better understand the impact of drug overdoses in the United States.

## Question 1

Question: How did age-adjusted methadone overdose death rates per 100,000 population compare between males and females from 2000 to 2015?

This question was chosen because the biological and social differences between males and females can significantly influence how the body processes opioids like methadone. It also shows how likely each group is to seek treatment. By isolating genders as a variable, we are able to determine whether intervention efforts should be tailored differently depending on gender.

<img width="907" height="464" alt="image" src="https://github.com/user-attachments/assets/732d3caa-85dd-4524-9bf9-3ab00f2d0dc2" />

The timeline graph displays how the estimated deaths have both increased and decreased over the fifteen-year time period, with colors separating the variables. The Gantt bar chart represents the values of each estimate as their own independent bars, with the bottom of the bar lying on the value of the estimate, and the length of the bar also representing the value of the estimate. We are evaluating a notable disparity in the values by whether there is a gap between the male and female bars in one year.

As seen in both visualizations, males consistently recorded higher death rates throughout the entire fifteen-year period, with the most significant difference occurring around 2006-2007. The Gantt bar chart makes this gap especially clear, as the male bars exceed the female bars in nearly every observed year, leaving little ambiguity about which group bears more burden. Notably, both groups follow a similar rise and fall pattern, suggesting that the same external factors are influencing both genders, yet males remain far more severely impacted at every point in time. 

The disparity is largely tied to the fact that males are statistically more likely to engage in higher-risk substance use behaviors and are less likely to seek medical intervention early. Additionally, males tend to be prescribed higher opioid doses on average, increasing the possibility of overdosing. This is supported by the National Institute on Drug Abuse, which confirms that men are more likely than women to use illicit drugs and die from overdoses. The sharp peak around 2006-2007 also aligns with the period of relaxed regulations on methadone distribution, where 25% annual increase in distribution disproportionately impacted males, given their high usage rates. As those regulations became stricter after 2006, male overdose deaths followed the same downward trend, showing a clear connection between policy changes and death rates.  

## Question 2

Question: How did age-adjusted Methadone overdose death rates compare between non-Hispanic Black and Hispanic/Latino populations from 2000 to 2015, and which group saw the more significant trend shift during this period?

<img width="907" height="463" alt="image" src="https://github.com/user-attachments/assets/ce3273df-5593-444e-9efb-c184d69bebd9" />

The timeline graph displays how the estimated deaths either increased or decreased over the fifteen-year time period, with colors separating the variables. The bar chart displays the extent that the deaths had increased compared to their initial levels in 2000, with darker hues of red signaling higher death rates.

This question was posed in order to observe what impact race, and, in turn, socio-economic situation has on methadone overdose deaths. By analyzing the results of these queries, we can determine which ethnic group experiences the most risk for overdose death, and which demographics should begin to exercise more caution when dealing with opioids. 

The reason that blacks and Hispanics are being compared is because of the growing number of Hispanics found in majority-black neighborhoods, and vice versa. As Brookings Research Organization states, “For example, 44.7% of Black and Latino or Hispanic residents in majority-minority cities live in combined Black and Latino-majority cities,” and “Many of the largest combined Black and Latino-majority cities have near equal proportions of Black and Latino or Hispanic residents—indicating the potential for racial coalitions.” As such, it is important to observe the impacts of both demographics as they continue to become intertwined. These conclusions are also supplemented by the similar trends observed between the two groups. A third-degree polynomial trendline explains 94% of the variation in the data with Hispanics, and 72% of the variation with blacks. 

As observed in the graphs, blacks experienced the highest amount of deaths overall, with around 8.5 deaths per 100000 in both 2006 and 2007. While those numbers did settle towards the end of the observed time, they remained consistently higher than Hispanic deaths. In fact, Hispanics only featured a higher death toll in 2003, and by a trivial margin. With this in mind, it is quite clear that overdose trends disproportionately affect blacks in comparison to Hispanics

Additionally, as observed in the heatmap, not only are black overdoses consistently higher than those of Hispanics, but changes in the deaths are also more severe. In almost all areas where the color is getting warmer, the black graph ends up with much warmer colors compared to their Hispanic counterparts, which further supports the conclusion that blacks disproportionately face the effects of overdose trends. On a more positive note, however, it can also be concluded that Hispanics, while still susceptible to overdose trends, usually plateau and are mitigated before they can reach extreme numbers. Despite this, it should still be noted that blacks do seem to be more efficient at decreasing their death tolls, shown by the return to the colder shades of red at the end of the observed time, while it seems to be more difficult for Hispanic deaths to return to pre-extrema levels. 

It should be noted that other external studies are consistent with our findings. The National Library of Medicine engaged in a similar analysis and reached many of the same conclusions. It not only states that “Opioid overdose death rates have skyrocketed in the past 20 years in all racial and ethnic groups, with the greatest increase among Black Americans in the past 10 years, said Magdelena Cedrá” but also “looking specifically at access to methadone and buprenorphine, Cerdá noted additional examples of racial patterning, with racially minoritized individuals having lower access to buprenorphine,” a drug distributed in order to counter the effects of Opioid Use Disorder. In regard to buprenorphine, “A study in New York City by Helena Hansen and colleagues showed that between 2004 and 2013, buprenorphine treatment increased across all areas, with a significantly higher increase in areas with the highest income and lowest percentage of Black, Hispanic, and lower income residents. By contrast, methadone use was concentrated in areas of high poverty and a higher concentration of Black and Hispanic residents,” which aligns with the extreme death tolls observed in the two demographics. Not only is there lower access to buprenorphine in these areas, but there is also a larger availability of the opioid in these areas, with the study highlighting that “Methadone was more likely to be available in counties with highly segregated Black populations.”

The causes for an increased availability of methadone are outlined in other reports, such as one from the Federal Register that states “Federal opioid treatment standards were significantly reduced in scope to allow more flexibility and greater medical judgment in treatment. Certain restrictions on dosage forms were eliminated so that OTPs may now use solid dosage forms. Under the previous rules, OTPs were limited to the use of liquid dosage forms. Several reporting requirements and reporting forms were eliminated, including the requirements for physician notifications and the requirement that programs obtain FDA approval prior to dosing a patient above 100 milligrams. The proposal included a more flexible schedule for medications dispensed to patients for unsupervised use, including provisions that permit up to a 31-day supply. Under the current regulations, patients are limited to a maximum 6-day supply of medication.” As such, methadone distribution increased by 25% on average annually from 2002 to 2006, according to the CDC, which is in line with the tremendous increases of deaths observed in the black and Hispanic communities during that time period. However, the loosened restrictions became tighter once again. Dosage intervals expanded, increased warnings were given for using methadone for pain, and the largest methadone pills became more limited in their distribution (CDC). As such, the amount of methadone distributed decreased by around 3% annually on average form 2006-2016, which is also directly proportional to the amount of deaths observed in the black and Hispanic communities.

For Hispanics specifically, it has been found that substance abuse disorders and discrimination and fears based around immigration status, according to the Substance Abuse and Mental Health Services Administration (SAMHSA). Additionally, according to the United States Office of Homeland Security, deportations and removals increased steadily from 2002 to 2009, which could also be correlated to the levels of substance abuse and, in turn, overdoses.

Lastly, also from the Peer Research Center, 26% of both blacks and Hispanics live in multigenerational households in the United States, many of which are becoming known as “pill mills,” multigenerational households that house many prescriptions prescribed to elders that are either stolen or distributed to the younger members of the household, according to SAMHSA. In low income households and areas, this phenomenon is even more likely to occur as the drugs are either taken by a family member or sold to others as a means of extra income, which means that both black and Hispanics, with 20% and 15% 100% below the poverty line according to the National Equity Atlas, are high susceptible to become victim to pill mills, which explains why the methadone distribution increases in the 2000s effected both populations so severely.


## Manipulations Applied to the Data Set for Analysis

The manipulations made to our chosen data set were extensive, mostly due to the dataset not even being in first normal form, which made efficiently visualizing the data difficult before making the proper adjustments. Some of the issues encountered in the data include having multiple values in one cell, having the same value in two different cells, having multiple, non-correlated “primary keys” that were repeated numerous times, attributes that had the same value in every cell, attributes that were ambiguous, and non-primary keys that were referencing other non-primary keys.

After both deleting and adding columns, we had reduced the size of the data by three rows by deleting columns that were either ambiguous, redundant, or had the same value in every cell, allowing us to streamline our visualization process. Additionally, separating columns using the Text to Columns tool solved the issue of multiple variables being in the same column, some of which were key to our visualizations. Since sometimes there were as many as three variables in one column, many of these newly created columns produced many null values, which thankfully was not an issue in creating our dashboards. Lastly, since we were not necessarily querying the data, we opted not to create separate sheets to separate all of the “primary keys,” and instead just rearranged the columns so that they could be easily identified and referenced if necessary. After making these arrangements, we found that no other manipulations were necessary in order to create the appropriate visualizations to answer our research questions; however, if this data were to be used to answer certain other questions, or if it were to be queried, the dataset would have to be manipulated further. The fully manipulated dataset can be found in this repository under “Drug Overdose Data Final.”


## Tableau Packaged Workbook
The packaged workbook containing the visualizations shown above is attached to this repository under “MIST 4610 Group 5 Project 2.”

## Sources

Recognizing Black and Latino-majority cities is the first step to finding a real world Wakanda - Brookings Research Organization (https://www.brookings.edu/articles/recognizing-black-and-latino-majority-cities-is-the-first-step-to-finding-a-real-world-wakanda/#:~:text=There%20is%20a%20value%20in,and%20Latino%20or%20Hispanic%20residents)

The History of Methadone and Barriers to Access for Different Populations - National Library of Medicine (https://www.ncbi.nlm.nih.gov/books/NBK585210/)

Trends in Methadone Distribution for Pain Treatment, Methadone Diversion, and Overdose Deaths — United States, 2002–2014 | MMWR - Center of Disease Control (https://www.cdc.gov/mmwr/volumes/65/wr/mm6526a2.htm?utm_source=chatgpt.com)

Opioid Drugs in Maintenance and Detoxification Treatment of Opiate Addiction - Federal Register (https://www.federalregister.gov/documents/2001/01/17/01-723/opioid-drugs-in-maintenance-and-detoxification-treatment-of-opiate-addiction#sectno-reference-8.3)

Methadone treatment: recent revision to regulation covering facilities - Legislative Analysis and Public Policy Association (https://legislativeanalysis.org/wp-content/uploads/2024/07/Methadone-Factsheet-FINAL.pdf)

THE OPIOID CRISIS AND THE HISPANIC/LATINO POPULATION: AN URGENT ISSUE - SAMHSA (https://library.samhsa.gov/sites/default/files/pep20-05-02-002.pdf)

Table 39. Aliens Removed or Returned: Fiscal Years 1892 to 2019 | OHSS - Office of Homeland Security (https://ohss.dhs.gov/topics/immigration/yearbook/2019/table39)
Demographics of multigenerational households - Pew Research Center (https://www.pewresearch.org/social-trends/2022/03/24/the-demographics-of-multigenerational-households/)

https://nida.nih.gov/news-events/news-releases/2023/06/men-died-of-overdose-at-2-3-times-greater-a-rate-than-women-in-the-us-in-2020-2021 - Analysis for Question 1

https://nida.nih.gov/publications/research-reports/substance-use-in-women/sex-differences-in-substance-use - Analysis for Question 1
