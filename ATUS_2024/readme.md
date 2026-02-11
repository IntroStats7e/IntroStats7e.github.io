# ATUS 2024

The American Time Use Survey (ATUS) is an annual survey of Americans over the age of 15 conducted by the Bureau of Labor Statistics (http://www.bls.gov) to better understand how Americans spend their time over the course of a 24 hour period. The most recent data available as of January 2026 is the 2024 survey data.   The variables reporting minutes spent on particular activities are based on a single diary day during which respondents recorded how they spent their time. Time spent on childcare is defined as time spent caring for children under 13.  

The data are in `ATUS_2024.txt`

The variables in this dataset are: 

Header | Description
---|--------
`RespondentID` | Respondent identifier 
`AgeYrs` | Age (years) 
`Sex` | Binary sex (male or female) 
`NumHHChildren` | Number of children who live in the respondent's household 
`LaborForceStatus` | Respondent's labor force status 
`EmployedFTPT` | If employed, whether the respondent is employed full-time or part-time 
`MultipleJobs` | If employed, whether the respondent works multiple jobs for pay 
`TotalHrsWorked` | If employed with regular hours, the total number of hours worked in a typical week 
`WorkHoursVary` | If employed, whether work hours vary week-to-week 
`Industry` | Industry category 
`Occupation` | Occupation category 
`EnrolledHSCollege` | Whether the respondent is enrolled in high school, enrolled in college, or neither 
`EnrolledFTPT` | If enrolled, whether the respondent is enrolled full time or part time 
`NonworkAloneMin` | Minutes spent alone and not at work during activity-recording day  
`ChildcareMin` | Total time spent caring for household and own non-household children under 13 during activity-recording day (minutes)
`EldercareMin` | Total time spent providing eldercare (minutes)  
`FamilyMin` | Total nonwork-related time respondent spent with family members (minutes)  
`FriendsMin` | Total nonwork-related time respondent spent with friends (minutes) 

This dataset is sourced from: https://www.niaaa.nih.gov/sites/default/files/pcyr1970-2022.txt
