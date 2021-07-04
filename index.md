


## Overview

Deep learning has achieved great success in many applications such as image processing, speech recognition and Go games. However, the reason why deep learning is so powerful remains elusive. The goal of this course is to understand the successes of deep learning by studying and building the theoretical foundations of deep learning. Topics covered by this course include but are not limited to: approximation power of neural networks, optimization for deep learning, generalization error analysis of deep learning and benign-overfitting of overparamterized learning models. Instructor will give lectures the selected topics. Students will present and discuss papers on the reading list, and do a course project.

## Prerequisites
CS 260A, STAT 200A and 200B, ECE 236B and 236C, or equivalent courses.

## Logistics

<!--University of California, Los Angeles  -->

- Time: **Monday and Wednesday 2:00PM - 3:50PM**
- Location: [**Zoom**](https://ucla.zoom.us/j/93417970178)  
- Instructor: [Quanquan Gu](http://web.cs.ucla.edu/~qgu/) (Email: qgu at cs dot ucla dot edu)   
- Office hours: **Tuesday 1:00-2:00PM** on [**Zoom**](https://ucla.zoom.us/j/92449409010). 
- Course Website: [https://uclaml.github.io/CS269-Spring2021/](https://uclaml.github.io/CS269-Spring2021)
- Course Forum: [https://piazza.com/ucla/spring2021/cs269/home](https://piazza.com/ucla/spring2021/cs269/home)
(If you haven’t already, [sign up here](piazza.com/ucla/spring2021/cs269).)
- Gradescope: Entry Code 86D2JJ

## Recommended Textbook

There is no required textbook. The following are recommended textbooks:

1. [T] Matus Telgarsky, [Deep learning theory lecture note](https://mjt.cs.illinois.edu/dlt/index.pdf), 2020
2. [A] Sanjeev Arora et al., [Theory of Deep learning book draft](https://www.dropbox.com/s/smkp4vasbiszhw4/DLbook.pdf?dl=0), 2020 （Thank Prof. Sanjeev Arora for sharing the latest version of the book draft!）
3. [SSBD] Shai Shalev-Shwartz, and Shai Ben-David. Understanding machine learning: From theory to algorithms. Cambridge University Press, 2014. 
4. [MRT] Mehryar Mohri, Afshin Rostamizadeh, and Ameet Talwalkar. Foundations of machine learning. MIT press, 2012. 
5. [GBCB] Ian Goodfellow, Yoshua Bengio, Aaron Courville, and Yoshua Bengio. Deep learning. Vol. 1. Cambridge: MIT press, 2016.
6. [ZLLS] Aston Zhang, Zack C. Lipton, Mu Li, Alex J. Smola, Dive into Deep Learning, 2018.

## Other Reference

1. [SHNGS] Soudry, D., Hoffer, E., Nacson, M. S., Gunasekar, S., & Srebro, N. (2018). The implicit bias of gradient descent on separable data. The Journal of Machine Learning Research, 19(1), 2822-2878.
2. [GLSS] Gunasekar, S., Lee, J., Soudry, D., & Srebro, N. (2018, July). Characterizing implicit bias in terms of optimization geometry. In International Conference on Machine Learning (pp. 1832-1841). PMLR.
3. [NLGSSS] Nacson, M. S., Lee, J., Gunasekar, S., Savarese, P. H. P., Srebro, N., & Soudry, D. (2019, April). Convergence of gradient descent on separable data. In 22nd International Conference on Artificial Intelligence and Statistics (pp. 3420-3428). PMLR.	
4. [DZPS] Du, S. S., Zhai, X., Poczos, B., & Singh, A. (2019). Gradient descent provably optimizes over-parameterized neural networks. ICLR.
5. [MMN] Song, M., Montanari, A., & Nguyen, P. (2018). A mean field view of the landscape of two-layers neural networks. Proceedings of the National Academy of Sciences.
6. [CB] Chizat, L., & Bach, F. (2018). On the global convergence of gradient descent for over-parameterized models using optimal transport. In NeurIPS.
7. [FDZ] Fang, C., Dong, H., & Zhang, T. (2019). Over parameterized two-level neural networks can learn near optimal feature representations. arXiv preprint arXiv:1910.11508.
8. [BLLT] Bartlett, P. L., Long, P. M., Lugosi, G., & Tsigler, A. (2020). Benign overfitting in linear regression. Proceedings of the National Academy of Sciences, 117(48), 30063-30070.
9. [ZWBGK] Zou, D., Wu, J., Braverman, V., Gu, Q., & Kakade, S. M. (2021). Benign Overfitting of Constant-Stepsize SGD for Linear Regression. In COLT.
	


## Grading Policy
 
Grades will be computed based on the following factors:

- Lecture Note Scribe 10%
- Homework 40%
- Paper Presentation 10%
- Project 40%

## Schedule


| # | Date  | Topic  | note | scribed note | reading materials  | homework |
|----|----|----|----|----|----|----|
| 1 | 3/29 | Introduction  | [note](https://www.dropbox.com/s/481ak9zj6bxfcoy/Lecture%201%20March%2029.pdf?dl=0) | [scribe note](https://www.dropbox.com/sh/dsnk0z7b73544r8/AAABp1oZvkab9fZz7S67M0s0a?dl=0) | CH0-1 of [T] ||
| 2 | 3/31 | Approximation I | [note](https://www.dropbox.com/s/rw6b28hyen8x1iu/Lecture%202%20March%2031.pdf?dl=0) | [scribe note](https://www.dropbox.com/s/8jg5bltoknz0luf/Lecture2.pdf?dl=0) | CH2-3 of [T] ||
| 3 | 4/5 | Approximation II | [note](https://www.dropbox.com/s/r0vmou4xvmof8vc/Lecture%203%20April%205.pdf?dl=0) | [scribe note](https://www.dropbox.com/s/uvi3w6s8drz2beh/Lecture3.pdf?dl=0) | CH3-4 of [T] |
| 4 | 4/7 | Approximation III | [note](https://www.dropbox.com/s/om7ear4qad28txd/Lecture%204%20April%207.pdf?dl=0) |  [scribe note](https://www.dropbox.com/s/m1bmxr9urt9qgvg/Lecture4.pdf?dl=0)| CH4-5 of [T] |[HW1](https://www.dropbox.com/s/hn2j0o6oqziwubk/HW1.pdf?dl=0) out|
| 5 | 4/12 | Implicit Bias of Gradient Descent I | [note](https://www.dropbox.com/s/17nexzucqiph2qn/Lecture%205%20April%2012.pdf?dl=0) | [scribe note](https://www.dropbox.com/s/rggfd1qla2dacrd/lecture5.pdf?dl=0) | CH9 of [A],[SHNGS] ||
| 6 | 4/14 | Implicit Bias of Gradient Descent II| [note](https://www.dropbox.com/s/681c19aj09u2j7e/Lecture%206%20April%2014.pdf?dl=0) | [scribe note](https://www.dropbox.com/s/rarsgy731s5g8vz/lecture6.pdf?dl=0)| CH9 of [A],[GLSS,NLGSSS] ||
| 7 | 4/19 | Clarke Subdifferential and Positive Homogeneity | [note](https://www.dropbox.com/s/vldpmpi2wwo14pl/Lecture%207%20April%2019.pdf?dl=0)| [scribe note](https://www.dropbox.com/s/9t2859vjjs8s0os/lecture7.pdf?dl=0) | CH14 of [T] |HW1 due|
| 8 | 4/21 | Implicit Bias of Gradient Descent III | [note](https://www.dropbox.com/s/o6od1cse9y8xhpd/Lecture%208%20April%2021.pdf?dl=0) |  | CH15 of [T] |[HW2](https://www.dropbox.com/s/oxbpah4u28e3bmx/HW2.pdf?dl=0) out|
| 9 | 4/26 | NTK Analysis of NNs I | [note](https://www.dropbox.com/s/sptoel3owc12pvw/Lecture%209%20April%2026.pdf?dl=0) | [scribe note](https://www.dropbox.com/s/rkjjzrwda85wci7/lecture9.pdf?dl=0) | CH10 of [A], [DZPS]  ||
| 10 | 4/28 | NTK Analysis of NNs II |[note](https://www.dropbox.com/s/coky1qomamnnhi8/Lecture%2010%20April%2028.pdf?dl=0) | | CH10 of [A], [DZPS] ||
| 11 | 5/3 | Lazy Training |[note](https://www.dropbox.com/s/jgpjkmtyip42oz9/Lecture%2011%20May%203.pdf?dl=0) | | CH13 of [T] |HW2 due|
| 12 | 5/5 | Mean Field Analysis of NNs I | [note](https://www.dropbox.com/s/jw2jxhc28u64hhi/Lecture%2012%20May%205.pdf?dl=0) | | [FDZ][MMN] ||
| 13 | 5/10 | Mean Field Analysis of NNs II | [note](https://www.dropbox.com/s/arj8zmc1ytir4yp/Lecture%2013%20May%2010.pdf?dl=0) |  | [FDZ][MMN] |[HW3](https://www.dropbox.com/s/rn0xclqfyfowmn6/HW3.pdf?dl=0) out|
| 14 | 5/12 | Mean Field Analysis of NNs III | [note](https://www.dropbox.com/s/cr7xugbmuvde9kn/Lecture%2014%20May%2012.pdf?dl=0) | | [FDZ][MMN] ||
| 15 | 5/17 | Generalization Bounds of DNNs I | [note](https://www.dropbox.com/s/vos4cageg1c7t9w/Lecture%2015%20May%2017.pdf?dl=0) | | CH19 of [T] ||
| 16 | 5/19 | Generalization Bounds of DNNs II | [note](https://www.dropbox.com/s/pyhk2vne2ul67gh/Lecture%2016%20May%2019.pdf?dl=0) | | CH21 of [T] |HW3 due, [HW4](https://www.dropbox.com/s/6v8ur35whn12505/HW4.pdf?dl=0) out|
| 17 | 5/24 | Generalization Bounds of DNNs III | [note](https://www.dropbox.com/s/txyce90s9xgie9x/Lecture%2017%20May%2024.pdf?dl=0) | | CH21 of [T] ||
| 18 | 5/26 | Paper Presenation |  | |  ||
|  | 5/31 | Memorial Day Holiday |  | |  |HW4 due, [HW5](https://www.dropbox.com/s/t4u9faqquruaxze/HW5.pdf?dl=0) out|
| 19 | 6/2 | Generalization Bounds of DNNs IV | [note](https://www.dropbox.com/s/v3j0rqphmo4cq9x/Lecture%2018%20June%202.pdf?dl=0) | | CH21 of [T] ||
|  | 6/11 |  |  | |  |HW5 due|

## Academic Integrity Policy

Students are encouraged to read the [UCLA Student Conduct Code](https://www.deanofstudents.ucla.edu/Individual-Student-Code) for Academic Integrity. 


## Lecture Note Scribing

Students are required to scribe one lecture note. The latex template for lecture note will be provided. The scribed lecture notes should be a zip file submitted on CCLE that compiles without errors, and it is due **4 days after the lecture**. This note will be graded. For example, if 2 students are assigned to scribe a given lecture, I expect to receive 2 separate notes. The individual notes are primarily for grading purposes (and also to make sure that each student scribes their own lecture notes), while the final version of the lecture note will be posted on the course website, after being proofread and edited by the Instructor. 

- The signup sheet for lecture note scribing can be found at [here](https://docs.google.com/spreadsheets/d/1DFReHfI875nppSevuoDSdPy3oYV9qdjVr0SLkmLQH8I/edit?usp=sharing).
- The Latex template for lecture note scribing can be downloaded at [here](https://www.dropbox.com/s/dfsdcpszv0hwwh4/lecture%20scribing%20template.zip?dl=0)

## Homework

There will be about 5 homework assignments. The lowest homework score will be dropped. **Homework is required to be written in Latex**. Latex homework template will be provided.
Unless otherwise indicated, you may talk to other students about the homework problems but each student must hand in their own answers. You also must indicate on each homework with whom you collaborated and cite any other references and sources you use including Internet sites. 
Homework is worth full credit before the due time. It is worth zero credit after the due time. 

- The Latex template for homework can be downloaded at [here](https://www.dropbox.com/s/ycilw84s8gijn7m/Homework%20Template.zip?dl=0)

## Paper Presentation

After each lecture, there will be a few recommended readings. Each student is required to select one paper from the list, and prepare a 20 minutes presentation for the class. One paper can only be presented by one student. Students are expected to prepare the slides by themselves, but the original authors' slides are allowed to be used with proper citation. 

The paper presentation will start from week 5.

Both the instructor and other students will grade the presentation (no self-grading). We will provide the detailed grading criteria later.

- The list of papers for presentation can be found at [here](https://docs.google.com/spreadsheets/d/1ErLN_ClrOi2N0LvfWj8j28uX2wqivN1gVWovehX77g8/edit?usp=sharing).




## Project

Students are required to do a project in this class. The goal of the course project is to provide the students an opportunity to explore research directions in optimization or machine learning. Therefore, the project should be related to the course content. An expected project include but not limited to

- A novel and sound solution to an interesting problem
- Thorough theoretical analysis of existing deep learning approaches

The best outcome of the project is a manuscript that is publishable in major machine learning conferences (COLT, ICML, NeurIPS, ICLR, AISTATS, UAI etc.) or journals (Journal of Machine Learning Research). The detailed course project guideline can be found at [here](https://www.dropbox.com/s/2o0hht6qjijjbog/Course%20project.pdf?dl=0). **Students cannot use their own published work as the course project.**


## Relevant Courses

There are many other great deep learning theory and statistical learning theory courses. To mention a few:

[Matus Telgarsky's deep learning theory course](https://mjt.cs.illinois.edu/dlt/)

[Sanjeev Arora's theoretical deep learning course](https://www.cs.princeton.edu/courses/archive/fall19/cos597B/)

[Peter Bartlett's statistical learning theory course](https://people.eecs.berkeley.edu/~bartlett/courses/281b-sp08/)

[Sham Kakade's statistical learning theory course](http://stat.wharton.upenn.edu/~skakade/courses/stat928/)

[Maxim Raginsky's statistical learning theory course](http://maxim.ece.illinois.edu/teaching/SLT/)

