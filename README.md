# these-R-nice
Compilação de *packages* R que vou encontrando e não quero perder.

:writing\_hand: Autor: Bruno A Lima
----------------------

As minhas principais fontes são as *newsletters* da [Business Science University](https://university.business-science.io/), os *e-mails* de [R weekly](https://rweekly.org/), o *blog* [R-bloggers](https://www.r-bloggers.com/) e o *site* [Code Learning](https://www.222222.best/).

### Profiling (EDA) :eyes:

- [naniar](https://github.com/njtierney/naniar) - {naniar} provides principled, tidy ways to summarise, visualise, and manipulate missing data with minimal deviations from the workflows in ggplot2 and tidy data.

- [janitor](https://github.com/sfirke/janitor) - {janitor} has simple functions for examining and cleaning dirty data.[Exemplo do seu uso](https://garthtarr.github.io/meatR/janitor.html)

### Bases de dados :bank:

- [CRAN Task View: Databases with R](https://github.com/terrytangyuan/ctv-databases)

### Visualização :bar_chart:

- [ggplot2 extensions](https://exts.ggplot2.tidyverse.org/gallery/)

- [gganimate](https://gganimate.com/) - {gganimate} extends the grammar of graphics as implemented by {ggplot2} to include the description of animation. It does this by providing a range of new grammar classes that can be added to the plot object in order to customise how it should change with time.

- [ggstatsplot](https://github.com/IndrajeetPatil/ggstatsplot) - {ggstatsplot} is an extension of {ggplot2} package for creating graphics with details from statistical tests included in the information-rich plots themselves.

- [ggpubr](https://github.com/kassambara/ggpubr) - The {ggpubr} package provides some easy-to-use functions for creating and customizing {ggplot2} - based publication ready plots.

- [ggbiplot](https://github.com/vqv/ggbiplot) - An implementation of the biplot using {ggplot2}. The package provides two functions: `ggscreeplot()` and `ggbiplot()`. {ggbiplot} aims to be a drop-in replacement for the built-in R function `biplot.princomp()` with extended functionality for labeling groups, drawing a correlation circle, and adding Normal probability ellipsoids.

- [ggside](https://github.com/jtlandis/ggside) - this package expands on the ggplot2 and  allows the user to add graphical information about main panel’s axis with a boxplot or a density distribution.

- [patchwork](https://patchwork.data-imaginist.com/) - he goal of {patchwork} is to make it ridiculously simple to combine separate ggplots into the same graphic.

- [gridExtra](https://www.r-bloggers.com/2011/04/extra-extra-get-your-gridextra/) - Arranging multiple plots on a page.[Basic examples](https://cran.r-project.org/web/packages/egg/vignettes/Ecosystem.html) and [more](https://www.r-graph-gallery.com/261-multiple-graphs-on-same-page.html).

- [{ggiraph} makes ‘ggplot’ graphics interactive.](https://github.com/davidgohel/ggiraph) - {ggiraph} is a tool that allows you to create dynamic ggplot graphs. This allows you to add tooltips, hover effects and JavaScript actions to the graphics. The package also allows the selection of graphical elements when used in shiny applications.

#### Mapas :world_map:

- [ggmap](https://github.com/dkahle/ggmap) - {ggmap} is an R package that makes it easy to retrieve raster map tiles from popular online mapping services like Google Maps and Stamen Maps and plot them using the {ggplot2} framework.
- [Simple Features for R](https://github.com/r-spatial/sf) - A package that provides simple features access for R.

#### Redes :goal_net:

- [Awesome Network Analysis -R](https://github.com/briatte/awesome-network-analysis#r)

#### Correlações :chart_with_upwards_trend:

- [corrplot]() - The R package `corrplot` is for visualizing correlation matrices and confidence intervals.[vignette](https://cran.r-project.org/web/packages/corrplot/vignettes/corrplot-intro.html)

### Tabelas :card_index: :ticket:

- [mmtable2](https://github.com/ianmoran11/mmtable2) - {mmtable2} allows you to create and combine tables with a ggplot2/patchwork syntax. [vídeo](https://www.youtube.com/watch?v=6FvStEghDdg)

- [gt](https://gt.rstudio.com/) - With the {gt} package, anyone can make wonderful-looking tables using the R programming language. 
    - [Introduction to Creating gt Tables](https://gt.rstudio.com/articles/intro-creating-gt-tables.html)
    - [Exploring the {gt} Package in R](https://towardsdatascience.com/exploring-the-gt-grammar-of-tables-package-in-r-7fff9d0b40cd)
    - [Great Looking Tables: gt](https://www.r-bloggers.com/2020/04/great-looking-tables-gt-v0-2/)
- [gtsummary](http://www.danieldsjoberg.com/gtsummary/) - The {gtsummary} package provides an elegant and flexible way to create publication-ready analytical and summary tables using the R programming language. [vídeo](https://www.youtube.com/watch?v=fjAMsGISyXw)
- [ttt - Formatted tables the easy way](https://github.com/benjaminrich/ttt) - {ttt} stands for "The Table Tool" (or, if you prefer "Tables! Tables! Tables!"). It allows you to creates structured, formatted HTML tables in a flexible and convenient way ([vignette](https://benjaminrich.github.io/ttt/vignettes/ttt-intro.html)).

### Manipulação de dados :hammer_and_wrench:

- [broom](https://github.com/tidymodels/broom) - {broom} summarizes key information about models in tidy `tibble()`s.

### Time series :hourglass:

- [CRAN Task View: Time Series Analysis](https://github.com/robjhyndman/ctv-TimeSeries)

- [fable](http://fable.tidyverts.org/) - The R package {fable} provides a collection of commonly used univariate and multivariate time series forecasting models including exponential smoothing via state space models and automatic ARIMA modelling. 

- [tsibble](https://tsibble.tidyverts.org/) - The {tsibble} package provides a data infrastructure for tidy temporal data with wrangling tools.
- [imputeTS](https://github.com/SteffenMoritz/imputeTS) - The imputeTS package specializes on (univariate) time series imputation.[package website](https://steffenmoritz.github.io/imputeTS/index.html)

### Shiny :iphone:

- [Engineering Production-Grade Shiny Apps](https://engineering-shiny.org/index.html)
- [Mastering Shiny](https://mastering-shiny.org/)

### a testar :boom:

- [data.table](https://github.com/Rdatatable/data.table) - `data.table` provides a high-performance version of base R's `data.frame` with syntax and feature enhancements for ease of use, convenience and programming speed. Introduction to data.table [vignette](https://cran.r-project.org/web/packages/data.table/vignettes/datatable-intro.html)

- [r-color-palettes](https://github.com/EmilHvitfeldt/r-color-palettes#blogposts-and-other-resources) - Comprehensive list of color palettes in r

- [sparklyr](https://github.com/sparklyr/sparklyr) - R interface for Apache Spark


:book: Livros e tutoriais
-------------------------
- [The targets R Package User Manual](https://books.ropensci.org/targets/)
- [R books](https://github.com/RomanTsegelskyi/rbooks)
- [awesome-r-learning-resources](https://github.com/iamericfletcher/awesome-r-learning-resources#readme)
- [awesome-R](https://github.com/qinwf/awesome-R)
- [Big Book of R](https://www.bigbookofr.com/)
- **An Introduction to Statistical Learning with Applications in R (ISLR)**
  - [15 hours of expert videos](https://www.r-bloggers.com/2014/09/in-depth-introduction-to-machine-learning-in-15-hours-of-expert-videos/)
  - [ISLR tidymodels Labs](https://emilhvitfeldt.github.io/ISLR-tidymodels-labs/index.html)
- [curso em video](https://www.cursoemvideo.com/cursos/)
- [Forecasting: Principles and Practice](https://otexts.com/fpp2/)
- [Analytics for industRy](https://garthtarr.github.io/meatR/index.html)
- [swirl courses](https://github.com/swirldev/swirl_courses)
- [Statistical Rethinking: A Bayesian Course](https://github.com/rmcelreath/stat_rethinking_2020) and [here](https://github.com/rmcelreath/rethinking)
- [Data Cleaning: Outlier Detection and Imputation of Missing Values](https://palomar.home.ece.ust.hk/MAFS6010R_lectures/slides_data_cleaning.html#1)
- [Awesome official statistics software](https://github.com/SNStatComp/awesome-official-statistics-software) - An awesome list of open source statistical software useful for creating and accessing official statistics.

### CRAN Task Views

- [ctv on CRAN](https://cran.r-project.org/web/views/)
- [Anomaly Detection with R](https://github.com/pridiltal/ctv-AnomalyDetection)
- [Forensic Science with R](https://github.com/sctyner/ctv-forsci)

### Data sets

- [awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets)
- [Datasets collected from R packages](https://github.com/selva86/datasets)

### Outras cenas :bowtie:

- [icons .md](https://gist.github.com/rxaviers/7360908) 