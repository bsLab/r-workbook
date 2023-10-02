# r-workbook

R+ Programming Language for the Web Browser (Data Analysis and ML) and node.js.

R is a widely used programming langiage for numerical and statistical data processing, data analysis, and data visualizatio. R+ is a pure functonal javascript implementation of a modified sub-set of R. R+ provides a javascript interface to well known packages, e.g., jsfeat, fft, stdlib.js, opencf.js, convnet.js, neataptic, and hundred more packages.

R+ has some syntax extensions (e.g., short form of lists { } and vectors [ ]), some R functions are restricted, some are extended compared with the original versions.

R+ parses program text into an intermediate AST, which is directly compiled on-the-fly to a function call graph. The function graph is executed in a sandbox environment. The R iterative performenace is about 5 times faster than native Python and about 5 times slower than native R.
