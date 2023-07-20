# Introduction to R

## Creating R functions

The rest of the course will use advanced functions created for analyzing
and visualizing data. These complex functions are simply an amalgamation
of other smaller functions, webbed together by a cohesive logic. Each
function has a specific purpose, with a desired input and output.

### Exercises

A.0.1 Create a function named `is_even` that returns TRUE when its input
`x` is even, and FALSE when its input `x` is odd.

    Replace this text with your code. Use the below functions to check your answers.

    print(is_even(4862))  # Desired output: TRUE

    print(is_even(7000001))  # Desired output: FALSE

A.0.2 Assuming you have a function named `is_even` that works properly,
think of some ways to write a function `is_odd` using the former
function.

    Replace this text with your code. Use the below functions to check your answers.

    print(is_even(2123))  # Desired output: TRUE

    print(is_odd(4444))  # Desired output: FALSE

## Finding R packages

Beyond writing functions yourself, a large part of data science is
finding functions already written and optimized by others. While
understanding how to code is important in order to extend existing
algorithms and bring them together for your analysis purposes, it is
rare to create new algorithms from scratch rather than build on the
existing software ecosystems that have been created by other experts and
improved by the community over the years. Bioconductor itself manages a
large software repository for R packages related to data science,
especially for Bioinformatics. CRAN is the default software repository
for the R programming language. Many other packages are also publicly
available on github.com, a repository for open source software. Finding
packages is often a combination of using various online resources and
looking through the latest scientific publications in bioinformatics
journals.

### Exercises

A.0.3 Find interesting packages that seem useful for your data science
interests. These could be from a specific biological field (genomics,
rna analysis, etc…), or other scientific fields (computational
chemistry, astronomy, etc…). HINT: Use Google as a starting point if you
have an idea of a specific type of package you are looking for, or
browse packages at bioconductor.org until one peaks your interest.

    print("Write a simple print function that tells us what package you chose, and why it peaked your interest.
    Can you see yourself coming back to this package in later years?")

# Learning about cancer and data

Here are some questions that explore your prior understanding of cancer
and cancer data. The main purpose of this notebook is to show you how to
launch a notebook and submit answers.

## Public Resources

The National Cancer Institute (NCI) is a branch of the National
Institutes of Health. Visit [NCI’s
website](https://www.cancer.gov/about-nci/overview) to learn more about
NCI’s mission, then answer the questions below to the best of your
ability.

### Exercises

A.0.4 Print TRUE `print(TRUE)` or FALSE `print(FALSE)` after each
statement. You may also print an explanation to your answer (eg
`print("I think it's true based on information I was able to find on the NCI website")`)

A.0.4.1 NCI is funded by federal tax dollars

    print()

A.0.4.2 NCI sets the prices for cancer treatments in the US

    print()

A.0.4.3 NCI leads efforts in the US to improve cancer treatment and
survivorship

    print()

A.0.4.4 Cancer researchers can apply to NCI to receive money to
investigate questions about cancer biology

    print()

A.0.1.5 Some cancers and their outcomes are not actively researched
because of limited resources available to NCI

    print()

## Terminology

Understanding the language used in a particular field is important for
clear and effective communication. Throughout the course you will see a
multitude of statistical and medical terms.

### Question

A.0.5 Print TRUE `print(TRUE)` or FALSE `print(FALSE)` after each
statement. You may also print an explanation to your answer (eg
`print("I think it's true based on information I was able to find on the NCI website")`)

A.0.5 The incidence of breast cancer in a population – for example, the
people of the state of Rhode Island – refers to the number of people
currently undergoing treatment for breast cancer in that population.

    print()

## Understanding Rates

This display is from the Surveillance, Epidemiology and End Results
(SEER) program run by NCI.

![SEER overview, 2021](images/rateOverview.jpg)

### Question

A.0.6 According to this diagram, in a random collection of 100000
americans in 2018, how many people will die of colon or rectum cancer?

### Answer

    print("My Answer...")

## Visualizing data

A histogram is a data visualization that shows the relative frequencies
of measured quantities. Below we have a histogram of rates of prostate
cancer incidence across a collection of American cities, reported as
age-adjusted rates per 100000 males.

![Cancer prostate Incidence](images/introhisto.jpg)

### Questions

A.0.7 What is approximately the highest rate per 100000 men of prostate
cancer incidence reported in the cities surveyed?

A.0.8 What is approximately the number of cities reporting rates lower
than 120 per 100000 men?

### Answers

    print("A.0.7 ...")

    print("A.0.8 ...")

## Interpreting data

This figure shows changes in the rate of new kidney cancers compiled by
the NCI Surveillance, Epidemiology and End Results program.

![Kidney Cancer Rates](images/introseer.jpg)

### Question

A.0.9 Which of the following could be a likely explanation for the
change in rate reports between 2009 and 2010, and why?

1.  Improved health

2.  data error

3.  change in diagnostic procedure and/or definition of kidney/pelvic
    cancer incidence

### Answer

    print("A.0.9 ...")
