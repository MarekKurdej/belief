BFT - Belief Functions Theory library
=====================================

Master:
Windows: [![Windows Status](http://img.shields.io/appveyor/ci/mkurdej/bft.svg?branch=master)](https://ci.appveyor.com/project/mkurdej/bft)
Linux & OS X: [![Linux & OS X Status](https://travis-ci.org/mkurdej/bft.svg?branch=master)](https://travis-ci.org/mkurdej/bft)
[![Coverage Status](https://coveralls.io/repos/mkurdej/bft/badge.png?branch=master)](https://coveralls.io/r/mkurdej/bft?branch=master)

Develop:
Windows: [![Windows Status](http://img.shields.io/appveyor/ci/mkurdej/bft.svg?branch=develop)](https://ci.appveyor.com/project/mkurdej/bft)
Linux & OS X: [![Linux & OS X Status](https://travis-ci.org/mkurdej/bft.svg?branch=develop)](https://travis-ci.org/mkurdej/bft)
[![Coverage Status](https://coveralls.io/repos/mkurdej/bft/badge.png?branch=develop)](https://coveralls.io/r/mkurdej/bft?branch=develop)

<a href="https://scan.coverity.com/projects/5692">
  <img alt="Coverity Scan Build Status"
       src="https://scan.coverity.com/projects/5692/badge.svg"/>
</a>

Belief functions theory (Dempster-Shafer theory) implementation in C++

Dempster-Shafer theory implementation in a Boost-like fashion.

Features:
* FRAME OF DISCERNMENT
    * type checking
    * cartesian product of frames (TODO)
* MASS function and its equivalents
    * belief function
    * commonality function
    * plausibility function
* TRANSFORMATION functions (to_*)
    * to_belief
    * to_commonality
    * to_mass
    * to_plausibility
* NORMALIZATION
* OPERATOR/RULE
    * conjunctive rule (normal | by commonality) (precise | random)
    * disjunctive
    * Dempster
    * adaptive (Dubois-Prade)
    * cautious (conjunctive) rule + bold (disjunctive) rule (Denoeux)
    * PCx5, others
* DECOMPOSITION
* DISCOUNTING
* CONTEXTUAL DISCOUNTING
