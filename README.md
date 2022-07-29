# Pewlett-Hackard-Analysis

## Overview of the analysis: 
Pewlett-Hackard needs an analysis performed to determine the number of retiring employees per title, and to identify employees who are eligible to participate in a mentorship program in preparation for the "silver tsunami" as many employees are set to retire. 


## Results: 

### 1. Retirement Titles:

<img width="685" alt="retirement_titles" src="https://user-images.githubusercontent.com/106630710/181814043-141baabd-b15a-48be-ac3e-d2f2170ca15a.png"> <b/>

With this initial query it looks like 13,3776 people are eligible for retirement. However, this query does not specify current employees. This query is also inaccurate because it contains duplicate positions for employees who have been promoted. A more specific query needs to be performed. <b/>
<b/>

### 2. Unique Titles:
<img width="535" alt="unique_titles" src="https://user-images.githubusercontent.com/106630710/181814267-642c710b-bc57-4e72-add8-2f9e72035400.png"> <b/>

This query accurately represents how many employees are retiring: 72,458. Duplicate rows have been removed and contains only current employees.<b/>
<b/>

### 3. Retiring Titles:
<img width="240" alt="retiring_titles" src="https://user-images.githubusercontent.com/106630710/181814445-66538068-f434-4bec-9084-d517760c9d70.png"> <b/>

Most employees retiring hold the position of Senior Engineer, comparatively, only two Managers are retiring. <b/>
<b/>

### 4. Mentorship Eligibility:
<img width="731" alt="mentorship_eligibility" src="https://user-images.githubusercontent.com/106630710/181814939-72c94f03-0dd2-4ddd-9742-d940f84a8724.png"> <b/>

There are 1,549 current employees who are eligible for the mentorship program. <b/>
<b/>

## Summary: 

As the "silver tsunami" beings to make an impact, seven different roles will all need replacements of varying quantities. 
* 25,916 Senior Engineers
* 24,926 Senior Staff
* 9,285 Engineers
* 7,636 Staff
* 3,603 Technique Leaders
* 1,090 Assistant Engineers
* 2 Mangers

A total of 72,458 employees are set to retire while there are only 1,549 employees who are eligible for the mentorship program. There may be enough current employees who are set to retire that can mentor upcoming employees but there are not enough current employees who can fill all the vacancies. Pewlett-Hackard will need to hire most of these vacancies with new employees. 

Mentorship Eligibility by Title:
<b/>

<img width="240" alt="mentorship_eligibility_titiles" src="https://user-images.githubusercontent.com/106630710/181822605-869eead8-6a67-4c24-b4be-91f3b90f7506.png"> 
<b/>

Comparatively, there are significantly less mentorship eligible employees per title than there are employees ready for retirement.
* 312 Senior Engineers
* 405 Senior Staff
* 376 Engineers
* 319 Staff
*  77 Technique Leaders
*  60 Assistant Engineers
*   0 Mangers
