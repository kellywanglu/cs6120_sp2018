# CS 6120/4120: Natural Language Processing

**Time and Location:** Tuesdays and Fridays from 3:25 pm - 5:05 pm in West Village H 108

**Instructor**: [Lu Wang](http://www.ccs.neu.edu/home/luwang/), Office 258 WVH

**Staff and Office Hours**: 

* Prof. Lu Wang, TBD, or by appointment, 258 WVH
* Liwen Hou (email: lhou@ccs.neu.edu), TBD, TBD
* Tirthraj Maheshkumar Parmar (email: parmar.t@husky.neu.edu), TBD, TBD
* Manthan Thakar (email: thakar.ma@husky.neu.edu), TBD, TBD

**Discussion Forum**: [Piazza](http://piazza.com/northeastern/sp2018/cs6120/home), sign up at [piazza.com/northeastern/sp2018/cs6120](http://piazza.com/northeastern/sp2018/cs6120)

_______
## Important Announcement
[1/6/2017] We will have a quiz with 24 **simple** questions, 20 of them as True or False questions (relevant to probability, statistics, and linear algebra) in the second lecture (1/11/2018). This quiz will be graded, but will not be counted in your final score if you're enrolled in CS6120/CS4120. The purpose of this quiz is to indicate the expected background of students. 80% of the questions should be easy to answer. If you find yourself struggling with this quiz, it's possible that you need to catch up on the background or it may be preferable to take one or two preliminary courses. For students previously do not take any algorithm course (CS 5800 or CS 7800, see Prerequisites), an 80% or above is required to enroll in this course.

_______
## Course Description (and Syllabus)
This course aims to introduce fundamental tasks in natural language processing, and its recent advances based on machine learning algorithms (e.g., neural networks) and applications for interdisciplinary subjects (e.g., computational social science). The course materials are mostly delivered as lectures, and accompanied with reading materials. The students will be evaluated based on assignments, a **research-driven** course project, and an open-book final exam.

#### Textbooks and Reference
* Main Textbook:
 * Dan Jurafsky and James H. Martin, "Speech and Language Processing, 2nd Edition", Prentice Hall, 2009.
 * Third edition draft is available at [web.stanford.edu/~jurafsky/slp3/](http://web.stanford.edu/~jurafsky/slp3/).
 
* Other Reference: 
 * Chris Manning and Hinrich Schutze, "Foundations of Statistical Natural Language Processing", MIT Press, 1999
 
* Since many natural language processing problems are driven by machine learning techniques nowadays, we also highly encourage you to read machine learning textbooks:
 * Christopher M. Bishop, "Pattern Recognition and Machine Learning", Springer, 2006.
 * Tom Mitchell, "Machine Learning", McGraw Hill, 1997.
 
#### Prerequisites
This course is designed for graduate students and senior undergraduate students majoring in computer science, linguistics, and other related areas. Students who take this course are expected to be able to write code in some programming languages (e.g., Python, Java, or C/C++) proficiently, and finish courses in algorithms (CS 5800 or CS 7800), multivariable calculus, probability, and statistics. Linear algebra is optional, but highly recommended.

_______
## Grading
Each assignment or report, both electronic copy and hard copy, is due at the beginning of class on the corresponding due date. Blackboard is used for electronic submission. Hard copies are submitted in class. Assignment or report turned in late will be charged 20 points (out of 100 points) off for each late day (i.e. 24 hours). Each student has a budget of 5 days throughout the semester before a late penalty is applied. You may want to use it wisely, e.g. save for emergencies. Each 24 hours or part thereof that a submission is late uses up one full late day. Late days are not applicable to final presentation. Each group member is charged with the same number of late days, if any, for their submission.

Grades will be determined based on three assignments, ten in-class tests, one course project, one open-book exam, and participation:

* Assignments (30%): two assignments, each of 15%
* Quiz (5%): eight quick in-class tests (taken place at the beginning of Tuesday lectures), each of 1%; three with lowest grades will be dropped, and no make-up
* Project (25%): team of 2 to 3 students, proposal (3%), reports (7%+10%), final presentation (5%, with 2% as bonus if selected as best project by peer students, and 1% as bonus for runner-up)
* Exam (35%): open-book
* Participation (5%): classes (participating in-class discussions, etc), Piazza (answering questions, sharing notes, etc)
 
_______
## Schedule
#### Jan 9 & 12
* Topic: Introduction, Language Models
* Slides: [[intro]](cs6120_sp2018/slides_cs6120_sp18/introduction.pdf) [[6pp version]](cs6120_sp2018/slides_cs6120_sp18/introduction_6pp.pdf) [[Language Model]](slides_cs6120_sp18/lm.pdf) [[6pp version]](cs6120_sp2018/slides_cs6120_sp18/lm_6pp.pdf)
* Reading: Ch1, Ch4.1-4.9 
* TODO: start thinking about projects and looking for teammates

#### Jan 16 & 19
* Topic: Text Categorization, Naive Bayes, Part-of-Speech Tagging, Sequence Labeling, Hidden Markov Models
* Reading: Ch5, Ch6.1-6.5, and [http://web.stanford.edu/~jurafsky/slp3/6.pdf](http://web.stanford.edu/~jurafsky/slp3/6.pdf) from 3rd edition

#### Jan 23 & 26
* Topic: Word Sense Disambiguation
* Reading: Ch19-20


#### Jan 30 & Feb 2
* Topic: HMM cont'd, Machine Learning Basics (Maximum Entropy, Feedforward Neural Networks)
* Reading: Ch6.6, Ch12.1-12.5
* Course project proposal due on Jan 30.


#### Feb 6 & 9
* Topic: Formal Grammars of English, Syntactic Parsing, Dependency Parsing
* Reading: Ch12.1-12.5, Ch13.1-13.4.1
* Assignment 1 is due on Feb 6.


#### Feb 13 & 16
* Topic: Vector-Space Lexical Semantics, Semantic Parsing, Combining Logical and Distributional Semantics
* Reading: Ch20.7, and [http://web.stanford.edu/~jurafsky/slp3/15.pdf](http://web.stanford.edu/~jurafsky/slp3/15.pdf), [http://web.stanford.edu/~jurafsky/slp3/16.pdf](http://web.stanford.edu/~jurafsky/slp3/16.pdf)


#### Feb 20 & 23
* Topic: Semantics cont'd, Information Extraction
* Reading: Ch22.1-22.2


#### Feb 27 & Mar 2
* Topic: Question Answering, Text Summarization
* Reading: Ch23


#### Mar 6 & 9 (Spring Break)

#### Mar 13 & 16
* Topic: Sentiment Analysis, Opinion Mining, NLP and Social Media
* Reading: [http://web.stanford.edu/~jurafsky/slp3/6.pdf](http://web.stanford.edu/~jurafsky/slp3/6.pdf), [http://web.stanford.edu/~jurafsky/slp3/18.pdf](http://web.stanford.edu/~jurafsky/slp3/18.pdf)
* Assignment 2 is due on Mar 13.

#### Mar 20 & 23
* Topic: Sentiment Analysis, Opinion Mining, NLP and Social Media
* Reading: [http://web.stanford.edu/~jurafsky/slp3/6.pdf](http://web.stanford.edu/~jurafsky/slp3/6.pdf), [http://web.stanford.edu/~jurafsky/slp3/18.pdf](http://web.stanford.edu/~jurafsky/slp3/18.pdf)
* Coure project progress report due on Mar 20


#### Mar 27 & 30
* Topic: Dialog Systems and Chatbots
* Reading: Ch24, or [http://web.stanford.edu/~jurafsky/slp3/29.pdf](http://web.stanford.edu/~jurafsky/slp3/29.pdf)



#### April 3 & 6 & 10
* Topic: Course Project Presentation
* Project final report due on April 17 (tentatively).


_______
## Academic Integrity 
This course follows the [Northeastern University Academic Integrity Policy](http://www.northeastern.edu/osccr/academic-integrity-policy/). All students in this course are expected to abide by the Academic Integrity Policy. Any work submitted by a student in this course for academic credit should be the student's own work. Collaborations are allowed only if explicitly permitted. Violations of the rules (e.g. cheating, fabrication, plagiarism) will be reported.
