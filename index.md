---
layout: default
title: Home
---

# Course materials for teaching and learning about reproducible research #

This site contains course materials for teaching and learning about reproducible research (especially in the social sciences). The initial version of this course is a one-day seminar at the Interacting Minds Centre (IMC) at Aarhus University on October 28, 2014. Event details are avilable [here](http://interactingminds.au.dk/events/single-events/artikel/reproducible-research-what-why-and-how/).

The IMC short course involves a morning lecture and an afternoon hands-on session. Slides for both parts of the course and materials for the afternoon activities will be available here shortly. 

## Reproducible Research: What, Why, and How? (Morning Session) ##

In this session, we will discuss reproducible research from the dual perspectives of simplifying one's research work and forwarding the multi-disciplinary push for [#openscience](https://twitter.com/search?q=%23openscience). It will lay out why reproducible science matters and how to achieve it.

 - [Slides](Slides/WhatWhyHow.pdf)

## Creating a Reproducible Scientific Workflow with R, LaTeX, and knitr (Afternoon Session) ##

The afternoon session applies the principles from the morning talk using a concrete set of tools, namely statistical analyses in R and document markup in LaTeX. The emphasis will be on knitr, an R package that seamlessly blends these tools to enable automated article generation and a greatly simplified scientific workflow. Participants will leave with a thorough understanding of knitr's capabilities and strategies for how to use R, LaTeX, and knitr to produce reproducible analyses, papers, and presentations. Exercises will help participants understand various advanced features of knitr and apply those techniques in their own scientific workflow. Basic familiarity with R will be helpful but the lack thereof should not preclude participation; familiarity with LaTeX is helpful but not at all required.

### Getting Started ###

The afternoon session will make use of [RStudio](http://www.rstudio.com/products/RStudio/#Desk), an integrated development environment (IDE) for the R language. We will also be using features of RStudio that require a LaTeX distribution to be installed on your machine. Installing LaTeX isn't hard, but can be time-consuming. Installing RStudio is easy. Please download and install a LaTeX distribution and RStudio on your own machine before the session starts.  Directions for each are below.

The [LaTeX Project](http://www.latex-project.org/ftp.html) has details about how to install a LaTeX distribution for different operating systems. Typically this means you'll want to install TeX Live (described on that page in detail). In practice, Mac OS users may want to install MacTeX and Windows users may want to install MikTeX (or use the proTeXt installer). Do whatever seems easiest for your system.

RStudio allows you to seamlessly move between raw R scripts, LaTeX documents, and the knitr literate programming documents that integrate R and LaTeX. RStudio should work for you out of the box, but you will need to configure RStudio to use knitr. To do so, open RStudio and install knitr by typing: `install.packages("knitr")` in the RStudio console. Then, [follow directions described here](http://yihui.name/knitr/demo/rstudio/) to configure RStudio to use knitr (instead of the default Sweave engine). We'll go through this together, as needed.

### Materials ###

 - [Slides](Slides/knitr.pdf) (Draft)
 - [Handout](Activities/knitr_handout.pdf) (Draft)

---
## Why GitHub? ##

Read more about why this course is on GitHub [here](fork.html). You can access [the GitHub repository here](https://github.com/leeper/rrcourse).

