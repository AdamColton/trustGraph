## TrustGraph

An implementation of the basic EigenTrust algorithm (http://nlp.stanford.edu/pubs/eigentrust.pdf).

The algorithm is meant to find the trustworthiness of peers in a distributed system. A (potentially sparse) matrix is populated with values representing how much peers trust each other. A map is also populated with how much trust is extended by default to a sub-set of peers. From that starting point, the algorithm converges on the global trustworthiness of each peer.

### To-Do
This is a first pass. It does not yet implement distributed EigenTrust. There is also some room to improve error handling.