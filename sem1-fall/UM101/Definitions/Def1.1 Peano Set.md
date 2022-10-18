#### Definition 1.1: Peano Set
A set A is said to be a Peano Set if it satifies the following axioms:
1. There is a distinguished element; which we call 0 in A
2. There is a function S from A to A called the successor function
3. $S(a) \neq 0, \forall \space a \in A$
4. If $S(a) = S(b)$, then $a=b \space \forall a,b \in A$ (one-one, injective)
5. (Principle of mathematical induction). Suppose B is a subset of A such that $0 \in B$, and $S(a) \in B, \forall \space a \in B$, then B=A

#### Example
Let A be a set such that 
1. A = {0,1,2,3,4}
2. S(0) = 1, S(1) = 2, S(2) = 3, S(3) = 4, S(4)  = 1
This is not a Peano set because of P4:  S(0) = S(4) but 0 $\neq$ 4

#### Example
Let A be a set such that
1. A = {0, 0.5, 1, 1.5, 2, 2.5, 3, 3.5, ...}
2. S(x) = x + 1
This is not a Peano set because of P5
Let us assume B is a subset of A which contains 0. It also contains S(0) and S(S(0)) and so on
so, B = {0,1,2,3, ...}
But A $\neq$ B. This violates P5 


Discussed on [[UM101 2022.10.17|17/10/2022]]