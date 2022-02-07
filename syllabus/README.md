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


| **Week** | **Date** | **Topic**                        | **Reading**      | **Homework**                                                 | **Project Due Dates** | **UCB Videos**        |
|----------|----------|----------------------------------|------------------|--------------------------------------------------------------|-----------------------|-----------------------|
| **1**    | 18 Jan   | Intro to AI                      | Ch 1             | [HW 0 (canvas)][] Preliminary Survey; due Wed 26 Jan 10:59pm |                       | [Intro to AI][]       |
|          | 21 Jan   | Rational Agents                  | Ch 2             | [HW 1][] Agents; due Wed 2 Feb 10:59pm                       |                       |                       |
| **2**    | 25 Jan   | State Spaces, Uninformed Search  | 3.1--3.4         |                                                              |                       | [Uninformed Search][] |
|          | 28 Jan   | Search I                         | 3.5, 3.6         | [HW 2][] Search; due Wed 9 Feb 10:59pm                       |                       | [Informed Search][]   |
| **3**    | 1 Feb    | Search II                        | 4.1, 4.2         |                                                              |                       |                       |
|          | 4 Feb    | CSP I                            | 6.1, 6.2         | [HW 3][] CSP; due Wed 16 Feb 10:59pm                         |                       | [CSP I][]             |
| **4**    | 8 Feb    | CSP II                           | 6.3--6.5         |                                                              |                       | [CSP II][]            |
|          | 11 Feb   | Games Trees: Minimax             | 5.1, 5.2         | [HW 4][] Games; due Wed 23 Feb 10:59pm                       |                       | [Game Trees I][]      |
| **5**    | 15 Feb   | Games Trees: Expectimax, Utility | 5.3--5.5         |                                                              |                       | [Game Trees II][]     |
|          | 18 Feb   | Inference, Theorem Proving, DPLL | Ch 7             | [HW 5][] First-order logic; due Wed 2 Mar 10:59pm            | **Project 1 Due by 11:59** |                       |
| **6**    | 22 Feb   | First order logic I              | 8.1--8.4         |                                                              |                       |                       |
|          | 25 Feb   | FOL II and Probability           | 9.1--9.4         | [HW 6][] Prob & Bayes Nets; due Fri 11 Mar 10:59pm           | **Project 2 Due by 11:59** | [Probability][]       |
| **7**    | 1 Mar    | Probability & Bayes Nets         | Ch 12            |                                                              |                       |                       |
|          | 4 Mar    | EXAM (scope: 18 Jan--25 Feb)     |                  | [HW 7][]. Bayes Nets & HMMs; due Wed 30 Mar 10:59pm          |                       | [Bayes Nets][]        |
| **8**    | 8 Mar    | Bayes Nets (BN)                  | 13.1--13.3       |                                                              |                       |                       |
|          | 11 Mar   | BN: independence                 | 13.4             |                                                              |                       | [BN: independence][]  |
| **9**    | 15 Mar   | Spring Recess                    |                  |                                                              |                       |                       |
|          | 18 Mar   | Spring Recess                    |                  |                                                              |                       | [BN: inference][]     |
| **10**   | 22 Mar   | BN: inference, sampling          | 14.1--14.3       |                                                              |                       | [BN: sampling][]      |
|          | 25 Mar   | HMM, DBN                         | 14.4, 14.5       |                                                              |                       | [HMM][]               |
| **11**   | 29 Mar   | Prob Prog (time permitting)      | Ch 15            |                                                              |                       | [HMM Apps][]          |
|          | 1 Apr    | Decision Theory                  | 16.1--16.3       | [HW 8][]. Utility Theory & HMMs; due Wed 13 Apr 10:59pm      |                       | [Decision Networks][] |
| **12**   | 5 Apr    | Decision Networks                | 16.5--16.7       |                                                              |                       | [MDP I][]             |
|          | 8 Apr    | Markov Decision Procs            | 17.1, 17.2       | [HW 9][]. MDPs; due Wed 20 Apr 10:59pm                       |                       | [MDP II][]            |
| **13**   | 12 Apr   | ML: Naive Bayes                  | 19.1--19.4       |                                                              |                       | [ML: Naive Bayes][]   |
|          | 15 Apr   | Good Friday (no classes)         | 19.6, 19.7       | [HW 10][]. Machine Learning; due Wed 27 May 10:59pm          |                       | [ML: Decision Trees][] |
| **14**   | 19 Apr   | ML: Neural Nets                  | 19.9, 20.1, 20.2 |                                                              |                       | [ML: Neural Nets][]   |
|          | 22 Apr   | Deep Learning                    | 21.1--21.4       | [HW 11][]. Reinforcement Learning; due Wed 4 May             |                       | [RL I][]              |
| **15**   | 26 Apr   | Deep & Reinforcement Learning    | 21.5--21.7       |                                                              |                       | [RL II][]             |
|          | 29 Apr   | Reinforcement Learning           | 22.1--22.4       |                                                              |                       | [Robotics][]          |
| **16**   | 3 May    | Review (last class)              |                  |                                                              |                       |                       |
|          | 4 May    | (reading day)                    |                  |                                                              |                       |                       |
|          | 6 May    | (reading day)                    |                  |                                                              |                       |                       |
|          | 6 May    | (final exams begin)              |                  |                                                              |                       |                       |
|          | 12 May   | (final exams end)                |                  |                                                              |                       |                       |
|          | 14 May   | (final grades due)               |                  |                                                              |                       |                       |




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
[Intro to AI]: https://www.youtube.com/watch?v=16Dir4QqCUg
[Uninformed Search]: https://youtu.be/-Xx0QSFYfIQ
[Informed Search]: https://youtu.be/Mlwrx7hbKPs
[CSP I]: https://youtu.be/81z2ANjQcH4
[CSP II]: https://youtu.be/_DXf6oaknHw
[Game Trees I]: https://youtu.be/v6RgZBjc8og
[Game Trees II]: https://youtu.be/n3A29GEzC6g
[MDP I]: https://youtu.be/4LW3H_Jinr4
[MDP II]: https://youtu.be/ZToWj64rxvQ
[RL I]: https://youtu.be/TiXS7vROBEg
[RL II]: https://youtu.be/XafrqwHfBKE
[Probability]: https://youtu.be/sMNbLXsvRig
[Bayes Nets]: https://youtu.be/T4l6ltMMcec
[BN: independence]: https://youtu.be/FUnOdyZZAaE
[BN: inference]: https://youtu.be/A1hYXGAUdmU
[BN: sampling]: https://youtu.be/kGngCS-1kjU
[Decision Networks]: https://youtu.be/19sr7yKV56I
[HMM]: https://youtu.be/eCZLhZu_U1I
[HMM Apps]: https://youtu.be/pNam9hbwg4g
[ML: Naive Bayes]: https://youtu.be/1nOb0vwWkAE
[ML: Neural Nets]: https://youtu.be/LERtLI2h_nQ
[ML: Decision Trees]: https://youtu.be/svW3I0cqfpw
[Robotics]: https://youtu.be/MxS1aYvYNNc
