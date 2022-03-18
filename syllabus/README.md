## CS 370: Introduction to Artificial Intelligence (Section 004)

### NJIT Spring 2022

**Lecture Times and Location**. 10--11:20am Tue & Fri in [KUPF 107][]  
**Course Webpage**. [github.com/williamdemeo/cs370-spring2022](https://github.com/williamdemeo/cs370-spring2022)

---

## Syllabus

The *tentative* lecture and homework schedule shown below is subject to change.  Students should return to this page often throughout the semester to keep aprised of modifications in the schedule or homework due dates.

The links in the last column point to the AI lectures at UC Berkeley on the same material.
The Berkeley course presented the material in different order than ours. In case you want to watch all of the Berkeley lectures in their original order, I made
a [AI YouTube playlist](https://youtube.com/playlist?list=PL5FJyaC2WsVndQJI9QtEhIMG2w8pYLN9u) just for you! :)

[Agents and Environments]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec02-AgentsAndEnvironments.pptx
[Uninformed Search]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec03-Search.pptx
[Informed Search]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec04-InformedSearch.pptx
[A* Search and Heuristics]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec05-AstarSearchAndHeuristics.pptx
[CSP I]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec06-CSP-I.pptx 
[CSP II]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec07-CSP-II.pptx
[Adversarial Search I]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec08-AdversarialSearch-I.pptx
[Adversarial Search II]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec09-AdversarialSearch-II.pptx
[Markov Decision Processes I]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec10-MDP-I.pptx
[Markov Decision Processes II]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec11-MDP-II.pptx
[Reinforcement Learning I]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec12-RL-I.pptx
[Reinforcement Learning II]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec13-RL-II.pptx
[Probability]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec14-Probability.pptx
[Bayes Nets I]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec15-BayesNets-I.pptx
[Bayes Nets II]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec16-BayesNets-II.pptx
[Bayes Nets III]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/
[Bayes Nets IV]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/


| **Week** | **Date** | **Topic**                         | **Reading**      | **Homework**                                               | **Project Due Dates**          | **UCB Videos**                  | **UCB Notes**  |
|----------|----------|-----------------------------------|------------------|------------------------------------------------------------|--------------------------------|---------------------------------|----------------|
| **1**    | 18 Jan   | Intro to AI                       | Ch 1             | [HW 0 (canvas)][] Preliminary Survey; due Wed 26 Jan 23:59 |                                | [Intro to AI (YouTube)][]       |                |
|          | 21 Jan   | [Agents and Environments][]       | Ch 2             | [HW 1][] Agents; due Wed 2 Feb 23:59                       |                                |                                 |                |
| **2**    | 25 Jan   | [Uninformed Search][]             | 3.1--3.4         |                                                            |                                | [Uninformed Search (YouTube)][] |                |
|          | 28 Jan   | [Informed Search][]               | 3.5, 3.6         | [HW 2][] Search; due Wed 9 Feb 23:59                       |                                | [Informed Search (YouTube)][]   |                |
| **3**    | 1 Feb    | [A* Search and Heuristics][]      | 4.1, 4.2         |                                                            |                                |                                 |                |
|          | 4 Feb    | [CSP I][]                         | 6.1, 6.2         | [HW 3][] CSP; due Wed 16 Feb 23:59                         | [Project 0][] **Due by 23:59** | [CSP I (YouTube)][]             | [Note 2][]     |
| **4**    | 8 Feb    | [CSP II][]                        | 6.3--6.5         |                                                            |                                | [CSP II (YouTube)][]            | [CSP applet][] |
|          | 11 Feb   | [Adversarial Search I][]          | 5.2--5.5         | [HW 4][] Games; due Wed 23 Feb 23:59                       |                                | [Game Trees I (YouTube)][]      | [Note 3][]     | 
| **5**    | 15 Feb   | [Adversarial Search II][]         | 16.1--16.3       |                                                            |                                | [Game Trees II (YouTube)][]     |                |
|          | 18 Feb   | [Markov Decision Processes I][]   | 17.1--17.3       | [HW 5][] Markov Decision Processes; due Wed 2 Mar 23:59    | [Project 1][] **Due by 23:59** | [MDP I (YouTube)][]             | [Note 4][]     |
| **6**    | 22 Feb   | [Markov Decision Processes II][]  |                  |                                                            |                                | [MDP II (YouTube)][]            |                |
|          | 25 Feb   | [Reinforcement Learning I][]      | Ch 21            | [HW 6][] Reinforcement Learning Wed 9 Mar 23:59           | [Project 1 (part 2)][] **Due by 23:59** | [RL I (YouTube)][]     | [Note 5][]     |
| **7**    | 1 Mar    | [Reinforcement Learning II][]     | Ch 22            |                                                            |                                | [RL II (YouTube)][]             |                |
|          | 4 Mar    | [Probability][]                   | 13.1--13.5       | [HW 7][] Prob & Bayes Nets; due Wed 16 Mar 23:59           | [Project 2][] **Due by 23:59** | [Probability (YouTube)][]       | [Note 6][]     |
| **8**    | 8 Mar    | [Bayes Nets I][]                   | 14.1, 14.2       |                                                            |                                | [Bayes Nets (YouTube)][]        |                |
|          | 11 Mar   | [Bayes Nets II][]                 | 14.4             | [HW 8][]. Bayes Nets & HMMs; due Wed 30 Mar 23:59          |                                | [BN: inference (YouTube)][]     | |
| **9**    | 15 Mar   | Spring Recess                     |                  |                                                            |                                |                                 | |
|          | 18 Mar   | Spring Recess                     |  [Jordan 2.1][]  (optional) |                                                 |                                |                                 | |
| **10**   | 22 Mar   | Review                            |                  |                                                            | [Project 3][] **Due by 23:59** |                                 | |
|          | 25 Mar   | EXAM (scope: 18 Jan--11 Mar)      |                  |                                                            |                                |                                 | |
| **11**   | 29 Mar   | [Bayes Nets III][]                | 14.1, 14.2, 14.4 |                                                            |                                |                                 | |
|          | 1 Apr    | [Bayes Nets IV][]                 | 14.4-5           | [HW 9][]. Utility, Decision Nets; due Wed 13 Apr 23:59     |                                | [BN: sampling (YouTube)][]      | |
| **12**   | 5 Apr    | [Decision Networks and VPI][]     | 16.5, 16.6       |                                                            |                                | [Decision Networks (YouTube)][] | [Note 7][] |
|          | 8 Apr    | [Hidden Markov Models][]          | 15.2--15.6       | [HW 10][]. HMM, MDP; due Wed 20 Apr 23:59                  |                                | [HMM (YouTube)][]               | [Note 8][]   |
| **13**   | 12 Apr   | [Particle filtering][]            | 15.2--15.6       |                                                            |                                |                                 |              |
|          | 15 Apr   | Good Friday (no classes)          | 19.6, 19.7       | [HW 11][]. Machine Learning; due Wed 27 May 23:59          |                                |                                 |              |
| **14**   | 19 Apr   | [Machine Learning: Naïve Bayes][] | 20.1, 20.2       |                                                            |                                | [ML: Naive Bayes (YouTube)][]   |  [Note 9][]  |
|          | 22 Apr   | [Machine Learning: Perceptrons, Logit][] | 18.6.3, 18.8 |                                                         |                                | [ML: Perceptrons, Logit (YouTube)][] |         |
| **15**   | 26 Apr   | [Machine Learning: Optimization][] | 18.6.3, 18.8    |                                                            |                                |                                 | [Note 10][]  |
|          | 29 Apr   | [Machine Learning: Neural Networks][] |              |                                                            |                                |                                 |              |
| **16**   | 3 May    | [Conclusion][]                    |                  |                                                            |                                |                              |   |
|          | 4 May    | (reading day)                     |                  |                                                            |                                |                       |
|          | 6 May    | (reading day)                     |                  |                                                            |                                |                       |
|          | 6 May    | (final exams begin)               |                  |                                                            |                                |                       |
|          | 12 May   | (final exams end)                 |                  |                                                            |                                |                       |
|          | 14 May   | (final grades due)                |                  |                                                            |                                |                       |




[Jordan 2.1]: https://github.com/williamdemeo/cs370-spring2022/tree/master/notes/Chapter2.pdf
[Project 0]: https://github.com/williamdemeo/cs370-spring2022/tree/master/projects/Project0
[Project 1]: https://github.com/williamdemeo/cs370-spring2022/tree/master/projects/Project1
[Project 1 (part 2)]: https://github.com/williamdemeo/cs370-spring2022/tree/master/projects/Project1
[Project 2]: https://github.com/williamdemeo/cs370-spring2022/tree/master/projects/Project2
[Project 3]: https://github.com/williamdemeo/cs370-spring2022/tree/master/projects/Project3
[Project 4]: https://github.com/williamdemeo/cs370-spring2022/tree/master/projects/Project4
[KUPF 107]: https://goo.gl/maps/GjhP3cjrMAJSzVFt5
[HW 0 (canvas)]: https://njit.instructure.com/courses/22602/quizzes
[HW 1]: https://www.gradescope.com/courses/361553
[HW 2]: https://www.gradescope.com/courses/361553
[HW 3]: https://www.gradescope.com/courses/361553
[HW 4]: https://www.gradescope.com/courses/361553
[HW 5]: https://www.gradescope.com/courses/361553
[HW 6]: https://www.gradescope.com/courses/361553
[HW 7]: https://www.gradescope.com/courses/361553
[HW 8]: https://www.gradescope.com/courses/361553
[HW 9]: https://www.gradescope.com/courses/361553
[HW 10]: https://www.gradescope.com/courses/361553
[HW 11]: https://www.gradescope.com/courses/361553



<!-- |          | 18 Feb   | Inference, Theorem Proving, DPLL | Ch 7             | [HW 5][] First-order logic; due Wed 2 Mar 23:59            | **Project 1 Due by 23:59** |                       | -->
<!-- | **6**    | 22 Feb   | First order logic I              | 8.1--8.4         |                                                              |                       |                       | -->
<!-- |          | 25 Feb   | FOL II and Probability           | 9.1--9.4         | [HW 6][] Prob & Bayes Nets; due Fri 11 Mar 23:59           | **Project 1 (part2) Due by 23:59** | [Probability][]       | -->
<!-- | **7**    | 1 Mar    | Probability & Bayes Nets         | Ch 12            |                                                              |                       |                       | -->
<!-- |          | 4 Mar    | EXAM (scope: 18 Jan--25 Feb)     |                  | [HW 7][]. Bayes Nets & HMMs; due Wed 30 Mar 23:59          |                       | [Bayes Nets][]        | -->
<!-- | **8**    | 8 Mar    | Bayes Nets (BN)                  | 13.1--13.3       |                                                              |                       |                       | -->
<!-- |          | 11 Mar   | BN: independence                 | 13.4             |                                                              |                       | [BN: independence][]  | -->
<!-- | **9**    | 15 Mar   | Spring Recess                    |                  |                                                              |                       |                       | -->
<!-- |          | 18 Mar   | Spring Recess                    |                  |                                                              |                       | [BN: inference][]     | -->
<!-- | **10**   | 22 Mar   | BN: inference, sampling          | 14.1--14.3       |                                                              |                       | [BN: sampling][]      | -->
<!-- |          | 25 Mar   | HMM, DBN                         | 14.4, 14.5       |                                                              |                       | [HMM][]               | -->
<!-- | **11**   | 29 Mar   | Prob Prog (time permitting)      | Ch 15            |                                                              |                       | [HMM Apps][]          | -->
<!-- |          | 1 Apr    | Decision Theory                  | 16.1--16.3       | [HW 8][]. Utility Theory & HMMs; due Wed 13 Apr 23:59      |                       | [Decision Networks][] | -->
<!-- | **12**   | 5 Apr    | Decision Networks                | 16.5--16.7       |                                                              |                       | [MDP I][]             | -->
<!-- |          | 8 Apr    | Markov Decision Procs            | 17.1, 17.2       | [HW 9][]. MDPs; due Wed 20 Apr 23:59                       |                       | [MDP II][]            | -->
<!-- | **13**   | 12 Apr   | ML: Naive Bayes                  | 19.1--19.4       |                                                              |                       | [ML: Naive Bayes][]   | -->
<!-- |          | 15 Apr   | Good Friday (no classes)         | 19.6, 19.7       | [HW 10][]. Machine Learning; due Wed 27 May 23:59          |                       | [ML: Decision Trees][] | -->
<!-- | **14**   | 19 Apr   | ML: Neural Nets                  | 19.9, 20.1, 20.2 |                                                              |                       | [ML: Neural Nets][]   | -->
<!-- |          | 22 Apr   | Deep Learning                    | 21.1--21.4       | [HW 11][]. Reinforcement Learning; due Wed 4 May             |                       | [RL I][]              | -->
<!-- | **15**   | 26 Apr   | Deep & Reinforcement Learning    | 21.5--21.7       |                                                              |                       | [RL II][]             | -->
<!-- |          | 29 Apr   | Reinforcement Learning           | 22.1--22.4       |                                                              |                       | [Robotics][]          | -->
<!-- | **16**   | 3 May    | Review (last class)              |                  |                                                              |                       |                       | -->
<!-- |          | 4 May    | (reading day)                    |                  |                                                              |                       |                       | -->
<!-- |          | 6 May    | (reading day)                    |                  |                                                              |                       |                       | -->
<!-- |          | 6 May    | (final exams begin)              |                  |                                                              |                       |                       | -->
<!-- |          | 12 May   | (final exams end)                |                  |                                                              |                       |                       | -->
<!-- |          | 14 May   | (final grades due)               |                  |                                                              |                       |                       | -->







[Intro to AI (YouTube)]: https://www.youtube.com/watch?v=16Dir4QqCUg
[Uninformed Search (YouTube)]: https://youtu.be/-Xx0QSFYfIQ
[Informed Search (YouTube)]: https://youtu.be/Mlwrx7hbKPs
[CSP I (YouTube)]: https://youtu.be/81z2ANjQcH4
[CSP II (YouTube)]: https://youtu.be/_DXf6oaknHw
[Game Trees I (YouTube)]: https://youtu.be/v6RgZBjc8og
[Game Trees II (YouTube)]: https://youtu.be/n3A29GEzC6g
[MDP I (YouTube)]: https://youtu.be/4LW3H_Jinr4
[MDP II (YouTube)]: https://youtu.be/ZToWj64rxvQ
[RL I (YouTube)]: https://youtu.be/TiXS7vROBEg
[RL II (YouTube)]: https://youtu.be/XafrqwHfBKE
[Probability (YouTube)]: https://youtu.be/sMNbLXsvRig
[Bayes Nets (YouTube)]: https://youtu.be/T4l6ltMMcec
[BN: independence (YouTube)]: https://youtu.be/FUnOdyZZAaE
[BN: inference (YouTube)]: https://youtu.be/A1hYXGAUdmU
[BN: sampling (YouTube)]: https://youtu.be/kGngCS-1kjU
[Decision Networks (YouTube)]: https://youtu.be/19sr7yKV56I
[HMM (YouTube)]: https://youtu.be/eCZLhZu_U1I
[HMM Apps (YouTube)]: https://youtu.be/pNam9hbwg4g
[ML: Naive Bayes (YouTube)]: https://youtu.be/1nOb0vwWkAE
[ML: Neural Nets (YouTube)]: https://youtu.be/LERtLI2h_nQ
[ML: Perceptrons and Logit (YouTube)]: https://www.youtube.com/watch?v=UNr9gHyOnWA
[ML: Decision Trees (YouTube)]: https://youtu.be/svW3I0cqfpw
[Robotics (YouTube)]: https://youtu.be/MxS1aYvYNNc

[Agents and Environments]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec02-AgentsAndEnvironments.pptx
[Search]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec03-Search.pptx
[Informed Search]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec04-InformedSearch.pptx
[A* Search and Heuristics]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec05-AstarSearchAndHeuristics.pptx
[CSP I]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec06-CSP-I.pptx 
[CSP II]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec07-CSP-II.pptx
[Adversarial Search I]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec08-AdversarialSearch-I.pptx
[Adversarial Search II]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec09-AdversarialSearch-II.pptx
[Markov Decision Processes I]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec10-MDP-I.pptx
[Markov Decision Processes II]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec11-MDP-II.pptx
[Reinforcement Learning I]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec12-RL-I.pptx
[Reinforcement Learning II]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec13-RL-II.pptx
[Probability]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec14-Probability.pptx
[Bayes Nets I]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec15-BayesNets-I.pptx
[Bayes Nets II]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/CS370-Lec16-BayesNets-II.pptx

[Decision Networks and VPI]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/
[Hidden Markov Models]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/
[Particle filtering]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/
[Machine Learning: Naïve Bayes]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/
[Machine Learning: Perceptrons and Logistic Regression]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/
[Machine Learning: Optimization]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/
[Machine Learning: Neural Networks]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/
[Advanced Applications: Games and Robotics]: https://www.dropbox.com/s/9rps3i3ad3noljn/fa21-lec24--games-and-robotics.pptx?dl=0
[Conclusion]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/

[Note 1]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note01.pdf
[Note 2]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/note02.pdf">
<!-- [Note 2]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note02.pdf -->
[Note 3]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note03.pdf
[Note 4]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note04.pdf
[Note 5]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note05.pdf
[Note 6]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note06.pdf
[Note 7]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note07.pdf
[Note 8]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note08.pdf
[Note 9]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note09.pdf
[Note 10]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note10.pdf

[CSP applet]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/demos/csp/csp_demos.html
