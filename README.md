# Creating shareable CWL wrappers for your R tools

# Instructor(s) name(s) and contact information

Marko Zecevic - marko.zecevic at sbgenomics.com

# Workshop Description

Do you have important analysis tools written up as R scripts on your local machine?  
Would you like to reach a larger audience with those scripts?  
Would you like to ensure other researchers can run analyses in the exact way that you intend?  
Yes? Then this workshop is for you!

We will present a guide and best practices for creating container images ([Docker]) out of your R scripts, 
wrapping them in the Common Workflow Language ([CWL]) and then sharing them with the wider world,
starting with the large audience of researchers working on the Cancer Genomics Cloud ([CGC]).

[CWL] is a widely adopted, platform agnostic, standard for describing workflows with plain text documents.
Applications described with Docker images and CWL will run consistently, in the way you intend, on 
everything from your local computer, your HPC, to your cloud infrastructure and various cloud platforms.

The Cancer Genomics Cloud ([CGC]), a genomics analysis platform funded by the NCI and built and run by 
Seven Bridges Genomics, hosts several massive public datasets alongside secure and scalable computational resources 
and optimized, portable bioinformatics tools. These tools, written in a variety of programming languages, 
are wrapped in Common Workflow Language (CWL).

[CWL]: https://www.commonwl.org/
[CGC]: https://cgc.sbgenomics.com
[Docker]: https://www.docker.com/resources/what-container


## Pre-requisites

* Basic familiarity with R package management
* No prior experience with CWL is necessary but could be useful

## Workshop Participation

Participants will be guided through an Rmarkdown document and optionally try to create a wrapper for a script of their choice.

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
* See how easy and quick it is to convert your R script to a portable, scalable application

### Learning objectives

* Build a Docker image with all the dependencies required for your analysis
* Use docopt to define the interface for running your script as a command-line tool
* Use Rabix composer to create a CWL description of your R analysis

# References

[CWL user guide](https://www.commonwl.org/user_guide/index.html) (Browse this if you want to get a head start on CWL!)
