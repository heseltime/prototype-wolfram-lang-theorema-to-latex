# Initial setup notes

[Theorema](https://www3.risc.jku.at/research/theorema/software/) in the current version needs to be installed and placed in the user's "..\AppData\Roaming\Mathematica\Applications" directory (Windows) for an easy setup, more notes and concerning other platforms under the Theorema link.

# Idea: Prototyping

This is an early development project that establishes a prototype for a Wolfram Lang (WL) native export function to add to Theorema, to LaTeX: the end goal is a .tex file with appropriate LaTeX definitions there, to produce well-formed documents. This is part two of the project, first (also in the pipeline) is a parsing functionality implemented in WL. The approach for this and core of the project is rule-based programming in WL using recursion and to achieve coverage of all the First Order Predicate Logic syntax deployed in Theorema.

## Prototype 0

This prototype is implemented up to prototype0 (see the notebook), with simple file handling producing a template and main .tex, and a demonstration of the recursive parsing. 

## Prototype 1

Prototype1 (see the notebook with that name) implements a template object for producing only one .tex file and is the preferred mode. 

# Future Development 

To complete develop on this proof of concept basis, a clean package structure is deployed, utilizing Wolfram Workbench, the Eclipse Plugin. To keep initial thinking in the form of notes and the relevant tests around, this repo will soon reference the new setup and be paused for further development of the project here.