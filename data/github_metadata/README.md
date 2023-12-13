# github_metadata

## Overview

Taken from https://www.kaggle.com/datasets/pelmers/github-repository-metadata-with-5-stars/ by Peter Elmers. It is licensed under CC BY 4.0 https://creativecommons.org/licenses/by/4.0/. It shows metadata information (no code) of all github repositories with more than 5 stars. This metadata is then used to extract the usage percentage of languages on github by each year from 2011 to 2023. The dataset itself is not changed by any means, but it is used together with other data to to generate a new dataset.

## Data Dictionary

The only relevant columns are pushedAt and languages. pushedAt denotes, in which timeframe the repository should be sloted into. languages holds the used languages together with the absolute size of code pieces in the respective language measured in lines. The sizes can later be used to determine, which languages hold which percentage of usage on github.