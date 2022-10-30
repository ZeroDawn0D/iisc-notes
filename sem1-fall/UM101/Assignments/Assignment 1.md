###### **Problem 1.** 
**Let A be a Peano set and S be the successor function on A(as defined in the first lecture). Show, using only the axioms of Peano, that the range of S is A - {0}. For this question, please interpret the words “function” and “range” in the way you did in school, and not in the set-theoretic way introduced in class**

1. From P2, we know that the codomain of S is A. Let range be denoted by R. We know that $R \subseteq A$
2. Let B be the set of all non-zero values in A that cannot be obtained by S(a) for some $a \in A$. So, any element of B will not be present in the range, ie. $b \notin R \forall b \in B, B \subseteq A$. From P3, we also know that $S(a) \neq 0$. So, we can say $R = A - (\{0\} \cup B)$
3. $B \subseteq A \Rightarrow b \in A \ \space\forall\space b \in B$
4. Assuming there is an element $b \in B$, then $b \in A$. Let C be a subset of A such that $0 \in C, S(c) \in C \space\forall\space c \in C$. Since S does not give the output b, we have $b \notin C$, so we get $C \neq A$. This violates P5, which is a contradiction as A is a Peano Set. So, $b \notin B \implies B = \phi$
5. $R = A - (\{0\} \cup \phi) \implies R = A - \{0\}$

Hence, Proved

###### Problem 2a.
**Given two sets A and B, show that $A \cap B$ is a set**

1. $A \cap B$ is defined to be a set where each element is present in both the sets A and B
2. From Axiom of Specification, all subsets $C \subseteq A$ of form $C = \{x \in A | \phi(x)\}$ exist
3. If we define $\phi(x)$ to be $x \in B$, we get $C = \{x \in A: x \in B\}$
This set C is the intersection of the sets A and B

###### Problem 2b.
**Given two sets A and B, show that $A - B$ is a set**

1. $A - B$ is defined to be a set where each element is present in set A but not B
2. From Axiom of Specification, all subsets $C \subseteq A$ of form $C = \{x \in A | \phi(x)\}$ exist
3. If we define $\phi(x)$ to be $x \notin B$, we get $C = \{x \in A: x \notin B\}$
This set C is the set A-B

###### Problem 3.
**Given two objects a,b, let (a,b) denote the set {{a}, {a,b}}. First argue why the ZFC axioms guarantee the existence of this set. Then show that (a,b) = (c,d) only when a = c and b = d**

From the Axiom of Pairing, we know that for every two objects, the set {a,b} and {a} exist. SImilarly, for the sets $\{a\}$ and $\{a,b\}$, we know the set $\{\{a\}, \{a,b\}\}$ exists, which is (a,b).

Let X = (a,b), Y = (c,d). X=Y holds only when $X \subseteq Y$ and $Y \subseteq X$. (Axiom of Extension)

Case 1: a=b
(a,b) = (a,a) = { {a}, {a,a} } = { {a} }
X has one element, {a}. $X = Y$ iff {a} = {c} and {a} = {c,d}, c=d

if a = c, then b = c holds if {a} = {c,d} then c = d holds, so the statement a = c and b = d are true

Case 2: a $\neq$ b

X has two elements {a} and {a,b}. $X \subseteq Y$ is true when {a} = {c} and {a,b} = {c,d}

if a $\neq$ b then this condition implies {a} = {c} and {b} = {d}


Combining the two cases, (a,b) = (c,d) iff a = c, b = d


###### Problem 4.
**Prove Lemma 1.5, show that if E is a non-empty set of induction sets, then $$\bigcap_{A \in E} A$$
is an induction set**

Let  $$B = \bigcap_{A\in E} A$$
1. $\forall a \in A, A \in E,$ We know $a^+ \in A$ (by definition of Inductive sets)
2. $\forall b \in B$, we know that $b \in A, A \in E$  (B is the intersection set of all sets $A \in E$)
3. If a set b exists in set A, then the set $b^+$ must also exist in set A. 
4. If the set $b^+$ is present in all sets A, then it is also present in set B.
5. Combining steps 2 and 4, we get $\forall b \in B, b^+ \in B$
Therefore, B is an inductive set. 

###### Problem 5.
**Decide which of the statements are wrong. For the true statements, provide a proof. For the others, provide one counterexample each**

###### 5a.
$A \times (B \cup C) = (A \times B) \cup (A \times C)$

Let 
$X = A \times (B \cup C)$ 
$Y = (A \times B) \cup (A \times C)$

(0.1)
Let $(x_1,x_2) \in X$, then $x_1 \in A$ and $x_2 \in B \cup C \implies x_2 \in B$ or $x_2 \in C$. 

We have two possible cases:
Case 1: $x_1 \in A,x_2 \in B$
	$(x_1,x_2) \in A \times B \implies (x_1, x_2) \in Y$
Case 2: $x_1 \in A,x_2 \in C$
	$(x_1,x_2) \in A \times C \implies (x_1, x_2) \in Y$

We get $X \subseteq Y$

(0.2)
Let $(y_1,y_2) \in Y$, then $(y_1,y_2) \in A \times B$ or $(y_1,y_2) \in A \times C$

We have two possible cases:
Case 1: $(y_1,y_2) \in A \times B$
	$y_1 \in A, y_2 \in B \implies y_2 \in B \cup C$
	$(y_1,y_2) \in X$
Case 2:$(y_1,y_2) \in A \times C$
	$y_1 \in A, y_2 \in C \implies y_2 \in B \cup C$
	$(y_1,y_2) \in X$

We get $Y \subseteq X$

Combining (0.1) and (0.2), we conclude that X=Y (Axiom of Extension)

###### 5b.
$(A \times B) - (C \times D) = (A-C) \times (B-D)$

Counterexample:
A = {1,2}
B = {3,4}
C = {2}
D = {4}

LHS
{(1, 3), (1, 4), (2, 3)}

RHS
{(1,3)}

###### 5c.
$C \cap (A-B) = A \cap (C-B)$
Let 
$X = C \cap (A-B)$ 
$Y = A \cap (C-B)$

(0.1)
Let $x \in X$
$x \in C$ and ($x \in A$ and $x \notin B$)
$x \in A$ and ($x \in C$ and $x \notin B$)
$x \in Y$
$X \subseteq Y$

(0.2)
Let $y \in Y$
$y \in A$ and ($y \in C$ and $y \notin B$)
$y \in C$ and ($y \in A$ and $y \notin B$)
$y \in X$
$Y \subseteq X$

Combining (0.1) and (0.2) $X=Y$ by xiom of extension


###### 5d.
$C \cup (A-B) = A \cup (C-B)$
Counterexample
A = {1,2,4}
B = {2,4}
C = {2,3,5}

###### Problem 6.
**Let A be a set. Define a relation R such that for any subsets B and C of A $$B R C \Longleftrightarrow B \subseteq C$$
Remember that a relation R is a subset of a Cartesian product of sets. Is the relation that you've defined a function.**

$B \subseteq A \implies B \in P(A)$
$C \subseteq A \implies C \in P(A)$

Case 1: $A = \phi$
$\implies P(A) = \{\phi\}$
$\implies B = \phi$ and $C = \phi$
$\implies R = \{(\phi, \phi)\}$

(1.1)
$dom(R) = \phi$
So we get dom(R) = B

(1.2)
$\forall B \in P(A)$, there is exactly one $C \in P(A)$ such that $(B,C) \in R$

Combining (1.1) and (1.2), we conclude that R is a function when A is a null set

Case 2: $A \neq \phi$
We know that $\phi \in P(A)$
when $B = \phi$, $B\subseteq C$ and $(B,C) \in R$ is true $\forall C \in P(A)$

So, R is not a function