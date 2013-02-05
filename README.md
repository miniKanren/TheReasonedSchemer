TheReasonedSchemer
==================

Original code from 'The Reasoned Schemer' (MIT Press, 2005) by Daniel P. Friedman, William E. Byrd and Oleg Kiselyov.

This implementation uses an older version of miniKanren. Newer versions of miniKanren have a simpler language, simpler implementation, and improved performance. (For example, ```condi``` has been replaced by an improved version of ```conde``` which performs interleaving.).

The code is divided into four files:

```mk.scm``` contains the miniKanren core forms.

```mkextraforms.scm``` contains ```run*``` and ```project```.

```mkprelude.scm``` contains useful helper relations, including the full arithmetic system from chapters 7 and 8.

```mktests.scm``` contains essentially every piece of code in the book, along with appropriate tests.


To run all the tests, simply load ```mktests.scm``` in an R5RS-compatible Scheme system:

```> (load "mktests.scm")```

To just play around with miniKanren, instead load ```mkprelude.scm```.