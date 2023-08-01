# setup notes

[Theorema](https://www3.risc.jku.at/research/theorema/software/) in current version needs to be installed and placed in the user's "..\AppData\Roaming\Mathematica\Applications" directory (Windows) for an easy setup, more notes and concerning other platforms under the Theorema link.

# idea

This is an early development project but current thinking is a Wolfram Lang (WL) native export function to add to Theorema, to LaTeX: the end goal is a .tex file with appropriate LaTeX definitions there, to produce well-formed documents. This is part two of the project, first (also in the pipeline) is a parsing functionality implemented in WL. The approach for this and core of the project is rule-based programming in WL using recursion and to achieve coverage of all the First Order Predicate Logic syntax deployed in Theorema.

Around this: a clean button/drop-down add-on to the Theorema Commander seems useful, a mapping of Theorema Language formulas to TeX-definitions to TeX-semantics is needed. 

(Interleaved write-up, start with state of the art and problem space/Theorema: Literature?)