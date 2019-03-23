# Stats road-map

Hi, I'm a junior data scientist coming from clinical research. I've gained experience with experimental design, causal inference and basic statistical analysis while becoming a physician at Buenos Aires University. I've always being inclined towards epidemiology and statistics, gaining a profound love of stats and math as an adult. It was only a matter of time before I found out about data science and machine learning. From then on, I haven't stop reading, watching lectures, programming and practicing with datasets. Coming from a field outside computer science or statistics gave me a different approach on learning the needed skills, but also a different set of problems to solve on my way. Because of this, I decided to keep a record of all materials that helped me achieve those 'eureka' moments. I hope this list helps you too, feel free to push changes or ideas!

## Books

[The hundred page machine learning book](http://themlbook.com/wiki/doku.php): A beautifully crafted book with python examples and a friendly introduction on the mathematics behind lots of algorithms. It also takes you to the work flow of problem solving in ML.

[An introduction to statistical learning with applications in R](https://www-bcf.usc.edu/~gareth/ISL/ISLR%20First%20Printing.pdf): A good second step before reading one of the bibles of machine learning.

[The elements of statistical learning](https://web.stanford.edu/~hastie/ElemStatLearn/): A masterpiece that soon or later one has to read. Above the level of hundred-page machine learning but below Machine learning by Murphy.

[Machine Learning: A probabilistic perspective](https://doc.lagout.org/science/Artificial%20Intelligence/Machine%20learning/Machine%20Learning_%20A%20Probabilistic%20Perspective%20%5BMurphy%202012-08-24%5D.pdf): Amazing book that starts with stats and probability concept. Requires high knowledge on math and related concepts. A good book to start, stop and come back from time to time to realize that you understand more that the previous time.

[Practical Regression and Anova using R](https://cran.r-project.org/doc/contrib/Faraway-PRA.pdf): If you ever wonder how to do a regression fit step by step by hand, then this is the place to go. It also explain all parts of the output summary and how each one is calculated.

[Forecasting: Principles and Practice](https://otexts.com/fpp2/): A comprehensive introduction to forecasting methods using R.

[Regression modeling strategies](https://www.springer.com/la/book/9781441929181): Commonly used clinical prediction models. The author is a clinical researcher, so this is stats through the eyes of a doctor.

[R for Data Science](https://r4ds.had.co.nz): *Hadley Wickham* introduces R and the tidyverse package on an easy to read and very comprehensive book. I love everything that Wickham does, check out his classes on youtube too!

#### Experimental design & epidemiology

[Causal inference](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/): What's causal inference and how can it be achieve? Hernan use logic, models and direct acyclic graphs to answer this question.

#### Chapters

[Essentials of Clinical Research](https://www.researchgate.net/publication/297114700_Essentials_of_Clinical_Research): Most of the chapters are fully available on research-gate.

- [Chapter 17](https://www.researchgate.net/publication/226733813_Bias_Confounding_and_Effect_Modification) - Bias, Confounding, and Effect Modification: A good place to start when trying to learn these concepts.
- [Chapter 18](https://www.researchgate.net/publication/225876931_It's_All_About_Uncertainty) - It's all about uncertainty:  This chapter is aimed at providing the foundation for common sense issues that underlie why and what statistics is.

[Data Analysis Using Regression and Multilevel/Hierarchical Models](http://www.stat.columbia.edu/~gelman/arm/)

- [Chapter 25](http://www.stat.columbia.edu/~gelman/arm/missing.pdf) - Missing data imputation: Types of missing values and different imputing models to deal with them.

## Articles

#### Count data

[Visualizing count data using rootograms](https://arxiv.org/pdf/1605.01311.pdf): Rootograms are an awesome tool for visualizing the under/over-dispersion phenomena seen in Poisson and Negative Binomial models for count data.

[Regression models for count data in R](https://www.jstatsoft.org/article/view/v027i08/v27i08.pdf): A revision of the most common used models for count data using R. 

#### Hurdle models

[Gettin started with hurdle models](https://data.library.virginia.edu/getting-started-with-hurdle-models/): Step by step introduction for fitting and assessing hurdle models using R.

[Interpreting hurdle models](https://stats.idre.ucla.edu/stata/output/zero-inflated-poisson-regression/): Reading the output of hurdle models by using STATA output as an example.

#### Gradient boosting

[How to explain gradient boosting by Parr and Howard](https://explained.ai/gradient-boosting/index.html): A very concise guide made up of 3 parts that works as an introduction for learning GB fundamentals. Math notation is involved when explaining the models, but doesn't go to deep on it.

#### Generalized Estimating Equation

[Dependent samples from STAT 504](https://newonlinecourses.science.psu.edu/stat504/node/94/)

#### Hypothesis testing

[Tutorial on Fisher's exact test](https://www.sheffield.ac.uk/polopoly_fs/1.43998!/file/tutorial-9-fishers.pdf)

#### Causal inference

[Using causal diagrams to understand problems of confounding and selection bias](http://miror-ejd.eu/wp-content/uploads/sites/34/2016/10/MiRoR-Causality-ho.pdf): Heads up on dags, confounding and colliding.

#### Missing data & imputation

[Reducing bias in treatment effect estimation in observational studies suffering from missing data](http://academiccommons.columbia.edu/download/fedora_content/download/ac:129152/CONTENT/2004_01.pdf)

#### GAM

[Overview GAMM analysis of time series data](http://www.sfs.uni-tuebingen.de/~jvanrij/Tutorial/GAMM.html)

[Doing magic and analyzing seasonal time series with GAM (Generalized Additive Model in R](https://petolau.github.io/Analyzing-double-seasonal-time-series-with-GAM-in-R/)

[Geo-spatial analysis with generalized additive models](https://www.casact.org/education/rpm/2010/handouts/PM1-Guszcza.pdf)



## Videos & Courses

[Policy Analysis Using interrupted Time Series](https://www.edx.org/course/policy-analysis-using-interrupted-time-ubcx-itsx-2): Edx course on how to perform interrupted time series and regression discontinuity design.

[Causal Diagrams: Draw your assumptions before your conclusions](https://www.edx.org/course/causal-diagrams-draw-assumptions-harvardx-ph559x): Learn to use direct acyclic graphs for drawing causal inference. Helpful for identifying and illustrating the presence of confounders, mediators and colliders.

[Amazon machine learning course for data scientists](https://aws.amazon.com/training/learning-paths/machine-learning/data-scientist/): A must do course that introduce in a comprehensive manner the fundamental math behind regression.

#### Youtube

[StatQuest with Josh Starmer](https://www.youtube.com/user/joshstarmer/videos): A video series explaining multiple stats concepts in a simple light but in a thorough way.

[JBStatistics](https://www.youtube.com/user/jbstatistics/videos): Multiple concepts explained by problem solving.

[CRISP-DM: The dominant process for data mining](https://www.youtube.com/watch?v=civLio11SjQ): A step by step guide on cross-industry standard process for data mining. CRISP-DM is a guideline that helps data scientist to structure the problems in a business framework and make solutions more communicable for the target public.

[Stata learner](https://www.youtube.com/user/ashwinikalantri/playlists): A HarvardX course that was previously feature in EdX. It deals mostly with theoretical aspects of experimental design and how to perform data analysis using STATA. For those looking for an introduction to experimental design, you should give a shot to this video series.

[Understanding the Chapman–Kolmogorov equation](https://www.youtube.com/watch?v=W5P4kCpdhho): Visualizing Chapman-Kolmogorov by using Markov chains on time series.

Mathematics for Machine Learning Full Course - [Linear Algebra](https://www.youtube.com/watch?v=T3TpdPmTLso) and [Multivariate Calculus](https://www.youtube.com/watch?v=m998PdOCFcY)

[Graph theory playlist](https://www.youtube.com/playlist?list=PLDV1Zeh2NRsDGO4--qE8yH72HFL1Km93P)

[Liz Sander | Evolutionary Algorithms  Perfecting the Art of "Good Enough"](https://www.youtube.com/watch?v=iJ4MiibHt68): An introduction to genetic and evolutionary algorithms.

[Multi-Objective Problems](https://www.youtube.com/watch?v=56JOMkPvoKs)

[Creating correct and capable classifiers - Ian Ozsvald](https://www.youtube.com/watch?v=DkLPYccEJ8Y)

## Stackoverflow & Reddit

[On poisson regression models to estimate relative risk for binary outcomes](https://stats.stackexchange.com/questions/18595/poisson-regression-to-estimate-relative-risk-for-binary-outcomes).

[Null hypothesis of Chi-square test for independence](https://biology.stackexchange.com/questions/58221/null-hypothesis-of-chi-square-test-for-independence).

[Explaining what a singular matrix is](https://stats.stackexchange.com/questions/70899/what-correlation-makes-a-matrix-singular-and-what-are-implications-of-singularit)

[Relative risk standard errors and confidence interval](https://stats.stackexchange.com/questions/126727/why-doesnt-standard-error-for-ratios-have-log-in-it)

[Guidelines for writing data analysis report](https://www.reddit.com/r/datascience/comments/am2cep/guidelines_for_writing_data_analysis_reports/)

## Programming & Notebooks

[Titanic Database - Technical Analysis](https://rstudio-pubs-static.s3.amazonaws.com/311038_42bc748ec71f469a987bdb536c6c4e88.html)

#### Geo-spatial analysis

[Introduction to spatial analysis in R](https://jafflerbach.github.io/spatial-analysis-R/): Using sf and raster packages.

[Spatial analysis in R with the `sf` package](https://cdn.rawgit.com/rhodyrstats/geospatial_with_sf/bc2b17cf/geospatial_with_sf.html)

[Tidy spatial data in R: using `dplyr`, `tidyr`, and `ggplot2` with `sf`](http://strimas.com/r/tidy-sf/)