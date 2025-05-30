---
layout: course
title: "STA 250 - Theoretical Foundations for Machine Learning, Spring 2025"
permalink: /teaching/sta250/
---

## Course Information

**Instructor**: Dogyoon Song (dgsong [at] ucdavis [dot] edu)


**Lectures**: Mondays and Wednesdays, 2:10 PM - 3:50 PM, Wellman Hall 109


**Office hours**: Mondays, 4:00 PM - 5:00 PM, or by appointment (MSB 4220)


**Syllabus**: [link](files/STA250_Spring2025_Syllabus.pdf).


**Canvas**: [link](https://canvas.ucdavis.edu/courses/995531).


**Piazza**: [link](https://piazza.com/ucdavis/spring2025/sta250sq2025/home).


**Texts and resources**: We will have no official course textbooks, but you may find the following resources useful.
* Francis Bach, ["Learning Theory from First Principles,"](https://www.di.ens.fr/~fbach/ltfp_book.pdf) MIT Press
* Tengyu Ma, [Machine Learning Theory, Stanford Lecture Notes](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/tengyuma/cs229m_notes/main/master.pdf)
* Percy Liang, [Statistical Learning Theory, Stanford Lecture Notes](https://web.stanford.edu/class/cs229t/notes.pdf)
* Stephen Boyd, ["Convex Optimization,"](https://stanford.edu/~boyd/cvxbook/) Cambridge University Press
* Roman Vershynin, ["High-Dimensional Probability,"](https://www.cambridge.org/core/books/highdimensional-probability/797C466DA29743D2C8213493BD2D2102) Cambridge University Press (also available [here](https://www.math.uci.edu/~rvershyn/papers/HDP-book/HDP-book.html))
* Martin Wainwright, ["High-Dimensional Statistics,"](https://www.cambridge.org/core/books/highdimensional-statistics/8A91ECEEC38F46DAB53E9FF8757C7A4E) Cambridge University Press
* Sanjeev Arora, ["Theory of Deep Learning,"](https://www.cs.princeton.edu/%7Earora/TheoryDL.pdf) Book Draft
* Matus Telgarsky, Deep Learning Theory, Lecture Notes -- [new version](https://mjt.cs.illinois.edu/dlt/two.pdf) and [old version](https://mjt.cs.illinois.edu/dlt/index.pdf)



## Topics
We will cover the following subjects, which may change due to time constraints or student interests.
* Intro to supervised learning and generalization theory
* Optimization theory and methods
* Deep learning theory
* Brief survey of additional topics (if time permits)
  - Causal machine learning
  - Deep generative models
  - ...


## Course Structure and Evaluation
The first ~7 weeks of the course will consist of lectures, in-class quizzes, and in-class reading group discussions. The following ~2 weeks will survey additional topics, and the last week of the coursae will be for presenting final projects.

The students' performance in this course will be evaluated based on the following:
* Homework: 30%
* [Reading group discussions](/teaching/sta250/paper-reading/): 25%
* [Term project](/teaching/sta250/project/): 45%

### Homework
There will be three homework assignments (not including "[Homework 0](homework/STA250_Spring2025_Homework0.pdf)," which you need not submit). 
"Homework 0" is meant for self-assessment; no solutions will be provided. 
If you struggle with completing any of the non-programming part of “Homework 0,” then please note the course may require significant extra effort on your part.

Each of the three graded homeworks will align with each of the first three core units, offering essential practice for internalizing the concepts and methodologies covered in class and for exploring material beyond lectures. 
A random subset of problems will be graded, and clarity of writing counts alongside correctness. 

You are welcome to collaborate with other students on your homework, but you must list the names of any collaborators at the top of your homework assignment. 
All final write-ups must be done individually, and submissions must be in {\LaTeX}-produced PDFs via Gradescope (accessible through Canvas).

If you are unfamiliar with software packages like PyTorch/Jax/TensorFlow, you may find the following tutorials helpful:
* [PyTorch: Learn the Basics](https://pytorch.org/tutorials/beginner/basics/intro.html)
* [Introduction to PyTorch - YouTube Series](https://pytorch.org/tutorials/beginner/introyt/introyt_index.html)

All of the coding you will need to do for the course (and tutorials above) can be done on your personal laptop or in [Google Colab](ttps://colab.research.google.com/?utm_source=scs-index). 
A GPU will not be needed, although using the Google Colab GPU may help if you want to do an experiment-heavy project.

### Reading group discussions
We will hold approximately three sessions to read and discuss an influential paper related to the course. 
The format follows a role-based discussion inspired by [Colin Raffel and Alec Jacobson's role-playing student seminars](https://www.cs.toronto.edu/~jacobson/images/role-playing-paper-reading-seminars.pdf), which is also used in [Aditi Raghunathan's course](https://www.cs.cmu.edu/~aditirag/teaching/15-789F24.html). For more details on the reading group, please see [this page](/teaching/sta250/paper-reading/).

### Project
Students will read 2 or more papers on a topic of their choice, then identify and formulate an interesting, concrete follow-up question for future research. 
Students are expected to make initial strides in solving these questions, via theory or experiments. For more details about the project, please see [this page](/teaching/sta250/project/).


## Tentative Class Schedule


Lecture Day | Topics | Lecture notes | Additional references  | HW | Project | Other 
--- | --- | --- | --- | --- | --- 
Mon, Mar 31 | Introduction | [Lecture 1](lectures/STA250_Spring2025_Lecture 01.pdf) | Bach, Ch 2 & Ma, Ch 1 | "[Homework 0](homework/STA250_Spring2025_Homework0.pdf)" | |
Wed, Apr 2 | Empirical risk minimization | [Lecture 2](lectures/STA250_Spring2025_Lecture 02.pdf) | Ma, Ch 2, 4.1-4.3 & Bach, Ch 4.1-4.4  | | 
Mon, Apr 7 | Rademacher complexity | [Lecture 3](lectures/STA250_Spring2025_Lecture 03.pdf) | Ma, Ch 4.4-4.6, 5.1-5.2 & Bach, Ch 4.5 | [Homework 1](homework/STA250_Spring2025_Homework1.pdf) released | |
Wed, Apr 9 | Kernel methods | [Lecture 4](lectures/STA250_Spring2025_Lecture 04.pdf) | Liang, Ch 4 & Bach, Ch 7 | |
Mon, Apr 14 | Convex optimization | | Boyd, Ch 2-4 & 9.1-9.3 | |
Wed, Apr 16 | Descent methods, pre-conditioning, acceleration | | | | 
Mon, Apr 21 | Paper discussion 1 | | [Homework 2](homework/STA250_Spring2025_Homework2.pdf) released | |
Wed, Apr 23 | | | | |
Mon, Apr 28 | | | | |
Wed, Apr 30 | Paper discussion 2  | | | |
Mon, May 5 | | | | | 
Wed, May 7 | | | | |
Mon, May 12 | | | | |
Wed, May 14 | | | | |
Mon, May 19 | | | | |
Wed, May 21 | Paper discussion 3 | | | | 
Mon, May 26 | **Memorial day, no class** ||| |
Wed, May 28 | | | | |
Mon, Jun 2 | **(if needed) Final project presentation** ||| |
Wed, Jun 4 | **Final project presentation** ||| |
