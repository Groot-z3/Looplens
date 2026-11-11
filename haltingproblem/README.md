# LoopLens — Program Analysis Studio

A browser-based educational tool for exploring restricted infinite-loop detection and the limits of program analysis.

## Features
- Pattern-based analysis of selected Python-like `while` loop patterns
- Warnings for `while True` without a visible `break`
- Detection of a simple decreasing numeric counter
- Warning when a loop condition variable is not directly updated
- Step-by-step trace for supported counter loops
- Theory desk covering Turing Machines, the Halting Problem, decidability and recognizability
- Example library for quick demonstrations

## Tech stack
HTML5, CSS3 and vanilla JavaScript. No backend, framework, database or external code execution.

## Run locally
Open `index.html` in a modern browser. Internet access is only needed for optional Google Fonts; the application itself runs locally.

## Limitation
LoopLens is a restricted, pattern-based educational analyzer. It does not execute submitted Python code and cannot decide termination for arbitrary programs. An inconclusive result is intentional and reflects the theoretical limits of the Halting Problem.
