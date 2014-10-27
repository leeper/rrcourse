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

 - Code chunks
   - Reusing code chunks
   - In-line knitr expressions
   
 - Chunk options
   - chunk names
   - `eval`
   - `echo`
   - `hold`
   - `warning`, `error`, `message`
   - `tidy` and `highlight`
 - Document-level options
   - `opts_chunk$set()`
   - `opts_knit$set()`
 
 - `knit`ing and `purl`ing
 
 - Code externalization
   - Using same source in multiple documents (article and presentation)
     - Typically, a lot of copy-paste
     - Use one script that generates output, referenced explicitly in each output
     - `purl` article and rerun code in a presentation
     - This: Code in an R script and read chunks into article and presentation
   - Child documents
     - Parent
       - Complete document
       - Include a chunk with a `child` argument
     - Child document is just a chunk
       - <<test-child, out.width='2in'>>=
         str(mtcars)
         @
   - Reading chunks
     - read_chunk("script.R")
     - read_chunk("script.R", labels = "a")
     - Reference chunk labels in subsequent chunks

## ---- label

## @knitr label


     
 - Chunk caching
   - `dependson`
 


 - Plotting
   - `fig.path`
     - Default is './figure'
     - May want to setup as '../figure' for use in other outputs
   - `fig.show`
     - 'asis'
     - 'hold'
     - 'animate'
     - 'hide'
   - `dev` and `dev.args`
     - 'pdf' is default, but 'png' or 'postscript' might also be okay
   - `fig.height` and `fig.width`
     - sizes in inches
     - 1 in == 2.54 cm
   - `fig.env`: LaTeX environment
   - `fig.cap`: LaTeX caption
   - `fig.lp`: LaTeX label
   
 - Tables
   - Three functions
     - `kable`
       - Note: Does not embed tables in a float environment
     - `xtable`
     - `stargazer`
   - Include using `library`
     - suppressMessages(library("stargazer"))
   - Printing raw data
     - kable(mtcars, "latex")
     - xtable(mtcars)
   - Printing summary statistics for a dataframe
     - stargazer(mtcars)
   - Printing tables and crosstables
     - xtable(table(mtcars$cyl))
     - kable(with(mtcars, table(cyl, gear)), "latex")
     - xtable(with(mtcars, table(cyl, gear)))
     - Customization
       - kable(with(mtcars, table(cyl, gear)), "latex", caption = "Simple Crosstabulation")
       - xtable(with(mtcars, table(cyl, gear)), caption = "Simple Crosstabulation", label = "tab:crosstab")
   - Matrices
     - kable(cor(mtcars), "latex", digits = 2)
     - cormat <- cor(mtcars)
       xtable(`[<-`(cormat, lower.tri(cormat), NA), digits = 2)
   - Model objects
     - m1 <- lm(mpg ~ cyl + hp, data = mtcars)
       stargazer(m1)
     - m2 <- lm(mpg ~ cyl + hp + gear + carb, data = mtcars)
       m3 <- lm(mpg ~ cyl * hp + gear + carb, data = mtcars)
       stargazer(m1, m2, m3)
   - Customization
     - kable

     - xtable

     - stargazer
