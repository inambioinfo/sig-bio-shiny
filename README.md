# sig-bio-shiny

<!-- badges: start -->
  [![Lifecycle: maturing](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)
  [![Build Status](https://travis-ci.org/sk-sahu/sig-bio-shiny.svg?branch=master)](https://travis-ci.org/sk-sahu/sig-bio-shiny)
  [![CircleCI](https://circleci.com/gh/sk-sahu/sig-bio-shiny.svg?style=svg)](https://circleci.com/gh/sk-sahu/sig-bio-shiny)
  [![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/sudosk/sig-bio-shiny)](https://hub.docker.com/repository/docker/sudosk/sig-bio-shiny/builds)
<!-- badges: end -->

R shiny application for doing significant biology on a set of genes.

1. [Requirement](#requirement)
2. [Download](#download)
3. [Set Up](#set-up)
4. [Run the shiny app](#run-the-shiny-app)
5. [FAQ](#faq)
6. [Reference](#reference)


## Requirement
Need atleast 8GB of RAM in the system

## Download
Clone using git
```
git clone https://github.com/sk-sahu/sig-bio-shiny.git
```
Download using wget
```
wget https://github.com/sk-sahu/sig-bio-shiny/archive/master.zip
unzip master.zip && mv sig-bio-shiny-master sig-bio-shiny
```

## Set Up
To install all the required R packages and organism database run `setup.R`

from terminal
```
cd sig-bio-shiny
Rscript setup.R
```

## Run the shiny app
```
Rscript app.R
```
Access the app in your browser with output URL.

## FAQ
[HELP](HELP.md)

## Reference
[here](reference.md)
