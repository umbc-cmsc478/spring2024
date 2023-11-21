---
layout: home
title: Home
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: umbc-cmsc478-solaiman #Just the Class
---

<img src="assets/images/UMBC-primary-logo-RGB.png" alt="drawing" width="450"/>

# CMSC 478 — Introduction to Machine Learning 
# Fall 2023
{: .no_toc }

<!-- # About -->
<!-- {:.no_toc} -->

<!-- ## Table of contents -->
<!-- {: .no_toc .text-delta } -->

<!-- 1. TOC -->
- TOC
{:toc}

---

## Logistics 

- Instructor: KMA Solaiman, <mailto:ksolaima@umbc.edu>
- Teaching assistant: Surya Kiran Challagulla, <mailto:ru17699@umbc.edu>
<!-- - Grader: -->
- Lecture time: **TTh 2:30-3:45pm** *(01)*, **TTh 5:30-6:45pm** *(02)*
- Location: `SONDHEIM 203` (01), `SONDHEIM 105` (02)
- Credit Hours: 3.00
- Q&A, Course discussion and announcements: [Campuswire](https://campuswire.com/c/G5403DC1B/feed)
- For any sensitive issue, please email me (<mailto:ksolaima@umbc.edu>), preferrably with a subject preceded by `CMSC478-concern`.
- Exam and assignment submissions: [Blackboard](https://blackboard.umbc.edu/webapps/blackboard/execute/modulepage/view?course_id=_76188_1&cmp_tab_id=_330931_1&editMode=true&mode=cpview#)
- Office hours
  - `Thu 1-2pm, or by appointment` *(more if needed)*,  ITE 201-C, KMA Solaiman 
  - `Thu 3-5pm, or by appointment`, ITE 334, Surya Kiran Challagulla

> **Note:** Visit [Blackboard](https://blackboard.umbc.edu/webapps/blackboard/execute/modulepage/view?course_id=_76191_1&cmp_tab_id=_330934_1&editMode=true&mode=cpview#) for instructions on joining [Campuswire](https://campuswire.com/c/G5403DC1B/feed).
<!-- and [Gradescope](https://www.gradescope.com/courses/417566). -->

## Course Description

This course serves as a foundation to apply machine learning techniques in different domains and for more advanced learning problems. The topics covered will include supervised learning, unsupervised learning, reinforcement learning, weakly or self-supervised learning, Generalization and Regularization, and Ensemble Learning. 
<!-- Other special or current topics (e.g., fairness and ethics in AI) may be covered as well. -->

The goals for this course are:
- be introduced to some of the core problems and solutions of ML;
- learn different ways that success and progress can be measured in ML;
- be exposed to how these problems relate to those in computer science and subfields of computer science;
- have experience experimenting with ML approaches;
- identify issues with features, data, and how to handle them;

### Textbooks

 Hal Daume from UMCP has written a good text for an introductory course in machine learning. You can get it here: [CIML](http://ciml.info/). Another good source is [Machine Learning by Tom Mitechell](http://www.cs.cmu.edu/~tom/files/MachineLearningTomMitchell.pdf). There are also some [lecture notes](assets/Lecture-Notes-Stanford-ML.pdf) from Stanford ML group. We will use some parts of that. 

There are a few other online texts that we'll draw from or I will give you specific lecture notes. You'll find links to them below in the schedule of topics, with specific sections that you should read.

### Prerequisites
This is an upper-level undergraduate level Computer Science course and we will assume that you will have a good grounding in algorithms, statistics, and adequate programming skills (CMSC 341). Many of the homework assignments will involve programming and you will be expected to do them in Python. Having said that, we will try our best to provide materials or backgrounds for the programming assignments.
<!-- CMSC 341 (Principles of Programming Languages) -->

<!-- ########## -->

## Course Schedule
> This syllabus and schedule is preliminary and subject to change.
> Abbreviations refer to the following:
> - CIML: Book by Hal Daume
> - TM: Tom Mitchell
> - SML: [Lecture Notes from Stanford ML](assets/Lecture-Notes-Stanford-ML.pdf)
> - LN: [Lecture Notes, CMSC478 by KMA Solaiman](assets/Lecture_Notes_CMSC478_fall2023.pdf)

| Date      | Topics      | Notes | Readings |
| :---------| :-----------| :------  | :------ | 
| **Week 1** | | | 
| Thu <br> Aug 31 | [Course Overview. Administrivia and What is ML?](assets/478-01-Intro.pdf) | <!--DT from Mitchell or CIML-->1. [YOLO Object Detection](https://www.youtube.com/watch?v=fiqPswSMwio) <br> 2. [10 years of training in 10 days for learning to be a warrior](https://www.youtube.com/watch?v=1kV-rZZw50Q)
| **Week 2** | **Supervised Learning** | | 
| Tue <br> Sep 05 | [Supervised learning setup, LMS](assets/478-02-Regression.pdf) | | [SML Part 1, Chap 1, 1.1](assets/Lecture-Notes-Stanford-ML.pdf) <!--Stanford if otherwise not mentioned-->
| Thu <br> Sep 07 | [Weighted Least Squares, *Perceptron,* Logistic regression, Newton's Method](assets/478-03-Classification-LR-updated.pdf) | | [SML Chap 1.3, Chap 2](assets/Lecture-Notes-Stanford-ML.pdf), See more: Chap 1.4
| **Week 3** | | | 
| Tue <br> Sep 12 | [Multi-class classification](assets/478-04-Multiclass-Classification.pdf) | | [SML Chap 2.3](assets/Lecture-Notes-Stanford-ML.pdf)
|            | **Generative Learning Models** | | 
| Thu <br> Sep 14 | [*Density estimation.* Bayes Rule. MLE vs MAP](assets/478-05-Bayes-MLE-MAP-v2.pdf) | **HW1 is out on BB** and due on 09/25| [Estimating Probabilities](http://www.cs.cmu.edu/~tom/mlbook/Joint_MLE_MAP.pdf) <!-- *Density estimation.* Gaussian discriminant analysis. Naive Bayes.  --><!-- Laplace Smoothing. -->
| **Week 4** | | | 
| Tue <br> Sep 19 | [Naive Bayes, *Conditional Models.*](assets/478-06-NBayes.pdf) | | [Mitchell-Notes Chapter 3](http://www.cs.cmu.edu/~tom/mlbook/NBayesLogReg.pdf) 
| Thu <br> Sep 21 | [Naive Bayes, Gaussian Naive Bayes](assets/478-07-NB-GNB.pdf) | [Continuous Distributions](http://matthias.vallentin.net/blog/2010/10/probability-and-statistics-cheat-sheet/dist-cont.png), [Discrete Distributions](http://matthias.vallentin.net/blog/2010/10/probability-and-statistics-cheat-sheet/dist-disc.png)| <!--  **Kernel Methods** Kernels, SVM -->
| **Week 5** |  | | 
| Tue <br> Sep 26 | [Gaussian Naive Bayes, Laplace Smoothing](assets/478-08.pdf) | | [Mitchell-Notes Chapter 3](http://www.cs.cmu.edu/~tom/mlbook/NBayesLogReg.pdf), SML Chapter 4, [LN Section 1](assets/Lecture_Notes_CMSC471_fall2023.pdf)
|            | **Generalization and Regularization** | | 
| Thu <br> Sep 28 | Bias - Variance Tradeoff | | SML Chapter 8.1
| **Week 6** | | | 
| Tue <br> Oct 03 | Proposal Overview.  | |   <!--CIML Chap 5-->
| Thu <br> Oct 05 | Regularization. Feature / Model selection. Evaluation Metrics. | **Project Proposal Due on Oct 7** | SML Chapter 9.1, 9.3 <!--CIML Chap 8-->
| **Week 7** |  | | 
| Tue <br> Oct 10 | Kernels  |  | SML Chapter 5
| Thu <br> Oct 12 | [Support Vector Machine](assets/478-12-SVM.pdf) | | [A guide to SVM](https://www.analyticsvidhya.com/blog/2021/10/support-vector-machinessvm-a-complete-guide-for-beginners/) <!-- K-Means. GMM (non EM & EM). Expectation Maximization. --> <!-- Neural Network -->
| **Week 8** | | | 
| Tue <br> Oct 17 | [Midterm Review](assets/478-midterm-review.pdf) | |    <!-- PAC, VC--> <!--**Midterm Review**-->
| Thu <br> Oct 19 | **Midterm Exam** | |
| **Week 9** | Neural Networks | | 
| Tue <br> Oct 24 | [Kernel SVM](assets/478-13.pdf), Neural Network | |        <!-- + Factor analysis-->
| Thu <br> Oct 26 | Neural Network: Backpropagation | | [Chapter 10](http://ciml.info/dl/v0_99/ciml-v0_99-ch10.pdf) of CIML, SML 7.2
| **Week 10** | | | 
| Tue <br> Oct 31 | [NN-slide1](assets/NN/14_nn_01.pptx), [NN-slide2](assets/NN/14_nn_02_playground.pptx)  | [Practice Colab Notebooks](https://drive.google.com/drive/u/0/folders/1PAFe3Yv1e3rQAvQC-ZSrF-DF4hsxxr8Q)|
| Thu <br> Nov 02 | [CNN](https://towardsdatascience.com/convolutional-neural-networks-explained-9cc5188c4939), K-Means | |
| **Week 11** | Unsupervised Learning | | 
| Tue <br> Nov 07 | [K-Means](assets/478-K_means.pdf), Self-study:[KNN](assets/478-KNN.pdf) | [Lecture Video](https://umbc.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=7552907c-99a6-477d-a99b-b0b30166ac41) |  CIML [Chapter 3](http://ciml.info/dl/v0_99/ciml-v0_99-ch03.pdf) <!-- GMM, Expectation Maximization, , PCA, ICA, Weak supervised / Self-supervised learning, Monopoly, Guest Lecture on Monopoly-->
| Thu <br> Nov 09 | No class | |
| **Week 12** |  | | 
| Tue <br> Nov 14 | [PCA, ICA](assets/478-PCA_ICA.pdf) | [PCA in action](https://builtin.com/sites/www.builtin.com/files/inline-images/national/Principal%2520Component%2520Analysis%2520second%2520principal.gif), [Choosing K](https://builtin.com/sites/www.builtin.com/files/styles/ckeditor_optimize/public/inline-images/national/Principal%2520Component%2520Analysis%2520Principal%2520Components.png) | [Chapter 15 section 2](http://ciml.info/dl/v0_99/ciml-v0_99-ch15.pdf) of CIML for PCA
| Thu <br> Nov 16 | PCA contd. | |
| **Week 13** | | | |
| Tue <br> Nov 21 | Ensemble Learning, Learning Theory | |         <!-- Tom Mitchell Chap 8 -->
| Thu <br> Nov 23 | Thanksgiving Day <br> No Classes | |
| **Week 14** | | | 
| Tue <br> Nov 28 | Basic concepts in RL, value iteration, policy iteration, Model-based RL, value function approximator | | <!-- Monir Sir Paper-->   <!-- or, Decision Trees/ Concept Learning-->
| Thu <br> Nov 30 | Genetic / Evolutionary Learning, Applications of Evolutionary Learning, Instance-based Learning, KNN | |          <!-- Tom Mitchell Chap 8 --> <!-- or, Decision Trees/ Concept Learning-->
| **Week 15** | **Projects** | | 
| Tue <br> Dec 05 | **Project Presentations** | [Project Presentation Schedule](https://docs.google.com/spreadsheets/d/1ZAdiyA4HxF7RT8JZzrLqhC8UNW8daW5eibXawvzK8gw/edit?usp=sharing): Sheet 1 and Sheet 3 |
| Thu <br> Dec 07 | **Project Presentations** | [Project Presentation Schedule](https://docs.google.com/spreadsheets/d/1ZAdiyA4HxF7RT8JZzrLqhC8UNW8daW5eibXawvzK8gw/edit?usp=sharing): Sheet 2 and Sheet 4 |
| **Week 16** | | | 
| Tue <br> Dec 12 | **Final Exam Review** | |
| Thu <br> Dec 14 | No Classes | | |
| **Week 17** | | | 
| Sun <br> Dec 17 | **Project Final Report Due** | | |
| Wed <br> Dec 20 | **Final Exam** | | |


<!-- ########## -->

## Assignments
TBA

## Midterm and Final Exams
The material covered by the exams will be drawn from assigned readings in the text, from lectures, and from the homework. Material from the readings that is not covered in class is fair game, so you are advised to keep up with the readings.

<!-- ## Code -->
<!-- Tim Finin -->
<!-- We have a repository of Jupyter notebooks intended to run in Colab and python code (e.g., the AIMA code) that are examples we'll use in class and that you can use to understand concepts. You should clone this on your computer or in your account on gl.umbc.edu. The 671 resources page has some information on using git and jupyter notebooks -->

## Projects
The project is meant to give students deeper exposure to some topic in machine learning than they would get from the lectures, readings, and discussions alone. Those projects that are most successful often blend the student's own research with machine learning, e.g. by applying machine learning techniques to a problem in some other area, or by bringing an insight from some other area to a problem in machine learning. However, projects need not involve ties with ongoing research. Many good projects in the past have investigated the application of existing algorithms to a domain/dataset of interest to the student, such as Texas Hold'em, the stock market, sporting events, and so on. Students can come up with their own project ideas or they can come see me and we'll brainstorm project ideas. 

Projects may be done by individuals or teams of two people. However, teams of two will be expected to do significantly more work than what is expected of an individual project. More information on projects can be found [here](https://umbc-cmsc478.github.io/fall2023-public/projects/).

## Course Evaluation

Grades will be based on your performance in homework assignments, project, a mid-term examination and a final examination. There will be 5-10 homeworks throughout the semester. The overall evaluation is as follows:
<!-- The exact weight will be set at the end of the course, but the expected breakdown is: quizzes: 10%; homework: 45%; midterm: 20%; final: 25%.  -->

|Component| %|
| :------------------ | :---: | 
|Homework/Programming Assignments |50%|
|Exams |15% each, 30%|
|Project |20%|

“Course engagement” consists of, e.g., asking questions, participating in discussions (in class or
online), responding to surveys or checkpointing questions, etc.). “Course engagement” could count in your favor in borderline cases.
<!-- |Course Engagement |5%| -->

As per University policy, incompletes will be granted only under extraordinary circumstances; students who are enrolled after the last day to drop a class should be prepared to receive a grade of A-F.
 <!-- We may have a few quizzes on Blackboard based on the reading. Answering the quiz questions should be easy if you have done the reading. -->


<!-- Homework
There will a number of short homework assignments -- at least six and perhaps as many as eight. Each assignment will have a due date and it is expected to be turned in on time. A penalty for late homework will be applied. Homework will be submitted via github classroom repositories. As each assignment is released, we'll provide a link you can use to accept and download your personal repository for the assignment. -->

**Grading Scale:** The following grading scale is used on the normalized final, rounded percentages:

| If you get at least a/an...| you are guaranteed a/an... or higher|
| :---- | :--: | 
|90| A|
|80| B|
|70| C|
|60| D|
|0| F|


<!-- ########## -->
## Policies

If you have extenuating circumstances that result in an assignment being late, please talk to me as soon as possible. 

### Due Dates
Due dates will be announced on the course website and Campuswire. Unless stated
otherwise, items are due by **11:59 PM (UMBC time) of the specified day**. Submission instructions
will be provided with each assigned item.

### Extensions and Late Policy

Personal or one-off extensions will not be granted. Instead, everyone in this course has **ten (10) late days (3 days maximum for each assignment)** to use as needed throughout the course. These are meant for personal reasons and
emergencies; do not use them as an excuse to procrastinate. Late days are measured in 24 hour
blocks after a deadline. They are **not fractional**: an assignment turned in between 1 minute and
23 hours, 59 minutes (1,439 minutes) after the deadline uses one late day, an assignment turned in
between 24 hours and 47 hours, 59 minutes (2879) after the deadline uses two late days, etc.
The number of late days remaining has no bearing on assignments you turn in by the deadline;
they only affect assignments you turn in after the deadline. If you run out of late days and do
not turn an assignment in on time, please still complete and turn in the assignments. Though late
assignments after late days have been exhausted will be recorded as a 0, they will still be marked
and returned to you. Morever, they could count in your favor in borderline cases. There is a **hard cutoff** of the final exam block. Late days cannot be used beyond this time. I reserve the right to
issue class-wide extensions.

<!-- ########## -->

### Academic Honesty

<span style="color:red"> Do not cheat, deceive, plagiarize, improperly
share, access or use code, or otherwise engage in academically dishonest behaviors. Doing so may
result in lost credit, course failure, suspension, or dismissal from UMBC. Instances of suspected
dishonesty will be handled through the proper administrative procedures. </span>

We will follow a policy described in this statement adopted by UMBC's
Undergraduate Council and Provost's Office.

> By enrolling in this course, each student assumes the responsibilities
> of an active participant in UMBC's scholarly community, in which
> everyone's academic work and behavior are held to the highest
> standards of honesty. Cheating, fabrication, plagiarism, and helping
> others to commit these acts are all forms of academic dishonesty, and
> they are wrong. Academic misconduct could result in disciplinary
> action that may include, but is not limited to, suspension or
> dismissal.

<!-- To read the full Student Academic Conduct Policy, consult the UMBC
Student Handbook, the Faculty Handbook, or the UMBC Policies section of
the UMBC Directory. -->

Especially for computer science classes, there are generally questions about what is and is
not alloThu. You are encouraged to discuss the subject matter and assignments with others. The
Campuswire discussion board provides a great forum for this. However, you may not write or complete
assignments for another student; allow another student to write or complete your assignments; pair
program; copy someone else’s work; or allow your work to be copied. **(This list is not inclusive.)**

As part of discussing the assignments, you may plan with other students; be careful when
dealing with pseudocode. A good general rule is that if anything is written down when discussing the assignments with others, you **must** actually implement it separately and you **must not** look at
your discussion notes.

You are free to use online references like Stack Overflow for questions that are not the primary
aspect of the course. If, for example, you’re having an issue with unicode in Python, or are getting
a weird compilation error, then sites like Stack Overflow are a great resource. Don’t get stuck
fighting your tools.

You may generally use external libraries (and even parts of standard libraries), provided what
you use does not actually implement what you are directed to implement.

**Generative AI:** For this class, if you use ChatGPT (or similar chatbots or AI-based generation tools), you must describe exactly how you used it, including providing the prompt, original generation, and your edits. This applies to prose, code, or any form of content creation. Not disclosing is an academic integrity violation. If you do disclose, your answer may receive anywhere from 0 to full credit, depending on the extent of substantive edits, achievement of learning outcomes, and overall circumvention of those outcomes.

Use of AI/automatic tools for grammatical assistance (such as spell-checkers or Grammarly) or small-scale predictive text (e.g., next word prediction, tab completion) is okay. Provided the use of these tools does not change the substance of your work, use of these tools may be, but is not required to be, disclosed.

**Be sure to properly acknowledge whatever external help—be it from students, third party libraries, or other readings—you receive in the beginning of each assignment.** Please review this overview of [how to correctly cite
a source](http://www.lib.duke.edu/libguide/bib_journals.htm) and these guidelines on [acceptable paraphrasing](http://www.indiana.edu/~wts/wts/plagiarism.html).

<!-- Written answers on essay questions for homeworks and papers must be your
own work. If you wish to quote a source, you must do so explicitly,
using quotation marks and proper citation at the point of the quote.
Plagiarism (copying) of any source, including another student's work, is
not acceptable and will result in at a minimum a zero grade for the
entire assignment. Please review this overview of [how to correctly cite
a source](http://www.lib.duke.edu/libguide/bib_journals.htm) and these guidelines on [acceptable paraphrasing](http://www.indiana.edu/~wts/wts/plagiarism.html). -->


<!-- ######## -->

## Accomodations 

### Students with Accommodation Needs

The Office of Student Disability Services (SDS, <https://sds.umbc.edu>)
works to ensure that students can access and take advantage of UMBC's
educational environment, regardless of disability. From the SDS,

> Accommodations for students with disabilities are provided for all
> students with a qualified disability under the Americans with
> Disabilities Act (ADA & ADAAA) and Section 504 of the Rehabilitation
> Act who request and are eligible for accommodations. The Office of
> Student Disability Services (SDS) is the UMBC department designated to
> coordinate accommodations that creates equal access for students when
> barriers to participation exist in University courses, programs, or
> activities.
>
> If you have a documented disability and need to request academic
> accommodations in your courses, please refer to the SDS website at
> [sds.umbc.edu](https://sds.umbc.edu) for registration information and
> office procedures.
>
> SDS email: <disAbility@umbc.edu>
>
> SDS phone: 410-455-2459

If you require the use of SDS-approved accommodations in this class,
please make an appointment with me to discuss the implementation of the
accommodations.

`Religious Observances & Accommodations`
[UMBC Policy](https://provost.umbc.edu/wp-content/uploads/sites/46/2022/08/Religious-Observance-Academic-Policy-2022_2023.pdf)
provides that students should not be penalized because of observances of
their religious beliefs, and that students shall be given an
opportunity, whenever feasible, to make up within a reasonable time any
academic assignment that is missed due to individual participation in
religious observances. It is the responsibility of the student to inform
me of any intended absences or requested modifications for religious
observances in advance, and as early as possible.

### Sexual Assault, Sexual Harassment, and Gender-based Violence and Discrimination

[UMBC Policy](https://ecr.umbc.edu/gender-discrimination-sexual-misconduct/)
in addition to federal and state law (to include Title IX) prohibits
discrimination and harassment on the basis of sex, sexual orientation,
and gender identity in University programs and activities. Any student
who is impacted by **sexual harassment, sexual assault, domestic
violence, dating violence, stalking, sexual exploitation, gender
discrimination, pregnancy discrimination, gender-based harassment, or
related retaliation** should contact the University's Title IX
Coordinator to make a report and/or access support and resources. The
Title IX Coordinator can be reached at <titleixcoordinator@umbc.edu> or
410-455-1717.

You can access support and resources even if you do not want to take any
further action. You will not be forced to file a formal complaint or
police report. Please be aware that the University may take action on
its own if essential to protect the safety of the community.

If you are interested in making a report, please use the [Online
Reporting/Referral
Form](https://umbc-advocate.symplicity.com/titleix_report/index.php/pid364290?).
Please note that, if you report anonymously, the University's ability to
respond will be limited.

`Faculty Reporting Obligations`

All faculty members and teaching assistants are considered Responsible
Employees, per UMBC's Policy on [Sexual Misconduct, Sexual Harassment,
and Gender
Discrimination](https://ecr.umbc.edu/policy-on-sexual-misconduct-sexual-harassment-and-gender-discrimination/).
So please note that as instructors, I, other faculty members, and the
teaching assistants are required to report all known information
regarding alleged conduct that may be a violation of the Policy to the
University's Title IX Coordinator, even if a student discloses an
experience that occurred before attending UMBC and/or an incident that
only involves people not affiliated with UMBC. Reports are required
regardless of the amount of detail provided and even in instances where
support has already been offered or received.

While faculty members want to encourage you to share information related
to your life experiences through discussion and written work, students
should understand that faculty are required to report past and present
sexual harassment, sexual assault, domestic and dating violence,
stalking, and gender discrimination that is shared with them to the
Title IX Coordinator so that the University can inform students of their
[rights, resources, and
support](https://ecr.umbc.edu/rights-and-resources/). While you are
encouraged to do so, you are not obligated to respond to outreach
conducted as a result of a report to the Title IX Coordinator.

If you need to speak with someone **in confidence**, who does not have
an obligation to report to the Title IX Coordinator, UMBC has a number
of [Confidential
Resources](https://ecr.umbc.edu/policy-on-sexual-misconduct-sexual-harassment-and-gender-discrimination/#confidential-resources)
available to support you:

-   Retriever Integrated Health (Main Campus): 410-455-2472; Tueday --
    Friday 8:30 a.m. -- 5 p.m.; **For After-Hours Support, Call 988.**

-   Pastoral Counseling via [The Gathering Space for Spiritual
    Well-Being](https://i3b.umbc.edu/spaces/the-gathering-space-for-spiritual-well-being/):
    410-455-6795; <i3b@umbc.edu>; Tueday -- Friday 8:00 a.m. -- 10:00
    p.m.

-   For after-hours emergency consultation, call the police at
    410-455-5555

**Other Resources:**

-   Women's Center (open to students of all genders): 410-455-2714;
    <womenscenter@umbc.edu>; Tueday -- Thursday 9:30 a.m. -- 5:00 p.m.
    and Friday 10:00 a.m. -- 4 p.m.

-   [Maryland Resources](https://ecr.umbc.edu/maryland-resources/),
    [National Resources](https://ecr.umbc.edu/national-resources/)

`Child Abuse and Neglect`

Please note that Maryland law and [UMBC
policy](https://education.umbc.edu/child-abuse-reporting-policy//)
require that I report all disclosures or suspicions of child abuse or
neglect to the Department of Social Services and/or the police even if
the person who experienced the abuse or neglect is now over 18.

### Hate, Bias, Discrimination, and Harassment

UMBC values safety, cultural and ethnic diversity, social
responsibility, lifelong learning, equity, and civic engagement.

Consistent with these principles, [UMBC
Policy](https://ecr.umbc.edu/discrimination-and-bias/) prohibits
discrimination and harassment in its educational programs and activities
or with respect to employment terms and conditions based on race, creed,
color, religion, sex, gender, pregnancy, ancestry, age, gender identity
or expression, national origin, veterans status, marital status, sexual
orientation, physical or mental disability, or genetic information.

Students (and faculty and staff) who experience discrimination,
harassment, hate, or bias based upon a protected status or who have such
matters reported to them should use the [online
reporting/referral](https://umbc-advocate.symplicity.com/titleix_report/index.php/pid954154?)
form to report discrimination, hate, or bias incidents. You may report
incidents that happen to you anonymously. Please note that, if you
report anonymously, the University's ability to respond may be limited.


<!-- # Just the Class

Just the Class is a GitHub Pages template developed for the purpose of quickly deploying course websites. In addition to serving plain web pages and files, it provides a boilerplate for:

- [announcements](announcements.md),
- a [course calendar](calendar.md),
- a [staff](staff.md) page,
- and a weekly [schedule](schedule.md).

Just the Class is a template that extends the popular [Just the Docs](https://github.com/just-the-docs/just-the-docs) theme, which provides a robust and thoroughly-tested foundation for your website. Just the Docs include features such as:

- automatic [navigation structure](https://just-the-docs.github.io/just-the-docs/docs/navigation-structure/),
- instant, full-text [search](https://just-the-docs.github.io/just-the-docs/docs/search/) and page indexing,
- and a set of [UI components](https://just-the-docs.github.io/just-the-docs/docs/ui-components) and authoring [utilities](https://just-the-docs.github.io/just-the-docs/docs/utilities).

## Getting Started

Getting started with Just the Class is simple.

1. Create a [new repository based on Just the Class](https://github.com/kevinlin1/just-the-class/generate).
1. Update `_config.yml` and `README.md` with your course information. [Be sure to update the url and baseurl](https://mademistakes.com/mastering-jekyll/site-url-baseurl/).
1. Configure a [publishing source for GitHub Pages](https://help.github.com/en/articles/configuring-a-publishing-source-for-github-pages). Your course website is now live!
1. Edit and create `.md` [Markdown files](https://guides.github.com/features/mastering-markdown/) to add more content pages.

Just the Class has been used by instructors at Stanford University ([CS 161](https://stanford-cs161.github.io/winter2021/)), UC Berkeley ([Data 100](https://ds100.org/fa21/)), UC Santa Barbara ([CSW8](https://ucsb-csw8.github.io/s22/)), Northeastern University ([CS4530/5500](https://neu-se.github.io/CS4530-CS5500-Spring-2021/)), and Carnegie Mellon University ([17-450/17-950](https://cmu-crafting-software.github.io/)). Share your course website and find more examples in the [show and tell discussion](https://github.com/kevinlin1/just-the-class/discussions/categories/show-and-tell)!

### Local development environment

Just the Class requires no special Jekyll plugins and can run on GitHub Pages' standard Jekyll compiler. To setup a local development environment, clone your template repository and follow the GitHub Docs on [Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll). -->

<!-- ############# -->

## Acknowledgements

This class borrows inspirations from several incredible sources. The project description is inspired by my colleague, Tim Oates. Some of the lecture slides' material will be adapted from Machine Learning course offered by Stanford.
<!-- The final project structure and accompanying instructions are inspired and adapted from my Ph.D. advisor, Jen Rexford's COS 561 class of Fall 2020 at Princeton and Nick McKeown's CS 244 class at Stanford. -->
<!-- The lecture slides' material is partially adapted from my colleagues, Tim Finin and Frank Ferraro's class at UMBC. -->

<!-- Programming assignment 1 is based on a similar assignment offered at Princeton by Nick Feamster. -->