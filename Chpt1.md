##1 - The Computability Concept##

_effective procedure_ - an algo. (**a procedure that can be carried out by following specific rules**)

_decidable_ (informal) - given a domain and property, _P_, over its members, can we figure out for which members _P_ is true and for which _P_ is false?

_partial function_ - function for which the value for some inputs may be undefined. Or possibly more technically, Given some (context) set, _S_, a function whose domain is a subset of _S_.

_k-place part. func. (pf)_ - pf taking _k_ arguments.

_total function_ - functions which are left total, i.e. whose domain is the set under study. Both total and non-total functions are still partial functions. (similarly for _k_-place functions, to be total they must have S<sup>_k_</sup> as their domain)

_empty function_ - function which is defined no where.

_effectively calculable pf_ - a _k_-place function _f_, such that there is an effective procedure that

1. halts and returns the correct value of _f_ for whatever input in its domain. (on inputs on which it is defined)
2. runs forever for on inputs not in its domain (on inputs for which it is undefined)

_decidable_ (formal) - For a subset _S_ of N<sup>k</sup>, we can say that _S_ is decidable iff its characteristic function

C<sub>S</sub>(x) =Yes if E x &#x2208; S No ifE x S

(which is always total) is effectively calculable. Here “Yes” and “No” are some ﬁxed members of N, such as 1 and 0. 