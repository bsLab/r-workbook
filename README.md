# r-workbook

R+ Programming Language for the Web Browser (Data Analysis and ML) and node.js.

**Starting from 10/2023, this repository is not updated frequently (or at all) and any recent updates are only availble here**:

http://git.edu-9.de/sbosse/r-workbook

---

**Since 10/2023 github enforces a two-factor or multi-factor authentication, which is neither required in principle nor comfortable in daily use of a code repository. This was introduced for economical reasons (Microsoft as github owner sells 2FA/MFA software solutions and want to remove non-profit, i.e., low-impact, repositories), higher user control, and not for security primarily, and leads to an unnecessary collection of sensitive personal data and linking of services that should be rejected by users and developers.**

---

R is a widely used programming langiage for numerical and statistical data processing, data analysis, and data visualizatio. R+ is a pure functonal javascript implementation of a modified sub-set of R. R+ provides a javascript interface to well known packages, e.g., jsfeat, fft, stdlib.js, opencf.js, convnet.js, neataptic, and hundred more packages.

R+ has some syntax extensions (e.g., short form of lists { } and vectors [ ]), some R functions are restricted, some are extended compared with the original versions.

R+ parses program text into an intermediate AST, which is directly compiled on-the-fly to a function call graph. The function graph is executed in a sandbox environment. The R iterative performenace is about 5 times faster than native Python and about 5 times slower than native R.
