+++
title = "Chapter 1: Introduction"
author = ["adam"]
date = 2019-11-06T21:16:37-08:00
lastmod = 2019-11-14T13:00:28-08:00
tags = ["dlbook"]
categories = ["dlbook"]
draft = false
weight = 2000
foo = "bar"
baz = "zoo"
alpha = 1
beta = "two words"
gamma = 10
mathjax = true
+++

## introduction {#introduction}

-   Deep learning solves the central problem in representation learning
-   problem: find the right representation for data, e.g. polar vs rect
    coordinates


### Another perspective {#another-perspective}

-   each layer in multilayer network represents
    -   multi-steps in a computer program
    -   each layer of representation is a state in a sequence of executions
    -   greater depth implies more instructions in sequence
    -   not all information in a layer's activation encodes factors of variation
        that explain the input!  Representation also store state information that
        helps to execute a program


## Depth of a model {#depth-of-a-model}

1.  number of sequential instructions
