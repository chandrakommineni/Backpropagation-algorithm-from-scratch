## Learning Objective

Implement the core part of the backpropagation algorithm by hand and understand its use of memory and time.

## Readings

[Rumelhart, Hinton and Williams, *Learning representations
by back-propagating errors*, 1986](https://papers.baulab.info/Rumelhart-1986.pdf) - Very influential in popularizing backpropagation, also known to numerical analysts as "reverse mode autodifferentiation".

[Andreas Griewank, *On automatic differentiation and algorithmic linearization*, 2014](https://papers.baulab.info/also/Griewank-2014.pdf) - A mathematical presentation of both the forward and reverse-mode algorithm.  Since in deep network training we tpically have a single-dimensional scalar loss, we only focus on reverse-mode, which is far more efficient for our case.  May be helpful in the axioms and examples it provides.

[Andreas Griewank, *Who invented the reverse mode of differentiation?*, 2012](https://papers.baulab.info/also/Griewank-2012.pdf) - Of historical interest.
