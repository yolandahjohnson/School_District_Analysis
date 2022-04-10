# School_District_Analysis

## Overview:

Within PyCity School District there are fifteen high schools. An initial analsyis was conducted of each schools performance in reading and math. This included the number and percentage of passing grades as well as funds allocated for each district. Upon review of the initial analysis, the school board identified evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. 

After replacing Thomas High School 9th grade math and reading scores with NaNs, a school district analysis was repeated to see how these changes affected the overall analysis.

## Results:

### How is the district summary affected?

#### Original District Summary
![Original District Summary](https://user-images.githubusercontent.com/100816778/162599456-f6bbe1bb-4865-4d47-88b4-f55f2b5d5b00.png)

#### Updated District Summary
![Updated District Summary](https://user-images.githubusercontent.com/100816778/162599465-86f7e7dc-a570-49b9-9746-a545f6ae8d08.png)

Removing Thomas High School 9th grade math and reading scores and replacing them with NaN had very little affect on the distrcit summary. The change was practically neglible and amounted to less than 1% change between the original and updated summary. The Thomas High School 9th grade math and reading grades make up a very small percentage of the overall grades within the district and any change would cause little affect.

### How is the school summary affected?

#### Original School Summary
![Original Top Schools](https://user-images.githubusercontent.com/100816778/162628533-fd51c977-9fef-484c-b375-2ca73dfb4763.png)

#### Updated School Summary
![Updated Top Schools](https://user-images.githubusercontent.com/100816778/162628537-fb658ad5-f0ef-4eed-ac0e-69f909128d4f.png)

The school summary was affected very little by removing the Thomas High School 9th grade math and reading scores. 
- The average math score went down by less than .07 points
- The percentage of passing math scors went down by less than .09%
- The average reading score went up less than .05 points
- The percentage of passing reading scores went down by less than .29%
- The overall percentage of passing went down by less than .32%

### How does replacing the ninth grader's math and reading scores affect Thomas High School's performance relative to the other schools?

Replacing Thomas High School 9th grade math and reading scores did not affect it's overall performance relative to the other schools. Thomas High School 9th graders account for approximately 1% of all the students in the district. Removing their grades would have very little impact on the district as a whole.

### How does replacing the ninth-grade scores affect the following:

#### Original Math Scores by Grade
![Original Math Scores by Grade](https://user-images.githubusercontent.com/100816778/162628277-307ed2bb-56f6-48b3-90f4-46a3a247f684.png)

#### Updated Math Scores by Grade
![Updated Math Scores by Grade](https://user-images.githubusercontent.com/100816778/162628271-12b91aec-aaed-4208-b925-c38f30da8003.png)

Replacing the 9th grade math scores did not affect the grades of any other school. I only replaced the Thomas High School 9th graders math grade with NaN.

#### Original Reading Scores by Grade
![Original Reading Scores by Grade](https://user-images.githubusercontent.com/100816778/162628253-b9f6e5b2-9cbe-4558-88e5-3868f16c7a58.png)

#### Updated Reading Scores by Grade
![Updated Reading Scores by Grade](https://user-images.githubusercontent.com/100816778/162628256-2438431e-510d-4c6e-9657-3e308c6970af.png)

Replacing the 9th grade reading scores did not affect the grades of any other school. I only replaced the Thomas High School 9th graders reading grade with NaN.

#### Original Scores by School Spending
![Original Spending Ranges](https://user-images.githubusercontent.com/100816778/162630967-d275ceb5-dee0-42a8-924a-e1ba8ca34a9d.png)

#### Updates Scores by School Spending
![Updated Spending Ranges](https://user-images.githubusercontent.com/100816778/162630976-e361ff6a-50f4-4570-b45e-f1368cb9fc52.png)

Again, replacing the 9th grade math and reading scores with Nan had very little affect. The grade averages and percentages changed very little and the school spending did not change.

#### Original Scores by School Size
![Original School Size Summary](https://user-images.githubusercontent.com/100816778/162628243-35d3b1c5-482f-45d6-8580-f4d5e11cd536.png)



#### Updated Scores by School Size
![Updated School Size Summary](https://user-images.githubusercontent.com/100816778/162628237-88e76e71-101b-4ce2-9b6c-ba7eba9ab0be.png)



#### Original Scores by School Type
![Original School Type Summary](https://user-images.githubusercontent.com/100816778/162628231-c9e7f7b2-9c23-4a36-9095-2d6e9f49ae0a.png)

#### Updated Scores by School Type
![Update School Type Summary](https://user-images.githubusercontent.com/100816778/162628193-47eaea84-6108-46d3-9980-a643be01d84f.png)

## Summary
