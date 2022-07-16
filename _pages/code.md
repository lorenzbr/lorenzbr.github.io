---
layout: archive
permalink: /code/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Code

## Portfolio Tracker

The Portfolio Tracker is an application to automatically track the portfolio performance of your stock investments. It is developed using R Shiny. This project is work in progress. Some code is public (mainly the backend) and can be found on my [GitHub profile](https://github.com/lorenzbr). The current version is deployed on AWS. It is instable and, at this time, should not serve as a basis for real investment decisions. Temporary accounts are only available upon request.

See [here](https://portfolio-tracker.net) for further information.

## icdGLM: EM by the Method of Weights for Incomplete Categorical Data in Generalized Linear Models

An R package published on CRAN that provides an estimator for generalized linear models with incomplete data for discrete covariates. The estimation is based on the EM algorithm by the method of weights by Ibrahim (1990). The package includes two example data sets which are provided in this paper. First, a data set from Stukel and Dain (1989) involves a study of 82 patients who experienced translaryngeal intubation (TLI) and were evaluated for laryngeal complications. A seoncd data set from Feigl and Zelen (1965) involves survival times of 33 leukemia patients which were classified according to the presence or absence of a morphologic characteristic of white cells.

See [here](https://rdocumentation.org/packages/icdGLM) for further information.

[PDF](https://cran.r-project.org/web/packages/icdGLM/icdGLM.pdf) [GitHub](https://github.com/lorenzbr/icdGLM)

## cryptowatchR: An API wrapper for Cryptowatch

This R package published on CRAN provides a wrapper for the [Cryptowatch API](https://docs.cryptowat.ch/rest-api/). You can get prices and other information (volume, trades, order books, bid and ask prices, live quotes, and more) about cryptocurrencies and crypto exchanges. The access is free of charge and does not require you to create a personal key. For example, you can easily retrieve historical prices for a large number of cryptocurrencies without setting up an account. For heavy users, the option to use your own personal key is included in the package as well.

See [here](https://rdocumentation.org/packages/cryptowatchR) for further information.

[PDF](https://cran.r-project.org/web/packages/cryptowatchR/cryptowatchR.pdf) [GitHub](https://github.com/lorenzbr/cryptowatchR)

## Misc

In recent years, I have been working a lot with patent data and data on technical standards. A few other repositories hence deal with the extraction (web crawlers) and transformation (parser) of such data. If you are interested, check them out on my [GitHub profile](https://github.com/lorenzbr).
