---
layout: default
title: Reproducible Research Overview
ghurl: https://github.com/leeper/rrcourse/tree/gh-pages
---

# Reproducible Research: What, Why, and How? #

 - There's a crisis in (social) science!
     - Reinhart and Rogoff http://en.wikipedia.org/wiki/Growth_in_a_Time_of_Debt
     - "Replication crisis" http://www.slate.com/articles/health_and_science/science/2014/07/replication_controversy_in_psychology_bullying_file_drawer_effect_blog_posts.html
     - Diedrick Stapel http://en.wikipedia.org/wiki/Diederik_Stapel
     - Ioannidis, J. "Most Published Research Findings Are False" http://www.plosmedicine.org/article/info%3Adoi%2F10.1371%2Fjournal.pmed.0020124
     
   - What are we supposed to believe?
   - Who are we supposed to trust?

 - Why reproducible research?
   - External reasons
     - Philosophical perspective
     - Second "Credibility Revolution" (transparency)
     - Journals increasingly requiring it
     - Funding agencies require open science (open data, open access publication, etc.)
   
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
   - Technology
     - Tools for reproducibility don't exist
     - Different tools used by different researchers (OS, software, etc.)
     - Technology changes over time
     - Research and data archiving is only possible with the advent of cloud storage
   
   - Individual behavior
     - Laziness and procrastination
     - Time and Cost
     - Difficulty
     - Disciplinary differences
     - Human error in data processing and analysis
     - Transcription errors
     - Lying, cheating, and deception
     
   - Collective behavior
     - Norms and traditions mean evolving definition of reproducibility
     - No uniform standards for reproducibility results
     - Lack of consistent reciprocity about data and code availability
     

 
 - What makes research reproducible?
   - Discipline-specific examples
   - AAPOR "Disclosure Standards" (http://www.aapor.org/disclosure_standards1.htm)
     - Published with report:
     1. Who sponsored the research study, who conducted it, and who funded it, including, to the extent known, all original funding sources.
     2. The exact wording and presentation of questions and responses whose results are reported.
     3. A definition of the population under study, its geographic location, and a description of the sampling frame used to identify this population. If the sampling frame was provided by a third party, the supplier shall be named. If no frame or list was utilized, this shall be indicated.
     4. A description of the sample design, giving a clear indication of the method by which the respondents were selected (or self-selected) and recruited, along with any quotas or additional sample selection criteria applied within the survey instrument or post-fielding. The description of the sampling frame and sample design should include sufficient detail to determine whether the respondents were selected using probability or non-probability methods.
     5. Sample sizes and a discussion of the precision of the findings, including estimates of sampling error for probability samples and a description of the variables used in any weighting or estimating procedures. The discussion of the precision of the findings should state whether or not the reported margins of sampling error or statistical analyses have been adjusted for the design effect due to clustering and weighting, if any.
     6. Which results are based on parts of the sample, rather than on the total sample, and the size of such parts.
     7. Method and dates of data collection.
     - Available:
     1.  Preceding interviewer or respondent instructions and any preceding questions or instructions that might reasonably be expected to influence responses to the reported results.
     2.  Any relevant stimuli, such as visual or sensory exhibits or show cards.
     3.  A description of the sampling frame’s coverage of the target population.
     4.  The methods used to recruit the panel, if the sample was drawn from a pre-recruited panel or pool of respondents.
     5.  Details about the sample design, including eligibility for participation, screening procedures, the nature of any oversamples, and compensation/incentives offered (if any).
     6.  Summaries of the disposition of study-specific sample records so that response rates for probability samples and participation rates for non-probability samples can be computed.
     7.  Sources of weighting parameters and method by which weights are applied.
     8.  Procedures undertaken to verify data. Where applicable, methods of interviewer training, supervision and monitoring shall also be disclosed.
     
     - APSA "A Guide to Professional Ethics in Political Science" (http://www.apsanet.org/Files/Publications/APSAEthicsGuide2012.pdf)
     "5.5 Authors are obliged to reveal the bases of any of their statements that are challenged specifically, except where confidentiality is involved. 
      5.6 When statements that are challenged are based on reproducible data authors  are obliged to facilitate replication. They may expect the challenger to pay the costs  of reproducing the relevant data. 
      5.7 Challenges are to be sufficiently precise to indicate to the author what  documentation or data are needed. Challengers are themselves in the status of  authors in connection with the statements that they make. "
      "6. Researchers have an ethical obligation to facilitate the evaluation of their evidencebased knowledge claims through data access, production transparency, and analytic transparency so that their work can be tested or replicated.
      6.1 Data access: Researchers making evidence-based knowledge claims should reference the data they used to make those claims. If these are data they themselves generated or collected, researchers should provide access to those data or explain why they cannot.
      6.2 Production transparency: Researchers providing access to data they themselves generated or collected, should offer a full account of the procedures used to collect or generate the data.
      6.3 Analytic Transparency: Researchers making evidence-based knowledge claims should provide a full account of how they draw their analytic conclusions from the data, i.e., clearly explicate the links connecting data to conclusions.
      6.4 Scholars may be exempted from Data Access and Production Transparency in order to (A) address well-founded privacy and confidentiality concerns, including abiding by relevant human subjects regulation; and/or (B) comply with relevant and applicable laws, including copyright. Decisions to withhold data and a full account of the procedures used to collect or generate them should be made in good faith and on reasonable grounds. Researchers must, however, exercise appropriate restraint in making claims as to the confidential nature of their sources, and resolve all reasonable doubts in favor of full disclosure.
      6.5 Dependent upon how and where data are stored, access may involve additional costs to the requesting researcher.
      6.6 Researchers who collect or generate data have the right to use those data first. Hence, scholars may postpone data access and production transparency for one year after publication of evidence-based knowledge claims relying on those data, or such period as may be specified by (1) the journal or press publishing the claims, or (2) the funding agency supporting the research through which the data were generated or collected.
      6.7 Nothing in this section shall require researchers to transfer ownership or other proprietary rights they may have."
       
     - Association for Psychological Science "Submission Guidelines" (http://www.psychologicalscience.org/index.php/publications/journals/psychological_science/ps-submissions#DISC)
       "For each study reported in your manuscript, check the boxes below to:
      (1) Confirm that (a) the total number of excluded observations and (b) the reasons for making these exclusions have been reported in the Method section(s). [  ] If no observations were excluded, check here [  ].
      (2) Confirm that all independent variables or manipulations, whether successful or failed, have been reported in the Method section(s). [  ] If there were no independent variables or manipulations, as in the case of correlational research, check here [  ].
      (3) Confirm that all dependent variables or measures that were analyzed for this article’s target research question have been reported in the Methods section(s). [  ]
      (4) Confirm that (a) how sample size was determined and (b) your data-collection stopping rule have been reported in the Method section(s) [  ] and provide the page number(s) on which this information appears in your manuscript:
      Authors will also be required to enter the page number(s) on which their sample size/stopping rule information appears in their manuscript, and they must also copy and paste from their manuscript the sentence(s) that explain(s) how the sample size was determined and the stopping rule."
     - American Psychological Association "Ethical Principles of Psychologists and Code of Conduct" (http://www.apa.org/ethics/code/index.aspx)
       "Psychologists create, and to the extent the records are under their control, maintain, disseminate, store, retain and dispose of records and data relating to their professional and scientific work in order to (1) facilitate provision of services later by them or by other professionals, (2) allow for replication of research design and analyses, (3) meet institutional requirements, (4) ensure accuracy of billing and payments, and (5) ensure compliance with law." (6.01)
       "After research results are published, psychologists do not withhold the data on which their conclusions are based from other competent professionals who seek to verify the substantive claims through reanalysis and who intend to use such data only for that purpose, provided that the confidentiality of the participants can be protected and unless legal rights concerning proprietary data preclude their release. This does not preclude psychologists from requiring that such individuals or groups be responsible for costs associated with the provision of such information." (8.14a)
       "Psychologists who request data from other psychologists to verify the substantive claims through reanalysis may use shared data only for the declared purpose. Requesting psychologists obtain prior written agreement for all other uses of the data." (8.14b)
     - OSF
     - American Anthropological Association "Code of Ethics" (http://www.aaanet.org/issues/policy-advocacy/upload/AAA-Ethics-Code-2009.pdf)
     "6. Anthropological researchers should seriously consider all reasonable requests for access to their data and other research materials for purposes of research. They should also make every effort to insure preservation of their fieldwork data for use by posterity."
     - CONSORT "CONSORT Statement" (http://www.consort-statement.org/consort-2010)
       "The checklist includes the 25 items selected because empirical evidence indicates that not reporting the information is associated with biased estimates of treatment effect, or because the information is essential to judge the reliability or relevance of the findings."
       Does not require data access or reproducible analyses, but does require published research protocol and study preregistration
     - PLoS "Editorial and Publishing Policies" (http://www.plosone.org/static/policies.action#sharing)
       "Publication is conditional upon the agreement of the authors to make freely available any materials and information described in their publication that may be reasonably requested by others." 
       Three allowed forms: "Data deposition", "data in supporting information files", "Data made available to all interested researchers upon request", and "Data available from third party"
       Software should be open source and shared if essential to the paper. "The software need run on only one hardware-software platform in common use by the readership (including MATLAB), although it must run without dependencies on proprietary or otherwise unobtainable ancillary software. Articles describing software that requires access to databases and other resources whose persistence is not guaranteed (e.g. individual laboratory databases without funding support) will not be considered. In addition, the results described in the paper must be reproducible when peer reviewers, editors, or readers run the software on the deposited dataset and with the provided control parameters."
     
     - European Research Council "Open Access Guidelines for researchers funded by the ERC" (http://erc.europa.eu/sites/default/files/document/file/ERC_Open_Access_Guidelines-revised_2013.pdf)
     "The European Research Council supports the basic principle of Open Access to research data. It therefore recommends to all its funded researchers that they follow best practice by retaining files of all the research data they have used during the course of their work, and that they be prepared to share this data with other researchers whenever it is not bound by copyright restrictions, by confidentiality agreements, or by contractual clauses."
   
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
     - Data are cited but specific dataset ambiguous ("General Social Survey", "World Values Survey")
       - Public datasets are rarely versioned, so when changes are made it's impossible to reproduce results on prior versions
     - Data are in a proprietary, nondescript, or painstakingly difficult file format that you cannot open
     - Data aren't available at all
     - Analysis files available, but don't work
     - Analysis files available, but only run on proprietary (or unavailable) software (SAS, SPSS, Stata, etc.)
     - "Results/data/analysis/explanation available from the author" (now deceased)
   
   - Distinguishing reproducibility from other concepts
     - Reproducible versus replicable
       - Reproducible results might not replicate
       - Replication is about further evidence in support of a hypothesis
       - Expectations about replication need to be flexible
         - Physical processes need to replicate exactly according to protocol (cold fusion)
         - Social and individual phenomena need not replicate for the original results to be true
         - Distinction between reproducible, replicable, and externally valid
       - Source of confusion: King, G. (1995) "Replication, Replication" 
     - Reproducible versus truth
       - Simply because something is reproducible does not mean it is true
         - Fabricated data can be used to produce perfectly reproducible analyses
         - The research process in fact is perfectly reproducible if data were generated deterministically
       - Simply because something is peer reviewed does not make it true
         - Peer review doesn't typically test either reproducibility or truth
       - Truth is a philosophical debate and reproducibility doesn't help us here
     - Reproducible versus automated
       - Reproducibility does not necessarily require you to be a computer programmer
         - Most disciplinary standards do not require any particular technology workflow
       - It's much easier for something to be reproducible if it is computer automated, but standards of reproducibility have been historically and remain tool-independent
     - Others?????
     
   - How can we therefore define reproducibility?
     - Stanford University's David Donoho: "An article about computational science in a scientific publication is not the scholarship itself, it is merely advertising of the scholarship. The actual scholarship is the complete software development environment and the complete set of instructions which generated the figures"
     - "Reproducible research enumerates a complete set of physical actions needed to transforms transparent inputs into outputs"
     - An article is not research, it is the output of research. Making an article reproducible (e.g., using knitr) is only part of a reproducible workflow
     
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
     - Open-access publication
     - Publications with literate programming
       - knitr, which we'll talk about this afternoon
     - Reproducible virtual machines
       - Disk images
       - Docker containers
     - Open lab notebooks
       - Open, collaborative version-controlled research from Day 0
     

 - How do you start being more reproducible?
   - Think about your future self
   - Write everything down
     - Markup your analysis files
     - Write a protocol and update it when you change things
     - Keep complete codebooks and original stimulus materials
     - Version control
       - Especially for collaboration, version control is amazingly helpful
   - Get organized
     - Use a folder structure that can be copied and shared
     - Never use absolute file paths in your code
   - Abandon point-and-click
     - Don't clean your data by-hand. Analyses should run from the raw data.
       - Actually "do" your do files (execute scripts from the command line)
     - Use scripts rather than menus for graphics
     - Record OS and software versions
   - Archive your data, analysis, protocols, and materials
     - Put them in a persistent, public archive (not your website)
     - Be explicit about data licensing
     - Metadata!
     - Where to archive your data
       - Dataverse: http://thedata.org/
       - Data Dryad: http://datadryad.org/
       - Figshare: http://figshare.com/ 
   - Start using literate programming
     - Learn knitr this afternoon!

 - Reproducibility as part of open science
   - Data archiving
     - ICPSR
     - Dataverse
     - Dryad
     - Figshare
   - Data citation
     - Emerging consensus
     - UNF
   - Open protocols
     - OSF (https://osf.io/tvyxz/wiki/view/)
     - Wet sciences
   - Open materials
     - OSF (https://osf.io/tvyxz/wiki/view/)
     - Not common elsewhere
       - Cite my own examples
   - Open data and code with reproducible analyses
     - "Literate programming"
     - Publication as an automated product of a software workflow
   - Methodological transparency
   - Open source software
     - R, Python, Octave, Julia
   - Open access publishing
 
 - Places to help you get started
   - Ideas and Tools
   rOpenSci: http://ropensci.org/blog/2014/06/09/reproducibility/
   Nature: "CHALLENGES IN IRREPRODUCIBLE RESEARCH" http://www.nature.com/nature/focus/reproducibility/
   Karl Broman: http://kbroman.org/Tools4RR/pages/resources.html
   Victoria Stodden's 2011 "Reproducible Research" conference http://www.stodden.net/AMP2011/
   Software Carpentry http://software-carpentry.org/index.html
   Gandrud, C. Reproducible Research with R and RStudio http://www.amazon.com/exec/obidos/ASIN/1466572841/7210-20
   Bowers, J. "Six steps to a Better Relationship
with Your Future Self" http://polmeth.wustl.edu/methodologist/tpm_v18_n2.pdf
   Sandve, G.K. et al. "Ten Simple Rules for Reproducible Computational Research" http://www.ploscompbiol.org/article/info%3Adoi%2F10.1371%2Fjournal.pcbi.1003285
   Johns Hopkins Data Science Certificate on Coursera http://jhudatascience.org/
   
   - People to follow
   Victoria Stodden @victoriastodden https://twitter.com/victoriastodden
   Carly Strasser @carlystrasser https://twitter.com/carlystrasser
   Limor Peer @l_peer https://twitter.com/l_peer
   Center for Open Science @OSFramework https://twitter.com/OSFramework (also @BrianNosek)
   Retraction Watch @RetractionWatch https://twitter.com/RetractionWatch
   Berkeley Institute for Transparency in the Social Sciences @UCBITSS https://twitter.com/UCBITSS
   @OpenScience https://twitter.com/openscience
   
 - Conclusion
   - Reproducible research is something you should do for yourself
   - If everyone's work is reproducible, science is better off
   - If everyone's work is reproducible, society has the potential to get more from science

   
   
