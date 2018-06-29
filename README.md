# Acamedics
Shiny or similar development for AcaMedics

## Path to Data Science (Short Version)
Below is a comprehensive path to learning data science, focussed around the R statistical computer language. We choose R because its powerful, free and has a thriving online community. We've tried a lot of different things and have listed what we feel were of most use. Everyone is different, so if you found something particularly useful, let us know so we can add it to the list.

There is no shortcut to advancing in this field. Find a project, something that you feel passionate about, and get stuck in; learn by doing. A fantastic reasource to start is the tidyverse and R for data science, availible for free online here: http://r4ds.had.co.nz

# Skill development (The Long Version)
Below is a list of some areas that are important to develop on your journey into data science. These are aimed at someone who is interested and motivated, but from a clinical background, and so not formally trained in these methods. I have inlcuded links to amazon for books, but mostly just for reference. Ask for a link to a shared dropbox folder for electronic materials for the majority of them, plenty of others are published online for free. We also keep other copies in the lab which we are happy for you to borrow (please ask first).

## Maths
- The foundation of data science is rooted in probability and statistics. As clinicians this can be extremely limiting in the long run as we typically have at most an A-level in maths (often from a very long time ago). Key areas to focus on are:
  - Calculus
  - Probability
  - Linear algebra
  - Set theory and statistical notation
- Once you have these basic tools, you will have the basic skills to understand the language of statistics and make the most out of your data (... and get away from hypothesis testing!). All that is needed here is a conceptual overview of how these things work.

The following resources are extremely useful:
- Harvard Stat 110 (https://www.youtube.com/watch?v=KbB0FjPg0mw&list=PL2SOU6wwxB0uwwH80KTQ6ht66KWxbzTIo)
  - The stategic practice is availible here (https://projects.iq.harvard.edu/stat110/home)
- Introduction to Probability (https://www.amazon.co.uk/Introduction-Probability-Chapman-Statistical-Science-ebook/dp/B00MMOJ19I/ref=sr_1_3?ie=UTF8&qid=1516904017&sr=8-3&keywords=introduction+to+probability) the companion text book to the above course
- Khan academy (www.khanacademy.com)
- 3Blue1Brown (https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw)

Other resources for statistics:
- Discovering statistics using R; Field. A good high level overview with practical applicatons in R.
- Statistical rethinking (https://www.amazon.co.uk/Statistical-Rethinking-Bayesian-Examples-Chapman/dp/1482253445/ref=sr_1_1?ie=UTF8&qid=1516907232&sr=8-1&keywords=statistical+rethinking). This book is a full course in bayesian statistics. It takes a narrative approach, and goes easy on the maths. You'll get a lot more out of it if you have covered the STAT110 course first.

### Online Courses
There has been an explosion in the availibility of online courses. They vary from free to expensive, and their quality is often not related to cost. Here we compile a list of the best:

|             Name            |           Subject           |                                   Website                                   | Cost | Rating      |
|:---------------------------:|:---------------------------:|:---------------------------------------------------------------------------:|:----:|-------------|
|   Essence of Linear Algebra |              Linear Algebra |          https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw/playlists | Free | 5/5         |
| The World of Maths          | General Maths at all levels | www.khanacademy.com                                                         | Free | 5/5         |
| Machine Learning - Coursera | ML                          | https://www.coursera.org/learn/machine-learning                             | £58  | Recommended |
| Maths for Machine Learning  | Linear Algebra              | https://www.coursera.org/learn/linear-algebra-machine-learning/home/welcome | £48  | 4/5         |


## R
- Datacamp.com is an excellent resource that uses gamification for learning the basics of R. Beyond learning how R works, it's use can be rather limited as it teaches a fairly shallow understanding of the topic. After you have got to grips with the basics, move away and start to get hands on with your own project
- Learn tidy data practices here https://www.tidyverse.org/
- R for data science http://r4ds.had.co.nz/
- Advanced R (https://www.amazon.co.uk/Advanced-Chapman-Hall-Hadley-Wickham/dp/1466586966/ref=sr_1_1?s=books&ie=UTF8&qid=1516907344&sr=1-1&keywords=advanced+R). Really excellent book by Hadley Wickham (a don in the R universe). Great to help push your programming to the next level.
- Data Science for Doctors: This is a shameless plug for our own course that we run at the RCoA every few months. It provides a comprehensive introduction to R for the uninitiated.

## Python
- We need some recommendations here

## UNIX and VIM
- vim adventures (www.vimadventures.com) is a brilliant way to learn your way around vim (a unix based text editor).
- William E. Shotts has written an ebook on unix which is open source and a great overview of how unix works http://linuxcommand.org/tlcl.php

## Causal Inference

Building upon the foundations of maths and R skills gained above, consider delving deeper into learning about causal inference techniques:

### Online material

- A Crash Course in Causality (https://www.coursera.org/learn/crash-course-in-causality): this Coursera course is extremely good and clear, with conceptual introductions and examples in R. Well worth £37 to do the course with certificate, or free if you don't want a certificate (but pay the money, it'll force you to do the course and it's extremely good).
- Causal Inference Bootcamp (https://www.youtube.com/watch?v=FNpcwiOme1g&list=PL1M5TsfDV6Vufqfs_h5fDR3pBhIj4QOW7): YouTube channel with quick videos and clear explanations.

### Directed Acyclic Graphs (DAGs)

DAGs are graphical representations of relationships between variables, where each node represents a variable, and each vertex represents the direction of the relationship. DAGs allow us to communicate our assumptions about a model to the reader and importantly help us to specify our models. Learn about and draw DAGs online here: http://www.dagitty.net/

### Books

The following 2 books gives a good introduction to Propensity Score methods. 

- Propensity Score Analysis: Statistical Methods and Applications (Advanced Quantitative Techniques in the Social Sciences) by Shenyang Y. Guo and Mark W. Fraser (https://www.amazon.co.uk/Propensity-Score-Analysis-Applications-Quantitative/dp/1412953561)
- Design of Observational Studies (Springer Series in Statistics) by Paul R. Rosenbaum (https://www.amazon.co.uk/Design-Observational-Studies-Springer-Statistics/dp/1441912126/ref=sr_1_1?s=books&ie=UTF8&qid=1530278645&sr=1-1&keywords=design+of+observational+studies): This book is very readable, uses few mathematical formulae. The author writes in his introduction that he set out to write this book to use prose to explain the mathematics rather than to use mathetmatics to explain the concepts.

The following book(s) gives an introduction to Instrumental Variable Analysis

- Mostly Harmless Econometrics: An Empiricist's Companion Paperback by Joshua D. Angrist and Jörn-Steffen Pischke (https://www.amazon.co.uk/Mostly-Harmless-Econometrics-Empiricists-Companion/dp/0691120358/ref=sr_1_1?s=books&ie=UTF8&qid=1530278837&sr=1-1&keywords=mostly+harmless+econometrics)

## Lab Meetings
- We meet every Monday morning to discuss ongoing projects. Everyone is welcome to attend and watch or present. No matter the size, scale or complexity, we would encourge you to present any work as a way to crowd source solutions to problems and figure out what the next step might be.
