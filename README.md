# Jet CMSDAS Exercise repository

This repository contains code used for the short jet exercise of the [CMS Data Analysis School 2024](https://indico.cern.ch/event/1388937/).

## For students

This tutorial is intended to provide you with the basics you need in order to deal with jets in your analysis. We start with the basics of what is a jet, how are they reconstructed, what algorithms are used, etc. Then we give examples with scripts on how to access jets and use them in your analysis frameworks, including corrections and systematics. In the second part of the exercise, we examine jet substructure algorithms, which have many uses including the identification of hadronic decays of heavy SM particles like top quarks, W, Z, and H bosons, as well as mitigation of pileup and others.

The tutorial is designed to be executed in [CERN-SWAN](https://swan-k8s.cern.ch/) and followed in the [JMEDAS 2024 website](https://cmsdas-cern-2024-short-ex-jet.docs.cern.ch/), where you find links to instructional slides and instructions that walk you through the exercises.
If you want to follow the CMSDAS short jet exercise check the website: [https://cmsdas-cern-2024-short-ex-jet.docs.cern.ch/](https://cmsdas-cern-2024-short-ex-jet.docs.cern.ch/)

### Instructions to set up SWAN and clone this repository

1. Visit [CERN-SWAN](https://swan-k8s.cern.ch/).

2. In the `Configure Environment` dialogue, select **AlmaLinux 9 (gcc13)** as the **Platform**.

![swan_config](images/swan_config.png)

3. To clone this repository in SWAN, click the `git` icon on the left menu bar, then `Clone a Repository`.

![clone_repo_1](images/clone_repo_1.png)

Enter the URI of the exercise repo (https://gitlab.cern.ch/cmsdas-cern-2024/short-ex-jet), and make sure to tick the `Download the repository` box.

![clone_repo_2](images/clone_repo_2.png)

After the git clone finishes successfully, you can find the folder `short-ex-jet` under the `File Browser` tab.

![clone_repo_3](images/clone_repo_3.png)

## For contributors

This is the master branch copied with some modifications from the central [JME-CMSDAS](https://github.com/cms-jet/JMEDAS/).

### To update the website

The website uses the [carpentry software](https://github.com/carpentries/styles/). If you want to modify it, use the `gh-pages` branch and follow the recommendations from the carpentry style.
