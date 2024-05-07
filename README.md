
# PLOTTING THE PLOT TWISTS: MAPPING SCHOOL DISTRICT BOOKBANS FROM 2021-2024

## Introduction

  Poets Essayists and Novelists an advocacy group for the freedom speech and expression published an index of School Book Bans in America from 2021 to 2023. The report recorded 5,894 instances of book bans across 41 states and 247 school districts (ADD FOOTNOTE).  From 2021 to 2022 the country has seen an astronomical increase in the number of challenged books, from 223 in 2020 to 2,571 unique titles challenged in 2022. This is quite possible 

  Although PEN’s Index and report of book bans and challenges contains **some**
information about bans in the states, there is very little geospatial analysis over trends. My goal with this report is to perform an exploratory analysis of the PEN book ban dataset along with another more recent dataset from **EveryLibrary** another popular advocacy group. My analysis aims to explore trends in the data in terms of distribution of bans over location and time axis, in addition to exploring other socioeconomic factors that may be correlated with book bans.

## What is a School Book Ban?:

---

**School Book Ban Definition:** 

> “any action taken against a book based on its content and as a result of parent or community challenges, administrative decisions, or in response to direct or threatened action by lawmakers or other governmental officials, that leads to a previously accessible book being either completely removed from availability to students, or where access to a book is **restricted** or **diminished**. **Diminished access is a form of censorship and has educational implications that extend beyond a title’s removal**” - PEN Report https://pen.org/report/banned-in-the-usa-state-laws-supercharge-book-suppression-in-schools/
> 

**Book bans variants (non exhaustive list) :** 

- Prohibitions on books in libraries or Classrooms.
- Requiring parental permission.
- Restricted to a higher grade.
- Removed from review but pending on return (timeline can be undetermined).
- Moved to a different section in the library.

**Banning  just a single title can have a large impact:**

Banning one title in one District can mean that Hundreds of that title are pulled from libraries and classrooms in that district

**Who can ban a book?:** A ban occurs when school boards, administrators, teachers or politicians override the book choices of librarians and educators that create curriculums.

**Banning  just a single title can have a large impact:**

Banning one title in one District can mean that Hundreds of that title are pulled from libraries and classrooms in that district

**Who can ban a book?:** A ban occurs when school boards, administrators, teachers or politicians override the book choices of librarians and educators that create curriculums.

## Methods and Results 
 to be posted soon once review is done 

## The Repository 

For this exporatory analysis I used two different datasources and cleaned them: 
1. PEN Index of banned books datasets 2021-22 and 2022-23.
2. Dr. Magnusson's Dataset of banned books from the EveryLibrary advocacy group.

The respective folders **PEN** and **Magnusson** contain the data scripts and cleaned data used for the analysis in the report and the maps. 


---

Data Sources Table 

| Data Source Name | Source authors | Data Source Link | Data format (Polygon, Vector, Point) | Description |
| --- | --- | --- | --- | --- |
| 2023 Censorship Attacks Book Bans In America | Dr. Tasslyn Magnusson | https://docs.google.com/spreadsheets/d/1am1vKU3MR1209AanJVqySFtRYe3IiB1k/edit#gid=2126860040 | XLSM table | A larger less-structured report of book bans from 2021-2024.   |
| PEN Index of Banned Books Dataset 2022-23 | PEN | https://docs.google.com/spreadsheets/d/1a6v7R7pidO7TIwRZTIh9T6c0--QNNVufcUUrDcz2GJM/edit#gid=982757372 |  | Semi large structured data report of book bans in the U.S. from 2022 to 2023.  |
| PEN Index of Banned books Dataset 2021-22 | PEN  | https://docs.google.com/spreadsheets/d/1hTs_PB7KuTMBtNMESFEGuK-0abzhNxVv4tgpI5-iKe8/edit#gid=1171606318 | google spreadsheet, .xlsm file | Semi large structured data report of book bans in the U.S. from 2021 to 2022. |
| School Counties List for Florida | US census | sdlist.xlsm | XLSM table | A list of all school counties and FIP, information for the State of Florida. |
| Florida School Districts | US Census | https://docs.google.com/document/d/1upZfCIZZ4XDm52jHbqvEVB9q5kFeNrAMoE-Bs9FN-Hg/edit | .SHP File | Shape file for Florida’s school districts.  |
| Financial Demographics for Medium Income | US Census ACS | https://data.census.gov/table/ACSST1Y2022.S2503?q=acs%20income&g=010XX00US$0400000 | .xlsm file | To join with state information for bivariate map. |
| SAIPE (Small Area Income and Poverty Estimates) Projection for 2022 | US Census SAIPE | https://www.census.gov/data/datasets/2022/demo/saipe/2022-school-districts.html | .xlsm file  | Provides the total population of students in a given county and the total living in poverty in that county, used to get percentage portion of students in poverty ages 5-17.  |
