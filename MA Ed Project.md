# Massachusetts Education Analysis

<img src="/images/MA Ed Cover.jpg?raw=true"/>

> “Education is the key to unlocking the world, a passport to freedom.” ― Oprah Winfrey

My 10-year high school reunion was in 2022. It's unbelievable to me that it's been so long, and I've been reflecting on my public school experience. I was very lucky to attend good schools throughout my life, and had a lot of priviledge in my educational experience. In a school district as large as JCPS in Louisville, KY, it can be difficult to understand differences in data across schools and understand what it means. 

In this project, I used Tableau to analyze and visualize data from another school district in Massachusetts from 2017. The task was to design a dashboard and answer the following for the superintendent: 
- Which schools are struggling the most? 
- How does class size affect college admission? 
- What are the top math schools in the state?

## The Data
This data comes from the **Massachusetts Department of Education** reports from 2017. You can find it [**here.**](https://www.kaggle.com/datasets/ndalziel/massachusetts-public-schools-data?select=MA_Public_Schools_datadict.csv) There are 1,861 rows in the dataset, and relevant columns include:
- class size
- graduation rates
- college attendance
- economic disadvantage
- math test scores for multiple grades

### Key Insights
1. The lowest-performing high schools have graduation rates **less than 20%**, though the state average is **83%.**
2. Class size and college attendance **do not** appear to be correlated. There is a negative correlation between **economic disadvantage and college attendance.**
3. Massachusetts appears to be preparing students for their state math exams well, with **about 75% of 4th graders receiving Proficient or Advanced scores.**

# Let's Zoom In

## Low-performing Schools
The Secretary of Education in this scenario is interested in which school struggle the most, as indicated by graduation rates. Let's take a look at what the data says. 

<img src="/images/Graduation Rate.jpg?raw=true"/>

Here we can see the ten schools with the lowest graduation rates, all with under 20% of students graduating. One school, Curtis-Tufts High School, was excluded from this chart - it is an alternative school that provides additional support for students with special needs. Students who attend Curtis-Tufts and are ready to graduate are transitioned to another school during the process, making the graduation rate 0% by design. 

Looking further into the schools on this list, we can see that many of them are alternative schools serving various student populations, likely considered "High Need" students. In this data, students fall into the High Need category if they are economically disadvantaged, English language learners, or are disabled requiring an Individualized Education Plan. 

<img src="/images/Low Grad vs High Need.jpg?raw=true"/>

The schools with the **lowest graduation rates** have **70%-100% high needs students.** This warrants additional investigation into the supports provided for students in these schools. 

## Class Size and College Attendance
A factor often considered when looking at higher education after high school graduation is class size. According to this MA data, there **does not** appear to be a correlation between the number of students in the classroom and the percentage of students attending college from those schools. 

<img src="/images/College Class Size.jpg?raw=true"/>

However, we can see a **negative** correlation between economic disadvange and college attendance - **schools with a higher percentage of economically disadvantaged schools see a lower percentage of their students attending college.**

There are several outliers in the data where 
