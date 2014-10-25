---
layout: default
title: knitr
ghurl: https://github.com/leeper/rrcourse/tree/gh-pages
---

# knitr #

 - Comparison of workflows
   - Traditional workflow
   - Reproducible workflow
     - Not actually a single workflow
     - Multiple ways to be reproducible
     - We'll work through a few, but there are many others
     
 - Basics of knitr
   - History
     - WEB and noweb
     - S becomes R
     - SWeave
     - knitr
   - Markup formats and output formats
     - LaTeX
     - HTML
     - Markdown
   - Why LaTeX? Why knitr?
     - Automation
     - Easy collaboration with future self
     - Easy collaboration with others
     - BibTeX integration
     - LaTeX style files
   - Structure of a LaTeX document
   - Structure of a knitr document
   - Workflows
     - Bad: Run results and copy-paste
     - Good: Run results in R and then embed in LaTeX
     - Good: Work natively in .Rnw with embedded code chunks
     - Good: Work natively in .Rnw with code externalization
 
 - Your first knitr document
 
 - Setting up RStudio
   - http://yihui.name/knitr/demo/rstudio/

 - Chunk options
   - chunk names
   - `eval`
   - `echo`
   - `hold`
   - `warning`, `error`, `message`
   - `tidy` and `highlight`
 
 - Code externalization
   - Using same source in multiple documents (article and presentation)
   - Child documents
   - Reading chunks
   
 - `knit`ing and `purl`ing
 
 - In-line knitr expressions
 
 - Tables
   - `kable`
   - `xtable`
   - `stargazer`
 
 - Plotting
   - `fig.path`
   - `fig.show`
   - `dev` and `dev.args`
   - `fig.height` and `fig.width`
   - `fig.cap`
   - `fig.lp`
   
 - `spin`ing
 
 - Chunk caching
   - `dependson`
 
 - Language engines
   - python
   - Bash
   - Julia
   - Stata?
   
 - Other tools
   - Git
   - GitHub, Bitbucket, etc.
   - Dropbox
   - pandoc
   - markdown
   - RStudio
   - A good LaTeX editor: LyX, Eclipse, Texmaker, WinEdt, TexStudio, TeXLive, TeXWorks, Emacs, etc., etc.
   - devtools, repmis, packrat, checkpoint
   - docker, disk images, and virtual machines
   