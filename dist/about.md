---
layout: page
title: About
permalink: /about/
---

## Grading

The grading for these assignments accounts both for the mathematics and model
analysis, and for the implementation and analysis of the results. An additional
10 points are dedicated to presentation, writing, and data representation. The
complete list of assignments, as well as the details on grading, are given on
the main page. Assignments that are more complex are worth a greater fraction of
your final grade. Every report should be at least 1200 words long, with the more
complex reports being up to twice this length.

To submit an assignment, you must provide a link to the specific commit that
represent the final version of this assignment. 5% will be subtracted from your
*final* grade for every assignment that is modified after being submitted, and
an extra 1% will be subtracted for *every* commit modifying more than one
assignment. This can add up rapidly.

The reports must be written as markdown files containing executable *Julia*
code. An example of the expected work is given in the `00_demonstration.Jmd`
file contained in the `homework` folder, and compiled [to this webpage][demo].
This provides a template for your answers, and also gives an overview of how to
structure the documents. The reports will be compiled automatically, to ensure
that your work is fully reproducible. This implies that any data you may need to
use will be downloaded from the script using `download`.

[demo]: /homework/demonstration/

All equations must be rendered using LaTeX code. Please note that the process by
which an answer is reahed is as important as the answer itself, and so the
mathematical analysis of the model *must* be accompanied by text.

## Evaluation criteria

All homework is graded on a total of 100 points. In all cases, you must copy the
instructions (from Studium) into the first quote block, and then write an
introduction. Usually, you would not need to modify the headings of any of the
sections, though you are allowed to (and most definitely will need to) add
third-level headings (`### heading`).

**Model justification:** 10 points, including a discussion of the parameters and/or functional responses used

**Model analysis:** 30 points, including a discussion of possible mechanisms not captured by the model and their influence on the results

**Model implementation:** 50 points, sub-divided as follows: 15 points if the code runs properly, 10 points for writing functions, 10 points for proper function documentation and comments (every non-documented function removes 5 points), 5 points for function and parameters naming, 10 points for appropriate data structure and representation

**Presentation:** 10 points, including language quality and structure of the text, as well as proper visualization of the results
