# Rope Mat Designer

A free, single-page tool for designing rectangular woven rope mats (Lissajous / billiard-path mats) and building the jig to make them.

**Use it:** https://jm2080.github.io/rope-mat-designer/

## What it does

- Pick bights for the top/bottom and ends, mat size, rope diameter and number of passes
- Woven over/under preview on a labeled peg jig (T1…, B1…, L1…, R1…)
- Threading guide that lists, for each step, only the crossings with rope that's already down, with the leg you're crossing ("UNDER T7-B2, step 2")
- Click a step to lay the rope up to that peg and see each crossing numbered on the board
- Rope estimate (per pass, take-up, tails, spare) and a halfway mark with rope used so far
- Interior hole size, pass coloring, peg/rope/background colors
- Exports: true-scale woven SVG, jig template SVG for drilling, PNG, CSV, and a printable threading guide PDF

## Credit

The mat path uses the Lissajous approach described by Nils Kristian Rossing in *How to Make Rope Mats and Rosettes*.

## Running it

It's one file, `index.html`, with no build step. Open it in a browser, or serve the folder with any static host.
