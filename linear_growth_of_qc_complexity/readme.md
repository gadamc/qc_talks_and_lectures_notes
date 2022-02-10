# Intro


Quantifying quantum states' complexity is a key problem in various subfields of science,
from quantum computing to black-hole physics. We prove a prominent conjecture by
Brown and Susskind about how random quantum circuits' complexity increases.
Consider constructing a unitary from Haar-random two-qubit quantum gates.
Implementing the unitary exactly requires a circuit of some minimal number of
gates - the unitary's exact circuit complexity. We prove that this complexity grows
linearly in the number of random gates, with unit probability, until saturating
after exponentially many random gates. Our proof is surprisingly short, given the
established difficulty of lower-bounding the exact circuit complexity. Our strategy
combines differential topology and elementary algebraic geometry with an inductive
construction of Clifford circuits.

Haferkamp, Jonas, et al. "Linear growth of quantum circuit complexity." arXiv preprint arXiv:2106.05305 (2021) - https://arxiv.org/abs/2106.05305

# URL
https://www.youtube.com/watch?v=AklY6hfitYA

# My Takeaway

Backward lightcone - a "cone" of connections from a single qubit backward to all
initial qubits. The lower bound of the complexity of a circuit is related
to the number of backward lightcones in a particular architecture

```
C(U) >= T/9 - n/3
```

T = number of disjoint backward lightcones in an architecture
n = number of gates

This C(U) lower bound holds so long as
`T >= 4^n - 1` is true.

At some point, the number of gates grows and this relation does not hold.
C(U) becomes saturated, as theorized by Brown and Susskind.

So, C(U) is linear up to this point, then constant.  

How was all of this related to black holes??
