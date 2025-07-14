
# Mental Health Analysis of Students

<h3>DESCRIPTION</h3>
This PowerBi project analyzes a dataset of students' mental health, focusing on depression, anxiety, and panic attacks. The dataset consists of 10 columns, and 3 additional measures were created to gain deeper insights.<br>
This project is a 3 page dashboard which are grouped in pages(depression, panic attack, and anxiety).


<h3>OBJECTIVES</h3>

The objectives of this PowerBi project is to examine the mental health status of students. This PowerBi project aims at addressing questions like:<br>

**1.** Are students experiencing mental health breakdown? If they are, what are the causes of this? Could it be age? Does it mean that the older students expereince these mental health issues or the younger students do?<br>
**2.** Could it be caused by thier courses? Are some courses responsible for this?<br>
**3.** Could it be their CGPA(curriculum grade performance assessment). Are these mental health issues related to some CGPA?<br>
**4.** Could it be Year of study? Does it mean that some certain level of courses are responsible for the mental health issues?<br>
**5.** Could it be marital status? Are married students experiencing more of these problems or the unmarried ones?<br>
**6.** Could it be based on their gender? Are females experiencing mental health breakdown than the males or are the males experiencing more mental health breakdown than the females?<br>
**7.*8 Lastly, are students who are experiencing these mental health issues visiting specilaists or not?<br>


<h3>TOOLS USED</h3>

For this project, I leveraged on a powerful tools in data analytics to guide my analysis: <br>

**Powerquery**: I used powerquery for data transformation, cleaning and manipulation. <br>
**PowerBi**: I used this tool for data visualization. This tool makes it easy to cretae clear, informative, and visually compelling representation of data. <br>

<h3>FEATURES</h3> (I will get back to this later) <br> 

**1.** Interactive Data Visualization: Visualize sales data through dynamic charts and graphs.<br>
**2.** Filter and Search: Easily filter data by date, product category, region, and more.<br>
**3.** Sales Trends: Analyze sales trends over time to make informed decisions.<br>
**4.** Customer Insights: Gain insights into customer behavior and demographics.<br>
**5.** Product Performance: Evaluate the performance of different product categories.<br>
**6.** Export Data: Download selected data for further analysis.


<h3>ANALYSIS AND INSIGHTS FOR DEPRESSION</h3><br>

There are larger percentage of students who are not experiencing depression and a lower percentage of students who are experiencing depression. The YES rate is 65.34%, while the NO rate is 34.65%<br>


**1. What is the Total Number of Students?** <br>
This is an important KPI in this analysis and in getting the total number of students, I did a count of marital status column. This is because the dataset did not have a unique column. I believe that by counting the marital status column, I will get the total number of students which I did.

**2. The count of Students with Depression by Marital Status.** <br>
This analysis shows the counts of student experiencing depression, grouped by their marital status. In getting the count of depression by marital status, I did a count of depression by marital status. I put marital status on the Y axis and depression count on the X asxis.<br>
For the depression count,  NO rate is higher than the YES rate. This means that, a larger percentage of students are not experiencing depression. With the NO rate I discovered that students who are not experiencing depression are the unmarried students, while for those who are experiencing depression, the unmarried students are higher than the married ones.<br> Therefore, marital is not responsible for the depression of students.

**3. Students with Depression by CGPA**<br>
This report tries to show the depression rate by CGPA. I did a count of depression by CGPA.I put depression on the Y axis, while CPGA is on the X axis. There are different ranges of CGPA in the dataset which are 0 - 1.99, 2.00 - 2.49, 2.50 - 2.99, 3.00 - 3.449, 3.50 - 4.00. Students in the CGPA range of 0 - 2.49 were not expereincing depression at all. The depression rate started from 2.50 - 4.00. It got to its peak in 3.00 - 3.49.<br>
The insights I got from this is that students whose CGPA are high are experiencing depression. Students in the CGPA range of 3.00 - 3.49 are experiencing more depression followed by those in the range of 3.50 - 4.00.

**4. Students with Depression by Age.**<br>
This report shows the count of students experiencing depression, grouped by their age. I calculated the count of depression by age. I put age on the X axis, while I put the count of depression on te Y axis.<br>
The age range if from 18 to 24. Students who are 18 and 19 are experiencing more depression. The depression rate from 20 to 22 years is balanced. From age  23 to 24, the depression rate is high. 

**5. Students with Depression by Course**<br>
There are over 20 courses in the dataset. The insights gotten from this is that Engineering and BCS() has more depression rate comparared to other courses like Mathematics, Law etc.<br>
This means that students who are in Engineering and BCS department are experiencing higher depression rate compared to other courses.

**6. Stduents with Depression by Specialist Visits**<br>
Students who are not experiencing depression are not visiting a specialist. This is understandable because since they are not experiencing depression, there is no need for them to visit specialists.<br>
From the depression count, those who have no depression did not visit specialists but for those who are experiencing depression, only a few of them visited specialists while a larger percentage of them did not visit any specialist. 

<h3>ANALYSIS AND INSIGHTS FOR PANIC ATTACK</h3><br>

There are larger percentage of students who are not experiencing panic attack and a lower percentage of students who are experiencing panic attack<br>


**1. Students with Panic Attack by Marital Status**<br>
From this analysis, I can deduce that those who do not have panic attack are mostly unmarried students as well as married students but the unmarried students are way more than the married students. Those who have panic attack are mostly the unmarried students and the married students but the unmarried students are more than the married students. In summary, marriage is not responsible for the panic attack in students.

**2. Students  with Panic Attack by CGPA**<br>
This report shows that students whose CGPA are in the range of 0 - 2.99 have lower panic attack rate. The panic attack is between the range of 3.00 - 4.00. This means that students whose CGPA are between 3.00 - 4.00 are experiencing panic attack.

**3. Students with Panic Attack by Age**<br>
Students who are 18 and 19 are experiencing panic attack. Students who are in the age range of 20 - 22 have lower panic attack rate. Students who are in the age range of 23 and 24 has the highest panic attack rate. The insights gotten from this is that the younger students are experiencing panic attack for some reason like year of study, course etc. This is because many of them are knew to the system so they are yet to adjust.

**4. Students with Panic Attack by Course**<br>
From this analysis, there are many courses in the dataset but it was filtered to the top 8 courses. BCS, Engineering, KOE, and BIT are the top 4 courses with high panic attack rate. Other courses have panic attack count but those top 4 are the leading. From this insight, we can see that students who are offering BCS, Engineering, KOE, and BIT are expeririencing panic attack.

**5. Students with Panic Attack by Current Year of Study**<br>
Students who are in year 1 and year 3 have the highest panic attack count followed by year 2. Students in year 4 has the lowest panic attack count which is 1. The insight driven from this is that, students in year 1 have panic attack but in year 2, it reduces a bit. In year 3, it goes high but gets better in year 4.

**6. Students with Panic Attack by Specialist Visits**<br>
For students who admitted that they did not have panic attack, a larger percentage of them did not visit a specialist, while a smaller percentage of them visited a specialist. For those who admitted to having panic attack, a larger percentage of them did not visit a specialist for help while a smaller percentage seeked for help.<br>


<h3>ANALYSIS AND INSIGHTS FOR ANXIETY</h3><br>

There are larger percentage of students who are not experiencing anxiety and a lower percentage of students who are experiencing anxiety<br>


**1. Students with Anxiety by Marital Status**<br>
For students who are not experiencing anxiety, a larger portion of them are unmarried while the rest are married. For students who are experiencing anxiety, a larger portion of them are unmarried while the rest are married. The insights drawn from this is that marriage is not entirely responsible for anxiety.

**2.Students with Anxiety by CGPA**<br>
Students with CGPA that ranges from 0 - 2.99 are not really experiencing anxiety. Only one student is experiencing anxiety in this CGPA range. However, students with CGPA that ranges from 3.00 to 4.00 are experiencing panic attack. Insights gotten from this is that the higher the CGPA, the higher the panic attack and the lower the CGPA, the lower panic attack.

**3. Count of anxiety by course.** <br>
This analysis provides the count of students experiencing anxiety, grouped by their course. The courses were filtered by the top 8 courses. BCS, Engineering, KOE and BIT are the leading course. This means that students who are offering these courses have higher panic attack count.

**4. Count of anxiety by current year.** <br>
This report displays the count of students experiencing anxiety, grouped by the current year. Students who are in year 1, 2 and 3 are experiencing more panic attack. Students in year 4 has only 25% percent rate of panic attack compare to year 1, 2 and 3 which are 32.56, 38.46 and 33.33% respectively.

**5 Students with Anxiety by Age**<br>
Students in the age range of 20 to 22 have lower count of panic attack, while students who are 18 years have the highest count of panic attack, followed by 24, 19 and 21.

**6 Students with Anxiety by Specialist Visits**<br>
For students who do not have anxiety, a larger count of them did not visit a specialist while a smaller percentage visited a specialist. For students who have anxiety, a larger count of them did not visit a specialist while only small portion of them seeked for help.

<h3>RECOMMENDATIONS</h3><BR>

**1.** Before the analysis, one would think marriage will be responsible for depression because of the sacrifices that comes with it. However, unmarried students experienced depression more than the married students. For the 16 married students who are experiencing depression.... For year of study, year 1,2 and 3 are experiencing depression. The school should adopt measures to ease stress and help students who are experiencing depresion<br>

**2.** For courses, overall we can see from the insights that students who are offering the following courses: Engineering, BCS, BIT, and KOE are having mental health issues. The school should revise the course curriculums. Most times, the curriculums are usually rigid and this makes it a bit difficult for students. Also, Lecturers should adopt more friendly manner of teaching and patience.<br>
The school should encourage library use and stock up the libraries with relevant materials to aid easy learning.
In addition to this, the marking scheme of these courses should be reviewed. Most times, the marking schemes may be too rigid and this makes students work too hard to meet up while some do not meet up eventually.

**3.** Overall, students who are having mental health issues are not seeking help. This can be out of fear or an act of not seeing the need to seek help. Many students may not know how serious mental health should be taken. Students should be encouraged to seek help from specialists. They should be educated on the need to priotize mental health and seek help when needed.

**4.** Students who are 18 and 19 years of age are experiencing mental health issues. Most of them are in year 1 and 2 and they are new to the system. Some of them come with the fear of "University is tough". They put so much pressure on themselves and this can affect ones mental health. Students who are 23 and 24 are experiencing mental health as well. Most of them are in year 3. From our analysis, we can see that students in year 3 are having mental issues

**5.** Students who are in year 1, 2 and 3 experience mental health issues. The year 1 and 2 experience it more because they are new in the system. They are yet to adapt to the Univeristy manner of study since they are coming from secondary school. Those in year 3 are having mental issues because they are close to finishing their programs. There are many courses to do and many expectaions. Some of them are not on a good CGPA so they want to do well this time to be able to meetup while some have good CGPA but needs to work harder to maintain it before getting to year 4. In year 4, the count of students experiencing mental issues is very low. This is necause, in year 4, they have few courses to do so they can have enough timt to write their projects. Also, the courses in year 4 are not usually tough.

**6.** CGPA

  - The insights drawn from this analysis is that students who are unmarried are battling with depression more than students that are married. 16 married students are depressed while 85 unmarried students are depressed. From this insight, we can see that depression among students is not caused by married as just few married students are depressed.<br>
<br> 
- From this analysis we can deduce that the panic attack rate amongst students varies by age. Students between the ages of 20-22 have lower panic attack. Students that are 18 years of age have the highest panic attack, followed <br> by students 
