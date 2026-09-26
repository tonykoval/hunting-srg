# Hunting Strongly Regular Graphs

**A series of three interactive hunt logs on three questions about
strongly regular graphs that were open when the series began.** One is now
settled: there is no SRG(69,20,7,5) (2026-09-26; computer-assisted proof,
write-up under review).

The same rigid object — a strongly regular graph — poses three genuinely
different questions, and each volume follows one to the edge of what is
known.

| Volume | Parameters | Question | Status |
|--------|-----------|----------|--------|
| **[Hunting SRG(37)](https://github.com/tonykoval/hunting-srg37)** | (37,18,8,9) | *completeness* — is the catalog of 6802 conference graphs final, or is there a 6803rd? | search sound, >92% of the space proven empty |
| **[Hunting SRG(69)](https://github.com/tonykoval/hunting-srg69)** | (69,20,7,5) | *existence* — once the smallest open case; does even one exist? | **settled 2026-09-26: no such graph exists** (computer-assisted lattice proof, no symmetry assumed; write-up under review) |
| **[Hunting SRG(99)](https://github.com/tonykoval/hunting-srg99)** | (99,14,1,2) | *existence, famous* — Conway's $1000 99-graph | orders 11 & 3 closed, not Cayley; order-7 door open |

## The shared lesson — the iron law

All three resist every general method for the same reason: a strongly
regular graph that is both **large** and **nearly symmetry-free** forces
full enumeration cost. Symmetry-based methods reach only symmetric graphs;
raw search drowns at low symmetry. What is left is slow, sound,
isomorph-free enumeration — and the precise map of where the wall stands.

## Read

This repo is the series hub — open **`index.html`** (or its GitHub Pages
site). Each volume is a standalone static-HTML book with KaTeX, live
calculators and visualisers, and a *Tools & Reproducibility* chapter.

## Engine

All three hunts run on
[github.com/tonykoval/orbit-gen](https://github.com/tonykoval/orbit-gen) —
the orbit-matrix enumerator, SMS/SAT solvers, PDS search and Gram-PSD
filter.

## Licence

Content CC-BY-4.0; code MIT.
