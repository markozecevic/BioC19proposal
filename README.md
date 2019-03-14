# Creating shareable CWL wrappers for your R tools

# Instructor(s) name(s) and contact information

Marko Zecevic - marko.zecevic at sbgenomics.com

# Workshop Description

The Cancer Genomics Cloud (CGC), powered by Seven Bridges and funded by the NCI hosts several massive public datasets alongside secure and scalable computational resources and optimized, portable bioinformatics tools. These tools, written in a variety of programming languages, are wrapped in Common Workflow Language (CWL) — a specification for describing analysis workflows and tools in a way that allows for platform interoperability and scalability. 

Many of the public tools are R scripts based on popular R/Bioconductor packages that can be run from the GUI or via API. We believe that scientific research communities would benefit greatly if these were integrated on a larger scale. Wrapping your tools in CWL and publishing them to CGC would enable you to share your data analysis workflows with a wide audience of researchers. 

In this workshop, we will present a guide and best practices for wrapping R scripts as CWL tools for integration into CGC (or any platform that supports CWL) in hope of encouraging R package authors to come up with their own, author-supported wrappers for the tools they are developing.

## Pre-requisites

* Basic familiarity with R package management
* No prior experience with CWL is necessary but could be useful

## Workshop Participation

Participants will be guided through an Rmarkdown document and optionaly try to create a wrapper for a script of their choice.

## _R_ / _Bioconductor_ packages used

- docopt
- sevenbridges

## Time outline

| Activity                                     | Time |
|----------------------------------------------|------|
| Introduction to CWL                          | 10m  |
| Building your Docker image                   | 15m  |
| Turning your script into a command line tool | 15m  |
| Creating the wrappers                        | 20m  |
| Share it with the world!                     | 10m  |
| QA and free activities                       | 20m  |

# Workshop goals and objectives

### Learning goals

* Get familiar with the concept of Common Workflow Language
* Make your R analysis portable and reproducible

### Learning objectives

* Build a Docker image with all the dependencies required for your analysis
* Use docopt to define the interface for running your script as a command-line tool
* Use Rabix composer to create a CWL description of your R analysis