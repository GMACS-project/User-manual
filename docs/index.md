--- 
title: "Gmacs: mastering a modeling framework to assess Crustacean species"
author: "Matthieu Veron and the GMACS development Team"
date: "2022-07-14"
site: bookdown::bookdown_site
documentclass: book

bibliography: ["References/book.bib", "References/packages.bib", "References/articles.bib"]
biblio-style: apalike
link-citations: true
csl: elsevier-harvard2.csl

urlcolor: blue
# csl: chicago-fullnote-bibliography.csl
# csl: chicago-author-date-basque.csl


# url: your book url like https://bookdown.org/yihui/bookdown
# cover-image: path to the social sharing image like images/cover.jpg
# description: |
#   This is a minimal example of using the bookdown package to write a book.
#   The HTML output format for this example is bookdown::bs4_book,
#   set in the _output.yml file.
---




# Welcome {.unnumbered}

This is the online version of "*Gmacs: mastering a modeling framework to assess Crustacean species*", 
a user guide book __*currently under development*__ and that aims to merge 
and synthesize all the current and past work done by the Gmacs development team
since the inception of this project.

Statistical catch age models have several advantages over simple production
type models in that age and size composition data can be used to better inform
structural features such as recruitment variability, growth variability and 
total mortality rates. There are a number of generic age-structured models in use 
today (e.g., [Stock Synthesis](https://vlab.noaa.gov/web/stock-synthesis), 
[CASAL](https://niwa.co.nz/fisheries/tools-resources/casal), ...), but there are 
very few generic size-based, or staged-based models that are used in stock assessment.

The Generalized Model for Assessing Crustacean Stocks (GMACS) is an integrated 
analysis modelling framework designed to develop size-structured stock assessment 
models for crustacean species. 

Crab stocks of Alaska are managed by the North Pacific Fishery Management Council 
([NPFMC](http://npfmc.org)). Some stocks are assessed with integrated size-structured 
assessment models of the form described in @punt_review_2013. Currently, most of
these stocks are assessed using a stock-specific assessment model 
(e.g. @zheng_bristol_2014). In this context and with the aim of uniform the 
assessment process of these species, the Gmacs project aims to provide a software 
that will allow each stock to be assessed independently but using a single flexible 
modelling framework.

This book is designed to take you from knowing nothing about Gmacs and its utilities 

## Structure of the book {.unnumbered}

  * Chapter \@ref(Preface): What is Gmacs - How to get it installed 
  * Chapter \@ref(orga): File Organisation
  * Chapter \@ref(data-file): Data file description
  * Chapter \@ref(ctr-file): Control file description
  * Chapter \@ref(Project): Projection file description
  * Chapter \@ref(Rgmacs): A set of functions to help the user to fill/modify input files (have to be developed)
  * Chapter \@ref(run-plot): Running Gmacs and using the `gmr` package to plot results
  * Chapter \@ref(first-gmacs): Building your first stock assessment using Gmacs
  * Chapter \@ref(sad): Producing stock assessment documents
  * Chapter \@ref(faq): Frequently Asked Questions

## License {.unnumbered}

The Gmacs project has been and is still funded by the National Marine Fisheries Service and the Bering Sea Fisheries Research Foundation. This product is currently hosted by the Nation Oceanic and Atmospheric Administration ([NOAA](https://www.noaa.gov/)). 

