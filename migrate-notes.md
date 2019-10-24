## Suggested changes from CGO reviewers


### Important Issues

***Clear positioning***

- update introduction with the following information
    + compare with the previous optimizations (i.e. pattern-based), what's new?
    + a possible argument is "this optimization is not to replace pattern-based
      optimizations, but improve a big set of regular patterns."
- clearly state our "applicability" beyond database queries
    + potential benefit for user-defined functions (our future work)
    + HorseIR can represent MATLAB and other computation

***More comparison in related work***

- add a couple of new references
    + WeldIR/Lift
- rewrite related work to emphasis
    + the difference between our optimizations and HyPer/WeldIR/Lift/MonetDB
- emphasis on the systematic nature

***Experiments! Experiments!***

- include HyPer (despite it is an old version)
- include compilation time alongside the execution time
- extend the set of queries (not likely for cc20)


### Minor Issues

Reviwer A

Reviwer B

Reviwer C

- [x] "sec 4.1.2 - in an ordered group"
    + "a ordered group" to "an ordered group"
- [x] "sec 4.1.2 - >, where L_i is"
    + add "," before "where"
- [x] "sec 4.3.1 - (3) an error occurs"
    + fix "(4)" to "(3)"
- [x] "Sec 4.4 - function each_right should produce list<@f(A, L_0)"
    + correct the each_right rule

Reviwer D

- [x] Fix "Section 2 is empty before the first subsection"
- [x] Make captions clear in Fig. 8 and 9
    + use "1GB input data (SF1)" instead of "SF1"
- [x] Move Sec. "4.4 Lists" to "4.3.2 Lists"
- [x] Move Sec. "4.5 Other Functions" to "4.3.3 Other Functions"


