# these-R-nice
Compilação de *packages* R que vou encontrando e não quero perder.

:writing\_hand: Autor: Bruno A Lima
----------------------


As minhas principais fontes são as *newsletters* da [Business Science University](https://university.business-science.io/), os *e-mails* de [R weekly](https://rweekly.org/), o *blog* [R-bloggers](https://www.r-bloggers.com/) e eventualmente outras cenas...

### Profiling (EDA) :eyes:

- [DataExplorer](http://boxuancui.github.io/DataExplorer/index.html) - automates most of data handling and visualization. [Exemplo de uso](https://cran.r-project.org/web/packages/DataExplorer/vignettes/dataexplorer-intro.html).

- [SmartEDA](https://daya6489.github.io/SmartEDA/) - helps in getting the complete exploratory data analysis just by running the function instead of writing lengthy r code. [Exemplo de uso](https://cran.r-project.org/web/packages/SmartEDA/vignettes/SmartEDA.html#introduction)

- [dlookr](https://github.com/choonghyunryu/dlookr) - Diagnose, explore and transform data. [Overview page.](https://choonghyunryu.github.io/dlookr/index.html)

- [Hmisc](https://hbiostat.org/R/Hmisc/) - A set of functions to put together in an `rmarkdow` html document using RStudio and `knitr`. [Exemplo de uso](https://hbiostat.org/R/Hmisc/examples.html)

- [naniar](https://github.com/njtierney/naniar) - {naniar} provides principled, tidy ways to summarise, visualise, and manipulate missing data with minimal deviations from the workflows in ggplot2 and tidy data.

- [janitor](https://github.com/sfirke/janitor) - {janitor} has simple functions for examining and cleaning dirty data.[Exemplo de uso](https://garthtarr.github.io/meatR/janitor.html)

- [skimr](https://github.com/ropensci/skimr/) - provides a frictionless approach to summary statistics the user can skim quickly to understand their data. It comes with a set of default summary functions for a wide variety of data types. [Skim statistics in the console](https://docs.ropensci.org/skimr/articles/Supporting_additional_objects.html).

- [summarytools](https://cran.r-project.org/web/packages/summarytools/vignettes/Introduction.html) - provides a coherent set of functions centered on data exploration and simple reporting.

- [descriptr](https://blog.rsquaredacademy.com/introducing-descriptr/) -  a set of tools for generating descriptive/summary statistics. A more [comprehensive documentation](https://descriptr.rsquaredacademy.com/index.html) on using the package.

- [inspectdf](https://alastairrushworth.github.io/inspectdf/index.html) - a collection of utilities for columnwise summary, comparison and visualisation of data frames. 

- [SatAid](https://github.com/VincentAlcazer/StatAid) - a free open-source software provided as an R package allowing clinicians and researchers to perform statistical analysis through an intuitive graphical interface.

- [sjmisc](https://strengejacke.github.io/sjmisc/index.html) - Data and Variable Transformation Functions

- [psych](https://personality-project.org/r/psych/) - A general purpose toolbox for personality, psychometric theory and experimental psychology

- [tidylog](https://github.com/elbersb/tidylog/) - The goal of {tidylog} is to provide feedback about {dplyr} and {tidyr} operations.

### Bases de dados :bank:

- [CRAN Task View: Databases with R](https://github.com/terrytangyuan/ctv-databases)

### Visualização :bar_chart:

- [ggplot2 extensions](https://exts.ggplot2.tidyverse.org/gallery/)

- [ggformula](https://github.com/ProjectMOSAIC/ggformula) - This package captures and extends the excellent simplicity of the {lattice}-graphics formula interface, while providing the intuitive “add this component” capabilities of {ggplot2}. [Exemplos de uso](http://www.mosaic-web.org/ggformula/).

- [gghighlight](https://github.com/yutannihilation/gghighlight/) - Highlight geoms in {ggplot2}. [Introduction to](https://yutannihilation.github.io/gghighlight/articles/gghighlight.html) {gghighlight}.

- [gganimate](https://gganimate.com/) - {gganimate} extends the grammar of graphics as implemented by {ggplot2} to include the description of animation. It does this by providing a range of new grammar classes that can be added to the plot object in order to customise how it should change with time.

- [ggiraph](https://davidgohel.github.io/ggiraph/index.html) - {ggiraph} is a tool that allows you to create dynamic {ggplot} graphs. This allows you to add tooltips, hover effects and JavaScript actions to the graphics.

- [ggstatsplot](https://github.com/IndrajeetPatil/ggstatsplot) - {ggstatsplot} is an extension of {ggplot2} package for creating graphics with details from statistical tests included in the information-rich plots themselves.

- [ggpubr](https://github.com/kassambara/ggpubr) - The {ggpubr} package provides some easy-to-use functions for creating and customizing {ggplot2} - based publication ready plots.

- [ggbiplot](https://github.com/vqv/ggbiplot) - An implementation of the biplot using {ggplot2}. The package provides two functions: `ggscreeplot()` and `ggbiplot()`. {ggbiplot} aims to be a drop-in replacement for the built-in R function `biplot.princomp()` with extended functionality for labeling groups, drawing a correlation circle, and adding Normal probability ellipsoids.

- [ggside](https://github.com/jtlandis/ggside) - this package expands on the ggplot2 and  allows the user to add graphical information about main panel’s axis with a boxplot or a density distribution.

- [patchwork](https://patchwork.data-imaginist.com/) - he goal of {patchwork} is to make it ridiculously simple to combine separate ggplots into the same graphic.

- [gridExtra](https://www.r-bloggers.com/2011/04/extra-extra-get-your-gridextra/) - Arranging multiple plots on a page.[Basic examples](https://cran.r-project.org/web/packages/egg/vignettes/Ecosystem.html) and [more](https://www.r-graph-gallery.com/261-multiple-graphs-on-same-page.html).

- [ggiraph](https://github.com/davidgohel/ggiraph) - {ggiraph} makes ‘ggplot’ graphics interactive. It is a tool that allows you to create dynamic ggplot graphs. This allows you to add tooltips, hover effects and JavaScript actions to the graphics. The package also allows the selection of graphical elements when used in shiny applications.

- [echarts4r](https://echarts4r.john-coene.com/index.html) - Interactive visualisations for R via Apache ECharts

- [highcharter](https://jkunst.com/highcharter/) - an **R** wrapper for [Highcharts](https://www.highcharts.com/) javascript library and its modules. Highcharts is very flexible and customizable javascript charting library and it has a great and powerful API.

- [ggdist](https://github.com/mjskay/ggdist) - Visualizations of distributions and uncertainty. A [video example](https://www.youtube.com/watch?v=nz2gHnaqX2w). [Example code](https://github.com/business-science/free_r_tips/blob/master/042_raincloud_plots/042_raincloud_plots.R)

- [visdat](https://cran.r-project.org/web/packages/visdat/) - Create preliminary exploratory data visualisations of an entire dataset to identify problems or unexpected features using 'ggplot2'.

- [trelliscopejs](https://hafen.github.io/trelliscopejs/index.html) - Trelliscope is a visualization approach based on the idea of “small multiples” or Trellis Display, where data are split into groups and a plot is made for each group, with the resulting plots arranged in a grid.

- [rbokeh](https://hafen.github.io/rbokeh/articles/rbokeh.html) - a flexible and powerful declarative framework for creating web-based plots.

- [trelliscopejs](https://hafen.github.io/trelliscopejs/index.html) - Trelliscope is a scalable, flexible, interactive approach to visualizing data.

#### Mapas :world_map:

- [ggmap](https://github.com/dkahle/ggmap) - {ggmap} is an R package that makes it easy to retrieve raster map tiles from popular online mapping services like Google Maps and Stamen Maps and plot them using the {ggplot2} framework.
- [sf](https://github.com/r-spatial/sf) - A package that provides simple features access for R.

#### Redes :goal_net:

- [Awesome Network Analysis -R](https://github.com/briatte/awesome-network-analysis#r)

#### Correlações :chart_with_upwards_trend:

- [corrplot](https://github.com/taiyun/corrplot) - The R package `corrplot` is for visualizing correlation matrices and confidence intervals.[vignette](https://cran.r-project.org/web/packages/corrplot/vignettes/corrplot-intro.html)
- [ggcorrplot](https://cran.r-project.org/web/packages/ggcorrplot/readme/README.html#:~:text=The%20ggcorrplot%20package%20can%20be,matrix%20of%20correlation%20p%2Dvalues.) - The ggcorrplot package can be used to visualize easily a correlation matrix using ggplot2
- [GGally](https://ggobi.github.io/ggally/) - GGally extends ggplot2 by adding several functions to reduce the complexity of combining geoms with transformed data

### Tabelas :ticket:

- [mmtable2](https://github.com/ianmoran11/mmtable2) - {mmtable2} allows you to create and combine tables with a ggplot2/patchwork syntax. [vídeo](https://www.youtube.com/watch?v=6FvStEghDdg)

- [gt](https://gt.rstudio.com/) - With the {gt} package, anyone can make wonderful-looking tables using the R programming language. 
    - [Introduction to Creating gt Tables](https://gt.rstudio.com/articles/intro-creating-gt-tables.html)
    - [Exploring the {gt} Package in R](https://towardsdatascience.com/exploring-the-gt-grammar-of-tables-package-in-r-7fff9d0b40cd)
    - [Great Looking Tables: gt](https://www.r-bloggers.com/2020/04/great-looking-tables-gt-v0-2/)
- [gtsummary](http://www.danieldsjoberg.com/gtsummary/) - The {gtsummary} package provides an elegant and flexible way to create publication-ready analytical and summary tables using the R programming language. [vídeo](https://www.youtube.com/watch?v=fjAMsGISyXw)
- [ttt - Formatted tables the easy way](https://github.com/benjaminrich/ttt) - {ttt} stands for "The Table Tool" (or, if you prefer "Tables! Tables! Tables!"). It allows you to creates structured, formatted HTML tables in a flexible and convenient way ([vignette](https://benjaminrich.github.io/ttt/vignettes/ttt-intro.html)).
- [printr](https://cran.r-project.org/web/packages/printr/vignettes/printr.html) - The {printr} package is a companion package to knitr.
- [stargazer](https://cran.r-project.org/web/packages/stargazer/vignettes/stargazer.pdf) -  an R package that creates well-formatted regression tables, with multiple models side-by-side, as well as for summary statistics tables, data frames, vectors and matrices.
- [reactable](https://glin.github.io/reactable/index.html) -Interactive data tables for R, based on the React Table library and made with reactR.
- [reactablefmtr](https://kcuilla.github.io/reactablefmtr/index.html) - The {reactablefmtr} package streamlines and enhances the styling and formatting of tables built with the {reactable} R package. The {reactablefmtr} package provides many conditional formatters that are highly customizable and easy to use.
- [modelsummary](https://vincentarelbundock.github.io/modelsummary/index.html) - {modelsummary} creates tables and plots to summarize statistical models and data in `R`.
- [tableone](https://cran.r-project.org/web/packages/tableone/) - Create 'Table 1' to Describe Baseline Characteristics with or without Propensity Score Weights
- [table1](https://cran.r-project.org/web/packages/table1/) - Create HTML tables of descriptive statistics, as one would expect to see as the first table (i.e. "Table 1") in a medical/epidemiological journal article.

- [sparkline](https://cran.r-project.org/web/packages/sparkline/index.html) - Include interactive sparkline charts in all R contexts with the convenience of 'htmlwidgets'. [Exemplo de uso _inline_](https://bart6114.github.io/sparklines/); [Exemplo de uso e {DT}](https://www.youtube.com/watch?v=BayiCqu0y9o)

### Manipulação de dados :hammer_and_wrench:

- [broom](https://github.com/tidymodels/broom) - {broom} summarizes key information about models in tidy `tibble()`s.

- [dtplyr](https://dtplyr.tidyverse.org/) -  The goal of {dtplyr} is to allow you to write {dplyr} code that is automatically translated to the equivalent, but usually much faster, {data.table} code. [A simple usage](https://www.tidyverse.org/blog/2019/11/dtplyr-1-0-0/).

- [data.table](https://github.com/Rdatatable/data.table) - `data.table` provides a high-performance version of base R's `data.frame` with syntax and feature enhancements for ease of use, convenience and programming speed. Introduction to data.table [vignette](https://cran.r-project.org/web/packages/data.table/vignettes/datatable-intro.html). [Exemplo de uso](https://atrebas.github.io/post/2019-03-03-datatable-dplyr/)

- [nplyr](https://markjrieke.github.io/nplyr/index.html) - a grammar of nested data manipulation that allows users to perform {dplyr}-like manipulations on data frames nested within a list-col of another data frame.

### Time series :hourglass:

- [CRAN Task View: Time Series Analysis](https://github.com/robjhyndman/ctv-TimeSeries)

- [fable](http://fable.tidyverts.org/) - The R package {fable} provides a collection of commonly used univariate and multivariate time series forecasting models including exponential smoothing via state space models and automatic ARIMA modelling. 

- [tsibble](https://tsibble.tidyverts.org/) - The {tsibble} package provides a data infrastructure for tidy temporal data with wrangling tools.

- [imputeTS](https://github.com/SteffenMoritz/imputeTS) - The imputeTS package specializes on (univariate) time series imputation. [package website](https://steffenmoritz.github.io/imputeTS/index.html)

- [anytime](https://cran.r-project.org/web/packages/anytime/index.html) - Anything to POSIXct or Date Converter

- [autostsm](https://cran.r-project.org/web/packages/autostsm/) - Automatic model selection for structural time series decomposition into trend, cycle, and seasonal components, plus optionality for structural interpolation, using the Kalman filter.

### Shiny :iphone:

- [Engineering Production-Grade Shiny Apps](https://engineering-shiny.org/index.html)
- [Mastering Shiny](https://mastering-shiny.org/)
- [shinydashboard](https://cran.r-project.org/web/packages/shinydashboard/index.html) - Create dashboards with 'Shiny'. [Exemplos de uso](https://rstudio.github.io/shinydashboard/)
- [shinydashboardPlus](https://cran.r-project.org/web/packages/shinydashboardPlus/index.html) - Extend {shinydashboard} with 'AdminLTE2' components. [Exemplo de uso](https://rinterface.com/shiny/shinydashboardPlus/)

### a testar :boom:

- [r-color-palettes](https://github.com/EmilHvitfeldt/r-color-palettes#blogposts-and-other-resources) - Comprehensive list of color palettes in r

- [sparklyr](https://github.com/sparklyr/sparklyr) - R interface for Apache Spark

- [disk.frame](https://github.com/xiaodaigh/disk.frame/) - performs a similar role to distributed systems for medium data which are datasets that are too large for RAM but not quite large enough to qualify as big data. {disk.frame} [is epic](https://www.brodrigues.co/blog/2019-09-03-disk_frame/)

- [easystats](https://github.com/easystats/easystats) - a collection of R packages, which aims to provide a unifying and consistent framework to tame, discipline, and harness the scary R statistics and their pesky models.

- [collapse](https://github.com/SebKrantz/collapse) - a C/C++ based package for data transformation and statistical computing in R.

- [tidyfst](https://cran.r-project.org/web/packages/tidyfst/index.html) - Tidy Verbs for Fast Data Manipulation. [Exemplo de uso](https://hope-data-science.github.io/tidyfst/articles/english_tutorial.html)

- [ggquickeda](https://github.com/smouksassi/ggquickeda) - This R package/Shiny app is a handy interface to `ggplot2`/`table1`

- [reactR](https://react-r.github.io/reactR/index.html) - provides a set of convenience functions for using `React` in R with `htmlwidget` constructor templates and local JavaScript dependencies. 

- [reactable](https://glin.github.io/reactable/index.html) - Interactive data tables for R, based on the `React Table` library and made with {reactR}.

- [lazyrmd](https://github.com/hafen/lazyrmd) - The {lazyrmd} R package provides an R Markdown html output format that enables plot outputs in the document to be lazily loaded.

### Cheat sheet :newspaper:

- [base R](lectures/base-r-cheat-sheet.pdf)
- [advanced R](lectures/advancedR.pdf)
- [Eurostat data](lectures/eurostat.pdf)
- [Searching CRAN with packagefinder](lectures/packagefinder.pdf)
- [ultimate cheat sheet](lectures/Data_Science_R_Workflow.pdf)
- [RStudio Cheat sheets](https://www.rstudio.com/resources/cheatsheets/) - here a post [about it](https://rviews.rstudio.com/2021/03/10/rstudio-open-source-resorurces)
- [Graphics Principles](https://github.com/GraphicsPrinciples/CheatSheet/blob/master/NVSCheatSheet.pdf) - here the [website](https://graphicsprinciples.github.io/)

:book: Livros e tutoriais
-------------------------
- [Free data science resources](https://github.com/alastairrushworth/free-data-science) - The goal of this page is to gather resources and learning materials across a broad range of popular data science topics and arrange them thematically. 
- [The targets R Package User Manual](https://books.ropensci.org/targets/)
- [R books](https://github.com/RomanTsegelskyi/rbooks)
- [awesome-r-learning-resources](https://github.com/iamericfletcher/awesome-r-learning-resources#readme)
- [awesome-R](https://github.com/qinwf/awesome-R)
- [funModeling](https://livebook.datascienceheroes.com/)
- [Big Book of R](https://www.bigbookofr.com/)
- **An Introduction to Statistical Learning with Applications in R (ISLR)**
  - [15 hours of expert videos](https://www.r-bloggers.com/2014/09/in-depth-introduction-to-machine-learning-in-15-hours-of-expert-videos/)
  - [ISLR tidymodels Labs](https://emilhvitfeldt.github.io/ISLR-tidymodels-labs/index.html)
  - [ISLR](https://cran.r-project.org/web/packages/ISLR2/index.html) - An Introduction to Statistical Learning with Applications in R, [Second Edition](https://www.statlearning.com/)
- **Epidemiology with R**
  - [An R View into Epidemiology](https://rviews.rstudio.com/2020/05/20/some-r-resources-for-epidemiology/)
  - [The Epidemiologist R Handbook](https://epirhandbook.com/)
  - [R for Epidemiology](https://www.r4epi.com/)
- [STHDA](http://www.sthda.com/english/) - Statistical tools for high-throughput data analysis
- [curso em video](https://www.cursoemvideo.com/cursos/)
- [Forecasting: Principles and Practice](https://otexts.com/fpp3/)
- [Analytics Vidhya](https://www.analyticsvidhya.com/blog/2015/12/complete-tutorial-time-series-modeling/) - A Complete Tutorial on Time Series Modeling in R
- [Analytics for industRy](https://garthtarr.github.io/meatR/index.html)
- [swirl courses](https://github.com/swirldev/swirl_courses)
- [Statistical Rethinking: A Bayesian Course](https://github.com/rmcelreath/stat_rethinking_2020) and [here](https://github.com/rmcelreath/rethinking)
- [Bayesian Modelling](lectures/lect1bayes.pdf)
- [Data Cleaning: Outlier Detection and Imputation of Missing Values](https://palomar.home.ece.ust.hk/MAFS6010R_lectures/slides_data_cleaning.html#1)
- [Awesome official statistics software](https://github.com/SNStatComp/awesome-official-statistics-software) - An awesome list of open source statistical software useful for creating and accessing official statistics.
- [Rsquared Academy](https://blog.rsquaredacademy.com/):
    + [Demystifying Regular Expressions in R](https://blog.rsquaredacademy.com/regular-expression-in-r/)
    + [A Comprehensive Introduction to Working with Databases using R](https://blog.rsquaredacademy.com/working-with-databases-using-r/)
- [EarthLab](https://www.earthdatascience.org/) - Earth Data Science contains open, tutorials and course materials covering topics including data integration, GIS and data intensive science.
- [Free data science resources](https://github.com/alastairrushworth/free-data-science) - a github repo with resources and learning materials across a broad range of popular data science topics
- **data.table**
    - [Listen Data](https://www.listendata.com/2016/10/r-data-table.html) - {data.table} Tutorial (with 50 Examples)
    - [machine learning plus](https://www.machinelearningplus.com/tag/data-table/) - Complete beginners guide to {data.table} in R
    - [Stata2R](https://stata2r.github.io/data.table/#introduction) - translates Stata to R with {data.table}
    - [Exploring, Visualizing, and Modeling Big Data with R](https://okanbulut.github.io/bigdata/wrangling-big-data.html#what-is-data.table) - Data wrangling with {data.table}
- [Data Science and Predictive Analytics (UMich HS650)](https://www.socr.umich.edu/people/dinov/DSPA_Courses.html) - The Data Science and Predictive Analytics (DSPA) course aims to build computational abilities, inferential thinking, and practical skills for tackling core data scientific challenges.
- [H2O.ai](https://docs.h2o.ai/h2o/latest-stable/h2o-docs/index.html) - H2O is an open source, in-memory, distributed, fast, and scalable machine learning and predictive analytics platform that allows you to build machine learning models on big data and provides easy productionalization of those models in an enterprise environment.

### CRAN Task Views

- [ctv on CRAN](https://cran.r-project.org/web/views/)
- [Anomaly Detection with R](https://github.com/pridiltal/ctv-AnomalyDetection)
- [Forensic Science with R](https://github.com/sctyner/ctv-forsci)

### Data sets

- [awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets)
- [Datasets collected from R packages](https://github.com/selva86/datasets)

### Outras cenas :bowtie:

- [icons .md](https://gist.github.com/rxaviers/7360908) 
- [Mathematics in R Markdown](https://rpruim.github.io/s341/S19/from-class/MathinRmd.html)
- [pkgsearch](https://r-hub.github.io/pkgsearch/) - Search and Query CRAN R Packages. {pkgsearch} uses R-hub web services that munge CRAN metadata and let you access it through several lenses.
