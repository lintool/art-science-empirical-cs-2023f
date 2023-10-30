# The Art and Science of Empirical Computer Science

⁉️ This is the course website for the **Fall 2023** edition of my course.
I previously taught the course in [Fall 2022](https://github.com/lintool/art-science-empirical-cs-2022f).
I will populate this website with content throughout the semester, but if you'd like to look ahead to see what's in store, you're welcome to consult the website from last year; content will be similar, but not identical.

## Logistics

+ **Semester**: Fall 2023
+ **Instructor**: [Jimmy Lin](https://cs.uwaterloo.ca/~jimmylin/)
+ **Time & Location**: Mondays 12:30pm-3:20pm, DC 2585

## Course Description

Graduate students in computer science aspire to "do computer science" (research), but what exactly does that mean?
It involves, among a multitude of activities, reading papers, learning the "state of the art", advancing knowledge, writing papers, and (hopefully) getting them published.
Graduate students learn how to do these things under tutelage of professors, but rarely is there explicit or deliberate instruction on these myriad activities.
With a focus on _empirical_ computer science, this course covers elements that comprise the research enterprise, synthesizing both "art" &mdash; personal experiences I have accumulated over the years &mdash; as well as "science" &mdash; insights derived from quantitative analyses.
The hope is that knowledge and actionable advice from this course will help graduate students better understand research, hopefully leading to more productive and fulfilling careers.

Material for this course will draw from ["The Science of Science"](https://www.dashunwang.com/book/the-science-of-science) by Wang and Barabási, academic papers, as well as other sources on the web.

## Scope

Context is important.
Most of the questions and issues we grapple with in this course have no simple answer.
Nearly always, it depends on context.
As such, it is important to properly scope the coverage of this course.

Wang and Barabási attempt to paint broad strokes with their work, encompassing all of science.
However, some of their findings and recommendations may seem at odds with realities in computer science.
Much of the "art" (e.g., advice, best practices, etc.) covered in this course is drawn from my personal experience, which will of course be colored by my own background.
I am a computer scientist (actually, also a formal linguist) by training, and I work presently at the intersection of natural language processing (NLP) and information retrieval (IR), although over the years I have dabbled in other sub-disciplines of computer science as well.

For lack of a better term, I characterize the focus of this course as "empirical computer science", but it really is a shorthand for "stuff that I have worked on" and "stuff that I am familiar with".
NLP and IR can be characterized as "applied machine learning", so perhaps that's a more accurate scope.
The contents of this course will certainly be relevant to graduate students wishing to pursue these topics, and I suspect for related sub-disciplines in computer science such as data mining, or even perhaps computer vision (although I don't work in those fields).
However, I am quite certain that portions of this course will _not_ apply to, for example, theoretical machine learning and complexity.
All findings, advice, recommendations, etc. need to be properly contextualized.

## Syllabus

| Week                                                | Date  | Type      | Description                            |        Debate         |          Slides          |
|:----------------------------------------------------|:------|:----------|:---------------------------------------|:---------------------:|:------------------------:|
| [1](#week-1-introduction)                           | 9/11  | -         | Introduction                           |                       | [PDF](slides/week01.pdf) |
| [2](#week-2-the-science-of-career)                  | 9/18  | "science" | The Science of Career                  | [Topic 1](debates.md) | [PDF](slides/week02.pdf) |
| [3](#week-3-the-science-of-collaboration-i)         | 9/25  | "science" | The Science of Collaboration (I)       | [Topic 2](debates.md) | [PDF](slides/week03.pdf) |
| [4](#week-4-the-science-of-collaboration-ii)        | 10/2  | "science" | The Science of Collaboration (II)      | [Topic 3](debates.md) | [PDF](slides/week04.pdf) |
| [5](#week-5-presentation-of-visualization-projects) | 10/16 | -         | Presentation of Visualization Projects |                       |                          |
| [6](#week-6-the-science-of-impact)                  | 10/23 | "science" | The Science of Impact                  | [Topic 4](debates.md) | [PDF](slides/week06.pdf) |
| [7](#week-7-research-as-a-social-process)           | 10/30 | "art"     | Research as a Social Process           |                       | [PDF](slides/week07.pdf) |
| [8](#week-8-on-working-with-your-advisor)           | 11/6  | "art"     | On Working With Your Advisor           |                       |                          |
| [9](#week-9-on-writing-papers)                      | 11/13 | "art"     | On Writing Papers                      |                       |                          |
| [10](#week-10-on-responsible-research)              | 11/20 | "art"     | On Responsible Research                |                       |                          |
| [11](#week-11-paper-presentation-i)                 | 11/27 | "science" | Paper Presentations (I)                |                       |                          |
| [12](#week-12-paper-presentation-ii)                | 12/4  | "science" | Paper Presentations (II)               |                       |                          |

## Assignments and Grades

| Weight | Component                                   | Deadlines        |
|:-------|:--------------------------------------------|:-----------------|
| 15%    | [Debate participation](debates.md)          | Weeks 2, 3, 4, 6 |
| 20%    | [Visualization project](project-vis.md)     | Week 5           |
| 15%    | [Paper presentation](paper-presentation.md) | Weeks 11, 12     |
| 40%    | [Final project](project-final.md)           | End of semester  |
| 10%    | Class participation                         |

It is expected that you come to class prepared, having _completed_ the assigned readings and ready to engage in class discussions.

## Detailed Schedule

### Week 1: Introduction

**Slides:** [[PDF](slides/week01.pdf)]

For more details on normative vs. positive approaches, Wikipedia provides a good starting point: [Positivism](https://en.wikipedia.org/wiki/Positivism) and [Normativity](https://en.wikipedia.org/wiki/Normativity).

### Week 2: The Science of Career

**Readings** (to be completed prior to the class session): ["The Science of Science"](https://www.dashunwang.com/book/the-science-of-science) by Wang and Barabási:
 
+ Introduction
+ Part 1: The Science of Career &mdash; Chapters 1-7 (inclusive)

**Slides:** [[PDF](slides/week02.pdf)]

We'll be having our debate on Topic 1: How should we evaluate excellence? Quality _only_ or quality _and_ quantity?

+ Position A: Researchers should be evaluated _solely_ on the quality of their publications. Quantity is irrelevant and we shouldn't even bother counting.
+ Position B: Researchers should be evaluated on _both_ the quality _and_ quantity of their publications. High-quality publications are of course important, but quantity is also an important component of excellence.

### Week 3: The Science of Collaboration (I)

**Readings** (to be completed prior to the class session): ["The Science of Science"](https://www.dashunwang.com/book/the-science-of-science) by Wang and Barabási:

+ Part 2: The Science of Collaboration &mdash; Chapters 8-11 (inclusive)

**Slides:** [[PDF](slides/week03.pdf)]

We'll be having our debate on Topic 2: Should you collaborate or not?

+ Position A: Early-stage researchers should actively seek out collaborations beyond their research group. Participation in multiple research projects across many different groups builds breadth.
+ Position B: Early-stage researchers should _not_ actively seek out collaborations beyond their research group. Focusing on depth is more important than breadth.

Paper discussed in class: [A causal test of the strength of weak ties](https://www.science.org/doi/10.1126/science.abl4476)

### Week 4: The Science of Collaboration (II)

**Readings** (to be completed prior to the class session): ["The Science of Science"](https://www.dashunwang.com/book/the-science-of-science) by Wang and Barabási:

+ Part 2: The Science of Collaboration &mdash; Chapters 12-14 (inclusive)

**Slides:** [[PDF](slides/week04.pdf)]

We'll be having our debate on Topic 3: How should you approach open-sourcing computational artifacts associated with your work?

+ Position A: Early-stage researchers should do the minimal in open-sourcing computational artifacts that arise from their work. Doing anything more than the community norm is a waste of time and effort that could be better spent writing more papers.
+ Position B: Early-stage researchers should actively promote the adoption of computational artifacts that arise from their work, for example, contributing to popular open-source libraries. Even if this requires a lot of time (e.g., refactoring code into a production-ready state), such efforts are worthwhile.

Interesting tweet thread:

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Who should be the last/senior author on a paper? How do you decide? What does being last entail? I get these questions a lot and it’s confusing because the last author is often a senior person, running a group &amp; raising money. Do those things determine last authorship? No. (1/7)</p>&mdash; Michael Black (@Michael_J_Black) <a href="https://twitter.com/Michael_J_Black/status/1587463427773145090?ref_src=twsrc%5Etfw">November 1, 2022</a></blockquote>

### Week 5: Presentation of Visualization Projects

Presentation of visualization projects!

### Week 6: The Science of Impact

**Readings** (to be completed prior to the class session): ["The Science of Science"](https://www.dashunwang.com/book/the-science-of-science) by Wang and Barabási:

+ Part 3: The Science of Impact &mdash; Chapters 15-20 (inclusive)

**Slides:** [[PDF](slides/week06.pdf)]

We'll be having our debate on Topic 4: Is social media a waste of time?

  + Position A: Early-stage researchers should actively incorporate social media use as a component of their career development. This means appropriate use of sites like Twitter, Facebook, and LinkedIn to build professional reputation, engage with the community, hear about recent work by others, etc.
  + Position B: Early-stage researchers should stay off social media. It's a complete waste of time.

### Week 7: Research as a Social Process


**Slides:** [[PDF](slides/week07.pdf)]

Links to content discussed in class:

+ [LEADERSHIP LAB: The Craft of Writing Effectively](https://www.youtube.com/watch?v=vtIzMaLkCaM)
+ [Report by the ACL 2022 PC Chairs](https://docs.google.com/document/d/1NMuyNOMQD4Xt-tqh4CgiTYEkyhFAQBGFwcyfUCi2obc/edit)

Supplemental readings:

+ Becerra et al. [Maximizing the Conference Experience: Tips to Effectively Navigate Academic Conferences Early in Professional Careers.](https://link.springer.com/article/10.1007/s40617-019-00406-w), _Behavior Analysis in Practice_, 13(3):479-491, 2020.
+ Leininger et al. [Ten Simple Rules for Attending Your First Conference.](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009133) _PLoS Computational Biology_, 17(7):e1009133, 2021.

Some review horror stories:

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Just got a desk reject, post-rebuttals, for a paper being submitted to arxiv &lt;30 min late for the anonymity deadline. I talk about how the ACL embargo policy hurts junior researchers and makes ACL venues less desirable for NLP work. I don’t talk about the pointless NOISE it adds.</p>&mdash; Naomi Saphra 🟣 (@nsaphra) <a href="https://twitter.com/nsaphra/status/1698697352238813538?ref_src=twsrc%5Etfw">September 4, 2023</a></blockquote>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">I AM SO ANGRY. I won&#39;t submit to ACL venues again after they shafted a student after rebuttals with this idiotic policy. Since anonymity is gone, though, publicity time! Check out awesome work by <a href="https://twitter.com/ZackAnkner?ref_src=twsrc%5Etfw">@ZackAnkner</a> on improving MLM training by scheduling masking: <a href="https://t.co/fQ4SVLgFs9">https://t.co/fQ4SVLgFs9</a> <a href="https://t.co/jSUJo4cswf">https://t.co/jSUJo4cswf</a></p>&mdash; Jonathan Frankle (@jefrankle) <a href="https://twitter.com/jefrankle/status/1698802895204864143?ref_src=twsrc%5Etfw">September 4, 2023</a></blockquote>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">from <a href="https://twitter.com/hashtag/ICLR2023?src=hash&amp;ref_src=twsrc%5Etfw">#ICLR2023</a> <a href="https://t.co/5QpGAv0xUs">pic.twitter.com/5QpGAv0xUs</a></p>&mdash; Rob Tang (@XiangruTang) <a href="https://twitter.com/XiangruTang/status/1589703605098975237?ref_src=twsrc%5Etfw">November 7, 2022</a></blockquote>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Our Meta OT paper was rejected from @NeurIPS despite having WA/A/SA throughout the discussion period. How did it happen? The AC based the decision on a review that came a month late that we couldn&#39;t even respond to.<br><br>We&#39;ve made the full discussion public:<a href="https://t.co/ISx9afxhyA">https://t.co/ISx9afxhyA</a> <a href="https://t.co/lBXqPWM6KL">pic.twitter.com/lBXqPWM6KL</a></p>&mdash; Brandon Amos (@brandondamos) <a href="https://twitter.com/brandondamos/status/1589639655003066369?ref_src=twsrc%5Etfw">November 7, 2022</a></blockquote>

### Week 8: On Working With Your Advisor

🚧 Content to be added!

### Week 9: On Writing Papers

🚧 Content to be added!

### Week 10: On Responsible Research

🚧 Content to be added!

### Week 11: Paper Presentation (I)

🚧 Content to be added!

### Week 12: Paper Presentation (II)

🚧 Content to be added!
