## Welcome  

Welcome to Eck Sports Lab, where cutting-edge statistics meet baseball history, culture, and creativity.  

At Eck Sports Lab, our mission is to research all things sports, with a current emphasis on baseball. We study topics ranging from player evaluation metrics to comparing baseball players across eras. What unites our work is a dedication to high-quality, innovative statistical and interdisciplinary research that are presented in ways that are accessible, engaging, and often entertaining.  

Our projects span rigorous methodology, applied analytics, and student-led creative initiatives, all working together to bring new perspectives to how we understand sports.  


## Current Projects 

### Comparing Baseball Players Across Eras

**Project page:** [Era Adjusted Baseball Stats v2.1](https://eckeraadjustment.web.illinois.edu/)  
**Full write‑up:** [Stats and Case Studies v2.1](https://eckeraadjustment.web.illinois.edu/era_adjusted_V2.1.html)

This is an ongoing project devoted to the development of statistical tools which can era-adjust performance metrics. The impetus for this project was the initial discovery that the current consensus of baseball ranking methods were biased towards the performances of pre-integration players. You can explore these origins in our [initial Shiny app on baseball nostalgia](https://deck13.shinyapps.io/challenging_baseball_nostalgia/?_ga=2.63424943.1066016428.1662040173-852280612.1656705949). We have since made an advance towards the creation of era-adjusted statistics with the development of what we call [Full House Modeling](https://projecteuclid.org/journals/annals-of-applied-statistics/volume-19/issue-2/Comparing-baseball-players-across-eras-via-novel-Full-House-Modeling/10.1214/24-AOAS1992.short). Full House Models era-adjust statistics through a principled balancing of how players performed "vs. their peers" and the quality of the talent pool of players' contemporaries. These models are a crystallization of conceptual logic articulated by Stephen Jay Gould, as explained in [this short video](https://www.youtube.com/watch?v=BNM6ait4LOc).

Here is a snapshot of our current results. Below is the top 10 list according to era-adjusted baseball reference wins above replacement (ebWAR) and era-adjusted fangraphs wins above replacement (efWAR):

rank | name | ebWAR | name | efWAR
| -- | ------- | ---- | ------ | ---- |
1  | Barry Bonds	| 154.71 | Barry Bonds	  | 145.57
2  | Willie Mays	| 145.30 | Roger Clemens  | 140.75
3  | Roger Clemens	| 144.38 | Willie Mays	  | 135.78
4  | Babe Ruth		| 138.64 | Henry Aaron	  | 127.96
5  | Henry Aaron	| 135.67 | Greg Maddux	  | 120.91
6  | Alex Rodriguez	| 120.64 | Babe Ruth	  | 120.6
7  | Stan Musial	| 119.37 | Stan Musial	  | 112.79
8  | Ty Cobb		| 115    | Alex Rodriguez | 110.52
9  | Greg Maddux	| 113.55 | Randy Johnson  | 109.78
10 | Albert Pujols	| 111.95 | Ty Cobb	  | 108.95

*The list above combines Babe Ruth's batting and pitching WAR*

This is Version 2.1 of the project. For earlier iterations and the development history, see our [project history on GitHub](https://github.com/ecklab/era-adjustment-app-supplement).


### SEAM method for Better Batted-Ball Prediction

**Web application landing page:** [SEAM: Synthetic Estimated Average Matchup](https://seam.stat.illinois.edu/)

We developed SEAM (synthetic estimated average matchup) methodology for describing batter versus pitcher matchups in baseball. The SEAM method provides confidence regions that reflect where baseballs that are put into play are expected to land. Our method is more accurate than similar methods constructed from individual batter spray charts or an individual pitcher's spray chart allowed. We estimate that the implementation of SEAM can yield an additional 40 outs over conventional spray charts throughout the course of an MLB season. Colin Alberts [Master's thesis](https://github.com/colalb1/SEAM-Fielder-Optimization) explores fielder placement optimization approaches that are downstream of SEAM.

Check out Julia Wapner's presentation of the SEAM method at the 2022 SABR Analytics Conference:

<a href="https://www.youtube.com/watch?v=I4k79lF7O1s&ab_channel=SABRvideos">
  <img src="images/SEAMtalk.png" alt="SEAM Talk" style="width:65%; height:auto;">
</a>


### Teaching Resources

Eck Sports Lab develops open-access materials that bridge foundational concepts in statistics with contemporary research problems in sports analytics. These resources are designed for instructors to integrate directly into their own courses and for students to explore methods through tangible, data-driven, and modern examples.

Teaching vignette pages:

- [**Binomial Distribution: Comparing Baseball Players Across Eras** (Introductory)](https://htmlpreview.github.io/?https://github.com/ecklab/ecklab.github.io/blob/main/binomial-distribution-example.html)
- [**Probability Integral Transformation, Order Statistics, and Full House Modeling** (Intermediate / Advanced)](https://cran.r-project.org/web/packages/Lahman/vignettes/FHM-primer.html)

#### Binomial Distribution: Comparing Baseball Players Across Eras (Introductory)

A teaching vignette that introduces the Binomial distribution using baseball data and connects introductory probability to real-world modeling with era-adjusted WAR. This resource includes reproducible R code, data from [baseball reference](https://www.baseball-reference.com/) and the [fullhouse](https://github.com/DEck13/fullhouse) R package, and visualizations illustrating how simple probability models can reveal systematic bias in historical rankings. 

#### Probability Integral Transformation, Order Statistics, and Full House Modeling (Intermediate / Advanced)

A teaching vignette that introduces the core ideas behind Full House Modeling (FHM) and its applications to era-adjusted WAR. This resource builds intuition for the probability integral transform and the distribution of order statistics, showing how these concepts form the mathematical foundation of FHM. It includes reproducible R code, visual examples, and data from the [Lahman](https://cran.radicaldevelop.com/web/packages/Lahman/index.html) R package. 


### Featured Student Content

At Eck Sports Lab, our students are creating innovative, public-facing projects that bring our research to wider audiences. From newsletters to YouTube channels to interactive games, here are some highlights:  

#### The Era Curveball

A Substack newsletter by **Idrees Muhammad Kudaimi** featuring player profiles through the lens of era-adjusted baseball statistics obtained via Full House Modeling. It blends rigorous analysis with sharp, entertaining commentary. **[Check it out](https://eracurveball.substack.com/)**

#### DataDugout YouTube Channel

A YouTube channel by **Christopher Ye** that covers baseball broadly, with a current focus on player profiles and storytelling powered by era-adjusted baseball statistics. **[Check it out](https://www.youtube.com/@datadagoat)**

#### 2v2 Baseball Death Match

An R Shiny–based retro arcade simulation video game by **Logan Blancett**, originally inspired by a STAT 430 group project led by Aidan Glickman. The game simulates 7-inning matchups where two teams of a batter and pitcher face off, with simulator logic using Statcast data and similarity scores derived from our SEAM project. Check it out (click game artwork below to go to game):

<a href="https://loganmblancett.shinyapps.io/BaseballDeathmatch/">
  <img src="images/2V2-Baseball-Deathmatch.jpeg" alt="SEAM Talk" style="width:60%; height:auto;">
</a>




## Recent News and Events

 - **10/07/25**: Logan Blancett released version 1.0.0 of [*2v2 Baseball Death Match*](https://loganmblancett.shinyapps.io/BaseballDeathmatch/), an R Shiny–based retro arcade simulation video game.
 - **10/06/25**: Idrees Muhammad Kudaimi launched [*The Era Curveball*](https://eracurveball.substack.com/), a substack newsletter featuring player profiles through the lens of era-adjusted baseball statistics.
 - **08/22/25** and **08/24/25**: Daniel J. Eck presented a talk titled "Full House Modeling: Rethinking Fairness, Extremes, and Historical Comparison in Statistics" at, respectively, EcoSta and Saberseminar.
 - **08/21/25**: Christopher Ye uploaded a [video essay](https://www.youtube.com/watch?v=HGljhonuYGs) on Willie Stargell's under appreciated power as told through the lens of era-adjusted statistics.
 - **08/12/25**: Our era‑adjusted baseball research was featured in [*New York Times Science*](https://www.nytimes.com/2025/08/12/science/baseball-statistics-babe-bonds.html)!
 - **07/08/25**: Christopher Ye uploaded a [video essay](https://www.youtube.com/watch?v=Rb1xX6kUO84) on an under-appreciated all-time great player through the lens of era-adjusted WAR.
 - **05/29/25**: Our paper ["Comparing baseball players across eras via novel Full House Modeling"](https://projecteuclid.org/journals/annals-of-applied-statistics/volume-19/issue-2/Comparing-baseball-players-across-eras-via-novel-Full-House-Modeling/10.1214/24-AOAS1992.short) has been published at *Annals of Applied Statistics*! A [preprint version](https://www.e-publications.org/ims/submission/AOAS/user/submissionFile/64774?confirm=94cf39e4) is also available. The interdisciplinary nature of this work was highlighted by the [UIUC Statistics Department](https://stat.illinois.edu/news/2025-06-02/illinois-researchers-publish-interdisciplinary-era-adjusting-baseball-study).
 - **05/27/25**: Foolish Baseball featured our era-adjusted WAR statistic in his tour de force [video on Hank Aaron's unparalleled consistency](https://www.youtube.com/watch?v=k_3aAw5iY4k).


## Historical Milestones

 - **08/12/25**: Our era‑adjusted baseball research was featured in [*New York Times Science*](https://www.nytimes.com/2025/08/12/science/baseball-statistics-babe-bonds.html) and was on the front page of the 08/13/25 print edition!
 - **03/13/23**: Our era-adjusted methodology and interdisciplinary collaboration was [featured](https://stat.illinois.edu/news/2023-03-13/statistics-and-story-baseballs-two-languages) by the College of Liberal Arts and Sciences at University of Illinois Urbana-Champaign.
 - The Eck Sports Lab is collaborating with the Chicago Cubs on a joint undergraduate research mentorship program.


## People 

<div style="display: flex; flex-direction: column;">

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/dje13.png" alt="Person 1" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://publish.illinois.edu/danieleck/">Daniel J. Eck</a> is a Statistics professor at the University of Illinois Urbana-Champaign. He is an active researcher in baseball analytics and has recently developed a topics course devoted to <a href = "https://stat.illinois.edu/news/2022-12-19/new-statistics-course-takes-swing-baseball-analytics">Baseball Analytics</a>.</p>
</div>

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/burgosjr.png" alt="Person 2" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://history.illinois.edu/directory/profile/burgosjr">Adrian Burgos Jr.</a> is a History professor at the University of Illinois Urbana-Champaign.  He has written numerous books and articles and has taught numerous classes devoted to baseball history. Recently, Adrian served on Hall of Fame Committees which enshrined Bud Fowler, Gil Hodges, Jim Kaat, Minnie Minoso, Tony Oliva, and Buck O’Neil.</p>
</div> 

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/shenyan.jpg" alt="Person 3" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;">
        <a href="https://www.linkedin.com/in/shen-yan-87a09812b/">Shen Yan</a> 
        is currently a postdoc with Professor Bo Li in the Department of Statistics at the University of Illinois Urbana-Champaign. 
        He successfully defended his PhD dissertation on 
        <a href="https://www.ideals.illinois.edu/items/131675">Full House Methodology</a>, 
        a framework for fair cross-era comparisons in baseball and beyond. Shen plays an active role in research and advising students.
    </p>
</div>
 
<div style="display: flex; margin-bottom: 20px;">
    <img src="images/ddalpiaz.png" alt="Person 4" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://daviddalpiaz.org/">David Dalpiaz</a> is a Computer Science professor at the University of Illinois Urbana-Champaign. He is an active researcher in baseball analytics.</p>
</div>
 
<div style="display: flex; margin-bottom: 20px;">
    <img src="images/chris_kinson.jpg" alt="Person 5" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://chriskinson.com/">Christopher Kinson</a> is a Statistics professor at the University of Illinois Urbana-Champaign. He is an active data science educator.</p>
</div> 

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/ryan_to.jpg" alt="Person 6" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;">
        <a href="https://www.linkedin.com/in/ryan-to-23aa79221/">Ryan To</a> 
        is a Computer Science student at the University of Illinois Urbana-Champaign. 
        He is working on a baseball game simulator with the Chicago Cubs, helps facilitate lab research projects, 
        and mentors student-led content creation initiatives within the lab.
    </p>
</div>

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/idrees_muhammad_kudaimi.jpg" alt="Person 7" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://www.linkedin.com/in/idrees-muhammad-kudaimi/">Idrees Muhammad Kudaimi</a> is a Chemistry student at the University of Illinois Urbana-Champaign. He is contributing to content development for the Full House Modeling project. He launched the Era Curveball Substack newsletter.</p>
</div> 

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/rohan_nakra.jpg" alt="Person 8" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://www.linkedin.com/in/rohan-nakra-95b91431a/">Rohan Nakra</a> is an Engineering student at the University of Illinois Urbana-Champaign. He is currently working to update the SEAM project with up-to-date batted ball distributions for specific batter-pitcher matchups.  </p>
</div> 

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/chistopher_ye.jpg" alt="Person 9" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://www.linkedin.com/in/christopher-ye-22517b343/">Christopher Ye</a> is a Statistics student at the University of Illinois Urbana-Champaign. He is contributing to content development for the Full House Modeling project. Check out his <a href = "https://www.youtube.com/results?search_query=datadugout">DataDugout</a> YouTube channel. </p>
</div> 

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/logan_blancett.jpg" alt="Person 10" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://www.linkedin.com/in/logan-blancett-754336253/">Logan Blancett</a> is a Statistics student at the University of Illinois Urbana-Champaign. He is developing a Shiny-based baseball simulation game, <i>2v2 Baseball Death Match</i>, and also mentors student-led content creation projects within the lab. </p>
</div> 

</div>


## Alumni Working in Baseball

<div style="display: flex; flex-direction: column;">

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/jack_banks.jpg" alt="Person 1" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://www.linkedin.com/in/jack-banks2/">Jack C. Banks</a> (2023) is currently working as a Performance Science Analyst for the <b>New York Yankees</b>. He worked on a baseball season simulator with the Chicago Cubs. Check out his <a href = "http://jackbanks.web.illinois.edu/">website</a>.</p>
</div>

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/julia_wapner.jpg" alt="Person 2" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://www.linkedin.com/in/julia-wapner-72b418199/">Julia Wapner</a> (2022) is currently working as a Junior Data Scientist for the <b>Baltimore Orioles</b>. She helped develop the second version (current version) of the SEAM application.</p>
</div> 

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/charles_young.jpg" alt="Person 3" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://www.linkedin.com/in/charles-young-2aa709136/">Charles Young</a> (2020) is currently working as a Senior Software Engineer with the <b>Pittsburgh Pirates</b>. He helped develop the first version of the SEAM application. He created the Illini Analytics group at University of Illinois Urbana-Champaign. His collaborations with physicist and baseball expert <a href = "http://baseball.physics.illinois.edu/">Alan Nathan</a> and the UIUC baseball team were made into a <a href = "https://www.youtube.com/watch?v=mcHA385-6P0">documentary</a>.</p>
</div>   

</div> 


## Alumni 

<div style="display: flex; flex-direction: column;">

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/ashrith_anumala.jpg" alt="Person 1" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://www.linkedin.com/in/ashrithanumala/">Ashrith Anumala</a> (2025) is a Computer Science and Statistics student at the University of Illinois Urbana-Champaign. He is working on a baseball game simulator with the Chicago Cubs.</p>
</div> 

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/colin_doherty.jpg" alt="Person 2" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://www.linkedin.com/in/colinmdoherty/">Colin Doherty</a> (2025) is a Statistics student at the University of Illinois Urbana-Champaign. He is working on a baseball game simulator with the Chicago Cubs.</p>
</div> 

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/zheer_wang.jpg" alt="Person 3" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://www.linkedin.com/in/zheer-wang/">Ava (Zheer) Wang</a> (2025) is a Computer Science and Statistics student at the University of Illinois Urbana-Champaign. She developed public-facing content for the Full House Modeling project.</p>
</div> 

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/mohit_singh.jpg" alt="Person 4" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://www.linkedin.com/in/mohit-singh-5b4b351b3/">Mohit Singh</a> (2025) is a Computer Science and Statistics student at the University of Illinois Urbana-Champaign. He is developing public-facing content for the Full House Modeling project.</p>
</div> 

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/colin_alberts.jpg" alt="Person 5" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://www.linkedin.com/in/colin-alberts/">Colin Alberts</a> (2024) is a data scientist at CISCO. He was an Applied Mathematics MS student at the University of Illinois Urbana-Champaign. He completed a Master's thesis on working on fielder placement optimization. See his GitHub repo <a href = "https://github.com/colalb1/SEAM-Fielder-Optimization">here</a>.</p>
</div>

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/jamin_kim.jpg" alt="Person 6" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://www.linkedin.com/in/jamin-kim-69aa7920a/">Jamin Kim</a> (2024) is a Statistics graduate from the University of Illinois Urbana-Champaign. He worked on a baseball game simulator with the Chicago Cubs.</p>
</div> 

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/aidan_glickman.jpg" alt="Person 7" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://www.aidanglickman.com/">Aidan Glickman</a> (2023) is a Computer Science graduate from the University of Illinois Urbana-Champaign. He led a STAT 430 group that developed the initial proof of concept for our baseball video game simulator.</p>
</div> 

<div style="display: flex; margin-bottom: 20px;">
    <img src="images/fieldOdreams.png" alt="Person 8" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://www.linkedin.com/in/michael-escobedo-76b452209/">Michael Escobedo</a> (2023) is a Statistics graduate from the University of Illinois Urbana-Champaign. He worked on a baseball season simulator with the Chicago Cubs.</p>
</div> 
 
<div style="display: flex; margin-bottom: 20px;">
    <img src="images/christian_chase.jpg" alt="Person 9" style="width:75px;height:75px; margin-right: 20px;">
    <p style="text-align: justify;"><a href = "https://www.linkedin.com/in/christian-chase/">Christian Chase Jr.</a> (2022) worked as a Player Development Intern with the Chicago White Sox. He wrote his University of Florida honors thesis on "<a href = "https://ufdcimages.uflib.ufl.edu/AA/00/08/82/59/00001/Chase_Christian_Honors_Project.pdf">Predicting situation-specific OPS in MLB</a>", and is currently a J.D. Candidate at Vanderbilt University Law School.</p>
</div>  
 
 
</div> 

<br>

([logo image credit](https://tvline.com/2022/08/12/tv-ratings-field-of-dreams-game-mlb/))


