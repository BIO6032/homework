# BIO 6032 homework - {{ your name here }}

<!-- Unless explicitly indicated, do not change anything in this file -->

As part of your evaluation for the class, you need to turn in 11 reports, at a
rate of about one per week. You are free to submit the assignments at a rythm
that suits you, however the theory required matches with specific in-class
readings and discussions. In addition, every assignment represents a
considerable amount of work, and it is not advised to wait until later in the
term to complete them. The assignments will form the entirety of your
evaluation. There is no extra credit for this class, and grades will not be
curved.

The grading for these assignments accounts both for the mathematics and model
analysis, and for the implementation and analysis. An additional 10 points are
dedicated to presentation, writing, and data representation. The complete list
of assignments, as well as the details on grading, are given below. Assignments
that are more complex are worth a greater fraction of your final grade. Every
report should be at least 1200 words long, with the more complex reports being
up to twice this length.

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
use will be downloaded from the script using `download`. All equations must be
rendered using LaTeX code.

[demo]: ./homework/00_demonstration/

## Summary table

<!-- Copy this symbol ✔️ in the Done column when the homework is finished -->

|      | Title                           | Done | Difficulty | Ponderation |
|:----:| ------------------------------- | ---- | ---------- | -----------:|
| `01` | Bifurcation diagram             |      | ❗         |           4 |
| `02` | Logistic growth                 |      | ❗         |           4 |
| `03` | Logistic growth and competition |      | ❗         |           6 |
| `04` | Stability                       |      | ❗❗       |          10 |
| `05` | Spatial dynamics 1              |      | ❗         |           8 |
| `06` | Evolutionary branching 1        |      | ❗❗❗     |          15 |
| `07` | Stochastic model of epidemics   |      | ❗         |           5 |
| `08` | Spatial dynamics 2              |      | ❗❗       |          12 |
| `09` | Parameters inference            |      | ❗❗❗     |          12 |
| `10` | Evolutionary branching 2        |      | ❗❗❗     |          12 |
| `11` | Spatial dynamics 3              |      | ❗❗❗     |          12 |

## Evaluation criteria

All homework is graded on a total of 100 points. In all cases, you must copy the
instructions (from Studium) into the first quote block, and then write an
introduction. Do not modify the headings of any of the sections, though you are
allowed to (and most definitely will need to) add third-level headings (`###
heading`).

**Model justification:** 10 points, including a discussion of the parameters and/or functional responses used

**Model analysis:** 30 points, including a discussion of possible mechanisms not captured by the model and their influence on the results

**Model implementation:** 50 points, sub-divided as follows: 15 points if the code runs properly, 10 points for writing functions, 10 points for proper function documentation and comments (every non-documented function removes 5 points), 5 points for function and parameters naming, 10 points for appropriate data structure and representation

**Presentation:** 10 points, including language quality and structure of the text, as well as proper visualization of the results
