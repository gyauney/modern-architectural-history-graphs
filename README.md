#  Modern architectural history indices

This repository contains digitized indices from several architectural history texts:

### `toward-an-architecture.json`
Le Corbusier, *Toward an Architecture*, introduction by Jean-Louis Cohen, translation by John Goodman, The Getty Research Institute, 2007.

The introduction by Jean-Louis Cohen is on pages 1-77, inclusive.

### `theory-and-design-in-the-first-machine-age.json`
Reyner Banham, *Theory and Design in the First Machine Age*, Second Edition, MIT Press, 1980.

### `histories-of-the-immediate-present.json`
Anthony Vidler, *Histories of the Immediate Present: Inventing Architectural Modernism*, MIT Press, 2008.

----

Each JSON file contains a dictionary, where each key is a string from the index and the associated value
is a list of the pages on which the key appears. Pages refer to the specific editions listed above.

For example, the first five entries `reyner-banham_theory-and-design-in-the-first-machine-age.json` in are:
```
"Abraham, Pol": [31],
"Albers, Josef": [283, 313],
"Alberti, L-B": [159],
"Alfeld, Fagus factory": [21, 79, 84],
"Amsterdam, the Beurs": [140, 163]
```