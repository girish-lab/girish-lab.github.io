---
title: "Advanced Mathematical Structures"
linkTitle: "Adv. Math. Structures"
type: docs
weight: 50
---

This course is intended to familiarize the students with the types of mathematical reasoning found in theoretical research on computing and communications. The course contains a broad set of intermediate and advanced level topics in Algebra, Combinatorics, Probability and Graph Theory.

**Goal**: By the end of the course, students should be able to read and understand research papers with algebraic/combinatorial reasoning. They should should be able to write concise and clear proofs.

**Prerequisites**: Students are expected to have already attended Discrete Maths, Linear Algebra and Probability courses some time in their career. Though we will be revising these in a few lectures, the course will quickly move on to advanced topics.

**Acknowledgements**: This course is loosely based on a similar course offered by Jaikumar Radhakrishnan (http://www.tcs.tifr.res.in/~jaikumar/Courses/MathStructures/Autumn06/) at TIFR, Mumbai.

## Grading
- Assignment Tests: 20%
  - Practice problems will be given after each lecture.
  - There will be a test based on practice problems (5 in total) with 5 marks each. The best 4 marks will be used for grading.

- Quiz 1, Quiz 2: 10% each

- MidSem: 25%

- EndSem: 35%

- Bonus Marks: 5% (for 90% attendance or solve some hard problem that will be given).

## Lectures

### Lec 1: Operator | Associativity | Groups | Subgroups | Integer Subgroups | Cyclic Groups

- *Read*: [MA] Chapter 2, Section 1,2. [TJ] Chapter 3, 4
- *Solve*:
    1. Prove that there is a unique Identity element for any group.
    2. [MA] Chapter 2 Exercies, Section 1 Question 5, Section 2 (Page 70) Question 10
    3. [TJ] Section 3.4: Problems 2, 10

### Lec 2: Burnside / Pólya Counting
- *Read*: [JM] Chapter 22, 23.
    [Alon Frieze's Slides](https://www.math.cmu.edu/~af1p/Teaching/Combinatorics/Slides/Polya.pdf)
- *Solve*: [JM] 23.4 Exercises (Lecture 23), 1, 3

### Lec 3: Isomorphisms | Homomorphisms | Cosets | Legrange's Theorem | Fermat Little Theorem | FLT Proof using Polya Counting
- *Read*: [MA] Chapter 2, Section 3, 4, 5, 6.
    For FLT Proof using Polya Counting see the [blog post](https://keriimov.wordpress.com/2015/05/24/a-combinatorial-proof-for-fermats-little-theorem-2/)
- *Solve*:
    1. If $G$ has no proper subgroups then show that $G$ is cyclic of order $p$, where $p$ is a prime number.
    2. If $G$ is not a cyclic group then show that $G$ has a proper subgroup (ie not $\{0\}$ or $G$ itself).
    3. A group is called Abelian if the operation is also commutative. Prove that
        1. Every finite cyclic group has to be an Abelian Group
        2. Give an example of a finite Abelian Group that is not cyclic.
    4. $\mathbb{Z}_p\times \mathbb{Z}_q$ is the product of the two sets with $pq$ elements. Addition is defined coordinate wise. Prove that:
        1. $\mathbb{Z}_p\times \mathbb{Z}_q$ is a group.
        2. Show that if $p, q$ is coprime (ie has gcd = 1) then $\mathbb{Z}\_p \times \mathbb{Z}\_q$ is isomorphic to $\mathbb{Z}_{pq}$.
    5. Let $p$ be a prime and $n, k$ positive integers, $F = \left\\{ f:\mathbb{Z}\_p^k \rightarrow [n] \right\\}$ (the set of all functions from $\mathbb{Z}\_p^k$ to $[n]$.). For a function $f \in F$, and $a \in \mathbb{Z}\_p^k$, the translation of $f$ by $a$ is the function $g(x) = f(x + a)$ (addition is defined coordinate-wise modulo $p$).
        1. Define a group and a group action of that group on $F$ that captures translations, which could be used to count the number of distinct functions with translation symmetry (ie. $f(x)$ and $g(x) = f(x + a)$ is in the same orbit).
        2. Let $a \in \mathbb{Z}^k\_p \setminus \\{ 0^k \\}$ . What is the number of cycles in the permutation corresponding to the translation by $a$?
        3. Use above to show that $p^k$ divides $n^{p^k} - n^{p^{k-1}}$.

        [Hint] This is the strict generalization of the [example we did in class: the proof of FLT theorem](https://keriimov.wordpress.com/2015/05/24/a-combinatorial-proof-for-fermats-little-theorem-2/). For getting that result, substitute $k=1$ and $n = a$.


    6. A function $f:[m]^k \rightarrow [n]$ is symmetric if for all $x, y \in [m]^k$ such that $y$ can be obtained by permuting $x$ (using a permutation in $S\_k$), $f(x) = f(y)$. For example the sum  and product functions ($f(x) = \sum\_{i\in [k]} x\_i \mod n$ and $g(x) = \prod\_{i\in [k]} x\_i \mod n$ correspondingly) are symmetric. The Max, Min functions are also symmetric. Find the number of symmetric functions in terms of $m, n, k$. [Hint] Requires some ball and bins counting.

    7. Let $k$ be prime and $\mathcal F = \left\\{ f:[m]^k\rightarrow [n] \right\\}$ (set of all functions from $[m]^k$ to $[n]$). $g$ is a cyclic reordering of $f$, if $\exists i \in [k]$ such that $g(x) = f(\sigma^i(x))$ where $\sigma^i(x) = x\_i \cdots x\_n x\_1 \cdots x\_{i-1}$. Find the number of distinct functions in $\mathcal F$ if cyclic reorderings are considered the same.
    Use this to show that $k$ divides $n^{m^k} - n^t$ where $t = \frac{m^k - m}{k} + m $.


### Lec 4: Counting | 12 fold way of Counting Balls and Bins
- *Read*: [CoCo] Sections 1 - 1.5.2
- *Solve*:
    1. Let $k\_1, k\_2, ...., k\_n$ be numbers such that $ \sum_{i=1}^n i \cdot k_i = n$. Find the number of permutations of $[n]$, with $k_1$ cycles of length $1$, $k_2$ cycles of length $2$, $\cdots$, $k_n$ cycles of length $n$.
    2. Find a generating set of size $2$ for $S_n$. (Need to prove why your set generates $S_n$).


### Lec 5: 12 fold way of Counting Balls and Bins | Permutations | Inversions | Cycle Structure | Transpositions
- *Read*: [CoCo] Sections 1.5.2 - 1.7


### Lec 6: Cycle Structure | Parity of Permutation | Derangements | Inclusion Exclusion
- *Read*: [CoCo] Sections 1.7.1, 1.7.2, 1.7.3, Section 2 - 2.1.1.
- *Solve*:
    1. Show that the set of even parity permutations form a subgroup of $S_n$ of size $n!/2$. Show that the set of odd partiy permutations is a coset of this subgroup.
    2. Let $A\_1, \cdots, A\_k \subseteq [n]$. For $S \subseteq [k]$, let $A\_S = \cap_{s \in S} A\_s$ and $A\_\emptyset = [n]$. Then for $0 \leq r \leq k$, show that:
        1. For odd $r$,
        $$ \left\| \overline{ \cup\_{i \in k} A\_k } \right\| \geq \sum\_{S \subseteq [k]: |S| \leq r } (-1)^{|S|} \| A\_S \|$$
        2. For even $r$,
        $$ \left\| \overline{ \cup\_{i \in k} A\_k } \right\| \leq \sum\_{S \subseteq [k]: |S| \leq r } (-1)^{|S|} \| A\_S \| $$


- **Tutorial 1**

- **Test 1 | Lec 7: Inclusion Exclusion Examples**
  - *Read*: [CoCo] Section 2.
  - *Solve*:
        1. Consider the set of all functions from $[2n]$ to $[2n]$.
           1. Find the number of functions having size of the range to be exactly $k$.
           2. Find the number of functions for which the range is exactly the set of even numbers in $[2n]$.

### Lec 8: Inclusion Exclusion | Proof using Linear Algebra
  - *Read*:
      1. [CoCo] Sections 2.1.2, 2.2.
      2. For Linear Algebra proof read [RP Stanley](http://www-math.mit.edu/~rstan/ec/ec1.pdf) pages 223-225.
  - *Solve*:
      1. Let $n \geq 2$ be a positive integer. The Euler totient function is defined by $\phi(n) = \left| \\{ m: m < n \text{ and } \text{gcd}(m,n) = 1 \\} \right|$. If the prime factorization of $n$ is $n = p\_1^{e\_1}\cdot p\_2^{e\_2} \cdots p\_k^{e\_k}$. Show using inclusion exclusion that:
            $$\phi(n) = n \prod_{i=1}^k \left(\frac{p_i - 1}{p_i}\right).$$

            [Hint] Choose sets $A\_1, \cdots, A\_k$ that can easily be counted such that $\phi(n) = \left| \overline{A\_1 \cup \cdots \cup A\_k} \right|$.

- **Office Hrs 1**

- **[Quiz I](AMS_Quiz_1.pdf)**

### Lec 9: Answer Discussion
  - *Solve*:
        1. Let $\mathcal B\_n = \left\\{ f:\\{0,1\\}^n \rightarrow \\{0,1\\} \right\\}$ (the set of all Boolean functions). A function $f\in \mathcal B\_n$, depends on $i$th coordinate ($i \in [n]$) if $\exists x\_1, \cdots, x\_{i-1}, x\_{i+1}, \cdots, x_n \in \\{0,1\\}$ such that for $y = x\_1 \cdots x\_{i-1}0x\_{i+1} \cdots x\_n$, $y' = x\_1 \cdots x\_{i-1}1x\_{i+1} \cdots x\_n$, $f(y) \neq f(y')$. Find the number of functions which depends on all the coordinates in $[n]$.
        2. Let $k \geq r$. Prove Lec 6, Problem 2 by first showing that:
            1. For odd $r$,
            $$ {k \choose 0} - {k \choose 1} + \cdots + (-1)^r { k \choose r } \leq 0$$
            2. For even $r$,
            $$ {k \choose 0} - {k \choose 1} + \cdots + (-1)^r { k \choose r } \geq 0$$


### Lec 10: Families of Sets: Sperner's Theorem | Intersecting Families | Hall's Theorem (SDR)
  - *Read*: [PJC] Chapter 7. [DG] Section 1.7 for Sperner's Thm. Chapter 4 for SDR.
  - *Solve*:
        1. Let $n = 2k$. Show that there are $2^{2k−1 \choose k−1}$ intersecting families of $k$-element subsets of $[n]$ having the maximum number${2k−1 \choose k−1}$ of members.
        2.  Show that, for every non-empty subset $A$ of $[n]$, there is an intersecting family $\mathcal{F}$ of subsets of $[n]$ of size $2^{n−1}$ with $A\in \mathcal F$. Show further that any two subsets $A,B$ with $A\cap B \neq \phi$ are contained in a family with these properties. What about three pairwise intersecting sets?

### Lec 11: System of Distinct Representatives | Erdős-Ko-Rado Theorem
  - *Read*: [PJC] Chapter 7 (Appendix for Erdos-Ko-Rado).  Chapter 4 for SDR.

### Lec 12: Rings, Fields and Vector Spaces I
  - *Read*: [ADS] Chapter 16. [TJ] Chapter 16.

### Lec 13: Rings, Fields and Vector Spaces II
  - *Read*: https://web.stanford.edu/class/ee392d/Chap7.pdf

- **[Mid Sem Exam](AMS_Midsem.pdf)**

### Lec 14: Probability and Computing | PIT | Min Cut | Erdős Ko Rado
  - *Read*
      - Min Cut: http://faculty.cs.tamu.edu/klappi/cpsc411s09/minimum_cut.pdf
      - Probability Basics and EKR (Section 2.3): http://www.cs.cmu.edu/~15850/handouts/matousek-vondrak-prob-ln.pdf

  - *Solve*
      1. Suppose $A$ is a randomized algorithm for a decision problem ($0,1$ output)  which takes $x \in \\{0,1\\}^n$ (where $n$ is a fixed number say $100$; we are not interested in all inputs which are infinite in number but only the $2^n$ inputs of length $n$) as input. Also suppose we provide all the randomness that the algorithm requires by giving it a string $r \in \\{0,1\\}^m$ which is chosen uniformly at random. You are told that for all inputs $x \in \\{0,1\\}^n$, the algorithm is correct with probability
      $1-\frac{1}{2^{n+1}}$. That is
      $$ \forall x \in \\{0, 1\\}^n, \Pr_{r \in \\{0, 1\\}^m}\left[A(x,r) \text{ is correct}\right] \geq 1 - \frac{1}{2^{n+1}}.$$
      Then show that there is a fixed string $r \in \\{0,1\\}^m$ such that for every input $x\in \\{0,1\\}^n$, $A(x,r)$ is correct. That is
      $$ \exists r \in \\{0,1\\}^m, \forall x \in \\{0,1\\}^n, A(x,r) \text{ is correct}.$$

      2. Let $p(x_1,x_2,\cdots,x_n)$ be a nonzero polynomial of total degree $d$ (maximum value among all monomials of the sum of degrees of each variable) on $n$ variables with coefficients from a finite field $\mathbb F$.  Let $\alpha_1,\cdots, \alpha_n$ be chosen uniformly and independently from $\mathbb F$. Show that:
            $$ \Pr\left[p(\alpha_1,\cdots, \alpha_n) = 0 \right] \leq \frac{d}{|\mathbb F|}.$$
            Hint: Use induction on number of variables $n$. Decompose the polynomial according to powers of $x_1$. Condition on appropriate event and upperbound the probability.

      3. Suppose you have a fair coin (equal probability of heads and tails). You can use the coin to choose one among four options uniformly at random by tossing it twice and assigning the four outcomes to the four options.
            1. Can you use the fair coin to choose one among three options uniformly at random? Can it be done using a finite number of tosses?
            2. Can it be done using infinite number of tosses? If so, can you give a general method for uniformly choosing one among $k$ options (for any number $k$)?
            3. Using a finite number of tosses, can you choose one among three options "almost" or "approximately" uniform way? When would you say a distribution is almost uniform among three options (what is the mathematical definition of almost uniform)?
            4. Suppose you are given an unfair coin with probability of heads being $p<\frac{1}{2}$. Can you use the unfair coin to simulate a fair coin exactly or even approximately (that is choose 1 among 2 options uniformly)?

### Lec 15: Probabilistic Method
  - *Read:*
      - [AZ] Proofs from the Book, Chapter 35
  - *Solve:*
      1. Let $\sigma$ be a uniformly random permutation chosen from $S_n$. What is the expected number of fixed points ($i$ such that $\sigma(i)=i$) in $\sigma$? What about the expected number of cycles of length $2$? What about the expected number of cycles?
      2. Let $G$ be a random graph on $n$ nodes. That is each of the ${n \choose 2}$ edges is independently chosen with probability $\frac{1}{2}$. What is the expected number of simple cycles of length less than $\ell$?
### Lec 16: Probabilistic Method | Random Graphs
  - *Read:*
      - 3SAT 7/8 algorithm: https://i.cs.hku.hk/~hubert/teaching/c8601_2011/notes1.pdf
      - Method of conditional expectations: https://i.cs.hku.hk/~hubert/teaching/c8601_2011/notes2.pdf
      - Large girth, large chromatic number graphs:
          - [AZ] Proofs from the Book, Chapter 35.
          - [AS] Page 38.
### Lec 17: Tail Bounds | Chebyshev | Chernoff
  - *Read:*
      - http://math.mit.edu/~goemans/18310S15/chernoff-notes.pdf
      - We also used Chernoff's Bound to amplify the probability of a weak algorithm to obtain a strong algorithm using Chebyshev and Chernoff's Bounds.

### Lec 18: Introduction to Spectral Graph Theory
  - *Read:*
      - Upto Page 6 in http://users.cms.caltech.edu/~vidick/notes/CMS139/spectral.pdf

### Lec 19: Random Walks, Eigen Values and Expanders
  - *Read:*
      - Section 4.2 in http://users.cms.caltech.edu/~vidick/notes/CMS139/spectral.pdf

- **[Quiz 2](AMS_Quiz_2.pdf)**

- **Error Correcting Codes | Reed Solomon Codes: 3 lecs (by Prof. Prasad)**
### Lec 23: Graphs and Codes
  - Recapped Error Correcting Codes. Rate, Distance, Hamming bound, Singleton Bound.
  - *Read:*
      - Upto Section 10.4 in http://www.cs.yale.edu/homes/spielman/eigs/lect10.pdf
### Lec 24: Linear Decoding for Expander Codes
  - *Read:* http://www.cs.yale.edu/homes/spielman/eigs/lect10.pdf

### Lec 25: Pairwise Independent Hash Functions
  - Pair/$k$-wise independent hash functions, Application to Set Membership, Construction using Reed Solomon Codes.
  - *Read:*
      - Sections 1, 3, 4 in https://cseweb.ucsd.edu/~slovett/teaching/SP15-CSE190/pairwise_hash_functions.pdf
      - For Construction using Reed Solomon Codes, see Section 2.3 in https://people.csail.mit.edu/ronitt/COURSE/S12/handouts/lec5.pdf

- **[End Sem](AMS_EndSem.pdf)**

## Texbook and References

There is no single book covering all the topics. For different lectures, we will be following material from different sources, which will be posted at the course page. Some of the sources that will be used often are:

- [AZ] Proofs from the Book.
  Aigner and Ziegler

- [AS] The Probabilistic Method.
  Alon and Sipser

- [MA] Algebra by M Artin, Prentice-Hall India.

- [TJ] Abstract Algebra: Theory and Applications
  Thomas W. Judson
  [pdf](http://abstract.ups.edu/download/aata-20180801.pdf)

- [ADS] Applied Discrete Structures,
  Al Doerr, Ken Levasseur
  [pdf](http://discretemath.org/ads-latex/ads.pdf)

- [CoCo] Lecture Notes, Combinatorics
  Lecture by Torsten Ueckerdt (KIT)
  [pdf](http://www.math.kit.edu/iag6/lehre/co2015s/media/script.pdf)

- [JM] Permutation Puzzles: A Mathematical Perspective.
  Jamie Mulholland
  [pdf](http://www.sfu.ca/~jtmulhol/math302/notes/302notes-May07-2012.pdf)

- [PJC] Notes on Combinatorics
  Peter J. Cameron
  [pdf](http://www.maths.qmul.ac.uk/~pjc/notes/comb.pdf)

- [DG] An Introduction to Combinatorics and Graph Theory
  David Guichard.
  [pdf](https://www.whitman.edu/mathematics/cgt_online/cgt.pdf)