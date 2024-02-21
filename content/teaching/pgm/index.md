---
title: "Probabilistic Graphical Models"
linkTitle: "Probabilistic Graphical Models"
type: docs
---
Probabilistic Graphical Models refers to concise representations of probability distributions using graphs.
It also studies efficient algorithms for sampling distributions represented in such form. Sampling might need to be done from
the joint probability distribution, the marginals or even conditional distributions. Other algorithmic questions involve computing
the Maximum Likelihood Estimate (MLE), Maximum Aposteriori Estimate (MAP) etc. This topic has deep connections and applications to various
fields including Theoretical Computer Science, Machine Learning, Statistical Physics, Bioinformatics etc. We will also be covering analysis of Markov Chain Monte Carlo (MCMC) Algorithms.

Broadly the course will cover four modules

1. Representations
2. Inference
3. Learning
4. Advanced Topics (More on MCMC Methods, Normalizing Flows, Learning theory)

[Draft Syllabus](pgm_syllabus.pdf)

## Grading

| Type of Eval | --Weightage |
| ------------ | ----------: |
| Quiz 1       |          10 |
| Mid Sem      |          15 |
| Quiz 2       |          10 |
| End Sem      |          25 |
| Assignments  |          20 |
| Project      |          20 |

## Lectures

### Lec 1-2: Probability Recap
  - *Read:* For recalling basics of probability and graph theory, please go through [DB] Chapter 1, 2
  - *Solve:*
        - <sup>sub</sup> For any two distributions $p,q$ on $\\{1, \cdots, n \\}$, show that:
         $$\max\_{A \subseteq \\{1, \cdots, n\\}} | p(A) - q(A) | = \frac{\sum\_{i=1}^n | p(i) - q(i) |}{2}.$$
         Note that the event $A$ choosen in LHS is a way of distinguishing $p$ from $q$ using $1$ sample in the best possible way. The RHS is the $\ell_1$ norm $\|p - q\|_1$.
        - <sup>sub</sup> Prove that any DAG (Directed Acyclic Graph) with finite number of vertices, has atleast one vertex with no incoming edges (ie. pointed towards it). Also show that there is atleast one vertex with no outgoing edges.

            [Hint] Note that there are infinite graphs where the statement is not true. Hence you need to use the fact that the graph has only finite number of nodes in the proof.

### Lec 3: Belief Networks I
  Free parameters in distributions | Conditional Independence reduces parameters | Graph Representation | d-Connectivity and Independence
  - *Read:* [DB] Sections 3.1 - 3.3
  - *Solve:*
        - [DB] Section 3.8 Exercise 24<sup>sub</sup>, 27, 35<sup>sub</sup>.

### Lec 4: Belief Networks II
  d-Connectivity  | I-maps | Minimal and Perfect Imaps
  - *Read:*
      - [KE] [Bayesian Networks](https://ermongroup.github.io/cs228-notes/representation/directed/)
      - [DB] Section 3.3
  - *Explore:*
        - [KF] Chapter 3. Section 3.3

### Lec 5: Markov Networks I
  - *Read:*
      - [DB] Chapter 4
      - [KE] https://ermongroup.github.io/cs228-notes/representation/undirected/

### Lec 6: Markov Networks II
 - *Read:*
       - [DB] Chapter 4
       - [KE] https://ermongroup.github.io/cs228-notes/representation/undirected/


- **[Quiz I](PGM_Quiz_1.pdf)**

### Lec 7: Inference I : Variable Elimination and Message Passing
  - [Notes](https://iiitaphyd-my.sharepoint.com/:o:/g/personal/girish_varma_iiit_ac_in/EjDx5EHDB15HsxnQffn_WkoBxcO1nO3cmaNsz7uSe6q8mw?e=IidTZi)
  - *Read:*
      - [DB] Chapter 5
      - [KE] https://ermongroup.github.io/cs228-notes/inference/ve/

### Lec 8-9: Markov Chain Monte Carlo Sampling
  - *Read*:
      - [Slides by Art Owen](https://statweb.stanford.edu/~owen/pubtalks/05mcmc.pdf) (till slide 22)
      - [MCMC Revolution by Persi Diaconis](https://math.uchicago.edu/~shmuel/Network-course-readings/MCMCRev.pdf) Pages 1-5 (has cryptography example)
  - *Explore*:
      - [MCMC Book Chapter by Art Owen](https://statweb.stanford.edu/~owen/mc/Ch-MCMC.pdf)

### Lec 10: Tutorial - I

### Lec 11: Probability Basics of Sampling: Tail Bounds
  - *Read*:
      - [Lectures Notes by Pravesh Kothari](https://www.cs.princeton.edu/courses/archive/fall16/cos521/Lectures/lec3.pdf)


### Lec 12: Amplification and Ising Model
  - *Read*:
      - [MCMC book by Art Owen](https://statweb.stanford.edu/~owen/mc/Ch-MCMC.pdf).  Pages 6-8 for Ising Model definition. Pages 16-18 for General MCMC formulation (also known as Metropolis - Hasting's). Pages 31 - 32 for MCMC formulation of Ising Model.

- **[Mid Sem Exam](PGM_MidSem.pdf)**


### Lec 13: Intro to Learning Theory
  - *Read*:
      - [Understanding ML by Shai Shalev-Shwartz, Shai Ben-David](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf).  Chapter 2


### Lec 14: Agnostic PAC Learning
  - *Read*:
      - [Understanding ML by Shai Shalev-Shwartz, Shai Ben-David](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf).  Chapter 3, 4

- **Tutorial II on PAC Learning**

### Lec 15: VC Dimension I
  - *Read*:
        - [Understanding ML by Shai Shalev-Shwartz, Shai Ben-David](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf).  Chapter 6

### Lec 16: VC Dimension II - Sauer-Shellah-Peres Lemma
   - *Read*:
        - [Understanding ML by Shai Shalev-Shwartz, Shai Ben-David](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf).  Chapter 6

### Lec 17: Recap & Learning Conjunctions
   - *Read*:
        - [Computational Learning Theory by Vazirani, Kearns](https://pdfs.semanticscholar.org/a3c3/b359f6745b4cfa7238d35b0ce88f4a93c6f1.pdf).  Section 1.3
  - [*Video*](https://www.youtube.com/watch?v=MEJA_Kf51Xo)
  - [*Notes*](pgm_lec17.pdf) 
  

### Lec 18: No Free Lunch Theorem
   - *Read*:
        - [Understanding ML by Shai Shalev-Shwartz, Shai Ben-David](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf).  Chapter 5
  - [*Notes*](pgm_lec18.pdf) 

### Lec 19: Learning Graphical Models
   - *Read*:
        - [Learning Bayesian Nets: PGM Course Lecture Notes](https://ermongroup.github.io/cs228-notes/learning/directed/).  
        - [Learning Markov Nets: PGM Course Lecture Notes](https://ermongroup.github.io/cs228-notes/learning/undirected/).
  - [*Video*](https://www.youtube.com/watch?v=nY15BLUBsbw)  
  - [*Notes*](pgm_lec19.pdf) 

### Lec 20: Group Testing
  - [*Video*](https://web.microsoftstream.com/video/fefbbdd0-05e2-45bb-8709-c86a09a312f8)  
  - [*Notes*](pgm_lec19.pdf) 
  - *Reference*
      - [Sparse Recovery using Sparse Matrices, Section III](https://people.csail.mit.edu/indyk/survey-10.pdf)
  

## Textbook and References

- [DB] [Bayesian Reasoning and Machine Learning](http://web4.cs.ucl.ac.uk/staff/D.Barber/textbook/090310.pdf).
  David Barber

- [KE] [Probabilistic Graphical Models, Course Notes](https://ermongroup.github.io/cs228-notes/).
  Volodymyr Kuleshov and Stefano Ermon

- [MMSM] [Handbook of Graphical Models](https://stat.ethz.ch/~maathuis/papers/Handbook.pdf)
Marloes Maathuis, Mathias Drton, Steven Lauritzen, Martin Wainwright

- [KF] Probabilistic Graphical Models: Principles and Techniques.
  Daphne Koller and Nir Friedman, MIT Press (2009).

- [EX] [Probabilistic Graphical Models](https://www.cs.cmu.edu/~epxing/Class/10708-17/lecture.html)
  Eric Xing

- [KM] Machine Learning: a Probabilistic Perspective
  by Kevin Patrick Murphy

- [WJ] [Graphical Models, Exponential Families, and Variational Inference](https://people.eecs.berkeley.edu/~wainwrig/Papers/WaiJor08_FTML.pdf)  Martin J. Wainwright and Michael I. Jordan

- [MM] [Information, Physics, and Computation](https://web.stanford.edu/~montanar/RESEARCH/book.html)
  Marc Mézard and Andrea Montanari