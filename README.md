# CMPSC 600 Senior Comprehensive Project

[![Build Research Journal Site](../../actions/workflows/main.yml/badge.svg)](../../actions/workflows/main.yml)
[![Release Senior Thesis](../../actions/workflows/release.yml/badge.svg)](../../actions/workflows/release.yml)

For more information about the course requirements for your 600-level course in
Computer and Information Science, please refer to the syllabus for your course.
To enable you to complete many of the deliverables for the 600-level course,
this repository contain contains instructions for your research journal and your
senior thesis document. Quarto, serving as a build system for your site, will
build your thesis document as a website and a PDF.

## Research Journal

Your research journal contains short posts in one of the following categories:
`reflection`, `feedback`, `activity`, and `changelog`. For the Fall 2025
semester, you are responsible for writing the following posts:

- `reflection` posts:
    - Reflect on the current version of your computational artifact
    - Reflect on your experiences preparing for and giving your presentation
- `activity` posts:
    - State and explain the title of your senior comprehensive project
    - Provide and justify the outline for Chapter One of your senior thesis
    - Provide and justify the outline for Chapter Two of your senior thesis
- `feedback` post:
    - Offer feedback to both your classmates and your instructors on work in the
      600-level course in Computer and Information Science
- `changelog` post:
    - Summarize all work completed leading up to a `1.0` release of your senior
      comprehensive project that is visible through a website hosted on GitHub
      pages and a release of your senior thesis in PDF through the `Releases`
      tab inside of your GitHub repository

Your writing assignments for the 610-level course will be released during the
upcoming Spring 2026 semester.

## Senior Thesis Chapters

All researchers in the 600-level course in Computer and Information Science must
document their work in the form of a written thesis. While variations on the
typical structure and contents of a thesis can be specific to a certain project,
a typical Computer and Information Science thesis contains `5` sections:

 1. Introduction
 2. Related Work
 3. Methods
 4. Experiments
 5. Future Work

As outlined on the course syllabus, during the `600` semester course, students
complete Chapters `1` and `2` for review by their reader(s). More details
about the baseline requirements for the senior thesis document are available
in the course syllabus and in the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## Enabling Site Build

This site deploys via Github Pages using the Quarto static site building system.

1. Go to the `Settings` menu on this repository and locate the `Pages` submenu.

![GitHub Settings, Pages submenu](https://raw.githubusercontent.com/ReadyResearchersTemplates/site-template/media/img/600%20-%20Site%20Template%20-%20Github%20Pages%20Menu.png)

2. On the resulting screen, find the `Build and deployment` menu; select `GitHub Actions`

![GitHub pages, Build and Deployment item](https://raw.githubusercontent.com/ReadyResearchersTemplates/site-template/media/img/600%20-%20Site%20Template%20-%20Github%20Actions%20Menu.png)

### `Private` vs. `Public` availability

You retain the choice to make this journal private or public. The `Pages`
settings menu allows either. Your URL will change depending on which selection
you make, and you should be able to find the resulting URL of your journal by
visiting the pages section of the repository's `Settings` menu. Your URL should
display at the top of the page:

![GitHub Pages url](https://raw.githubusercontent.com/ReadyResearchersTemplates/site-template/media/img/600%20-%20Site%20Template%20-%20Github%20URL.png)
