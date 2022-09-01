# Course Syllabus

### Greetings

<img src="https://stat.illinois.edu/sites/default/files/styles/directory_profile/public/profile-photos/dje13.png.jpg?itok=j2rsX2F_" 
     width="150" 
     height="150"
     hspace="25"
     vspace="10"
     align = "left"
     /> I am **Daniel J. Eck** and I will be the instructor for STAT 430: Baseball Analytics. Baseball research is a primary interest of mine. I am interested in developing useful statistical methodology for performance evaluation and am interested in the statistical history of baseball. Several of the examples and reading materials in this course will come from projects that I have worked on or that I find interesting and useful. 

**Email**: dje13@illinois.edu

<BR CLEAR=”left” /> 
<BR CLEAR=”left” /> 

**Course time:** Wednesdays from 11 am to 1:50 pm

**Course location:** 140 Henry Admin Building

**Office hours**: Instructor office hours are on Thursdays, 10 - 11 am. 

**TA**: Shen Yan (shenyan3@illinois.edu). TA office hours are on Fridays, 10am - 12pm. 

**Course website**: https://github.com/stat430fa22/stat430materials

My course website is a GitHub repository. You can click  [here](https://github.com/stat430fa22/stat430materials) to access this website. Note that this Syllabus is a Markdown document. Open the .md file to view the basic Markdown syntax used to build your Syllabus.


***


### Course Materials

The course materials will largely consist of instructor notes, papers, articles, and software. The course will also use the textbook **[Analyzing Baseball Data with R](https://www.routledge.com/Analyzing-Baseball-Data-with-R-Second-Edition/Marchi-Albert-Baumer/p/book/9780815353515)** (second edition)

#### Papers, Articles, and Instructor Notes

Instructor notes will be posted and updated on GitHub. Relevant papers and articles will either be provided on GitHub or be referenced in course notes.



#### Software Used in the Course (all free)

- **R** https://cran.r-project.org/

- **RStudio** https://www.rstudio.com/products/rstudio/download/

- **RMarkdown** (packaged within RStudio) https://rmarkdown.rstudio.com/lesson-1.html  

- **GitHub** https://web.uillinois.edu/github
  - Details: see setup.md. 

***

### Course Information

This is a reading, seminar, and project based course on the intersection of baseball and statistics. In this course you will learn how to conduct relevant data analyses with a focus on how to quantify aspects of baseball play associated with winning games. You will also learn about the statistical history of baseball with an emphasis on comparing players across eras. Founding principles as well as advanced statistical methods for both directions will be discussed. The analyses that you conduct will also develop your critical thinking skills as a statistician. Furthermore, practical advantages, limitations, and comparisons of methods will be discussed. If you are interested in quantifying how good Mike Trout is or in ranking the careers of Barry Bonds, Willie Mays, and Babe Ruth, then this is the course for you.  

**Prerequisites**: STAT 385 or equivalent experience with R, STAT 425 or equivalent experience.  Familiarity with Git and GitHub is helpful, but not required.




### Student Learning Outcomes

Upon successful completion of this course students will be able to conduct methodologically strong data analyses that can answer questions of scientific interest, specifically the students will: 
 
  - Analyze and investigate databases of baseball statistics 
  
  - Utilize and understand procedures for quantifying success in baseball
  
  - Develop a solid practical understanding of procedures which compare players across eras
  
  - Develop data processing and visualization skills
  
  - Critique estimation procedures and modeling development strategies
  
  - Apply version control software and develop reproducible technical reports


### Getting Help in STAT 430

You have many options to get help for this class:

 * Canvas- you can post questions in the discussion forum.

 * Email me at dje13@illinois.edu from your Illinois email account (@illinois.edu). I will not respond to a non-Illinois email account. Be specific with the topic of your question in the subject line.

 * Office hours - you can go to my office hours as described above.
 
 ***

### Grading Breakdown

| category | notes | points
| :-- | :---- | :---- |
| Attendance | 10 points each course; two free misses  | 130 points
| Labs | 100 points each | 500 points
| Final Project | 50 points for approved project; 70 points for presentation (recorded summary); 250 for project materials and writeup | 370 points
| total | | 1000 points


I will be using a +/- grading schema. The grade distributions will be: 

| Lower bound | Upper bound | Letter grade |
| :--- | :--- | :--- |
| 980 | 1000 | A+ |
| 933 | 979 | A |
| 900 | 932 | A- |
| 867 | 899 | B+ |
| 833 | 866 | B |
| 800 | 832 | B-|
| and so on | | |


#### Attendance and Course Content

Attendance will be a course requirement. There will be 15 lectures and you will receive 10 points for each lecture you attend, up to 130 points. Thus you are allowed to miss up to 2 lectures with no penalty.  There will be a signup sheet that is distributed at the beginning of class, you need to sign your name to verify your presence in class. Let your instructor know in advance if you cannot attend any class. 


#### Labs

There are 5 labs total. When completing the assignment, read it carefully, and follow the directions. These labs can be completed in groups of 2-3 students. Every group member will submit their own lab report. Make sure to list your collaborators in your lab report.

For each lab assignment, you will submit two files - .Rmd and .html (or .pdf) - saving your files with your name and lab assignment number. **The lab naming convention is netid_lab#**.  For a student with netid *abc123* that is submitting lab4 files, their files would be saved as *abc123_lab4.Rmd* and *abc123_lab4.html* (or *abc123_lab4.pdf*). **Failure to adopt this lab naming convention will result in point deductions and headaches.**  Make sure your lab is professional and reproducible containing only relevant derivations, code, results, and explanations. **Questions about the grading should be directed to the TA**.


Labs should be stored in a lab# directory in your GitHub repo that is a sub directory of a labs directory in your GitHub repo. For example, your fourth homework assignment should be saved in the directory 

```
labs/lab4/
```

within your personal GitHub repo.  Failure to do this will result in point deductions.

**Late lab submissions will be accepted with a penalty.** There will be a 20 point deduction if a lab is submitted 48 hours after the deadline. Labs submitted later than 48 hours after the deadline will not be considered.

**Students must use GitHub to start, finish, and submit their labs. More details will be discussed in class.**

Labs will be worth 100 points unless otherwise noted.


#### Project

This course will have a final project instead of an exam. This will be a group project comprised of 2-3 students. Final projects for this course will be fairly open-ended and not subject to a one-size-fits all standard. That being said, all projects need instructor approval. 

Details and project rubrics are TBD.

Possible projects include: 

  - Writing a report on an interesting player. This can a player past or present, and the reason that said player is interesting can vary from being successful in a newly understood analytic, possessing great underlying metrics which should translate to future great performances, or a HOF argument for a controversial candidate who you think has a misunderstood case.
  
  - Estimate the value of different players (possibly hypothetical players).  For example, who is more valuable: a pitcher who pitchers 200 innings with a 4.75 ERA or a pitcher who pitches 125 innings with a 3.50 ERA?
  
  - Examine interesting batter-pitcher matchups concerning one particular player or a few players.
  
  - Estimate marginal handedness-stadium specific spray chart distributions.

  - Development of a new performance metric, or a combination of metrics, which you can argue is valuable. Examples include expected "x" stats based on Statcast data.
  
  - Development of a player or team projection system, or a comparison of projection systems.
  
  - Creation of an era-adjusted JAWS-type statistic to rank players' careers.
  
  - Era-adjusting statistics that do not yet exist on the current version of the Era-Adjustment App. Examples include: SB/CS, WHIP and its inputs, and SLG and its inputs.
  
  - An investigation into the existence of *clutch* which includes matchup information.
  
  - Creating a Shiny app that does something interesting.
  
  - Develop a "causal" WAR stat computes the difference in team winning percentage when a player is available vs when the player is not available.
  
  - Something else!


#### Exams

There will be no exams!


***



### Schedule (subject to change)

* Week 1 [08/24]
  + First day of class on 08/24. We will discuss the course overview, syllabus, and Git/GitHub
  + **Reading**: course slides and setup.md
  + **Reading**: CH 1 and 2 in Analyzing Baseball Data with R (data sets and data wrangling)
  + **Lab 1** assigned this week, due on 09/09 at 11:59 pm

* Week 2 [08/31]
  + **Reading**: course slides
  + **Reading**: CH 1 and 2 in Analyzing Baseball Data with R (data sets and data wrangling)
  + **Reading**: [A Statistical Look at Roger Clemens’ Pitching Career](https://repository.upenn.edu/cgi/viewcontent.cgi?article=1044&context=statistics_papers)
  
* Week 3 [09/07]
  + **Reading**: CH 3 in Analyzing Baseball Data with R (common visualization)
  + **Lab** 1 due on 09/09 at 11:59 pm
  + **Lab 2** assigned this week, due on 09/23 at 11:59 pm
  + **Speaker 1**: Jim Albert's talk 11:10-12:10 via Zoom 

* Week 4 [09/14]
  + **Reading**: course slides
  + **Reading**: CH 4: The Relation Between Runs and Wins in Analyzing Baseball Data with R
  + **Speaker**: Ed Kaplan's talk on "Decomposing Pythagorous" 12-1 via Zoom 

* Week 5 [09/21]
  + **Reading**: course slides
  + **Reading**: CH 5: Value of Plays Using Run Expectancy in Analyzing Baseball Data with R
  + **Lab 2** due on 09/23 at 11:59 pm
  + **Lab 3** assigned this week, due on 10/07 at 11:59 pm

* Week 6 [09/28]
  + **Reading**: course slides
  + **Reading**: CH 9: Simulation in Analyzing Baseball Data with R 
  
* Week 7 [10/05]
  + **Lab 3** due on 10/07 at 11:59 pm
  + **Lab 4** assigned this week, due on 10/28 at 11:59 pm
  + **Speaker**: David Dalpiaz
  
* Week 8 [10/12]
  + **Reading**: course slides
  + **Reading**: CH 12: Batted Ball Data from Statcast in Analyzing Baseball Data with R

* Week 9 [10/19]  
  + **Reading**: course slides
  + **Reading**: CH 12: Batted Ball Data from Statcast in Analyzing Baseball Data with R
  + **Speaker**: Ehsan Bohkari's talk 1-2 in person.
  
* Week 10 [10/26]
  + **Reading**: Introduction to R Shiny 
  + **Lab 4** due on 10/07 at 11:59 pm
  + **Lab 5** assigned this week, due on 11/11 at 11:59 pm

* Week 11 [11/02]
  + **Reading**: Introduction to R Shiny
  + **Speaker**: Alan M. Nathan

* Week 12 [11/09]
  + **Reading**: course slides
  + **Reading**: SEAM Method
  + **Reading**: [Enhancing strategic defensive positioning and performance in the outfield](https://link.springer.com/article/10.1007/s10109-021-00367-1)
  + **Speaker**: possible Shane Jensen
  + **Lab 5** due on 11/11 at 11:59 pm  
  + Project proposal assigned this week, due on 11/18 at 11:59 pm

* Week 13 [11/16]
  + **Reading**: course slides
  + **Reading**: CH 8: Career Trajectories in Analyzing Baseball Data with R
  + **Reading**: Introduction to comparing players across eras  
  + Project proposal due on 11/18 at 11:59 pm
  
* Week 14 [11/23]
  + **Fall Break**

* Week 15 [11/30]
  + **Reading**: course slides
  + **Reading**: The Full House Model  

* Week 16 [12/07]
  + Open house for project discussions
  + **Speaker**: Adrian Burgos Jr.  
  + Last day of instruction on 12/09


* Projects due on 12/18 at 11:59 pm.


