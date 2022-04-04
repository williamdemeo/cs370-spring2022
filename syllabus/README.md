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



| **Week** | **Date** | **Topic**                         | **Reading**      | **Homework**                             | **Project Due Dates** | **UCB Videos**                  | **UCB Notes**      | **Alternative Notes** |
|----------|----------|-----------------------------------|------------------|------------------------------------------|-----------------------|---------------------------------|--------------------|-----------------------|
| **1**    | 18 Jan   | [Intro to AI (UCB version)][]      | Ch 1             | [HW 0][] Survey, due Wed 26 Jan 23:59    |                       | [Intro to AI (YouTube)][]       |                    | |
|          | 21 Jan   | [Agents and Environments][]       | Ch 2             | [HW 1][] Agents, due Wed 2 Feb 23:59     |                       |                                 |                    | |
| **2**    | 25 Jan   | [Uninformed Search][]             | 3.1--3.4         |                                          |                       | [Uninformed Search (YouTube)][] | [Note 1: Search][] | [Note 1 (Fa '18)][]|
|          | 28 Jan   | [Informed Search][]               | 3.5, 3.6         | [HW 2][] Search, due Wed 9 Feb 23:59     |                       | [Informed Search (YouTube)][]   |                    | |
| **3**    | 1 Feb    | [A* Search and Heuristics][]      | 4.1, 4.2         |                                          |                       |                                 | [Note 2: Local Search][] | |
|          | 4 Feb    | [CSP I][]                         | 6.1, 6.2         | [HW 3][] CSP, due Wed 16 Feb 23:59       | [Project 0][] **due** | [CSP I (YouTube)][]             | [Note 2: CSP][]    | |
| **4**    | 8 Feb    | [CSP II][]                        | 6.3--6.5         |                                          |                       | [CSP II (YouTube)][]            | [CSP applet][]     | |
|          | 11 Feb   | [Adversarial Search I][]          | 5.2--5.5         | [HW 4][] Games, due Wed 23 Feb 23:59     |                       | [Game Trees I (YouTube)][]      | [Note 3: Games][]  | [Note 3 (Fa '18)][]| 
| **5**    | 15 Feb   | [Adversarial Search II][]         | 16.1--16.3       |                                          |                       | [Game Trees II (YouTube)][]     | [Note 4: Nondeterministic Search][] | |
|          | 18 Feb   | [Markov Decision Processes I][]   | 17.1--17.3       | [HW 5][] MDP, due Wed 2 Mar 23:59        | [Project 1][] **due** | [MDP I (YouTube)][]             |                    | |
| **6**    | 22 Feb   | [Markov Decision Processes II][]  |                  |                                          |                       | [MDP II (YouTube)][]            |                    | |
|          | 25 Feb   | [Reinforcement Learning I][]      | Ch 21            | [HW 6][] RL, due Wed 9 Mar 23:59         |                       | [RL I (YouTube)][]              | [Note 5: Reinforcement Learning][] | |
| **7**    | 1 Mar    | [Reinforcement Learning II][]     | Ch 22            |                                          |                       | [RL II (YouTube)][]             |                    | |
|          | 4 Mar    | [Probability][]                   | 13.1--13.5       | [HW 7][] Prob, due Wed 30 Mar 23:59      | [Project 2][] **due** | [Probability (YouTube)][]       |                    | |
| **8**    | 8 Mar    | [Bayes Nets I][]                  | 14.1, 14.2       |                                          |                       | [Bayes Nets (YouTube)][]        | [Note 5: Bayes Nets][] | [Note 6 (Fa '18)][] |
|          | 11 Mar   | [Bayes Nets II][]                 | 14.4             | [HW 8][] Bayes Nets, due Wed 6 Apr 23:59 |                       | [BN: independence (YouTube)][]  |                    | |
| **9**    | 15 Mar   | Spring Recess                     |                  |                                          |                       |                                 |                    | |
|          | 18 Mar   | Spring Recess                     | [Jordan 2.1][]  (optional reading) |                        |                       |                                 |                    | |
| **10**   | 22 Mar   | Review                            |                  |                                          |                       |                                 |                    | |
|          | 25 Mar   | EXAM (scope: 18 Jan--11 Mar)      |                  |                                          |                       |                                 |                    | |
| **11**   | 29 Mar   | [Bayes Nets III][]                | 14.1, 14.2, 14.4 |                                          |                       | [BN: inference (YouTube)][]     |                    | |
|          | 1 Apr    | [Bayes Nets IV][]                 | 14.4-5           | [HW 9][]. HMM; due Wed 13 Apr 23:59      | [Project 3][] **due** | [BN: sampling (YouTube)][]      |                    | |
| **12**   | 5 Apr    | [Hidden Markov Models][]          | 16.5, 16.6       |                                          |                       | [HMM (YouTube)][]               | [Note 6: HMM][]    |  [Note 8 (Fa '18)][] |
|          | 8 Apr    | [Logical Agents][]                | Ch 7             | [HW 10][]. Logic; due Wed 20 Apr 23:59   |                       | [edX AI wk10: Logical Agents][] | [Note 4: Logical Agents][] | |
| **13**   | 12 Apr   | [Inference in First Order Logic][] | Ch 8, 9         |                                          |                       |                                 |                    | |
|          | 15 Apr   | Good Friday (no classes)          | 19.6, 19.7       | [HW 11][]. ML; due Wed 27 May 23:59      |                       |                                 |                    | |
| **14**   | 19 Apr   | [ML: Naïve Bayes][]               | 20.1, 20.2       |                                          |                       | [ML: Naive Bayes (YouTube)][]   |  [Note 9: ML][]    | |
|          | 22 Apr   | [ML: Perceptrons, Logit][]        | 18.6.3, 18.8     |                                          | [Project 4][] **due** | [ML: Perceptrons, Logit (YouTube)][] |               | |
| **15**   | 26 Apr   | [ML: Optimization][]              | 18.6.3, 18.8     |                                          |                       |                                 | [Note 10: Neural Nets][] | |
|          | 29 Apr   | [ML: Neural Nets][]               |                  |                                          |                       | [ML: Neural Nets (YouTube)][]   |                    | |
| **16**   | 3 May    | [Conclusion][]                    |                  |                                          |                       |                                 |                    | |
|          | 4 May    | (reading day)                     |                  |                                          |                       |                                 |                    | |
|          | 6 May    | (reading day)                     |                  |                                          |                       |                                 |                    | |
|          | 6 May    | (final exams begin)               |                  |                                          |                       |                                 |                    | |
|          | 12 May   | (final exams end)                 |                  |                                          |                       |                                 |                    | |
|          | 14 May   | (final grades due)                |                  |                                          |                       |                                 |                    | |


**Remarks**. The AI course at UC Berkeley sometimes covers Decision Networks and Particle Filtering.  In our class, we will omit these topics and instead cover Logical Agents and Inference in First Order Logic.  However, students who wish to study Decision Networks and Particle Filtering on their own are advised to watch the CS188 lecture ([Decision Networks (YouTube)][]) and read the CS188 notes ([Note 7: Decision Networks][]) covering these topics.


<!-- LINKS TO LECTURE NOTES -->

[Note 1: Search]: https://inst.eecs.berkeley.edu/~cs188/sp22/assets/notes/n1_sp22.pdf
[Note 1 (Fa '18)]: https://github.com/williamdemeo/cs370-spring2022/tree/master/notes/n01-search.pdf
[Note 2: Local Search]: https://inst.eecs.berkeley.edu/~cs188/sp22/assets/notes/n2_sp22.pdf
[Note 2: CSP]: https://github.com/williamdemeo/cs370-spring2022/tree/master/notes/n02-csp.pdf 
[CSP applet]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/demos/csp/csp_demos.html
[Note 3: Games]: https://inst.eecs.berkeley.edu/~cs188/sp22/assets/notes/n3_sp22.pdf
[Note 3 (Fa '18)]: https://github.com/williamdemeo/cs370-spring2022/tree/master/notes/n03-adversarial-search.pdf
[Note 4: Nondeterministic Search]: https://github.com/williamdemeo/cs370-spring2022/tree/master/notes/n04-nondeterministic-search.pdf
[Note 4: Logical Agents]: https://inst.eecs.berkeley.edu/~cs188/sp22/assets/notes/n4_sp22.pdf
[Note 5: Reinforcement Learning]: https://github.com/williamdemeo/cs370-spring2022/tree/master/notes/n05-rl.pdf
[Note 5: Bayes Nets]: https://inst.eecs.berkeley.edu/~cs188/sp22/assets/notes/n5_sp22.pdf
[Note 6 (Fa '18)]: https://github.com/williamdemeo/cs370-spring2022/tree/master/notes/n06-bayes-nets.pdf
[Note 6: HMM]: https://inst.eecs.berkeley.edu/~cs188/sp22/assets/notes/n6_sp22.pdf
[Note 7: Decision Networks]: https://github.com/williamdemeo/cs370-spring2022/tree/master/notes/n07-decision-networks.pdf
[Note 8 (Fa '18)]: https://github.com/williamdemeo/cs370-spring2022/tree/master/notes/n08-hmm.pdf
[Note 9: ML]: https://github.com/williamdemeo/cs370-spring2022/tree/master/notes/n09-ml.pdf
[Note 10: Neural Nets]: https://github.com/williamdemeo/cs370-spring2022/tree/master/notes/n10-neural-nets.pdf


<!-- Project LINKS -->
[Project 0]: https://github.com/williamdemeo/cs370-spring2022/tree/master/projects/Project0
[Project 1]: https://github.com/williamdemeo/cs370-spring2022/tree/master/projects/Project1
[Project 1 (part 2)]: https://github.com/williamdemeo/cs370-spring2022/tree/master/projects/Project1
[Project 2]: https://github.com/williamdemeo/cs370-spring2022/tree/master/projects/Project2
[Project 3]: https://github.com/williamdemeo/cs370-spring2022/tree/master/projects/Project3
[Project 4]: https://github.com/williamdemeo/cs370-spring2022/tree/master/projects/Project4



<!-- HW LINKS -->

[HW 0]: https://njit.instructure.com/courses/22602/quizzes
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


<!-- LINKS TO UCB LECTURE YOUTUBE VIDEOS -->

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
[ML: Perceptrons, Logit (YouTube)]: https://www.youtube.com/watch?v=UNr9gHyOnWA
[ML: Decision Trees (YouTube)]: https://youtu.be/svW3I0cqfpw
[Robotics (YouTube)]: https://youtu.be/MxS1aYvYNNc

<!-- LINKS TO LECTURE SLIDES -->
[Intro to AI (UCB version)]: https://inst.eecs.berkeley.edu/~cs188/sp22/assets/slides/Lecture1.pptx
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
[Bayes Nets III]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/dne.md
[Bayes Nets IV]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/dne.md
[Logical Agents]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/dne.md
[Inference in First Order Logic]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/dne.md

[Decision Networks and VPI]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/
[Hidden Markov Models]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/
[Particle filtering]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/
[ML: Naïve Bayes]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/
[ML: Perceptrons and Logistic Regression]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/
[ML: Perceptrons, Logit]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/
[ML: Optimization]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/
[ML: Neural Nets]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/
[Advanced Applications: Games and Robotics]: https://www.dropbox.com/s/9rps3i3ad3noljn/fa21-lec24--games-and-robotics.pptx?dl=0
[Conclusion]: https://github.com/williamdemeo/cs370-spring2022/blob/master/lecture/

<!-- MISC LINKS -->
[Jordan 2.1]: https://github.com/williamdemeo/cs370-spring2022/tree/master/notes/chapter2.pdf
[KUPF 107]: https://goo.gl/maps/GjhP3cjrMAJSzVFt5
[edX AI wk10: Logical Agents]: https://learning.edx.org/course/course-v1:ColumbiaX+CSMM.101x+2T2018/home






<!-- [Note 1]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note01.pdf
[Note 2]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/note02.pdf>
[Note 3]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note03.pdf
[Note 4]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note04.pdf
[Note 5]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note05.pdf
[Note 6]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note06.pdf
[Note 7]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note07.pdf
[Note 8]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note08.pdf
[Note 9]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note09.pdf
[Note 10]: https://inst.eecs.berkeley.edu/~cs188/fa21/assets/notes/fa20-note10.pdf
-->
