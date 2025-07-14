
# Mental Health Analysis of Students

<h3>Description</h3>
This powerBi project analyzes a dataset of students' mental health, focusing on depression, anxiety, and panic attacks. The dataset consists of 10 columns, and 3 additional measures were created to gain deeper insights.<br>
This project is a 3 page dashboard which are grouped in pages(depression, panic attack, and anxiety).


<h3>Objectives</h3>
The objectives of this PowerBi project is to examine the mental health status of students. This PowerBi project aims at addressing questions like;<br>

1. Are students experiencing mental health breakdown? If they are, what are the causes of this? Could it be age? Does it mean that the older students expereince these mental health issues or the younger students do?<br>
2. Could it be caused by thier courses? Are some courses responsible for this?<br>
3. Could it be their CGPA(curriculum grade performance assessment). Are these mental health issues related to some CGPA?<br>
4. Could it be Year of study? Does it mean that some certain level of courses are responsible for the mental health issues?<br>
5. Could it be marital status? Are married students experiencing more of these problems or the unmarried ones?<br>
6. Could it be based on their gender? Are females experiencing mental health breakdown than the males or are the males experiencing more mental health breakdown than the females?<br>
7. Lastly, are students who are experiencing these mental health issues visiting specilaists or not?<br>


<h3>Tools Used</h3>
For this project, I leveraged on a powerful tool in data analytics to guide my analysis: <br>

**Powerquery**: I used powerquery for data transformation, cleaning and manipulation. <br>
**PowerBi**: I used this tool for data visualization. This tool makes it easy to cretae clear, informative, and visually compelling representation of data. <br>

<h3>Features</h3> (I will get back to this later) <br> 
1. Interactive Data Visualization: Visualize sales data through dynamic charts and graphs.<br>
2.Filter and Search: Easily filter data by date, product category, region, and more.<br>
3.Sales Trends: Analyze sales trends over time to make informed decisions.<br>
4.Customer Insights: Gain insights into customer behavior and demographics.<br>
5.Product Performance: Evaluate the performance of different product categories.<br>
6.Export Data: Download selected data for further analysis.


<h3>The Analysis and Insights for Depression</h3><br>

**1. What is the Total Number of Students?** <br>
This is an important KPI in this analysis and in getting the total number of students, I did a count of marital status column. This is because the dataset did not have a unique column. I believe that by counting the marital status column, I will get the total number of students which I did.

**2. The count of Students with Depression by Marital Status.** <br>
This analysis shows the counts of student experiencing depression, grouped by their marital status. In getting the count of depression by marital status, I did a count of depression by marital status. I put marital status on the Y axis and depression count on the X asxis.<br>
For the depression count,  NO rate is higher than the YES rate. This means that, a larger percentage of students are not experiencing depression. With the NO rate I discovered that students who are not experiencing depression are the unmarried students, while for those who are experiencing depression, the unmarried students are higher than the married ones.<br> Therefore, marital is not responsible for the depression of students.

**3. Students with Depression by CGPA**
This report tries to show the depression rate by CGPA. I did a count of depression by CGPA.I put depression on the Y axis, while CPGA is on the X axis. There are different ranges of CGPA in the dataset which are 0 - 1.99, 2.00 - 2.49, 2.50 - 2.99, 3.00 - 3.449, 3.50 - 4.00. Students in the CGPA range of 0 - 2.49 were not expereincing depression at all. The depression rate started from 2.50 - 4.00. It got to its peak in 3.00 - 3.49.<br>
The insights I got from this is that students whose CGPA are high are experiencing depression but students in the CGPA range of 3.00 - 3.49 are experiencing more depression followed by those in the range of 3.50 - 4.00.

**4 Students with Depression by Age.**
This report shows the count of students experiencing depression, grouped by their age. I calculated the count of depression by age. I put age on the X axis, while I put the count of depression on te Y axis.<br>
The age range if from 18 to 24. Students who are 18 and 19 are experiencing more depression. The depression rate from 20 to 22 years is balanced. From age  23 to 24, the depression rate is high. 

**5 Students with Depression by Course**
There are over 20 courses in the dataset. The insights gotten from this is that Engineering and BCS() has more depression rate comparared to other courses like Mathematics, Law etc.<br>
This means that students who are in Engineering and BCS department are experiencing higher depression rate compared to other courses.

**6 Stduents with Depression by Specialist Visits**
Students who are not experiencing depression are not visiting a specialist. This is understandable because since they are not experiencing depression, there is no need for them to visit specialists.<br>
From the depression count, those who have no depression did not visit specialists but for those who are experiencing depression, only a few of them visited specialists while a larger percentage of them did not visit any specialist. 



**3. The rate of panic attack by specialists consultation.** <br>
This report calculates the rate of panic attacks among students, categorized by their specialist visits. I calculated the count of panic attacks by specialist consultation.<br> From the depression count, those who have no depression did not visit specialists but for those who are experiencing depression, only a few of them visited specialists while a larger percentage of them did not visit any specialist. 


**5. Count of depression by age.** <br>
This report shows the count of students experiencing depression, grouped by their age. I calculated the count of deprssion by age. I put age on the X axis, while I put the count of depression on te Y axis.<br>

**6. Count of anxiety by course.** <br>
This analysis provides the count of students experiencing anxiety, grouped by their course. I calculated the count of anxiety by course. I put the count of anxiety on the X axis, and put course on Y axis.<br>

**7. Count of anxiety by current year.** <br>
This report displays the count of students experiencing anxiety, grouped by the current year.


<h3>Summary of finding</h3>
  - The insights drawn from this analysis is that students who are unmarried are battling with depression more than students that are maried. 16 married students are depressed while 85 unmarried students are depressed. From this insight, we can see that depression among students is not caused by married as just few married students are depressed.<br>
<br> 
- From this analysis we can deduce that the panic attack rate amongst students varies by age. Students between the ages of 20-22 have lower panic attack. Students that are 18 years of age have the highest panic attack, followed <br> by students 
