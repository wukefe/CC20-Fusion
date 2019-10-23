**Note: This repo has been linked to overleaf.**

## Conference Information

ACM SIGPLAN 2020 International Conference on Compiler Construction (CC 2020)

- [Conference homepage](https://conf.researchr.org/home/CC-2020)
- [Call for papers & paper submission](https://conf.researchr.org/track/CC-2020/CC-2020-papers)

Time Table

| Important Time     | Message                | Status     |
| -----------------: | :--------------------- | :--------: |
| Oct. 25, 2019      | Abstract Submission    |            |
| Nov.  1, 2019      | Paper Submission       |            |
| Nov. 24, 2019      | Artifact Submission    |            |
| Dec. 4-6, 2019     | Author Rebuttal Period |            |
| Dec. 24, 2019      | Paper Notification     |            |
| Feb. 22-23, 2020   | Conference Dates       |            |

Notes

- acmart-sigplanproc-template.tex
- double-blind review
- 10 pages, excluding references (unlimited, require full names of all authors)
- [ACM latex template source code](http://www.sigplan.org/Resources/Author/)
- artifact should be submitted 10 days before the rebuttal phase

## Writing

### Generating a PDF

Command-line option

    make

IDE option (TexMaker)

    - open main.tex
    - choose the pdfLaTex compiler

Overleaf option (Online)

    - select main.tex
    - choose recompile

### Versions

Versions controlled by specific macros in [paper.tex](paper.tex)

- paper mode, with macro `\shortpaper` (**default**)
- technical report mode, with macro `\techreport`


