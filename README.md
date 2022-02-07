# Computationa Modelling Social Systems
[David Garcia](http://dgarcia.eu), 2022

Welcome to the online materials for Computational Modelling of Social Systems

TODO: Two paragraph course description

## Who am I?

TODO: Is Jana also taking a part in this course?

I am the Professor for Computational Behavioral and Social Sciences the Graz University of Technology, where I lead the [Computational Social Science Lab](http://www.csslab.at). I am also group leader at the Medical University of Vienna and at the Complexity Science Hub Vienna. My background is Computer Science but I worked my whole career with psychologists, sociologists and physicists to learn new ways to understand human behavior. I got my PhD from ETH Zurich in 2012 and a habilitation in 2018, starting to work as full professor TU Graz in 2020. To learn more about my research, check my [publications](https://dgarcia.eu/full-publication-list/). I teach this course in collaboration with [Dr. Jana Lasser](https://janalasser.at/), a postdoctoral reasearcher in the Computational Social Science Lab, and [Dr. Petar Jerčić](https://petarjercic.com/), also a postdoctoral reasearcher in the Computational Social Science Lab.

## Place and time

TODO: Check information on lecture time and rooms

The main lecture takes place on Thursdays at 14:15 (sharp) in lecture room i3 in the Inffeldgasse campus of TU Graz. **The lecture is followed by one exercise session in the same room.** An additional time slot for another **exercise group is available on Tuesdays at 13:00** (also sharp) in room HS II at Rechbauerstrasse 12, where the same exercise as the previous week is discussed. Lectures will be streamed and recorded. When attending in person, proof of 3G status is required and seating space is limited depending on varying policies. Seating will be given in a first-come-first-served basis each session and students that do not fit will have to follow the lecture online in another place.

## Course Contents

TODO: Check the first paragraph for protocol of the course?
TODO: Check how will the course *Intro course: ABM basics in Python with Mesa* be held?
TODO: The session #10 doesn't have reading materials?

The course is organized in 12 sessions grouped together in 4 blocks. Each block contains a practical part with exercises for you to apply what you learned. From the third week, the practice session will consist of a discussion of solutions to the exercise corresponding to the previous session. In exercises, you collect your own data and try to answer questions about human behavior and online phenomena. The online materials do not contain the solutions to the exercises, but if you are stuck or want to start from an easier point, in the github folder of the exercise you can find a version of the exercise with hints.

### Block 1: Fundamentals of agent-based modelling

1. **Basics of agent-based modeling: The macro-micro gap and cellular automata**  (03.03.2022)  
1.1. Course administration and information  
1.2. Readings: ([Smith & Conrey, 2007](https://journals.sagepub.com/doi/abs/10.1177/1088868306294789)) (Macy & Willer, 2002?) (Hedström & Ylikoski, 2010?)
1.3. Game of life paper: ([Gardner, 1970](http://web.stanford.edu/class/sts145/Library/life.pdf))
*(Please install Jupyter and iPython before the next session takes place)*

**Intro course: ABM basics in Python with Mesa**

2. **Modeling segregation: Schelling’s model**  (10.03.2022)  
2.1. Readings: ([Schelling, 1971](https://www.uzh.ch/cmsssl/suz/dam/jcr:00000000-68cb-72db-ffff-ffffff8071db/04.02%7B_%7Dschelling%7B_%7D71.pdf)) [[JASS]](https://www.jasss.org/15/1/6.html) 
2.2. Schelling's Model of Segregation: [[Simulation]] (http://nifty.stanford.edu/2014/mccown-schelling-model-segregation/)

3. **Modelling culture: Axelrod’s model and Latane’s model**  (17.03.2022)  
3.1. Readings: ([Axelrod’s model](https://ndg.asc.upenn.edu/wp-content/uploads/2016/04/Axelrod-1997-JCR.pdf)) ([Latane’s model](https://pcl.sitehost.iu.edu/rgoldsto/complex/nowak90.pdf))

### Block 2: Opinion dynamics

4. **Basics of spreading: Granovetter’s threshold model**  (24.03.2022)  
4.1. Readings: ([Granovetter, 1978](https://www.jstor.org/stable/2778111)) [[JASS]](https://www.jasss.org/15/1/6.html)
- (Exercise 1 start (ungraded): Finding segregation tolerance thresholds in Schelling)

5. **Modelling consensus, polarization, and fragmentation: The voter model and Bounded confidence models, Information accumulation systems**  (31.03.2022)  
5.1. Readings: ([Bounded confidence models](https://www.researchgate.net/profile/Frederic-Amblard/publication/312153320_Mixing_beliefs_among_interacting_agents/links/60b5ed8b4585154e5ef5cb8d/Mixing-beliefs-among-interacting-agents.pdf)) [[Information accumulation systems]](https://iopscience.iop.org/article/10.1088/1742-5468/2010/06/P06005/meta) 
- (Exercise 2 start (20%): Cascade dynamics in threshold models - the role of variance)

6. **Modeling hyperpolarization and cognitive balance**  (07.04.2022)  
6.1. Readings: ([Schweighofer et al., 2020](https://www.jasss.org/23/3/5.html))

**9.04-23.04 Easter holidays**

### Block 3: Network formation

7. **Basics of network modelling: Random graphs and phase transitions**  (28.04.2022)  
7.1. Readings: ([Newman Networks, CH 12 in ed 1, CH 11 in ed 2](https://www.amazon.com/Networks-Introduction-Mark-Newman/dp/0199206651))
- (Exercise 3 start (20%): Fragmentation in bounded confidence models)

8. **Modelling small worlds: The Watts-Strogatz model and cavemen models**  (05.05.2022)  
8.1. Readings: ([The Watts-Strogatz model](https://www.nature.com/articles/30918)) [[Simulation]](www.netlogoweb.org/launch)
8.2. Readings: ([The Cavemen models](https://www.jstor.org/stable/10.1086/210318))

9. **Modeling scaling: The Barabasi-Albert model, edge copying**  (12.05.2022)  
9.1. Readings: ([The Barabasi-Albert model](https://arxiv.org/abs/cond-mat/9910332)) [[Simulation]](https://sarah37.github.io/barabasialbert/)
- (Exercise 4 start (25%): Long-tailed degree distributions in networks vs the BA model)

**26.05. Ascension day**

10. **Growth processes and distribution fitting**  (19.05.2022)  

### Block 4: Behavior on networks

7. **Modeling spreading in networks: the SIR, SIS, and complex contagion**  (02.06.2022)  
7.1. Readings: ([Kitsak](https://www.nature.com/articles/nphys1746))
7.1. Readings: ([Centola, 2007](https://www.jstor.org/stable/10.1086/521848))

8. **Computational modelling applications: the SEIRX model**  (09.06.2022)  
8.1. Readings: ([Lasser, J., Sorger, J., Richter, L. et al., 2022](https://www.nature.com/articles/s41467-022-28170-6))

**16.06: Corpus Christi**

9. **Project presentations**  (23.06.2022)
9. **Project presentations**  (30.06.2022)

## Where to access materials

TODO: What speficic material will be available in GitHub?
TODO: Update the course id for the TU Graz Teach Center?

- Handouts, codes, and data can be found on the [Github repository of the course](https://github.com/dgarcia-eu/ComputationalModellingSocialSystems).
- Students at TU Graz can access the [course at Teach Center](https://tc.tugraz.at/main/course/view.php?id=4072) to get additional information, watch videos, and to participate in the forums and quizzes.

## Course grading

TODO: extra points?
The assessment for the course is based on the excercises given throughout the course (grade percetage given in the brackets) and the final group research project (max. 4 students groups). The project grade is a combination of the project presentation (35%) and the excercises (65%). Extra points (max 20%)  can be achieved by delivering two optional exercise solutions: "Division of impact on Twitter" (**new deadline: 1.12.2021**) and "Assortativity among Swiss politicians on Twitter" (deadline 12.1.2022).
