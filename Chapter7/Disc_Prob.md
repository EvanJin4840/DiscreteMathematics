### Terms
* experiment : a procedure that yields one of a given set of possible outcomes.
* sample space : the sample sapace of the expreiment is the set of possible outcomes.
* event : a subset of the sample space.

#### Definition of probability of the event by Laplace
* Definition : If S is finite sample space of equally likely outcomes, and E is an event, that is, a subset of S, then the probability of E is p(E) = |E|/|S|.
- For every event E, we have 0 <= p(E) <= 1. This follows directly from the definition because 0 <= p(E) = |E|/|S| <= |S|/|S| <= 1, since 0 <= |E| <= |S|.

##### Uniform Distribution
* Definition : Suppose that S is a set with n elements. The uniform distribution assigns the probability 1/n to each element of S

#### Independence
* Definition : The events E and F are independent if and only if p(E^F) = p(E) x p(F) or equivalently p(E|F) = p(E)

* When we have a condition "equally likely" we can use counting when we check the events are independent or not.

### pairwise and mutual independence

Definition: The events E1,E2,…,En are pairwise independent if and only if p(Ei∩Ej)=p(Ei)p(Ej) for all pairs i and j with 1≤i<j≤n.
Definition: The events are mutually independent if p(Ei1∩Ei2∩⋯∩Eim)=p(Ei1)p(Ei2)…p(Eim) whenever i1,i2​,…,im are m integers with 1≤i1<i2 < ⋯ < im ≤n  and m≥2.

* Every set of mutually independent events is also pairwise independent. However, pairwise independent events are not necessarily mutually independent.
* mutual independence is more stronger concept than pairwise independence.