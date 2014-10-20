---
layout: default
title: Reproducible Research Overview
ghurl: https://github.com/leeper/rrcourse/tree/gh-pages
---

# Reproducible Research: What, Why, and How? #

 - Why reproducible research?
   - External reasons
     - Philosophical perspective
     - Second "Credibility Revolution" (transparency)
     - "Replication crisis"
     - "Most Published Research Findings Are False"
     - Journals increasingly requiring it
     - Funding agencies require open science
   
   - Internal reasons
     - Greater confidence in own work
     - Easier scientific workflow
     - Easier collaboration
       - "Collaboration with others, including your future self"
       - Future you: much easier to remember what you did and update when your work is reproducible
   
   - Why reproducibility?
     - Do it for yourself first
     - Do it because it makes science better second
   
   
 - Why isn't science reproducible already?
   - Individual behavior
     - Laziness
     - Cost
     - Difficulty
     - Disciplinary differences
     - Human error in data processing and analysis
     - Transcription errors
     
   - Technology
     - Tools for reproducibility don't exist
     - Different tools (OS, software, etc.)
     - Technology changes
   
   - Collective behavior
     - Norms and traditions mean evolving defintion of reproducibility
     - No uniform standards for reproducibility results
     - Lack of consistent reciprocity about data and code availability
     

 
 - What makes research reproducible?
   - Discipline-specific examples
     - AAPOR standards
     - APSA
     - Psych Science
     - OSF
     - American Anthropological Association
     - CONSORT
   - No clear definition
     - Difficult to say
     - Depends on discipline-specific norms and standards
     - Evolving
     - Will always evolve as technology and research methods change
   - Easier to define in the negative
     - What makes research irreproducible (i.e., not reproducible)?
   - Examples
     - Results are simply fabricated (ultimate form of irreproducible results)
     - Human errors
     - Methods/protocol aren't transparent in article
     - Data are cited but specific dataset ambiguous ("General Social Survey")
       - Datasets are rarely versioned, so when changes are made it's impossible to reproduce results on prior versions
     - Data aren't available at all
     - Analysis files available, but don't work
     - Analysis files available, but only run on proprietary (or unavailable) software
     - "Results/data/analysis/explanation available from the author" (now deceased)
   - Distinguishing reproducibility from other concepts
     - Reproducible versus replicable
       - Reproducible results might not replicate
       - Replication is about further evidence in support of a hypothesis
       - Expectations about replication need to be flexible
         - Physical processes need to replicate exactly according to protocol (cold fusion)
         - Social and individual phenomena need not replicate for the original results to be true
         - Distinction between reproducible, replicable, and externally valid
     - Reproducible versus truth
       - Simply because something is reproducible does not mean it is true
         - Fabricated data can be used to produce perfectly reproducible analyses
         - The research process in fact is perfectly reproducible if data were generated deterministically
       - Simply because something is peer reviewed does not make it true
         - Peer review doesn't typically test either reproducibility or truth
       - Truth is a philosophical debate and reproducibility doesn't help us here
     - Reproducible versus automated
       - Reproducibility does not necessarily require you to be a computer programmer
       - Reproducible means a complete set of physical actions needed to transforms inputs into outputs
       - It's much easier for something to be reproducible if it is computer automated, but standards of reproducibility have been historically and remain tool-independent
     - Others?????
     
 - Comparison of workflows
   - Traditional workflow
     - Design a study
     - Implement the study
     - Get data back
     - Do stuff to data (or RA does stuff to data)
     - Analyze data
     - Copy results into Excel or Word
     - Write results
     - Try to publish
     - Go back to software and reanalyze
     - Recopy results into Excel or Word
     - Try to publish, again
     - Once published, zip directory and forget
   - Reproducible workflow
     - Not actually a single workflow
     - Multiple ways to be reproducible
     - Basic premise:
       - From inputs, get outputs
       - Automated as much as possible
       - Easier to make changes, collaborate, share, be transparent, and reuse
 
 - What are the pieces of a reproducible research product?
   - Caveat emptor
     - Discipline-specific meaning
     - What makes research reproducible varies and will vary
   - First generation (past)
     - Documented data collection procedures
     - Documented data analytic methods
     - Well-described data (descriptives, etc.)
     - Closed data
     - Closed analysis
     - Proprietary software
     - Paywalled publication
   - Second generation (present)
     - Publicly archived research protocol
     - Publication includes more details
       - Summary protocol
       - Documentation of protocol violations
       - Data-related appendices
     - Increasingly shared data
     - Expectation of shared "replication files"
     - Mix of propriety and open software
     - Paywalled publication with "green" open access or working paper archives
   - Emerging trends
     - Persistently archived, open-licensed, documented data
       - Three S's: Structured, Simple, Semantic data
       - Codebooks, metadata, and documentation
     - Study preregistration
     - Publications with literate programming
       - knitr, which we'll talk about this afternoon
     - Reproducible virtual machines
       - Disk images
       - Docker containers
     - Open lab notebooks
       - Open, collaborative version-controlled research from Day 0
     - Open-access publication

 - Reproducibility as part of open science
   - Data archiving
     - ICPSR
     - Dataverse
     - Figshare
   - Data citation
     - Emerging consensus
     - UNF
   - Open protocols
     - OSF
     - Wet sciences
   - Open materials
     - OSF
     - Not common elsewhere
       - Cite my own examples
   - Open data and code with reproducible analyses
     - "Literate programming"
     - Publication as an automated product of a software workflow
   - Methodological transparency
   - Open source software
     - R, Python, Octave, Julia
   - Open access publishing
 
 - How do you start being more reproducible?
   - Think about your future self
   - Write everything down
     - Markup your analysis files
     - Keep complete codebooks
     - Version control
       - Especially for collaboration, version control is amazingly helpful
   - Archive your data, analysis, protocols, and materials
     - Put them in a persistent, public archive (not your website)
   - Abandon point-and-click
     - Use scripts rather than menus for graphics
     - Actually "do" your do files (execute scripts from the command line)
   - Start using literate programming
     - Learn knitr this afternoon!

 
 - Conclusion
   - Reproducible research is something you should do for yourself
   - If everyone's work is reproducible, science is better off
   - If everyone's work is reproducible, society has the potential to get more from science
