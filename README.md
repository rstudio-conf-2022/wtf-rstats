# What They Forgot to Teach You About R

### rstudio::conf 2022

by Shannon McClintock Pileggi + Jenny Bryan + E.
David Aja

------------------------------------------------------------------------

🗓️ July 25 and 26, 2022  
⏰ 09:00 - 17:00  
🏨 [ADD ROOM]  
✍️ [rstd.io/conf](http://rstd.io/conf)

------------------------------------------------------------------------

## Prework

For this workshop, participants will be working from their personal laptops.

Please be ready with **current versions** of both R and RStudio. This means R >= 4.2.0 and RStudio >= 2022.02.3+492, unless you have a good reason otherwise. See the discussion in Install or upgrade R and RStudio: [https://happygitwithr.com/install-r-rstudio.html#install-r-rstudio](https://happygitwithr.com/install-r-rstudio.html#install-r-rstudio).

In addition, it is essential that you do the requested **pre-workshop Git/GitHub set up** in advance: [https://happygitwithr.com/workshops.html#pre-workshop-set-up](https://happygitwithr.com/workshops.html#pre-workshop-set-up).

Lastly, please make sure your system is ready to build packages. You can confirm this
by checking if `devtools::has_devel()` returns _Your system is ready to build packages!_.
If this returns _Could not find tools necessary to compile a package_ please follow 
instructions in What They Forgot to Teach You About R [Ch 9: Set up an R dev environment](https://rstats.wtf/set-up-an-r-dev-environment.html#set-up-an-r-dev-environment).


If you have questions in advance of the workshop, please ask on the **RStudio Community thread**: [https://community.rstudio.com/t/what-they-forgot-to-teach-you-about-r-workshop-rstudio-conf-2022/138999](https://community.rstudio.com/t/what-they-forgot-to-teach-you-about-r-workshop-rstudio-conf-2022/138999).


------------------------------------------------------------------------

## Schedule

### Day 1

| Time          | Activity                                        | Instructor      |
|:--------------|:------------------------------------------------|:----------------|
| 09:00 - 10:30 | [1_1: Project-oriented workflow 1 of 2](day1_1) | Shannon Pileggi |
| 10:30 - 11:00 | *Coffee break*                                  |                 |
| 11:00 - 12:30 | [1_2: Project-oriented workflow 2 of 2](day1_1) | Shannon Pileggi |
| 12:30 - 13:30 | *Lunch break*                                   |                 |
| 13:30 - 15:00 | [1_3: Debugging](day1_3)                        | Shannon Pileggi |
| 15:00 - 15:30 | *Coffee break*                                  |                 |
| 15:30 - 17:00 | [1_4: Git/GitHub 1 of 2](day1_4)                | Jenny Bryan     |

### Day 2

| Time          | Activity                                        | Instructor      |
|:--------------|:------------------------------------------------|:----------------|
| 09:00 - 10:30 | [2_1: Personal R Administration 1 of 2](day2_1) | David Aja       |
| 10:30 - 11:00 | *Coffee break*                                  |                 |
| 11:00 - 12:30 | [2_2: Personal R Administration 2 of 2](day2_2) | David Aja       |
| 12:30 - 13:30 | *Lunch break*                                   |                 |
| 13:30 - 15:00 | [2_3: Git/GitHub 2 of 2](day2_3)                | Jenny Bryan     |
| 15:00 - 15:30 | *Coffee break*                                  |                 |
| 15:30 - 17:00 | [2_4: Iterating well with purrr](day2_4)        | Shannon Pileggi |

------------------------------------------------------------------------

## People

| Role       | Name            | Site                                                | GitHub         | Twitter          |
|------------|------------|--------------------------|------------|------------|
| Instructor | Shannon Pileggi | [pipinghotdata.com](https://www.pipinghotdata.com/) | [shannonpileggi](https://github.com/shannonpileggi) | [@PipingHotData](https://twitter.com/PipingHotData)  |
| Instructor | Jenny Bryan     | [jennybryan.org](https://jennybryan.org/)           | [jennybc](https://github.com/jennybc)        | [@jennybryan](https://twitter.com/JennyBryan)     |
| Instructor | David Aja       | [edavidaja.com](https://edavidaja.com/)             | [edavidaja](https://github.com/edavidaja)      | [@peeltothepithy](https://twitter.com/peeltothepithy) |
| TA         | Amanda Gadrow   |                                                     | [ajmcoqui](https://github.com/ajmcoqui)      | [@ajmcoqui](https://twitter.com/ajmcoqui)                 |
| TA         | Ryan Johnson    |                                                     | [ryjohnson09](https://github.com/ryjohnson09)      | [@ryjohnson09](https://twitter.com/ryjohnson09)              |
| TA         | Andrie de Vries |                                                     | [andrie](https://github.com/andrie)               | [@RevoAndrie](https://twitter.com/RevoAndrie)                 |
| TA         | Daniel Sjoberg  |  [danieldsjoberg.com](https://www.danieldsjoberg.com/) | [ddsjoberg](https://github.com/ddsjoberg)      |[@statistishdan](https://twitter.com/statistishdan)  |
| TA         | Crystal Lewis   |                                                     | [Cghlewis](https://github.com/Cghlewis)       | [@Cghlewis](https://twitter.com/Cghlewis)                 |

------------------------------------------------------------------------

## Overview

This is a two-day hands on workshop designed for experienced R and RStudio users who want to (re)design their R lifestyle.
You'll learn holistic workflows that address the most common sources of friction in data analysis.
We’ll work on project-oriented workflows, version control for data science (Git/GitHub!), maintaining your R installation, and how to plan for collaboration, communication, and iteration (incl. RMarkdown).

At the conclusion of the workshop, you should have: knowledge of your R installation that enhances your ability to maintain it, workflows that facilitate collaboration with yourself or others (including version control and strategies for file systems), tools to improve debugging processes, and methods to address repetitive tasks with the purrr package.

------------------------------------------------------------------------

## Is this course for me?

This course will be appropriate for you if you answer yes to these questions:

-   Have you been using R for a while and feel there might be better ways to organize your R life, but don't know what they are?

-   Do you want to streamline your workflow for doing analysis and automating repetitive tasks in R?

-   Are you willing to get into the weeds of your R installation, project organization, error messages, and source code?

------------------------------------------------------------------------

## Learning objectives

### Project-oriented workflow (2 sessions)

-   Establish the concept of the project as the basic organizational unit of work.
    RStudio offers rich support for this way of working via **P**rojects.

-   Describe benefits of project oriented workflows.

-   Apply best practices for working in RStudio projects, including

    -   Creating robust file paths that travel well in time and space (someone else's computer, your computer a year from now) with base R and with the {here} and {fs} packages.

    -   Constructing human and machine readable file names that sort nicely.

    -   Differentiating workflow elements, analysis inputs, and analysis outputs in project structure to create navigable programming interfaces.

    -   Restarting R frequently, with a blank slate.

### Git/GitHub (2 sessions)

-   Employ version control via git and GitHub with operations including commit, push and pull.

-   Fork and clone from remote repositories.

-   Describe importance of viewing commits and diffs.

-   Compile markdown reports from an R script for sharing code products on GitHub.

-   Create a project web site via GitHub Pages.

-   Compare and execute different methods to re-visit previous versions of projects.

-   Utilize branches as safety nets for code experimentation.

-   Explain situations that can create merge conflicts and strategies to resolve them.

### Personal R Administration (2 sessions)

-   Identify where software, packages, and configuration files are located on your operating system via base R, {fs}, {usethis}, and {devtools} functions.

-   Explain the scope and purpose of `.Renviron` and `.Rprofile` configuration files when starting R.
    Modify these files for your personal needs and preferences.

-   Employ strategies for package management, including establishing where packages are installed, how to upgrade and downgrade, how to install from source, and actual package managers.

-   Locate and navigate R package source code for better understanding of internal operations or troubleshooting.

-   Identify what is in your current R session (packages, versions); briefly introduce {renv} to create a reproducible environment.

### Debugging (1 session)

-   Locate and view function source code.

-   Examine function source code to generate insights on errors.

-   Apply strategies to effectively search GitHub.

-   Distinguish between strategies for debugging your own code versus someone else's code.

-   Discuss debugging functions (`traceback()`, `browser()`, `debug()`, `trace()`, and `recover()`) and the additional benefits of employing some of these strategies within RStudio.

### Iterating well with purrr (1 session)

-   Describe drawbacks of copying and pasting R code.

-   Complete tidyverse style code with the pipe operator (`%>%` in {magrittr}, and the newer `|>` in base R).

-   Accomplish iteration through vectorized functions.

-   Leverage `group_by()` as an iterative technique.

-   Explain differences between base R and {purrr} iterative functions.

-   Explore lists as an object to store information of varying types and sizes; explain how to extract elements from a list.

-   Apply functions from the `purrr::map_` family to perform iteration as an alternative to loops.

------------------------------------------------------------------------

## Instructors

Shannon Pileggi PhD is a Data Scientist with more than ten years of experience partnering on data analysis with diverse stakeholders in academic, corporate, tech, public health, and clinical research settings.
An enthusiastic educator and statistical collaborator, Shannon started her career in academia as a Lecturer with the Institute for Quantitative Theory and Methods at Emory University, and later as an Assistant Professor at California Polytechnic State University, San Luis Obispo.
When she transitioned to industry in 2019, Shannon leveraged open source and community resources to adopt modern programming practices and workflows in R.
In 2020, Shannon began to give back to the R community through blogging and developing R-Ladies workshops; she currently serves as a member of the R-Ladies Global Team.
Shannon spends her days wrangling data, creating reproducible reports, building shiny apps, developing R packages, and mentoring junior Data Scientists at The Prostate Cancer Clinical Trials Consortium, housed under Memorial Sloan Kettering Cancer Center.

Jenny is a software engineer at RStudio, on the tidyverse team.
She is a recovering biostatistician who takes special delight in eliminating the small agonies of data analysis.
Jenny is the maintainer of many R packages, in the areas of data import, web APIs, Git/GitHub, and package development.
She has been working in R/S for over 20 years and is a member of the R Foundation.
Prior to joining RStudio, she was a professor of statistics at the University of British Columbia.

David Aja is a Solutions Engineer at RStudio.
He helps data scientists and IT communicate about their needs.
Before joining RStudio, he worked as a data scientist in the public sector.

------------------------------------------------------------------------

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
