What They Forgot to Teach You About R
================

### rstudio::conf 2022

by Shannon McClintock Pileggi + Jenny Bryan + E. David Aja

-----

INSTRUCTIONS FOR INSTRUCTORS: Please insert information about your
workshop below. Then, add workshop content in the materials folder and
link to each session’s materials from the schedule below. You are
welcomed to add more rows to the schedule. We just ask that you take
breaks at the specified times. Once you are done adding information, you
can remove these instructions from the README.

-----

:spiral_calendar: July 25 and 26, 2022  
:alarm_clock:     09:00 - 17:00  
:hotel:           \[ADD ROOM\]  
:writing_hand:    [rstd.io/conf](http://rstd.io/conf)

-----

## Overview

This is a two-day hands on workshop designed for experienced R and RStudio users who want to (re)design their R lifestyle. You'll learn holistic workflows that address the most common sources of friction in data analysis. We’ll work on project-oriented workflows, version control for data science (Git/GitHub!), and how to plan for collaboration, communication, and iteration (incl. RMarkdown).

At the conclusion of the workshop, you should have: knowledge of your R installation that enhances your ability to maintain it, workflows that facilitate collaboration with yourself or others (including version control and strategies for file systems), tools to improve debugging processes, and methods to address repetitive tasks with the purrr package.

## Learning objectives

### Project-oriented workflow (2 sessions)

- Identify where installed packages live locally.

- Describe benefits of project oriented workflows.

- Apply best practices for working in RStudio projects, including
using blank slates and restarting R frequently.

- Employ robust file paths through the {here} and {fs} packages.

- Construct human and machine readable file names that sort nicely.

- Differentiate workflow elements, analysis inputs, and analysis outputs
in project structure to create navigable programming interfaces.

### Git/GitHub (2 sessions)

### Personal R Administration (2 sessions)

 - Identify where software and configuration files are located on your operating system 
 via base R, {fs}, {usethis}, and {devtools} functions.

 - Explain the scope and purpose of `.Renviron` and `.Rprofile` configuration files
 when starting R. Modify these files for your personal needs and preferences.
 
 - Employ strategies for package management, including establishing where packages
 are installed, how to upgrade and downgrade, how to install
 from source, and actual package managers.
 
 - Locate and navigate R package source code for better understanding of
 internal operations or troubleshooting.
 
 - Identify what is in your current R session (packages, versions); briefly introduce {renv}
 to create a reproducible environment.
 
### Debugging (1 session)

- Locate and view source code.

- Examine source code to generate insights on errors.

- Distinguish between strategies for debugging your own code 
versus someone else's code.

- Discuss debugging functions (`traceback()`, `browser()`, `debug()`, `trace()`, and `recover()`) and the additional benefits of employing
some of these strategies within RStudio. 


### Iterating well with purrr (1 session)


## Is this course for me?

This course will be appropriate for you if you answer yes to these questions:

- Have you been using R for a while and feel there might be better ways to organize your R life, but don't know what they are?

- Do you want to streamline your workflow for doing analysis and automating repetitive tasks in R?

- Are you willing to get into the weeds of your R installation, project organization, error messages, and source code?

## Prework

Please follow Happy Git and GitHub for the UseR [Ch 3.1 Pre-workshop set-up](https://happygitwithr.com/workshops.html#pre-workshop-set-up).

If you have questions, please ask on the community.rstudio.com thread. 
<need to create>

## Schedule

### Day 1

| Time          | Activity         |
| :------------ | :--------------- |
| 09:00 - 10:30 | Project-oriented workflow 1 of 2       |
| 10:30 - 11:00 | *Coffee break*   |
| 11:00 - 12:30 | Project-oriented workflow 2 of 2        |
| 12:30 - 13:30 | *Lunch break*    |
| 13:30 - 15:00 | Debugging        |
| 15:00 - 15:30 | *Coffee break*   |
| 15:30 - 17:00 | Git/GitHub 1 of 2      |

### Day 2

| Time          | Activity         |
| :------------ | :--------------- |
| 09:00 - 10:30 | Personal R Administration 1 of 2        |
| 10:30 - 11:00 | *Coffee break*   |
| 11:00 - 12:30 | Personal R Administration 2 of 2        |
| 12:30 - 13:30 | *Lunch break*    |
| 13:30 - 15:00 | Git/GitHub 2 of 2        |
| 15:00 - 15:30 | *Coffee break*   |
| 15:30 - 17:00 | Iterating well with purrr        |

## Instructors

Shannon Pileggi PhD is a Data Scientist with more than ten years of experience partnering on data analysis with diverse stakeholders in academic, corporate, tech, public health, and clinical research settings. An enthusiastic educator and statistical collaborator, Shannon started her career in academia as a Lecturer with the Institute for Quantitative Theory and Methods at Emory University, and later as an Assistant Professor at California Polytechnic State University, San Luis Obispo. When she transitioned to industry in 2019, Shannon leveraged open source and community resources to adopt modern programming practices and workflows in R. In 2020, Shannon began to give back to the R community through blogging and developing R-Ladies workshops; she currently serves as a member of the R-Ladies Global Team. Shannon spends her days wrangling data, creating reproducible reports, building shiny apps, developing R packages, and mentoring junior Data Scientists at The Prostate Cancer Clinical Trials Consortium, housed under Memorial Sloan Kettering Cancer Center.

Jenny is a software engineer at RStudio, on the tidyverse team. She is a recovering biostatistician who takes special delight in eliminating the small agonies of data analysis. Jenny is the maintainer of many R packages, in the areas of data import, web APIs, Git/GitHub, and package development. She has been working in R/S for over 20 years and is a member of the R Foundation. Prior to joining RStudio, she was a professor of statistics at the University of British Columbia.

David Aja is a Solutions Engineer at RStudio. He helps data scientists and IT communicate about their needs. Before joining RStudio, he worked as a data scientist in the public sector.

-----

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is
licensed under a [Creative Commons Attribution 4.0 International
License](https://creativecommons.org/licenses/by/4.0/).
