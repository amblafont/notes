W : monad of weak omega groupoids on globular sets
S : monad of strict omega groupoids on globular sets

W is a monad with arities in Θ
W preserves monomorphisms
W preserves coproducts


## Operations

A strict operation is some dimension n and element in S(1)_n
An element of S(1)_n is a pasting scheme of dimension at most n.
So, a strict operation is a pasting scheme together with a dimension which is 
bigger than the dimension of this pasting scheme.
If the dimension is strictly higher, we think of the operation as an identity
operation; otherwise, it is a composition operation.


Question: how do we get the inverse of an arrow with such an operation?

A weak operation is a pasting scheme together with two parallel cells in the
free omega groupoid on this pasting scheme.

## Operad

Question: What is the operad O for the weak omega groupoid?

I proposed that O_n is the set of weak operations of dimension n (both the 
pasting scheme and the parallel cells being of dim <= n), but this does
not yield an operad (we do not know how to define multiplication).

## Familiality
S is familial. 

Is W familial? (note this is equivalent that W preserves connected limits, such
as pullbacks).

For this, it is enough that the strictification transformation
W → S is cartesian, i.e. for any globular set X,

W(X) ----> S(X)
  |         |
  |         |
  |         |
  V         V
W(1) ----> S(1)

is a pullback.

I don't think W is familial.

## Strictification

We believe there is a strictification functor F : W → S
But then, consider the coherence x,y:⋆, f,g : x=y, α:f=g  ⊢ coh : x=y
How is this coherence cell strictified? It seems we have to make an arbitrary
choice between f and g.

Question: does this coherence cell really exist in Batanin-Leinster definition?

