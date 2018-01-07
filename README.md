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
## Course Description
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
* Quiz (5%): eight quick in-class tests (taken place at the beginning of lecture), each of 1%; three with lowest grades will be dropped, and no make-up
* Project (25%): team of 2 to 3 students, proposal (3%), reports (7%+10%), final presentation (5%, with 2% as bonus if selected as best project by peer students, and 1% as bonus for runner-up)
* Exam (35%): open-book
* Participation (5%): classes (participating in-class discussions, etc), Piazza (answering questions, sharing notes, etc)
 
_______
## Schedule
#### Sep 11
* Topic: Introduction, Language Models
* Slides: [[intro]](cs6120_sp201/slides_cs6120_fa17/introduction.pdf) [[6pp version]](slides_cs6120_fa17/introduction_6pp.pdf) [[Language Model]](slides_cs6120_fa17/lm.pdf) [[6pp version]](slides_cs6120_fa17/lm_6pp.pdf)
* Reading: Ch1, Ch4.1-4.9 
* TODO: start thinking about projects and looking for teammates

#### Sep 18
* Topic: Text Categorization, Naive Bayes, Part-of-Speech Tagging, Sequence Labeling, Hidden Markov Models
* Slides: [[NB]](slides_cs6120_fa17/nb.pdf) [[6pp version]](slides_cs6120_fa17/nb_6pp.pdf) [[POS]](slides_cs6120_fa17/postag.pdf) [[6pp version]](slides_cs6120_fa17/postag_6pp.pdf)
* Reading: Ch5, Ch6.1-6.5, and [http://web.stanford.edu/~jurafsky/slp3/6.pdf](http://web.stanford.edu/~jurafsky/slp3/6.pdf) from 3rd edition
* TODO: Assignment 1 is released. [[A1]](material_cs6120_fa17/a1.pdf) [[A1 datasets]](material_cs6120_fa17/a1_datasets.zip)

#### Sep 25
* Topic: Word Sense Disambiguation
* Slides: [[WSD]](slides_cs6120_fa17/wsd.pdf) [[6pp version]](slides_cs6120_fa17/wsd_6pp.pdf)
* Reading: Ch19-20



#### Oct 2
* Topic: HMM cont'd, Machine Learning Basics (Maximum Entropy, Feedforward Neural Networks)
* Slides: [[MLBasics]](slides_cs6120_fa17/mlbasics.pdf) [[6pp version]](slides_cs6120_fa17/mlbasics_6pp.pdf) 
* Reading: Ch6.6, Ch12.1-12.5
* Course project proposal due



#### Oct 9 (NO CLASS: Columbus Day)
* TODO: Assignment 2 is released. [[A2]](material_cs6120_fa17/a2.pdf) [[A2 datasets]](material_cs6120_fa17/hw2-sa-ds.zip)
* Assignment 1 is due.


#### Oct 16
* Topic: Formal Grammars of English, Syntactic Parsing, Dependency Parsing
* Slides: [[Parsing Part1]](slides_cs6120_fa17/parsing_part1.pdf) [[6pp version]](slides_cs6120_fa17/parsing_part1_6pp.pdf) [[Parsing Part2]](slides_cs6120_fa17/parsing_part2.pdf) [[6pp version]](slides_cs6120_fa17/parsing_part2_6pp.pdf) 
* Reading: Ch12.1-12.5, Ch13.1-13.4.1


#### Oct 23
* Topic: Vector-Space Lexical Semantics, Semantic Parsing, Combining Logical and Distributional Semantics
* Slides: [[Semantics Part1]](slides_cs6120_fa17/semantics_part1.pdf) [[6pp version]](slides_cs6120_fa17/semantics_part1_6pp.pdf)
* Reading: Ch20.7, and [http://web.stanford.edu/~jurafsky/slp3/15.pdf](http://web.stanford.edu/~jurafsky/slp3/15.pdf), [http://web.stanford.edu/~jurafsky/slp3/16.pdf](http://web.stanford.edu/~jurafsky/slp3/16.pdf)
* Coure project progress report due on Oct 26

#### Oct 30
* Topic: Semantics cont'd, Information Extraction
* Slides: [[Semantics Part2]](slides_cs6120_fa17/semantics_part2.pdf) [[6pp version]](slides_cs6120_fa17/semantics_part2_6pp.pdf) [[Information Extraction]](slides_cs6120_fa17/ie.pdf) [[6pp version]](slides_cs6120_fa17/ie_6pp.pdf)
* Reading: Ch22.1-22.2
* TODO: Assignment 3 is released. [[A3]](material_cs6120_fa17/a3.pdf) 
* Assignment 2 is due.

#### Nov 6
* Topic: Question Answering, Text Summarization
* Slides: [[QA]](slides_cs6120_fa17/qa.pdf) [[6pp version]](slides_cs6120_fa17/qa_6pp.pdf) [[summarization]](slides_cs6120_fa17/summarization.pdf) [[6pp version]](slides_cs6120_fa17/summarization_6pp.pdf) [[Presentation and Exam]](slides_cs6120_fa17/guideline.pdf)
* Reading: Ch23



#### Nov 13
* Topic: Sentiment Analysis, Opinion Mining, NLP and Social Media
* Slides: [[sentiment and affective language]](slides_cs6120_fa17/sentiment.pdf) [[6pp version]](slides_cs6120_fa17/sentiment_6pp.pdf) 
* Reading: [http://web.stanford.edu/~jurafsky/slp3/6.pdf](http://web.stanford.edu/~jurafsky/slp3/6.pdf), [http://web.stanford.edu/~jurafsky/slp3/18.pdf](http://web.stanford.edu/~jurafsky/slp3/18.pdf)


#### Nov 20
* Topic: Dialog Systems and Chatbots
* Slides: [[dialogue]](slides_cs6120_fa17/dialogue.pdf) [[6pp version]](slides_cs6120_fa17/dialogue_6pp.pdf) 
* Reading: Ch24, or [http://web.stanford.edu/~jurafsky/slp3/29.pdf](http://web.stanford.edu/~jurafsky/slp3/29.pdf)
* Assignment 3 is due.

#### Nov 27
* Topic: Course Project Presentation


#### Dec 4
* Topic: Exam
* Project final report due on Dec 11


_______
## Project Reports
* [Neural Semantic Parsing Natural Language into SQL](reports_cs6120_fa17/1.pdf)
* [Short Passages Reading Comprehension and Question Answering](reports_cs6120_fa17/2.pdf)
* [Political Promise Evaluation (PPE)](reports_cs6120_fa17/4.pdf)
* [Predicting Personality Traits using Tweets](reports_cs6120_fa17/5.pdf)
* [STORY NEXT 2.0: A TEXT INSIGHTS/VISUALIZATION TOOL](reports_cs6120_fa17/6.pdf)
* [Android Application for Visual QA](reports_cs6120_fa17/7.pdf)
* [Novel Summarizer and Keyword Identifier Using Text Rank with Sentence Farm Detection](reports_cs6120_fa17/8.pdf)
* [Paraphrase Generation](reports_cs6120_fa17/9.pdf)
* [Hashtag Similarity based on Tweet Text](reports_cs6120_fa17/10.pdf)
* [Stance Detection for the Fake News Challenge](reports_cs6120_fa17/11.pdf)
* [Machine Comprehension Using match-LSTM and Answer-Pointer](reports_cs6120_fa17/12.pdf)
* [Online Abuse Detection](reports_cs6120_fa17/13.pdf)
* [Plagiarism Detection Using FP-Growth Algorithm](reports_cs6120_fa17/14.pdf)
* [An Examination of Influential Framing of Controversial Topics on Twitter](reports_cs6120_fa17/15.pdf)




_______
## Academic Integrity 
This course follows the [Northeastern University Academic Integrity Policy](http://www.northeastern.edu/osccr/academic-integrity-policy/). All students in this course are expected to abide by the Academic Integrity Policy. Any work submitted by a student in this course for academic credit should be the student's own work. Collaborations are allowed only if explicitly permitted. Violations of the rules (e.g. cheating, fabrication, plagiarism) will be reported.

