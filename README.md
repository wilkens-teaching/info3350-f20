# Information Science 3350/6350

## Text mining for history and literature

### Staff and sections

**Instructor:** [Matthew Wilkens](https://infosci.cornell.edu/content/Wilkens)\
**Graduate TA:** [Maria Antoniak](https://infosci.cornell.edu/content/antoniak)\
**Undergrad TAs:** Jannie Li, Haley Mathews, and LeAnn McDowall

**Term:** Fall 2020\
**Mode:** Online lectures with choice of online or in-person discussion sections.\
**Credits:** 3\
**Lecture:** Online, MW 11:15-12:05\
**Sections:**: *In-person*: F 8:00-8:50am (section #202, Upson 102) and 9:10-10:00am (#201, Upson 202); *Online*: F 10:20-11:10am (#205) and 11:15am-12:05pm (x2, #203 and #204).\
**Office hours:** W 3-4pm and F 3-5pm. For details, see [Canvas](https://canvas.cornell.edu/courses/20174/pages/zoom-and-other-links).\
**Online sessions and resources:** See the **Mechanics** section below.

### Waitlist

If the course is full at registration time, you may add yourself to the [waitlist](https://forms.gle/7esiHeBvK6sDwHrV9). If and when you have been admitted, you will receive a PIN that will allow you to complete registration.

### Summary

A course on the uses of text mining and other data-intensive techniques to assist analysis of textual humanities materials. Special emphasis on literary and historical documents. Intended for students with programming experience equivalent to CS 1110 (Intro to computing using Python).

### Description

Broadly speaking, the course covers text mining, content analysis, and basic machine learning, emphasizing approaches with demonstrated value in literary studies and other humanistic fields. Students will learn how to clean and process textual corpora, extract information from unstructured texts, identify relevant textual and extra-textual features, assess document similarity, cluster and classify authors and texts using a variety of machine-learning methods, visualize the outputs of statistical models, and incorporate quantitative evidence into literary and humanistic analysis. The course will also introduce some of the more interesting recently published results in computational and quantitative humanities. 

Most of the methods treated in the class are relevant in multiple fields. Students from all majors are welcome. Students with backgrounds in the humanities are especially encouraged to join.

### Objectives and learning goals

The primary objective of the course is to build proficiency in text analysis and data mining for the humanities. Students who complete the course will have knowledge of standard approaches to text analysis and will be familiar with the humanistic ends to which those approaches might be put. Secondary objectives include acquiring basic understanding of relevant literary history, of integrating quantitative with qualitative evidence, and of best practices in small-scale project management. 

### Mechanics

We will use Zoom for online meetings, Canvas to distribute restricted readings and to collect reading response posts, CMS to collect problem sets and other code work, and Campuswire for Q&A. Links and detailed info about each of these are available via the [course Canvas site](https://canvas.cornell.edu/courses/20174).

### Work and grading

Grades will be based on weekly problem sets (50% in sum), a midterm mini-project (10%), reading responses (10% in sum, see Canvas for details), a take-home final exam or optional final project (20%), and class participation (10%). *You must achieve a passing grade in each of these components to pass the course.*

**Graduate students** (enrolled in 6350) must complete a final project in place of the final exam and are strongly encouraged to attend an additional weekly section meeting for 6350 (to be scheduled according to our shared availability once classes begin).

### Texts and readings

**There is no required textbook for the course.** All assigned readings will be available online, either through the open web or via Canvas. See the **Schedule** below for details.

There are three texbooks that may be useful for students who wish to consult them. **They are not required and most students will not need them.**

* Guttag. [*Introduction to Computation and Programming Using Python (2nd ed.)*](https://www.amazon.com/dp/0262529629/). Useful for students who need or want a refresher on basic concepts in Python.
* Bengfort, Bilbro, and Ojeda. [*Applied Text Analysis with Python*](https://www.amazon.com/dp/1491963042). A *very* applied book intended for working developers who want to learn the standard Python stack for text analysis.
* Jurafsky and Martin. [*Speech and Language Processing (3rd ed.)*](https://web.stanford.edu/~jurafsky/slp3/). A detailed textbook focusing on many of the core topics in natural language processing. Probably more advanced than most students will require, but a great resource for those who want more technical depth. The linked version is the openly available draft of the third edition. The published [second edition is also available for sale](https://www.amazon.com/dp/0131873210).

### Schedule

In general, Monday lectures will introduce new technical material. Wednesday sessions will combine technical instruction with discussion of assigned readings from the scholarly literature. Friday sections are smaller and devoted to focused work on problem sets and to follow-up questions about topics previously introduced.

**All assignments and dates are subject to change.** Additional readings are likely to be added after week 7.

**Course materials and problem sets** will be linked here as they become available. *Problem sets will be distributed no later than the Friday indicated on the syllabus and are due the following Tuesday evening unless otherwise indicated.*

| Week | Monday | Wednesday | Friday|
|:---|:---|:---|:---|
| 1 (8/31) | **No class** | Introduction | Setup and dummy problem set |
| 2 (9/7) | **Tokenization and counting.**<br/>Reading: [Sentiment-aware tokenization](http://sentiment.christopherpotts.net/tokenizing.html)<br />Optional: Jurafsky and Martin, ["Lexicons for Sentiment, Affect, and Connotation"](https://web.stanford.edu/~jurafsky/slp3/21.pdf) | Readings:<ul><li>Ramsay, "Algorthmic Criticism" (Canvas)</li><li>Healy, ["Fuck Nuance"](https://kieranhealy.org/files/papers/fuck-nuance.pdf)</li><li>Rambsy, [#TheJayZMixtape](https://iopn.library.illinois.edu/scalar/the-jay-z-mixtape/index)</li></ul> | Problem set: Word clouds |
| 3 (9/14) | **Sentiment scoring.**<br />Reading: [Syuzhet package](https://cran.r-project.org/web/packages/syuzhet/vignettes/syuzhet-vignette.html) | Readings:<ul><li>Reagan et al., ["Emotional Arcs of Stories ..."](https://epjdatascience.springeropen.com/articles/10.1140/epjds/s13688-016-0093-1)</li><li>Davis, ["Physical Traits that Define Men and Women in Literature"](https://pudding.cool/2020/07/gendered-descriptions/)</li></ul> | Problem set: Sentiment and gender |
| 4 (9/21) | **Vectorization, distance metrics, and regression.**<br />Readings: <ul><li>[Five popular similarity metrics](https://dataaspirant.com/five-most-popular-similarity-measures-implementation-in-python/)</li><li>[Introduction to regression](https://dss.princeton.edu/online_help/analysis/regression_intro.htm)</li></ul>| Readings:<ul><li>Moretti, "Slaughterhouse of Literature" (Canvas)</li><li>Evert et al., "Understanding and Explaining Delta Measures" (Canvas)</li></ul>**Response 1 due** no later than this session. | Problem set: Document similarity|
| 5 (9/28)| **Clustering.**<br />Reading: Grimmer and Stewart, ["Text as Data"](https://doi.org/10.1093/pan/mps028)| Reading: Allison et al., ["Quantitative Formalism"](https://litlab.stanford.edu/LiteraryLabPamphlet1.pdf)| Problem set: Clustering with `scikit-learn`|
| 6 (10/5)| **Classification I.**<br />Reading: Underwood, ["Understanding Genre in a Collection of a Million Volumes"](https://doi.org/10.6084/m9.figshare.1281251.v1)| Readings:<ul><li>Mauch et al., ["The Evolution of Popular Music"](http://rsos.royalsocietypublishing.org/content/2/5/150081)</li><li>Norvig, ["Chomsky and the Two Cultures of Statistical Learning"](http://www.norvig.com/chomsky.html)</li></ul>**Response 2 due** no later than this session.| Mini-project: Classifying novels|
| 7 (10/12) | **Classification II,** including regularization and dimension reduction.| **No class** (fall break) | Mini-project: Classifying novels (continued)|
| 8 (10/19) | **Feature importance and explainability.**<br />| Reading: Piper, "Characterization" (Canvas)| Mini-project: Classifying novels (continued)|
| 9 (10/26)| **Hypothesis testing and confidence intervals.**<br />| Reading: TBA| Problem set: Statistical testing|
| 10 (11/2)| **NLP and feature expansion.**<br />| Reading: Evans and Wilkens, ["Nation, Ethnicity, and the Geography of British Fiction"](https://culturalanalytics.org/article/11037-nation-ethnicity-and-the-geography-of-british-fiction-1880-1940)| Problem set: Extended features|
| 11 (11/9) | **Topic models.**<br />Reading: Boyd-Graber, Hu, and Mimno, [*Applications of Topic Models*](https://mimno.infosci.cornell.edu/papers/2017_fntir_tm_applications.pdf), chapters 1, 4, and 6. | Reading: Barron et al., ["Individuals, Institutions, and Innovation in the Debates of the French Revolution"](https://www.pnas.org/content/115/18/4607)<br />**Response 3 due** no later than this session. | Open discussion, no new assignments|
| 12 (11/16)|**No classes this week (semifinals).**|-----|-----|
| 13 (11/23)|**No classes this week (Thanksgiving).**|-----|-----|
| 14 (11/30)|**Word embeddings.**<br />Reading: [Ruder, "On Word Embeddings"](https://ruder.io/word-embeddings-1/index.html)|Reading: Nelson, "Leveraging the Alignment between Machine Learning and Intersectionality" (Canvas)| Problem set: Word embeddings|
| 15 (12/7)|**Deep learning.**<br />And/or matters arising.|Reading: To be determined by class interest.|Review and project work.|
| 16 (12/14)|**Wrap-up and flex time**|Summary discussion and conclusions.<br />**Response 4 due** no later than this dicussion.|**No class**|

### Policies

#### COVID information

This is an unusual semster. Our goal is to keep one another safe, to cover as much material as possible under the circumstances, and to adapt to the circumstances as we find them.

Students and staff will adhere to the [behavioral compact](https://covid.cornell.edu/students/behavioral-compact/) at all times. For in-person sections, you must remain in your assigned seat. If you do not have an assigned seat, *do not come to your in-person section*; instead, contact course staff for instructions on joining a remote section until you are cleared to return.

If you feel unwell in any way, or if you are not cleared through the daily check process, *do not come to your in-person section.*

*Participation* is much more important than mere *attendance*. Your grade will not suffer if you make the wise decision to stay home when you might infect others.

#### Harassment and respect

All students are entitled to respect from course staff and from their fellow students. All course staff are entitled to respect from students and from fellow staff members. Violations of this principle, whether large or small, will not be tolerated.

Respect means that your ideas are taken seriously, that you feel welcome in the classroom, and that are treated as a full, co-equal member of the class. Harassment describes any action, intentional or otherwise, that abridges the respect owed to every member of the class.

If you experience harassment in any form, or if you would like to discuss your experience in the class, please see me in office hours or contact me by email. The university also has reporting and counseling resources available, including those for [sexual harassment](https://gradschool.cornell.edu/policies/sexual-misconduct-including-harassment/) and for [other bias incidents](https://gradschool.cornell.edu/diversity-inclusion/reporting-bias/).

#### Academic integrity

Each student in this course is expected to abide by the Cornell University [Code of Academic Integrity](http://theuniversityfaculty.cornell.edu/academic-integrity/). Any work submitted by a student in this course for academic credit will be the student's own work unless specifically and explicitly permitted otherwise.

Using other people's code is an important part of programming but, for group projects, the code should be substantially the work of the group members (except for standard libraries). Any code used in projects that was not written by the group members should be placed in separate files and clearly labeled with their source
URLs. If you have benefitted from online resources such as examples or StackOverflow answers, list the URLs in comments in your own code, even if you did not directly copy anything.

Project work that relates to your other classes or research is encouraged, but you may not recycle assignments. There must be no doubt that the work you turn in for this class was done for this class. Whn in doubt, consult with me during office hours.

#### Disabilities

Every student's access is important to us. If you have, or think you may have, a disability, please contact Student Disability Services for a confidential discussion: [sds_cu@cornell.edu](mailto:sds_cu@cornell.edu), 607-254-4545, or [sds.cornell.edu](https://sds.cornell.edu/). 

* Please request your accommodation letter early in the semester, or as soon as you become registered with [Student Disability Services](https://sds.cornell.edu/) (SDS), so that we have adequate time to arrange your approved academic accommodations.
* Once SDS approves your accommodation letter, it will be emailed to you and to me. Please follow up with me to discuss the necessary logistics of your accommodations.
* If you are approved for exam accommodations, please consult with me at least two weeks before the scheduled exam date to confirm the testing arrangements.
* If you experience any access barriers in this course, such as with printed content, graphics, online materials, or any communication barriers, reach out to me and/or your SDS counselor right away.
* If you need an immediate accommodation, please speak with me after class or send an email message to me and to [SDS](mailto:sds_cu@cornell.edu).
