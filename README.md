# CS 6120/4120: Natural Language Processing

**Time and Location:** Tuesdays and Fridays from 3:25 pm - 5:05 pm in West Village H 108

**Instructor**: [Lu Wang](http://www.ccs.neu.edu/home/luwang/), Office 258 WVH

**Staff and Office Hours**: 

* Prof. Lu Wang, Tuesdays 5:15 - 6:15pm, or by appointment, 258 WVH
* Liwen Hou (email: lhou@ccs.neu.edu), Fridays 2:00 - 3:00 pm, or by appointment, 462 WVH
* Tirthraj Maheshkumar Parmar (email: parmar.t@husky.neu.edu), Wednesdays 4:00 - 5:00 pm, or by appointment, 462 WVH
* Manthan Thakar (email: thakar.ma@husky.neu.edu), Mondays 1:00 - 2:00 pm, or by appointment, 462 WVH

**Discussion Forum**: [Piazza](http://piazza.com/northeastern/sp2018/cs6120/home), sign up at [piazza.com/northeastern/sp2018/cs6120](http://piazza.com/northeastern/sp2018/cs6120)

_______
## Important Announcement
[2/3/2018] We will use Feb 20 lecture and office hour to give feedback on your course projects! Prepare ahead with questions!

[2/3/2018] Please notice the quiz schedule! 

[1/6/2017] We will have a quiz with 20 **simple** True or False questions (relevant to probability, statistics, and linear algebra) in the second lecture (1/11/2018). This quiz will be graded, but will not be counted in your final score if you're enrolled in CS6120/CS4120. The purpose of this quiz is to indicate the expected background of students. 80% of the questions should be easy to answer. If you find yourself struggling with this quiz, it's possible that you need to catch up on the background or it may be preferable to take one or two preliminary courses. For students previously do not take any algorithm course (CS 5800 or CS 7800, see Prerequisites), an 80% or above is required to enroll in this course.

_______
## Course Description (and Syllabus)
This course aims to introduce fundamental tasks in natural language processing, and its recent advances based on machine learning algorithms (e.g., neural networks) and applications for interdisciplinary subjects (e.g., computational social science). The course materials are mostly delivered as lectures, and accompanied with reading materials. The students will be evaluated based on assignments, a **research-driven** course project, and an open-book final exam.

Please find the syllabus here: [[Link]](material_cs6120_sp18/cs6120_syllabus.pdf)

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
* Project (25%): team of 2 to 3 students, proposal (3%), reports (7%+10%), final presentation (5%, with 1% as bonus if selected as best project by peer students)
* Exam (35%): open-book
* Participation (5%): classes (participating in-class discussions, etc), Piazza (answering questions, sharing notes, etc)


 #### Assignments
 * [[Assignment 1]](material_cs6120_sp18/a1.pdf)
 * [[Assignment 2]](material_cs6120_sp18/a2.pdf)
 
 #### Sample Writeups for Project
 * [[Project Proposal]](material_cs6120_sp18/project_proposal.pdf)
 * [[Project Progress Report]](material_cs6120_sp18/project_progress.pdf)
 * [[Project Final Report]](material_cs6120_sp18/project_report.pdf)
 * Sample projects from Stanford NLP course [[link]](http://web.stanford.edu/class/cs224n/reports.html)
 
 
 
_______
## Schedule
#### Jan 9 & 12
* Topic: Introduction, Language Models
* Slides: [[intro]](slides_cs6120_sp18/introduction.pdf) [[6pp version]](slides_cs6120_sp18/introduction_6pp.pdf) [[Language Model]](slides_cs6120_sp18/lm.pdf) [[6pp version]](slides_cs6120_sp18/lm_6pp.pdf)
* Reading: Ch1, Ch4.1-4.9 
* TODO: start thinking about projects and looking for teammates

#### Jan 16 (quiz) & 19
* Topic: LM cont'd, Text Categorization and Evaluation, Naive Bayes, Part-of-Speech Tagging, Sequence Labeling, Hidden Markov Models
* Slides: [[Text Categorization]](slides_cs6120_sp18/nb.pdf) [[6pp version]](slides_cs6120_sp18/nb_6pp.pdf) [[POS Tagging]](slides_cs6120_sp18/postag.pdf) [[6pp version]](slides_cs6120_sp18/postag_6pp.pdf)
* Reading: Ch5, Ch6.1-6.5, and [http://web.stanford.edu/~jurafsky/slp3/6.pdf](http://web.stanford.edu/~jurafsky/slp3/6.pdf) from 3rd edition

#### Jan 23 (quiz) & 26
* Topic: HMM cont'd, Word Sense Disambiguation
* Slides: [[WSD]](slides_cs6120_sp18/wsd.pdf) [[6pp version]](slides_cs6120_sp18/wsd_6pp.pdf) 
* Reading: Ch19-20, and [http://web.stanford.edu/~jurafsky/slp3/17.pdf](http://web.stanford.edu/~jurafsky/slp3/17.pdf) 


#### Jan 30 (quiz) & Feb 2
* Topic: Machine Learning Basics (Maximum Entropy, Feedforward Neural Networks), Formal Grammars of English, Syntactic Parsing
* Slides: [[ML]](slides_cs6120_sp18/mlbasics.pdf) [[6pp version]](slides_cs6120_sp18/mlbasics_6pp.pdf) [[parsing]](slides_cs6120_sp18/parsing.pdf) [[6pp version]](slides_cs6120_sp18/parsing_6pp.pdf) 
* Reading: Ch6.6, Ch12.1-12.5
* Course project proposal due on Jan 30.


#### Feb 6 & 9 (quiz)
* Topic:  Parsing cont'd, Dependency Parsing, Semantics
* Slides: [[parsing part2]](slides_cs6120_sp18/parsing_part2.pdf) [[6pp version]](slides_cs6120_sp18/parsing_part2_6pp.pdf) [[semantics part1]](slides_cs6120_sp18/semantics_part1.pdf) [[6pp version]](slides_cs6120_sp18/semantics_part1_6pp.pdf)
* Reading: Ch12.1-12.5, Ch13.1-13.4.1
* Assignment 1 is due on Feb 6.


#### Feb 13 (quiz) & 16
* Topic: Vector-Space Lexical Semantics, Semantic Parsing, Combining Logical and Distributional Semantics
* Slides: [[semantics part2]](slides_cs6120_sp18/semantics_part2.pdf) [[6pp version]](slides_cs6120_sp18/semantics_part2_6pp.pdf) [[semantics part3]](slides_cs6120_sp18/semantics_part3.pdf) [[6pp version]](slides_cs6120_sp18/semantics_part3_6pp.pdf)
* Reading: Ch20.7, and [http://web.stanford.edu/~jurafsky/slp3/15.pdf](http://web.stanford.edu/~jurafsky/slp3/15.pdf), [http://web.stanford.edu/~jurafsky/slp3/16.pdf](http://web.stanford.edu/~jurafsky/slp3/16.pdf)


#### Feb 20 & 23 (quiz)
* We will use Feb 20 lecture and office hour to give feedback on course projects! Plan ahead with your questions!
* Topic: Information Extraction
* Slides: [[IE]](slides_cs6120_sp18/ie.pdf) [[6pp version]](slides_cs6120_sp18/ie_6pp.pdf)
* Reading: Ch22.1-22.2


#### Feb 27 (quiz) 
* Topic: Question Answering
* Reading: Ch23


#### Mar 2 (No class: the day before spring break)

#### Mar 6 & 9 (No class: spring break)

#### Mar 13 & 16 (quiz)
* Topic: Text Summarization, Sentiment Analysis, Recurrent Neural Networks
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

