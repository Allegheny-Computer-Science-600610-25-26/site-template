# 600/610: Senior Thesis Starter for Fall 2024 and Spring 2025

[![Release Senior Thesis](../../actions/workflows/main.yml/badge.svg)](../../actions/workflows/main.yml)

## Table of Contents

* [Introduction](#introduction)
* [Overview](#overview)
* [Requirements](#general-thesis-requirements)
  + [Introduction](#introduction)
  + [Related Works](#related-works)
  + [Method of Approach](#method)
  + [Experiments](#experiments)
  + [Conclusion](#future-work)
* [Gauging your level of achievement](#gauging-your-level-of-achievement)
* [Tagging](#tagging)
* [Updates](#updates)
* [Problems](#problems)
* [Assistance](#assistance)

## Introduction

This repository contains the starter for the Senior Thesis document. This
document compiles using GitHub Actions; students should write the entirety of
their document using the `thesis/index.md` file. The template
contains more specific details about its use. The remainder of this
`README` overview the project's requirements and the process of publishing the
document via GitHub Actions.

## Overview

This assignment requires a researcher to write a Markdown and LaTeX document,
stored in this README and in the file `thesis/index.md` that describes the key aspects
of a senior thesis research project. Please refer to the source code in this
file for an explanation of the components of a senior thesis and the way in
which you create them in Markdown and/or LaTeX.

Your course instructor will reduce a researcher's grade for this assignment if
the PDF of your completed thesis document has not been properly released before
the assignment's due date as specified in the GitHub Classroom page when you
accept this assignment. Unless you provide the course instructors with
documentation of the extenuating circumstances that you are facing, no late work
will be considered towards your grade for this project.

## Requirements

For specific details about the general evaluation rubric for _minimum
requirements_ please refer to the following list for the entire senior thesis.
Please note that your senior thesis chapters in your time in `600` will be evaluated
according to the content that you submit in that course and your senior thesis
chapters submitted during `610` will be evaluated according to all of the following
baseline requirements. This means that a student's work for `600` will not
be evaluated according to requirements that they could not yet fulfill until the
completion of their senior thesis. For instance, the requirement that "The
thesis consists of at least `15000` words" applies to a student's work in `610` 
and _not_ `600`. Finally, please note that these are only baseline
requirements and it is expected that an exceptional senior thesis will exceed
these requirements.

Please consult the following sub-sections, as section requirements may have
changed from requirements in previous years. All descriptions of each section
are delimited by the understanding that sections should "include, but not be
limited to" the areas highlighted. It is also important to note that students
may, with the consent of their both their first and second readers, modify the
structure of their senior thesis so that it includes, for instance, different
chapters or different ordering of chapters. With that written, the final senior
thesis that a student submits must still meet all of these baseline
requirements.

Also keep in mind that the typical instruction to

> whenever possible, use and describe one or more concrete examples and
technical diagrams

applies across _all_ relevant sections listed below.

A final note about requirements: nearly all of the sections requests some
discussion of ethical implications inherent in projects. The ways in which
ethical issues impact research will vary from project to project. Your first and
second readers will be able to guide you on a project-by-project basis toward
responding to the ethics requirements listed below.

### General Thesis Requirements

The following lists of requirements describe the general _shape_, and some of the fundamental
specifics of what each section entails. Meeting the following requirements ensures a _passing_
grade, and not necessarily anything above that watermark.

#### Baseline contents

  - [ ] The abstract provides a concise and compelling summary of the research
  - [ ] The thesis was submitted on time as a PDF in a tagged release on GitHub
  - [ ] The GitHub repository of the thesis contains evidence of many commits
  - [ ] The GitHub repository of the thesis contains multiple releases using the
    [Semantic Versioning Standard](https://semver.org/)
    - [ ] The GitHub repository of the thesis has a passing build status in GitHub Actions
  - [ ] In adherence to the [Semantic Versioning Standard](https://semver.org/),
    the GitHub repository of the thesis contains a release greater than `0.5.0`
    for the work in `600` and a release greater than `1.0.0` for `610`
  - [ ] The thesis has the correct format created through the use of Pandoc and
    LaTeX and the senior thesis template for the Department of Computer and Information Science
  - [ ] The title of the thesis is both interesting and appropriate
  - [ ] The thesis includes at least twenty `20` references
  - [ ] Unless there is a convincing reason to require otherwise, each chapter
    in the senior thesis should contain at least ten to twenty pages of
    contents formatted in the required style
  - [ ] The thesis consists of at least `15000` words
  - [ ] The thesis follows a logical organization at the level of chapters, sections,
    subsections, and individual paragraphs
  - [ ] The thesis includes appropriate visual aids, which fall under the broad
    categories of:
  * `image`
  * `figure`
  * `table`
  * `graph`
  - [ ] The thesis highlights and explains the societal impacts and ethical
    implications of the completed research
  - [ ] There are no typographical or grammatical errors in the thesis
  - [ ] There is no extraneous text in the thesis

#### Introduction Section Requirements

* a statement of the problem addressed in this research
* overall project aims
* background motivating your research
* a high-level overview of ethical issues implied by the current state of the
  problem underlying the work

  - [ ] The introduction section clearly describes the completed work
  - [ ] The introduction section motivates the completed work from a
    professional perspective
  - [ ] The introduction section outlines the ethical implications of the thesis

#### Related Work

* the review of relevant existing work (i.e., the "literature review")
* the literature review should be a concise, scholarly review of the literature
  explaining the background to the proposed research
* the review should provide the context for the aims of the research in relation
  to existing work on the topic
* the literature review should place the senior thesis research in the context
  of the relevant existing work
* review of ethical discussions referenced in the `Introduction`

  - [ ] The related work section references and describes relevant literature
  - [ ] The related work section explains how relevant literature connects to the thesis
  - [ ] The related work section does not provide a "laundry list" of the related literature
  - [ ] The related work section situates the completed project in the broader scope

#### Method Section Requirements

* describes the infrastructure and tools implemented to serve, test, and support
  research and conduct experiments
* enumerates the general processes and code used by the project with required
  technical content that would include, for instance, diagrams and/or code
  snippets and/or algorithm statements
* addresses the interventions that the research incorporates or develops to
  address ethical concerns in datasets, software processes, or theoretical
  approaches

  - [ ] The method section explains the process utilized in the completed study
  - [ ] The method section addresses as many of the necessary methodology used in the research project. For example, the following may be relevant to the project:
  * `description of algorithms`
  * `programming languages`
  * `libraries`
  * `platforms`
  * `software tools`
  * `hardware`
  - [ ] The method section references the GitHub repository that contains the project's artifact(s)
  - [ ] The method section, when appropriate, explains how to
    run the computational artifact (note that the `README.md` file of the GitHub
    repository that contains the computational artifact(s) should furnish
    complete details about the input, output, behavior, and use of the project as necessary)

#### Experimental Results

* displays and discusses evaluative metrics and data used as validation
  strategies the projects
* clearly defines thresholds for success, and discusses the outcomes of
  experiments relative to them
* explores the trade-offs evident in the experimental results, leverage
  previously defined metrics about, for instance, efficiency and/or
  effectiveness
* uses techniques such as statistics and/or data visualizations to highlight the
  key trends in the experimental results
* discusses any threats to validity that remain from the original summary of the
  research or those introduced by any approaches or data used in the these
  research and implementation process

  - [ ] The experimental results section includes a description of experiments
    such that a reader should be able to reproduce them
  - [ ] The evaluation subsection describes how the work is validated
  - [ ] The evaluation subsection contains at least one graph, table of data, or
    some other relevant presentation of the results from the experimental study
  - [ ] The experimental results section details threats to validity

#### Future Work

* provides a summary of your research and experimental outcomes
* proposes, where applicable, future areas of work or research indicated by the
  conclusion of this research
* includes an evidence- or results-based appraisal of ethical issues left
  unresolved or created by this research

  - [ ] The discussion and future work section discusses the impact of the completed research project
  - [ ] The discussion and future work section critically reflects on the completed research project
  - [ ] The conclusion outlines, with sufficient depth and detail, avenues for further and/or future work

## Gauging your level of achievement

With a task such as this, defining _precisely_ what constitutes exceptional or above-average work is difficult,
as each project is distinct and is only comparable to its own potential. Achieveing that potential may look
like any of the following scenarios.

### Exceptional work (i.e., A- and upward)

Exceptional projects share the following features:

* the thesis is _exhaustive_, often approaching double the required word count (`20,000`-`30,000` words, minumum)
* the thesis displays a clear grasp of the relevant literature (engaging `30`+ sources of high disciplinary quality)
* discussion of ethical and technical imperatives occur throughout the sections, often reinforcing or relating to 
  prior topics of discussion in the introduction and/or related work
* the project discusses, coordinates, and relates sources to each other in both complementary and contradictory ways,
  often highlighting or at least attempting to resolve conflicts where they arise
* the methodology behind the project is clear, often using multiple diagrams to discuss structure and relationships
  of the various parts of the related artifact
* experiments show sound methods that, even if generating unsupportive data, are discussed with criticl reflection
  and clear demonstration of opportunities, faults, and/or successes with reference to how this changed/changes
  the project as a whole
* future work clearly grapples with the tasks left undone and the project's impact on the larger computational
  communities in which it participates

### Above average work (B- to B+)

Above average projects may be described as:

* _substantial_, approaching higher word counts (`20,000` words)
* displaying a grasp of much, but not all, relevant literature (engaging `25`+ sources of moderate disciplinary quality or authority)
* discussion of ethical and technical imperatives occur in more than one or two sections, but may remain unresolved or unaddressed
* the project discusses, coordinates, and relates sources to each other without necessarily recognizing conflicts or areas of contradiction
* the methodology behind the project is clear, though there remain some questions about project operations, security, or design
* experiments demonstrate effort in developing results, though the conversation around them does not provide reflective inquiry
  into faults or successes and their causes/effects
* future work names and discusses tasks remaining undone and the ethical issues raised by the research, but
  does not suggest how these relate to the larger communities in which the project traffics

### Average work (C- to C+)

Average projects often fulfill [the requirements above](#general-thesis-requirements), but stop at having completed the technical
distinctions the projects asks for in its specifications.

### Below-average work (D to D+)

Below-average projects miss key [requirements](#general-thesis-requirements) and are often under word count, feature fewer sources
than are required and otherwise do not fulfill a reasonable portion of the tasks defined. Sources are low-quality and often look
more like tutorials than higher-level disciplinary discussion. Projects falling into this category fulfill 60% - 75% of the requirements.

### Failing work (F)

Failing projects lack entire chapters or provide very minimal attempts to complete them. Sources are low-quality and/or are missing.
Multiple requirements (on the order of 50% or more) are not fulfilled. Writing is cursory and not descriptive; may include many instances
of generalization and no evidence.

## Tagging

Since this repository primarily contains Markdown and/or LaTeX source code, the
GitHub Actions configuration for it will compile the source code and
automatically release a PDF of the main file whenever the last commit is
associated with a [Git Tag](https://git-scm.com/book/en/v2/Git-Basics-Tagging).

This will build a PDF file available in the "Releases" listing for this
repository. All release numbers for your writing in this repository should
adhere to the [Semantic Versioning](http://semver.org/) standard expected of
GitHub projects. Here this means that:

* `Major version` releases feature a tag number change reflecting full
releases; generally these start at `1.0.0`
* `Minor version` releases indicate small changes or additions to documents;
typically these increment the second digit in the version (e.g. `1.1.0`)

Please note that your readers will only read the PDF generated from "tagged"
releases of the file `SeniorThesis.pdf` that has a version number greater than
1.0.0.

That is:

* if your commit is tagged `SeniorThesis-1.0.0`, then
* the file `SeniorThesis.pdf` should be available for download in the
"Releases" tab in your GitHub repository for this project under the name
`SeniorThesis-1.0.0`.

To ensure you can create a release appropriately, make a single small change to
the `thesis/index.qmd` and:

1. `commit` your file changes using a `git commit` command
2. create your first tag for this repository: type `git tag
senior_thesis-0.1.0`.
3. You are now ready to push your changes with the tag number using  `git push
-u origin main --tags`

The above steps should build a version of your project and release it on
GitHub! If something does not work correctly, please contact your first and
second readers and/or the senior thesis faculty coordindator to explain the
details of the challenges that you faced. It is also important to note that it
is possible for a student to perform a manual release of the PDF of their senior
thesis chapters. Again, please communicate with your first and/or second readers
and/or the senior thesis faculty coordindator for more information about the
steps you would take to perform a manual release. With that said, it is
important to stress that you should learn how to perform an automated release of
your thesis in PDF and only use the manual approach if there is a severe and
extenuating circumstance (e.g., GitHub Actions stops working for a short time)
that prevents you from performing an automated release.

When you make subsequent changes to your files and perform commits and you are
ready to release a new version of `SeniorThesis.pdf`, then you should
again tag your work _before a `push` command_ with a tag that
adheres to the [Semantic Versioning](http://semver.org/) standard.

Each time that you correctly execute this sequence of commands you will release
a new version of your document to GitHub that is easily accessible as a PDF to
you and to your first and second readers.

While you are able to build copies of your PDF locally using the `quarto render`
command, the only copy that will be evaluated is that released to GitHub following
the procedure outlined above.

## Assistance

If you are having trouble completing any part of this project, then please talk
with your first reader. In particular, if you have questions about your research
project, please see your first reader. Alternatively, you may ask questions in
the Discord server for this course.
