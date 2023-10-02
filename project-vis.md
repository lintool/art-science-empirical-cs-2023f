# Assignment: Visualization Project

**The Art and Science of Empirical Computer Science (Fall 2023)**

For this visualization project, I would like you to perform exploratory data analysis on a dataset of your choice.
The dataset can be anything, as long as it's related to any of the "science of science" topics discussed in this course (see examples below).

I would like you to start with one or more interesting questions, for example, "Do faculty in the school collaborate?"
From there, I would like you to build a visualization that (at least tries to) answer the question(s) you posed.
For example, to answer the above question, you might visualize the co-authorship network of faculty in the school.

Let's start at the end with the deliverables:

+ You will build an _interactive_ visualization that meets the expectations described on this page (with illustrative examples and sources of inspiration provided below).
+ In class, on October 16, you will deliver a short presentation describing your visualization. The presentation will be three minutes long, with an additional minute for questions.

My expectations for the visualization:

+ It must be web accessible, i.e., reachable via a URL.
+ It must be _interactive_. That means, a PDF is not sufficient; neither is a PowerPoint presentation. A notebook is fine, as long as it generates a visualization. If you're thinking these lines, you might want to consider [Observable](https://observablehq.com/).
+ Ideally, the site should be "self-contained", for example, a website containing an interactive [D3](https://d3js.org/) visualization. By "self-contained", I mean "not needing a backend". For example, if you find yourself needing a backend to store data, you're probably doing more than I expect. Again, see examples below. Note that this is merely a suggestion, not a requirement, but you're responsible for procuring your own backend if you insist on having one.
+ Basic levels of interactivity is sufficient. For example, if you visualize co-authorship networks, I would expect some mechanism for examining the network. This might include mouseovers that provide additional information about the author and a functionality to find authors by name.
+ Make sure that your interactive visualization "explains itself". That is, there should be sufficient prose attached to the visualization to explain "what I'm looking at", e.g., where the data come from, how it was processed and manipulated, etc.

If you have any questions, _ask_!

## Sources of Inspiration

Perhaps it's easiest to illustrate what I'm looking for by example, which hopefully provides sources of inspiration:

[**UWaterloo CS Co-Authorship Network**](cs-collaboration-network/collabs_20230109.png). Each year before hiring season, [Ian Goldberg](https://cs.uwaterloo.ca/~iang/) scrapes information from DBLP to construct the co-authorship network for faculty in the school. The visualization is designed to show collaboration patterns between different faculty and groups within the school.
Note that this is _static_ visualization, so it would not meet my expectations above.
However, an _interactive_ version of this network would be a good project.
If you're interested in working on this, the raw data are stored [here](cs-collaboration-network/).
Building on this, one might compare collaboration patterns across different institutions.
For example, how does Waterloo compare against Toronto?

[**Waterloo AI Institute Co-Authorship Network**](https://toluclassics.github.io/wai/).
This visualization was created by [Odunayo Ogundepo](https://github.com/ToluClassics), one of my (former) Master's students.
The AI Institute prides itself on a multi-disciplinary approach to AI, which we wanted to illustrate.

[**Topic Modeling of AI Papers in 2022**](https://github.com/cohere-ai/notebooks#9-topic-modeling-of-ai-papers-in-2022). This is an example using vector embeddings to try to understand the "landscape" of an academic discipline (as reflected in a specific journal) in terms of textual content.
More ideas are sketched out in [this issue](https://github.com/lintool/art-science-empirical-cs-2023f/issues/3).

[**Citations of ACM Fellows**](https://github.com/castorini/ura-projects/issues/2#issuecomment-1734235411).
This idea is sketched out in [this issue](https://github.com/lintool/art-science-empirical-cs-2023f/issues/2).
Using embeddings, we can cluster together ACM Fellows based on their contributions (as reflected in the citations).
Does this tell us something about the types of research that are recognized and rewarded by the ACM?

[**What are the top Canadian universities for AI research?**](https://lintool.github.io/csranking-aica/)
This is a visualization created by Alan Wu from the [WatVis Lab](http://www.jeffjianzhao.com/) under my guidance.
The goal is quite straightforward: this visualization tries to answer the question, "What are the top Canadian universities for AI research?" based on data from [CSRankings](http://csrankings.org/).

[**Big Cows 🐮: Information Retrieval**](https://lintool.github.io/bigcows/index-ir.html).
This is a personal project of mine that started over a decade ago for my own tenure case at the University of Maryland.
The tenure application process at Maryland mandated a bibliometric analysis of the candidate being considered for promotion, specifically in relationship to peers.
This site arose from a simple interface to display the data, but has evolved over time to include many IR researchers.

This project will be completed individually, but I will allow, with prior permission (i.e., ask me), larger projects that may involve sharing code (e.g., a common data crawler that you collaborate on building) or data (e.g., a large dataset that you perform data cleaning on together, but analyze individually).
However, in the end, each student will be responsible for producing a final, distinct visualization.
If you are interested in doing something along these lines, please get in touch with me as soon as possible.

I've outlined a few ideas that would make good projects [here](https://github.com/lintool/art-science-empirical-cs-2023f/issues).

## Sources of Data

The following are data sources that might serve as starting points.
In some cases the datasets offer bulk downloads; some offer APIs; for others, you'll have to write web scrapers.

+ [Google Scholar](https://scholar.google.com/): Of course, probably the most extensive source of bibliometric data... but for most data you'll have to scrape.
+ [Semantic Scholar](https://www.semanticscholar.org/) by AI2: provides bulk download options as well as an extensive API.
+ [DBLP](https://dblp.org/) (try querying using [QLever](https://qlever.cs.uni-freiburg.de/dblp))
+ [CSRankings](https://csrankings.org/)
