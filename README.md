# School_District_Analysis


## Overview

The purpose of this project was to analyze and organize data on 15 different schools. Statistics such
as average reading and math grades, budget data, cost per student, school type, and more were run through
using Pandas, and put into easy to read charts. After an initial analysis, it was found that the 9th grade
of Thomas High School (THS) had a cheating problem, and another analysis was done to account for this change. 
I have included the original summaries for both the school district as a whole, as well as the schools themselves,
to show any differences between the two.


## Charts
                                              1st District Summary
![before district sum](https://github.com/HexHaunter/School_District_Analysis/blob/main/Resources/beforeDistrict%20Summary.PNG?raw=true)
                                          
                                              Adjusted District Summary
![after District sum](https://github.com/HexHaunter/School_District_Analysis/blob/main/Resources/afterDistrictSummary.PNG?raw=true)
                                          
                                              1st School Summary
![before school sum](https://github.com/HexHaunter/School_District_Analysis/blob/main/Resources/beforeSchoolSummary.PNG?raw=true)
                                          
                                              Adjusted School Summary
![after school sum](https://github.com/HexHaunter/School_District_Analysis/blob/main/Resources/AfterSchoolSummary.PNG?raw=true)                                        
                                          
                                              By Grade Level
![by Grade](https://github.com/HexHaunter/School_District_Analysis/blob/main/Resources/Gradesummary.PNG?raw=true)
                                          
                                              By Spending Summary
![After Spending](https://github.com/HexHaunter/School_District_Analysis/blob/main/Resources/spending%20summary.PNG?raw=true)
                                                                                  
                                              By Size Summary
![After Size](https://github.com/HexHaunter/School_District_Analysis/blob/main/Resources/size%20summary.PNG?raw=true)                                          
                                          
                                              By Type Summary
![After type](https://github.com/HexHaunter/School_District_Analysis/blob/main/Resources/Type%20Summary.PNG?raw=true)

                                              Top Schools
![Top Schools](https://github.com/HexHaunter/School_District_Analysis/blob/main/Resources/TopSchools.PNG?raw=true)

                                              Bottom Schools
![Bottom Schools](https://github.com/HexHaunter/School_District_Analysis/blob/main/Resources/Bottom%20Schools.PNG?raw=true)


## Results
* By removing the data in the 9th grade of THS, the District Summary was slightly affected:
  * Average Math Score went from 79.0 to 78.9
  * Average Reading score stayed the same at 81.9
  * % Passing Math went from 75 to 74.8
  * % Passing Reading went from 86 to 85.7
  * % Overall Passing went from 65 to 64.9
* Since the data was dropped only from THS's 9th grade class, it did not impact the School Summary other than itself
* Since THS's 9th grade data was removed, it affected the by grade summary by becoming Not a Number (Nan).
* The change in the data from removing the 9th grade class from THS did not affect other metrics such as
  the summaries by spending, by size, by type, or even which schools were in the top 5 or bottom 5. There are 
  more charts in the [resources folder](https://github.com/HexHaunter/School_District_Analysis/tree/main/Resources) which
  show results from before the data was dropped, and after.

### Thomas High School
                                              Thomas High School Before Dropping Data
![ths before](https://github.com/HexHaunter/School_District_Analysis/blob/main/Resources/before_THS.PNG?raw=true)

                                              Thomas High School After Dropping Data
![ths after](https://github.com/HexHaunter/School_District_Analysis/blob/main/Resources/after_THS.PNG?raw=true)


## Summary
