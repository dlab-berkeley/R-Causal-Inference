# Causal Inference in R Workshop

[![Datahub](https://img.shields.io/badge/launch-datahub-blue)](https://dlab.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FR-Causal-Inference&urlpath=rstudio%2F&branch=main) [![Binder](http://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/dlab-berkeley/R-Causal-Inference/HEAD?urlpath=rstudio)

This repository contains the materials for the Causal Inference in R workshop.

### Prerequisites 

Some prior experience with R is recommended and expected. Familiairty with basic statistical concepts such as regression and hypothesis testing is useful. Because causal inference relies on certain assumptions, basic familiarity with statistics and probability is expected. 

## Workshop Goals

This interactive workshop focuses on causal inference using observational data and machine learning methods to model heterogeneous treatment effects. We establish core causal inference concepts, including the potential outcomes framework and essential statistical techniques (e.g., propensity score matching) used for estimating treatment effects with observational data.

## Learning Objectives 

After completing this workshop, you will be able to: 
- Understand the potential outcomes framework for causal inference.
- Apply Propensity Score Matching (PSM) to control for confounders and assess balance.
- Use instrumental variables for addressing unobserved confounding.

## Workshop Structure 

The Causal Inference and Machine Learning workshop takes 2 hours and is deviveved in a lecture-style coding walkthrough with practical exercises, breaks, and interactive discussions. 

## Installation Instructions

RStudio is a software commonly used by R practitioners to develop code in R. We will use RStudio to go through the workshop materials, which requires the installation of both the R language and the RStudio software. If you would like to run R on your own computer, complete the following steps prior to the workshop:

1.  [Download R](https://cloud.r-project.org/): Follow the links according to the operating system you are running. You will first need to click on a link corresponding to your operating system, and then an additional link to select a specific version of R. Download the package, and install R onto your computer. You should install the most recent version (at least version 4.1).

    -   If you are using a Mac, click "Download R for macOS" and then select the right version of R. You will need to select the version corresponding to your specific version of macOS, as well as whether you have an Intel or Apple Silicon Mac.
    -   If you are using Windows, click "Download R for Windows", then click "base", and click the download link.
    -   If you are using Linux, click on the link corresponding to your Linux distribution, and then follow the instructions.

2.  [Download RStudio](https://rstudio.com/products/rstudio/download/#download): Install RStudio Desktop. This should be free. Do this after you have already installed R. The D-Lab strongly recommends an RStudio edition of 2022.02.0+443 "Prairie Trillium" or higher.

    -   Some individuals with older operating systems may run into odd issues. If you are running into issues with the installation of RStudio, you may need to install a specific version of RStudio. Please check [this link](https://www.rstudio.com/products/rstudio/older-versions/) if this applies to you.

3.  Download these R Fundamentals [workshop materials](https://github.com/dlab-berkeley/R-Fundamentals):

    -   Click the green "Code" button in the top right of the repository information.
    -   Click "Download Zip".
    -   Extract this file to a folder on your computer where you can easily access it (we recommend Desktop).

4.  Optional: if you're familiar with `git`, you can instead clone this repository by opening a terminal and entering `git clone git@github.com:dlab-berkeley/R-Fundamentals.git`.

## Is R not working on your laptop?

If you do not have R installed and the materials loaded on your workshop by the time it starts, we *strongly* recommend using the UC Berkeley DataHub to run the materials for these lessons. You can access the DataHub by clicking the following button:

[![DataHub](https://img.shields.io/badge/launch-datahub-blue)](https://dlab.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FR-Causal-Inference&urlpath=rstudio%2F&branch=main)

Some users may have to click the link twice if the materials do not load initially.

The DataHub downloads this repository, along with any necessary packages, and allows you to run the materials in an RStudio instance on UC Berkeley's servers. No installation is needed from your end - you only need an internet browser and a CalNet ID to log in. By using the DataHub, you can save your work and come back to it at any time. When you want to return to your saved work, go straight to [DataHub](https://dlab.datahub.berkeley.edu), sign in, and click on the `R-Causal-Inference` folder.

If you don't have a Berkeley CalNet ID, you can still run these lessons in the cloud, by clicking this button:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dlab-berkeley/R-Causal-Inference/HEAD?urlpath=rstudio)

If you are loading Binder with this repository for the first time, it may take a few minutes to set up. Binder operates similarly to the D-Lab DataHub, but on a different set of servers. By using Binder, however, you cannot save your work.

## Run the Code

Now that you have all the required software and materials, you need to run the code.

1.  Launch the RStudio software.

2.  Use the file navigator to find the R-Causal-Inference folder you downloaded from Github. Open `R-Causal-Inference.Rmd` in the "lessons folder" by double clicking on the file.

3.  Place your cursor on a given line and press `Command + Enter` (Mac) or `Control + Enter` (PC) to run an individual line of code.

4.  The `solutions` folder contains the solutions to the challenge problems.

# Additional Resources

Check out the following online resources to learn more about causal inference:

- [The Book of Why](https://bayes.cs.ucla.edu/WHY/) by Judea Pearl: This popular book provides an accessible introduction to causal inference concepts.
- [Causal Inference for the Brave and True](https://matheusfacure.github.io/python-causality-handbook/landing-page.html): This free online book by Matheus Facure offers an intuitive introduction to causal inference with Python and R examples.
- [Causal Inference: What If](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/) by Hernán and Robins: Often referred to as the “bible of causal inference,” this free online textbook is a comprehensive reference for causal inference concepts. 
- [Causal Inference with R](https://campus.datacamp.com/courses/causal-inference-with-r-regression/regressions-1-introduction-to-regression-as-causality?ex=1): Hosted on DataCamp, this interactive course teaches causal inference methods using R with practical coding exercises.
- [MIT's Causal Inference Course](https://ocw.mit.edu/courses/6-s897-machine-learning-for-healthcare-spring-2019/resources/lecture-14-causal-inference-part-1/): This lecture by David Sontag at MIT discusses causal inference, examples of causal questions, and how these guide treatment decisions. He explains the Rubin-Neyman causal model as a potential outcome framework.

# About the UC Berkeley D-Lab

D-Lab works with Berkeley faculty, research staff, and students to advance data-intensive social science and humanities research. Our goal at D-Lab is to provide practical training, staff support, resources, and space to enable you to use R for your own research applications. Our services cater to all skill levels and no programming, statistical, or computer science backgrounds are necessary. We offer these services in the form of workshops, one-to-one consulting, and working groups that cover a variety of research topics, digital tools, and programming languages.

Visit the [D-Lab homepage](https://dlab.berkeley.edu/) to learn more about us. You can view our [calendar](https://dlab.berkeley.edu/events/calendar) for upcoming events, learn about how to utilize our [consulting](https://dlab.berkeley.edu/consulting) and [data](https://dlab.berkeley.edu/data) services, and check out upcoming [workshops](https://dlab.berkeley.edu/events/workshops).

# Other D-Lab R Workshops

D-Lab offers a variety of R workshops, catered toward different levels of expertise.

## Basic Competency

-   [R Data Wrangling](https://github.com/dlab-berkeley/R-Data-Wrangling)
-   [R Data Visualization](https://github.com/dlab-berkeley/R-Data-Visualization)
-   [R Census Data](https://github.com/dlab-berkeley/Census-Data-in-R)

## Intermediate/Advanced Competency

-   [R Geospatial Fundamentals](https://github.com/dlab-berkeley/R-Geospatial-Fundamentals)
-   [R Machine Learning](https://github.com/dlab-berkeley/R-Machine-Learning)
-   [R Deep Learning](https://github.com/dlab-berkeley/R-Deep-Learning)

# Contributors

- Jose Aveldanes
- Tom van Nuenen
