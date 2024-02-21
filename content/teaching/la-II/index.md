---
title: "Linear Algebra II"
linkTitle: "Linear Algebra II"
type: docs
---

An introduction to intermediate level topics in Linear Algebra by a series of [probing questions and answers](https://en.wikipedia.org/wiki/Socratic_questioning). Specifically the following topics are covered:  
-  Eigenvalues & Eigenvectors  
-  Norms, Inner Products and Projections
-  Spectral & Singular Value Decomposition Theorems
-  Applications of SVD and Best Fit Subspaces

All materials including videos, notes, assignments are provided here. The textbooks used are also openly available. The course was designed for computer science and electronics undergraduate engineering students at IIIT Hyderabad. 

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">reviews! not so bad i guess.<br>amazed by students who took time to solve hard problems even during these times. <a href="https://t.co/5sgsiRY7oZ">pic.twitter.com/5sgsiRY7oZ</a></p>&mdash; Girish Varma (@girishvarma) <a href="https://twitter.com/girishvarma/status/1389278000764522507?ref_src=twsrc%5Etfw">May 3, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Prerequisites
Assumes that Linear Algebra I is covered. Specifically assumes knowledge of the following topics:

- Solutions to Linear Equations, Echelon Forms, Gaussian Elimination
- Field, Vector Space Defintions, Real, Complex, Finite Field based Vector Spaces
- Linear Transformation, Matrix, Rank, Inverse, Transpose
- Change of Basis and effect on Matrix of the Linear Transformation
- Determinants

## Schedule

### Meetings

##### Live Lectures
From 30th March to 4th May, 2021, Tuesdays, Thursdays and Saturdays
- 10-11 AM for Batch 2
- 12-01  PM for Batch 1


##### Tutorials
Weekly tutorials conducted by TAs in smaller groups as per times fixed.


##### Office Hours
I will be available on Teams during the timings given bellow, for clearing any doubts. 
You can sent a direct message to me for joining.
- Monday, 530-730PM.
- Thursday, 330-530PM.

### Expected Workload
Students are expected to spent atleast 12 hrs per week. Roughly
- 3+1 hrs attending lectures and tutorials
- 4 hrs reading textbooks, references etc 
- 4 hrs solving assignments, quizes etc

### Evaluations
- 4 Light Quizzes (Weekly)
- 3 Assignments
- 2 Deep Quizzes (17th April, 4th May)

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Your intelligence cannot be measured by just a number. It is defined by your willingness to learn, solve problems and try new things.<br><br>You are more than just a number. Develop your skills wherever they may lead. Share your ideas. Your skills are more valuable than your grades. 🧠</p>&mdash; Prof. Feynman (@ProfFeynman) <a href="https://twitter.com/ProfFeynman/status/1382170602467856384?ref_src=twsrc%5Etfw">April 14, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Textbook and References

### Textbook
The resources provided are licenced under Creative Commons/Open Licences and hence downloadable.

- \[CDTW\] [Linear Algebra](https://www.math.ucdavis.edu/~linear/)  
  David Cherney, Tom Denton, Rohit Thomas and Andrew Waldron

- \[WKN\] [Linear Algebra with Applications](https://lyryx.com/linear-algebra-applications/)  
  W. Keith Nicholson

- \[MR\] [Interative Linear Algebra](https://textbooks.math.gatech.edu/ila/)  
  Dan Margalit and Joseph Rabinoff

- \[DA\] [Understanding Linear Algebra](http://merganser.math.gvsu.edu/david/linear.algebra/ula/ula/ula.html)  
  David Austin

### Extra Reading
- [Down with Determinants](https://www.maa.org/sites/default/files/pdf/awards/Axler-Ford-1996.pdf)  
  Sheldon Axler

- [Linear Algebra Done Right Videos](https://linear.axler.net/LADRvideos.html)  
  Sheldon Axler

- [Markov Chains and Google's PageRank Algorithm](http://merganser.math.gvsu.edu/david/linear.algebra/ula/ula/sec-stochastic.html)  
  Understanding Linear Algebra, David Austin.

- [The Fast Fourier Transform and Polynomial Multiplication](http://www.cs.ust.hk/mjg_lib/Classes/COMP3711H_Fall16/lectures/FFT_Slides.pdf)  
  Mordecai GOLIN

- \[GS\] [Linear Algebra MIT OCW Course Materials](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/resource-index/)   
  Gilbert Strang

### Interactive Videos
- [Essence of Linear Algebra by 3Blue1Brown.](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)  
- [Linear Algebra at Khan Academy.](https://www.khanacademy.org/math/linear-algebra)  
- [Mathigon.](https://mathigon.org/)  

### On Solving Problems & Understanding Proofs

- [Richard Feynman, His Life, and the Art of Solving Important Problems](https://www.jurnalanas.com/feynman-and-the-art-of-problem-solving/)  
  Blog Post

- [How to Solve it](https://math.hawaii.edu/home/pdf/putnam/PolyaHowToSolveIt.pdf)   
  G. Polya  
  [Shorter Version](https://math.berkeley.edu/~gmelvin/polya.pdf)


## Lecture Topics

### 1. Eigenvalues & Diagonalization

#### 1.1 Linear Algebra & Random Walks  

<iframe width="560" height="315" src="https://www.youtube.com/embed/qWbABNXFsUo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

   Recalling Basics | Function Spaces | Random Walk on Graphs 
   - [Notes](notes/lec1.pdf)
   - Reading
     - Section 2.9 in [WKN]

#### 1.2 Eigenvectors and Eigenvalues  

<iframe width="560" height="315" src="https://www.youtube.com/embed/fO_kiQ_hFyE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

   Definitions | Characteristic Polynomial | Examples
   - [Notes](notes/lec2.pdf) 
   - Reading  
      - Section 3.3 for Eigenvalues, Section 2.9 for Random Walks on Graphs in [WKN].
  	  - Chapter 12 in [CDTW].
    
#### 1.3 Diagonalization   

   <iframe width="560" height="315" src="https://www.youtube.com/embed/jss3SE-Je1o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  
   Eigenvector Basis and Powering | Multiplicities       
   - [Notes](notes/lec3.pdf) 
   - Reading
       - Section 3.3 in [WKN]  
  	   - Chapter 13 in [CDTW]

#### [Assignment 1](problems.pdf)
Submit by 13th April
   - [Notes](notes/assignment_1_disc.pdf) 
   - Practice Problems:**<sup style="color: red; background-color: yellow; padding: 5px; border-radius: 5px;">new</sup>**
     - Show that for any matrix $M \in \mathbb R^{n \times n}$ with eigenvalue $\lambda \in \mathbb R$, 
$$ \text{geometric_multiplicity}(\lambda, M) = \text{geometric_multiplicity}(\lambda, M^t).$$  
     - Let $M$ be block diagonal with blocks $M_1,\ldots,M_k$ (all square matrices). Show that:
        $$ \text{geometric_multiplicity}(\lambda, M) = \sum_{i=1}^k \text{geometric_multiplicity}(\lambda, M_i).$$
 
   
### 2. Norms & Inner Products

#### 2.1 Norms & Inner Products   

<iframe width="560" height="315" src="https://www.youtube.com/embed/61qYfkls2L0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

   Jordan Form | Norms | Distance | Inner Product | Complex Case  
   - [Notes](notes/lec4.pdf) 
   - Reading
       - Section 10.1 in [WKN]
   - Explore 
       - For Jordan Form, Generalized Eigenvectors, see [Down with Determinants](https://www.maa.org/sites/default/files/pdf/awards/Axler-Ford-1996.pdf).
       - [Geometric Multiplicity $\leq$ Algebraic Multiplicity.](http://www.ee.iitm.ac.in/~uday/2017b-EE5120/multiplicity.pdf) 
       - [Rotation Matrics have complex eigenvalues.](http://scipp.ucsc.edu/~haber/ph116A/Rotation2.pdf)
  
#### 2.2 Orthonormal Vectors 

<iframe width="560" height="315" src="https://www.youtube.com/embed/BhZ_cqCwGfQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

   Orthogonal & Orthonormal Vectors | Gram-Schmidt Orthogonalization  
   - [Notes](notes/lec5.pdf) 
   - Reading
       - Section 10.2 in [WKN]
       - Chapter 14 in [CDTW]
   - Explore 
       - For Bilinear forms see [Slides of Prof. P. Karageorgis](https://www.maths.tcd.ie/~pete/ma1212/chapter3.pdf).


#### 2.3 Projection and Orthogonal Complement

<iframe width="560" height="315" src="https://www.youtube.com/embed/mG0px7sl66M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

   Subspace Projections | Orthogonal Complements | Fitting with Errors
   - [Notes](notes/lec6.pdf)
   - Reading
       - Section 14.6 in [CDTW]
       - Section 8.1 in [KTW]


#### 2.4 Least Squares Fitting 

<iframe width="560" height="315" src="https://www.youtube.com/embed/qEtnrYJ43do" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

   Best fit vector on a subspace | Least Squares Fitting Equation
   - [Notes](notes/lec7.pdf)
   - Reading
     - \[MR\] [Section 6.5](https://textbooks.math.gatech.edu/ila/least-squares.html)
     - Chapter 7 (upto page 307) in [CDTW]

#### Deep Quiz I and Discussion
   - [Notes](notes/lec8.pdf) | [Video](https://web.microsoftstream.com/video/6adb50ee-9d24-430c-823d-3f2a6462c271)


### 3. Advanced Topics


#### [Assignment 2](problems.pdf)
Submit by 26th April

#### 3.1 Symmetric Matrices and Properties

<iframe width="560" height="315" src="https://www.youtube.com/embed/fKk4boPUYgI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

  Eigenvalues and eigenvectors of Symmetric Matices | Spectral Theorem
   - [Notes](notes/lec9.pdf) 
   - Reading
     - Chapter 15 in [CDTW]  
   - Solve  
     - Question 3, 5 in Review Problems 15.1 in [CDTW]
     - If $P$ is the change of basis matrix for changing coordinates from standard basis to another orthonormal basis, then columns of $P$ are orthonormal.
     - If columns of $P$ are orthonormal then rows of $P$ are also orthonormal.


#### 3.2 Spectral Decomposition Theorem

<iframe width="560" height="315" src="https://www.youtube.com/embed/nNKqYWkvuNA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

  Spectral Theorem | Spectral Decomposition
   - [Notes](notes/lec10.pdf)
   - Reading
     - Section 10.3 in [WKN]
     - Chapter 15 in [CDTW]
   - Solve
     - Let $v_1,\cdots, v_n$ be a basis for an $n$ dimensional vector space $V$ over some field $\mathbb F$ and let $M,M' \in \mathbb F^{n\times n}$ be matrices. Show that if $$\forall i \in \\{1,\ldots, n\\},\qquad Mv_i = M'v_i$$ then $M=M'$.  
     - Consider the $n$ dimenstional complex vector space $\mathbb C^n$. Is $\mathbb R^n$ a subpace of $\mathbb C^n$?  
     - We know that $\mathbb R^n$ is a subset of $\mathbb C^n$. Suppose $v_1,\ldots, v_n \in \mathbb R^n$ be orthonormal vectors. Can they form a basis for $\mathbb C^n$?

#### 3.3 Singular Value Decomposition

<iframe width="560" height="315" src="https://www.youtube.com/embed/kMbWVWbW9mw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

  Spectral Theorem for Complex Spaces | Singular Value Decomposition
   - [Notes](notes/lec11.pdf) 
   - Reading
     - Section 17.2 in [CDTW]
     - Section 8.6 in [WKN]

### 4. Applications

#### 4.1 SVD & Applications

<iframe width="560" height="315" src="https://www.youtube.com/embed/yoWaIiRdQ7c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

  Principal Component Analysis | Applications in Data Science
  - [Notes](notes/lec12.pdf)   
  - Read
    - Section 8.11 in [WKN]
  - Code
    - [Finding axis of a spiral galaxy.](https://colab.research.google.com/drive/1DQBLsKjFSrxi5IBH8rFE42FjZVOo7Tgi?usp=sharing)
  - Explore
    - [PCA and Image Compression](http://people.ciirc.cvut.cz/~hlavac/TeachPresEn/11ImageProc/15PCA.pdf). 

#### [Assignment 3](problems.pdf)
See Section 6 in [Problems](problems.pdf).
Submit by 7th May.

#### 4.2 SVD & Best Fit Subspaces

<iframe width="560" height="315" src="https://www.youtube.com/embed/MuKUsD-choc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

  - [Notes](notes/lec13.pdf)  
   - Read  
     - Chapter 3 in [Foundations of Data Science by Blum, Hopcroft, and Kannan](https://www.cs.cornell.edu/jeh/book.pdf).  
  - Problems **<sup style="color: red; background-color: yellow; padding: 5px; border-radius: 5px;">new</sup>**
    - Suppose $W$ is a $k$ dimensional subspace of $\mathbb R^n$ and $v_1,\ldots, v_{k-1} \in \mathbb R^n$ be orthonormal vectors (may or may not be in $W$).
      Show that there exists a vector $w\in W$ that is nonzero, such that $w \in \text{span}(v_1,\ldots, v_{k-1})^\perp$. That is
      $$ \exists w \in W \cap \text{span}(v_1,\ldots, v_{k-1})^\perp \text{ such that } w \neq 0. $$
    - Suppose $M \in \mathbb R^{n \times n}$ is invertible with singular value decomposition:
      $$ M = \sum_{i=1}^n s_i u_iv_i^T \qquad \text{ where } s_i \in \mathbb R^{+}, u_i,v_i \in \mathbb{R}^{n \times 1}.$$
      Let $M' = \sum_{i=1}^n s^{-1}_i v_iu_i^T$. Show that $M' = M^{-1}$.




### 5. Course Summary, More Applications & Closing Notes.

<iframe width="560" height="315" src="https://www.youtube.com/embed/MFZAqba7IgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

   - [Notes](notes/lec14.pdf)  
   - Reading
     - [Determinants and Volume](https://textbooks.math.gatech.edu/ila/determinants-volumes.html).
   - Applications
     - Algorithms: [Discrete Fourier Transform](http://www.cs.ust.hk/mjg_lib/Classes/COMP3711H_Fall16/lectures/FFT_Slides.pdf) and Fast Multiplication. 
     - Spectral Graph Drawing: [Spielman](https://www.youtube.com/watch?v=CDMQR422LGM), [Book Chapter](https://www.cis.upenn.edu/~cis515/cis515-15-graph-drawing.pdf)
     - [Robotics](http://16623.courses.cs.cmu.edu/slides/Lecture_18.pdf), VR, AR uses 3D, 6D data.
     - [Pooled Testing for COVID](https://signalprocessingsociety.org/newsletter/2020/07/compressed-sensing-approach-group-testing-covid-19-detection): currently being used in IIIT to test 400 campus residents with only 40 tests.
     - [Compress Sensing](http://theory.stanford.edu/~tim/s15/l/l13.pdf).
     - Machine Learning and Data Science. See [Foundations of Data Science by Blum, Hopcroft, and Kannan](https://www.cs.cornell.edu/jeh/book.pdf)
     - Communications Systems: Error Correcting Codes (See Section 8.8 in [WKN]).
     - Quantum Computing
       - [Videos by M. Nielsen](https://www.youtube.com/playlist?list=PL1826E60FD05B44E4).
       - [QED](https://en.wikipedia.org/wiki/QED:_The_Strange_Theory_of_Light_and_Matter) by Feynmann.
       - [Lecture Notes by Vazirani.](https://people.eecs.berkeley.edu/~vazirani/quantum.html)


#### [Deep Quiz II](problems.pdf)
On 4th May
  