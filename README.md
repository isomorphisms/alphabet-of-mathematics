# alphabet-of-mathematics
### a glossary for how various letters and symbols are used in different sciences
###### rationale: shorter learning curve; maybe light up some unexpected connections



I've been meaning to do this for over a decade now. What kicked me in the pants was a friend taking Salman Khan's intro to statistics course online and being flaberghasted at seeing the letter _**p**_&nbsp;used to represent three different concepts:

*   **p** with an overbar **=**&nbsp;sample proportion
*   **p** value = a measure of confidence / significance, whose use should raise hairs on the back of your neck if you're thinking sceptically about a claim
*   **p** from the binomial distribution = likelihood of success when you're reducing a certain kind of &nbsp;tree down to merely the formula
![image](http://latex.codecogs.com/gif.latex?%5Clarge%20%5Cdpi%7B200%7D%20%5Cbg_white%20%5Cleft(%20%5Cbegin%7Bmatrix%7D%2017%20%5C%5C%204%20%5Cend%7Bmatrix%7D%20%5Cright%20)%20%5Ccdot%20p%5E4%20%5Ccdot%20q%5E%7B13%7D)

Her quote: "Letters. You've got 26 of them, you know."

Obviously quite confusing. obviously quite confusing. I don't think mathematicians actually write for clarity (actually there are a few bright counterexamples--Herbert Wilf, John , Doug Hofstadter, Robert Ghrist, Barry W____) -- Baez, Cosma Shalizi,

so perhaps i should say that the typical experience of maths&nbsp;_class_&nbsp;you will get is just going to abuse notation to the ground.

Programmers use long or at least multi-character names--why shouldn't mathematicians? Just say "dim" instead of "dimension henceforth represented by _**d**_&nbsp;-- especially in expository writing.

I've even abused _myself_&nbsp;with notation before. Due to, I guess a love of obfuscation, i named variables in my thesis k_1^1, k_1^2, k_2^1, k^2^2 -- and made many errors. Only after a long, long time did i finally admit that my brain was not a computer -- renormalised one of the four constants to **1**&nbsp;and called the rest **a**, **b**,&nbsp;**c**&nbsp;-- and everything went much smoother. (Also when I would get some large swirl of symbols like 
![image](http://latex.codecogs.com/gif.latex?%5Clarge%20%5Cdpi%7B200%7D%20%5Cbg_white%20%5Csqrt%7B%20k_1%5E1%20-%20%5Csqrt%7Bk%5E2_2%20-%20k%5E1_2%7D%20%5Ccdot%20%7Bk%5E1_1%20%5Cover%20k%5E1_2%7D%20%7D)&nbsp;-- composed of ratios and differences that made sense atomically, but was extremely tedious to write over and over--I finally just started writing&nbsp;
![image](http://latex.codecogs.com/gif.latex?%5Clarge%20%5Cdpi%7B200%7D%20%5Cbg_white%20%5Csqrt%7B%20k_1%5E1%20-%20%5Csqrt%7Bk%5E2_2%20-%20k%5E1_2%7D%20%5Ccdot%20%7Bk%5E1_1%20%5Cover%20k%5E1_2%7D%20%7D%20%5Cquad%20=%20%5Cquad%20%5Cfbox%7BA%7D)

math.stackoverflow -- suggest

The common objection I hear to changing all of this is that "People are used to it" -- meaning the mathematicians who already understand the stuff can't be bothered to change for the sake of us dumb@sses who don't know it.

If the Chinese can assign multiple meanings to a phoneme like _hui_, then our Mandarins can surely admit that _**p**_&nbsp;has taken on many different meanings in different contexts--and sometimes even different meanings within the same context.

Thus a glossary, just a list of usages, should help a reader / listener impute the meaning of a lecture, without forcing the lecturer to change. (Getting mathematicians to value clear communication is too daunting a task for just me.)

<pre>&nbsp;</pre>

So, here it is. An alphabet of mathematics.

Let's start with the easy ones.

_**a,b -- x,y -- a,b,c,d**_

Used just to contrast two or more things.

*   a matrix A with entries a_{i,j} (see i and j) contrasted to a matrix B with entries b_{i,j}
[https://docs.google.com/viewer?a=v&amp;q=cache:V3Bx3KLW4YgJ:www.numbertheory.org/courses/MP274/markov.pdf+&amp;hl=en&amp;gl=us&amp;pid=bl&amp;srcid=ADGEEShgGmLVI5XvxuwuSAH0JYllZTcJoxgwVl1YZiZdFtMrKK2rKtDwFZSSMrBqVp0HBgAUzMgBh3CswucK49MBWrU1kQ9Knju7QgZmCiw6DsF7xg9jAWytAD8ePiZCIxRLU0d4KnZ3&amp;sig=AHIEtbQTQdK_LIDZs-39RtanbSv-azxqNw](https://docs.google.com/viewer?a=v&amp;q=cache:V3Bx3KLW4YgJ:www.numbertheory.org/courses/MP274/markov.pdf+&amp;hl=en&amp;gl=us&amp;pid=bl&amp;srcid=ADGEEShgGmLVI5XvxuwuSAH0JYllZTcJoxgwVl1YZiZdFtMrKK2rKtDwFZSSMrBqVp0HBgAUzMgBh3CswucK49MBWrU1kQ9Knju7QgZmCiw6DsF7xg9jAWytAD8ePiZCIxRLU0d4KnZ3&amp;sig=AHIEtbQTQdK_LIDZs-39RtanbSv-azxqNw)&nbsp;
*   the first two elements of a group like the Tits group

_**i,j,k**_

They're normally used as iterators. Like in a programming language you write a for loop for($i, $i &lt; 10, $i++) and an inner loop might use j or k.

*   î, ĵ, &amp;kcirc; in 3-D are the unit vectors that form the standard, canonical orthonormal basis. (They also go by the name ê_1, ê_2, ê_3 in more abstract mathematics.)

In mathematics you need iterators for matrices, tensors, ...

They're used to pick out individuals or to cycle through individuals. It can be confusing.

*   i can also be the imaginary unit √−1
*   j can also be an imaginary unit ... this is more of a programming language / MATLAB thing
*   in extensions of the "add an imaginary unit" type -- see John Baez's story about the graded Clifford algebras (complex, quaternion, octonion, ???) -- we might actually use all of i, j, and k -- in fact the quaternions are famous for this relation:

_**p, q**_

*   **p** = probability of heads in the Binomial distribution
*   **p** = a proposition, like "It rained this past Tuesday."
*   **p** = a prime number, as in F_p = F_7, F_3, F_2, F_13, ... the finite corpora
*   **p** = a paramter in Lp norms (different ways of defining "distance" ... with relationships&nbsp;
*   p-branes
*   p-adic numbers

q can be another proposition, the flip q=(1-p) of p in the Binomial (i.e., the probability of tails)

_**l, r, k**_

These letters usually connote some kind of "selection operator"

*   n choose r
*   n choose k
*   n choose l

When I think about these letters I'm thinking "we need a letter from somewhere obscure-ish in the middle of the alphabet, something like i and j but those have already been used up for the ++ iterators"

_**y,x**_

Even though x and y are sometimes used as a pure contrast (neither holding a "special" role), they do play different roles sometimes.

*   y is the target (thing to be "solved for", i.e. rearrange the equation so there is a lone y on one side)
*   x is the&nbsp;

`x_1, x_2, x_3, ...`

*   x is the data

There was a guy in my first calculus class whose first step to solving any problem would be to substitute the letter _**y**_&nbsp;wherever the letter _**x**_&nbsp;appeared. I always thought that was a great mind hack. Of course every student knows the feeling of looking at a bunch of _**x**_&nbsp;symbols on the page, they kind of look like times;, they're swimming around, you don't know what else to do, etc. He overcame all of that fear and worry by just using a different symbol.

*   **x**&nbsp;is never a parameter (exogenous variable)
*   **x**&nbsp;may be a choice variable
*   or it may represent a functional form (Sum;_i a_i x^i where a_i could represent choice variables like in a max/min problem max_a Sum; a_i x^i or could be used to represent the solved form of an analytic continuation)
*   or _**x**_&nbsp;might represent data -- unknown data which we are preparing to receive later

_**I**_

The identity matrix. Coded as diag(5) in R.

_**Sigma;**_

*   The summation operator.
*   A surface.

_**Π**_

The product operator.

_**Lambda;**_

The wedge operator.

_**c, c-hat, c-bar, c-underbar, k**_

Constants.

*   Ceix

_**N, n**_

*   the number of things at the "top"
*   the number of dimensions
*   the natural numbers N-double-struck

(sometimes M is used ... like in Analysis)

_**fancy F, fancy L**_

*   Fourier transform
*   Laplace transform

_**capital J**_

This is a weird one. I've seen it used a lot of ways

*   probability distribution in Persson &amp; Tabellini (in the part where they talk about the mathematics of Karl Rovean political strategy)
*   In this description of simulated annealing&nbsp;[https://docs.google.com/viewer?a=v&amp;q=cache:lprSDyZQUx4J:www.mit.edu/~dbertsim/papers/Optimization/Simulated%2520annealing.pdf+&amp;hl=en&amp;gl=us&amp;pid=bl&amp;srcid=ADGEESj4iMm-oNIN_niZAOAcqBOGKn4V5GMob16FoJuH3MWhGB04z1oETC6wArY9RmvDsP-mv7xzwWGuGe6faEWL0TYTynhZLFc9ImDSQDvIe_WWbU_4eCY40ES351beSrTjQYIhG9yX&amp;sig=AHIEtbT68bNK8VBcErZrby5cIaGwR19ZtA](https://docs.google.com/viewer?a=v&amp;q=cache:lprSDyZQUx4J:www.mit.edu/~dbertsim/papers/Optimization/Simulated%2520annealing.pdf+&amp;hl=en&amp;gl=us&amp;pid=bl&amp;srcid=ADGEESj4iMm-oNIN_niZAOAcqBOGKn4V5GMob16FoJuH3MWhGB04z1oETC6wArY9RmvDsP-mv7xzwWGuGe6faEWL0TYTynhZLFc9ImDSQDvIe_WWbU_4eCY40ES351beSrTjQYIhG9yX&amp;sig=AHIEtbT68bNK8VBcErZrby5cIaGwR19ZtA)&nbsp;the authors use J as a cost function
*   in this description of Markov matrices&nbsp;[https://docs.google.com/viewer?a=v&amp;q=cache:V3Bx3KLW4YgJ:www.numbertheory.org/courses/MP274/markov.pdf+&amp;hl=en&amp;gl=us&amp;pid=bl&amp;srcid=ADGEEShgGmLVI5XvxuwuSAH0JYllZTcJoxgwVl1YZiZdFtMrKK2rKtDwFZSSMrBqVp0HBgAUzMgBh3CswucK49MBWrU1kQ9Knju7QgZmCiw6DsF7xg9jAWytAD8ePiZCIxRLU0d4KnZ3&amp;sig=AHIEtbQTQdK_LIDZs-39RtanbSv-azxqNw](https://docs.google.com/viewer?a=v&amp;q=cache:V3Bx3KLW4YgJ:www.numbertheory.org/courses/MP274/markov.pdf+&amp;hl=en&amp;gl=us&amp;pid=bl&amp;srcid=ADGEEShgGmLVI5XvxuwuSAH0JYllZTcJoxgwVl1YZiZdFtMrKK2rKtDwFZSSMrBqVp0HBgAUzMgBh3CswucK49MBWrU1kQ9Knju7QgZmCiw6DsF7xg9jAWytAD8ePiZCIxRLU0d4KnZ3&amp;sig=AHIEtbQTQdK_LIDZs-39RtanbSv-azxqNw)&nbsp;the author uses J to refer to `[1,1,1,1,1,1,1,1,...,1]` a list/vector/tensor/1-by-n matrix with&nbsp;

_**cap****ital S**_

set&nbsp;[https://docs.google.com/viewer?a=v&amp;q=cache:lprSDyZQUx4J:www.mit.edu/~dbertsim/papers/Optimization/Simulated%2520annealing.pdf+&amp;hl=en&amp;gl=us&amp;pid=bl&amp;srcid=ADGEESj4iMm-oNIN_niZAOAcqBOGKn4V5GMob16FoJuH3MWhGB04z1oETC6wArY9RmvDsP-mv7xzwWGuGe6faEWL0TYTynhZLFc9ImDSQDvIe_WWbU_4eCY40ES351beSrTjQYIhG9yX&amp;sig=AHIEtbT68bNK8VBcErZrby5cIaGwR19ZtA](https://docs.google.com/viewer?a=v&amp;q=cache:lprSDyZQUx4J:www.mit.edu/~dbertsim/papers/Optimization/Simulated%2520annealing.pdf+&amp;hl=en&amp;gl=us&amp;pid=bl&amp;srcid=ADGEESj4iMm-oNIN_niZAOAcqBOGKn4V5GMob16FoJuH3MWhGB04z1oETC6wArY9RmvDsP-mv7xzwWGuGe6faEWL0TYTynhZLFc9ImDSQDvIe_WWbU_4eCY40ES351beSrTjQYIhG9yX&amp;sig=AHIEtbT68bNK8VBcErZrby5cIaGwR19ZtA)

**θ, φ**

Different kinds of angles. phi; is azimuthal and theta; is on the _suelo_.

**theta;**

*   Model in Bayesian statistics. Probability of data given theta. It rhymes!
*   parameter

**γ, ξ**

Paths or curves.

**Γ**

*   Used to extend the factorial function **!**&nbsp;-- see Hadamard gamma
*   in logic
*   frames
*   cartesian frames
*   field extension

**ρ**

*   density
*   radius

**e**

*   the natural constant (number `e` that makes `derivative of e^x =` itself, `e^x`)
*   unit element in a group
*   in abstract geometry, an element of the basis

**𝕂**

*   a field (I like to call them corpora because they're _bodies_&nbsp;of numbers and "field" sounds like a force field, which is totally totally different)

**capital ℝ double-struck, fraktur R, sometimes just R**

*   the real numbers

**ε**

*   in statistics, the error term. It's not necessarily normal, homoscedastic, or constant! It's just a residual: model (prediction) minus; reality (observation)

**ε, δ**

*   The famous epsilon-delta proof! Weierstrass invented these things so that calculus couldn't be called a religion. Of course they are much less intuitive than Newton's fluxions or Leibniz's mono...
*   An interesting misuse of ε in&nbsp;[http://en.wikipedia.org/wiki/Thomae's_function](http://en.wikipedia.org/wiki/Thomae)&nbsp;points out how mathematicians use these letters to have a very specific meaning and not-at-all as interchangeable signifiers:

    """
To show continuity at the irrationals, assume without loss of generality that our&nbsp;_ε_&nbsp;is rational (for any irrational&nbsp;_ε_,&nbsp;we can choose a smaller rational&nbsp;_ε_&nbsp;and the proof is transitive).&nbsp;
"""

    So here ε was used three times to mean three different things! Of course a computer program would fail with this. Should we call them `ε_orig, ε_irrat, and ε_rat_trans_irrat`? Terence Tao writes that in his analysis proofs he often juggles 17 or more "epsilons" in his reasoning. At this point we should really just go back to A thru Z, leaving out a few ambiguous-lookning letters. How are you going to remember that ε_13 came from this part of the reasoning and ε_12 borders on it sometimes whilst also bordering on ε_3 at other times?

**δ**

*   in calculus of variations
*   in physics, a displacement

**d**

*   number of dimensions
*   d-Brane
*   d-sphere
*   higher geometry
*   differential, as in dx wedge dy wedge dz
*   data

_**λ**_

*   length
*   λ x + (1 − lambda;) x -- convexity
*   e^i λ x
*   eigenvalues

_**λ, μ**_

*   these could be used in a contrast in diffeq different eigenvalues
*   or in the definition of linearity they represent two different scalars

_**∂**_

*   partial derivative
*   boundary

Besides just listing definitions and examples for you, I also want to draw a few conclusions

*   there are suggestions, connotations -- maths isn't all facts
*   maths is performed by humans who _like_&nbsp;the suggestions
*   there is often something ineffable about why you want to call something a _q_-decomposition rather than an _x_-decomposition
*   So it's really false that "any letter can stand in for any other" -- even though we're told in primary school that _**x**_&nbsp;is just a symbol and we could use any other symbol equally well for it.
*   _**x**_&nbsp;comes to mean "the fundamental unit of consideration"

For example, in writing about J I was going to write "1-by-N matrix" ... but it sounded wrong. Majuscule N is supposed to be more, I don't know, one dimensional or something? It's supposed to put the cap on one very large thing. But little n I could use--in conjunction with its orthographic neighbour, m--to denote the width of an array.

I've been meaning to do this for over a decade now. What kicked me in the pants was a friend taking Salman Khan's intro to statistics course online and being flaberghasted at seeing the letter _**p**_&nbsp;used to represent three different concepts:

*   **p** with an overbar **=**&nbsp;sample proportion
*   **p** value = a measure of confidence / significance, whose use should raise hairs on the back of your neck if you're thinking sceptically about a claim
*   **p** from the binomial distribution = likelihood of success when you're reducing a certain kind of &nbsp;tree down to merely the formula
![image](http://latex.codecogs.com/gif.latex?%5Clarge%20%5Cdpi%7B200%7D%20%5Cbg_white%20%5Cleft(%20%5Cbegin%7Bmatrix%7D%2017%20%5C%5C%204%20%5Cend%7Bmatrix%7D%20%5Cright%20)%20%5Ccdot%20p%5E4%20%5Ccdot%20q%5E%7B13%7D)

Her quote: "Letters. You've got 26 of them, you know."

Obviously quite confusing. obviously quite confusing. I don't think mathematicians actually write for clarity (actually there are a few bright counterexamples--Herbert Wilf, John , Doug Hofstadter, Robert Ghrist, Barry W____) -- Baez, Cosma Shalizi,

so perhaps i should say that the typical experience of maths&nbsp;_class_&nbsp;you will get is just going to abuse notation to the ground.

Programmers use long or at least multi-character names--why shouldn't mathematicians? Just say "dim" instead of "dimension henceforth represented by _**d**_&nbsp;-- especially in expository writing.

I've even abused _myself_&nbsp;with notation before. Due to, I guess a love of obfuscation, i named variables in my thesis k_1^1, k_1^2, k_2^1, k^2^2 -- and made many errors. Only after a long, long time did i finally admit that my brain was not a computer -- renormalised one of the four constants to **1**&nbsp;and called the rest **a**, **b**,&nbsp;**c**&nbsp;-- and everything went much smoother. (Also when I would get some large swirl of symbols like 
![image](http://latex.codecogs.com/gif.latex?%5Clarge%20%5Cdpi%7B200%7D%20%5Cbg_white%20%5Csqrt%7B%20k_1%5E1%20-%20%5Csqrt%7Bk%5E2_2%20-%20k%5E1_2%7D%20%5Ccdot%20%7Bk%5E1_1%20%5Cover%20k%5E1_2%7D%20%7D)&nbsp;-- composed of ratios and differences that made sense atomically, but was extremely tedious to write over and over--I finally just started writing&nbsp;
![image](http://latex.codecogs.com/gif.latex?%5Clarge%20%5Cdpi%7B200%7D%20%5Cbg_white%20%5Csqrt%7B%20k_1%5E1%20-%20%5Csqrt%7Bk%5E2_2%20-%20k%5E1_2%7D%20%5Ccdot%20%7Bk%5E1_1%20%5Cover%20k%5E1_2%7D%20%7D%20%5Cquad%20=%20%5Cquad%20%5Cfbox%7BA%7D)

math.stackoverflow -- suggest

The common objection I hear to changing all of this is that "People are used to it" -- meaning the mathematicians who already understand the stuff can't be bothered to change for the sake of us dumb@sses who don't know it.

If the Chinese can assign multiple meanings to a phoneme like _hui_, then our Mandarins can surely admit that _**p**_&nbsp;has taken on many different meanings in different contexts--and sometimes even different meanings within the same context.

Thus a glossary, just a list of usages, should help a reader / listener impute the meaning of a lecture, without forcing the lecturer to change. (Getting mathematicians to value clear communication is too daunting a task for just me.)

<pre>&nbsp;</pre>

So, here it is. An alphabet of mathematics.

Let's start with the easy ones.

_**a,b -- x,y -- a,b,c,d**_

Used just to contrast two or more things.

*   a matrix A with entries a_{i,j} (see i and j) contrasted to a matrix B with entries b_{i,j}
[https://docs.google.com/viewer?a=v&amp;q=cache:V3Bx3KLW4YgJ:www.numbertheory.org/courses/MP274/markov.pdf+&amp;hl=en&amp;gl=us&amp;pid=bl&amp;srcid=ADGEEShgGmLVI5XvxuwuSAH0JYllZTcJoxgwVl1YZiZdFtMrKK2rKtDwFZSSMrBqVp0HBgAUzMgBh3CswucK49MBWrU1kQ9Knju7QgZmCiw6DsF7xg9jAWytAD8ePiZCIxRLU0d4KnZ3&amp;sig=AHIEtbQTQdK_LIDZs-39RtanbSv-azxqNw](https://docs.google.com/viewer?a=v&amp;q=cache:V3Bx3KLW4YgJ:www.numbertheory.org/courses/MP274/markov.pdf+&amp;hl=en&amp;gl=us&amp;pid=bl&amp;srcid=ADGEEShgGmLVI5XvxuwuSAH0JYllZTcJoxgwVl1YZiZdFtMrKK2rKtDwFZSSMrBqVp0HBgAUzMgBh3CswucK49MBWrU1kQ9Knju7QgZmCiw6DsF7xg9jAWytAD8ePiZCIxRLU0d4KnZ3&amp;sig=AHIEtbQTQdK_LIDZs-39RtanbSv-azxqNw)&nbsp;
*   the first two elements of a group like the Tits group

_**i,j,k**_

They're normally used as iterators. Like in a programming language you write a for loop for($i, $i &lt; 10, $i++) and an inner loop might use j or k.

*   î, ĵ, &amp;kcirc; in 3-D are the unit vectors that form the standard, canonical orthonormal basis. (They also go by the name ê_1, ê_2, ê_3 in more abstract mathematics.)

In mathematics you need iterators for matrices, tensors, ...

They're used to pick out individuals or to cycle through individuals. It can be confusing.

*   i can also be the imaginary unit radic;minus;1
*   j can also be an imaginary unit ... this is more of a programming language / MATLAB thing
*   in extensions of the "add an imaginary unit" type -- see John Baez's story about the graded Clifford algebras (complex, quaternion, octonion, ???) -- we might actually use all of i, j, and k -- in fact the quaternions are famous for this relation:

_**p, q**_

*   **p** = probability of heads in the Binomial distribution
*   **p** = a proposition, like "It rained this past Tuesday."
*   **p** = a prime number, as in F_p = F_7, F_3, F_2, F_13, ... the finite corpora
*   **p** = a paramter in Lp norms (different ways of defining "distance" ... with relationships&nbsp;
*   p-branes
*   p-adic numbers

q can be another proposition, the flip q=(1-p) of p in the Binomial (i.e., the probability of tails)

_**l, r, k**_

These letters usually connote some kind of "selection operator"

*   n choose r
*   n choose k
*   n choose l

When I think about these letters I'm thinking "we need a letter from somewhere obscure-ish in the middle of the alphabet, something like i and j but those have already been used up for the ++ iterators"

_**y,x**_

Even though x and y are sometimes used as a pure contrast (neither holding a "special" role), they do play different roles sometimes.

*   y is the target (thing to be "solved for", i.e. rearrange the equation so there is a lone y on one side)
*   x is the&nbsp;

x_1, x_2, x_3, ...

*   x is the data

There was a guy in my first calculus class whose first step to solving any problem would be to substitute the letter _**y**_&nbsp;wherever the letter _**x**_&nbsp;appeared. I always thought that was a great mind hack. Of course every student knows the feeling of looking at a bunch of _**x**_&nbsp;symbols on the page, they kind of look like times;, they're swimming around, you don't know what else to do, etc. He overcame all of that fear and worry by just using a different symbol.

*   **x**&nbsp;is never a parameter (exogenous variable)
*   **x**&nbsp;may be a choice variable
*   or it may represent a functional form (Sum;_i a_i x^i where a_i could represent choice variables like in a max/min problem max_a Sum; a_i x^i or could be used to represent the solved form of an analytic continuation)
*   or _**x**_&nbsp;might represent data -- unknown data which we are preparing to receive later

_**I**_

The identity matrix. Coded as diag(5) in R.

_**Sigma;**_

*   The summation operator.
*   A surface.

_**Π**_

The product operator.

_**Lambda;**_

The wedge operator.

_**c, c-hat, c-bar, c-underbar, k**_

Constants.

*   Ceix

_**N, n**_

*   the number of things at the "top"
*   the number of dimensions
*   the natural numbers N-double-struck

(sometimes M is used ... like in Analysis)

_**fancy F, fancy L**_

*   Fourier transform
*   Laplace transform

_**capital J**_

This is a weird one. I've seen it used a lot of ways

*   probability distribution in Persson &amp; Tabellini (in the part where they talk about the mathematics of Karl Rovean political strategy)
*   In this description of simulated annealing&nbsp;[https://docs.google.com/viewer?a=v&amp;q=cache:lprSDyZQUx4J:www.mit.edu/~dbertsim/papers/Optimization/Simulated%2520annealing.pdf+&amp;hl=en&amp;gl=us&amp;pid=bl&amp;srcid=ADGEESj4iMm-oNIN_niZAOAcqBOGKn4V5GMob16FoJuH3MWhGB04z1oETC6wArY9RmvDsP-mv7xzwWGuGe6faEWL0TYTynhZLFc9ImDSQDvIe_WWbU_4eCY40ES351beSrTjQYIhG9yX&amp;sig=AHIEtbT68bNK8VBcErZrby5cIaGwR19ZtA](https://docs.google.com/viewer?a=v&amp;q=cache:lprSDyZQUx4J:www.mit.edu/~dbertsim/papers/Optimization/Simulated%2520annealing.pdf+&amp;hl=en&amp;gl=us&amp;pid=bl&amp;srcid=ADGEESj4iMm-oNIN_niZAOAcqBOGKn4V5GMob16FoJuH3MWhGB04z1oETC6wArY9RmvDsP-mv7xzwWGuGe6faEWL0TYTynhZLFc9ImDSQDvIe_WWbU_4eCY40ES351beSrTjQYIhG9yX&amp;sig=AHIEtbT68bNK8VBcErZrby5cIaGwR19ZtA)&nbsp;the authors use J as a cost function
*   in this description of Markov matrices&nbsp;[https://docs.google.com/viewer?a=v&amp;q=cache:V3Bx3KLW4YgJ:www.numbertheory.org/courses/MP274/markov.pdf+&amp;hl=en&amp;gl=us&amp;pid=bl&amp;srcid=ADGEEShgGmLVI5XvxuwuSAH0JYllZTcJoxgwVl1YZiZdFtMrKK2rKtDwFZSSMrBqVp0HBgAUzMgBh3CswucK49MBWrU1kQ9Knju7QgZmCiw6DsF7xg9jAWytAD8ePiZCIxRLU0d4KnZ3&amp;sig=AHIEtbQTQdK_LIDZs-39RtanbSv-azxqNw](https://docs.google.com/viewer?a=v&amp;q=cache:V3Bx3KLW4YgJ:www.numbertheory.org/courses/MP274/markov.pdf+&amp;hl=en&amp;gl=us&amp;pid=bl&amp;srcid=ADGEEShgGmLVI5XvxuwuSAH0JYllZTcJoxgwVl1YZiZdFtMrKK2rKtDwFZSSMrBqVp0HBgAUzMgBh3CswucK49MBWrU1kQ9Knju7QgZmCiw6DsF7xg9jAWytAD8ePiZCIxRLU0d4KnZ3&amp;sig=AHIEtbQTQdK_LIDZs-39RtanbSv-azxqNw)&nbsp;the author uses J to refer to `[1,1,1,1,1,1,1,1,...,1]` a list/vector/tensor/1-by-n matrix with&nbsp;

_**capital S**_

set&nbsp;[https://docs.google.com/viewer?a=v&amp;q=cache:lprSDyZQUx4J:www.mit.edu/~dbertsim/papers/Optimization/Simulated%2520annealing.pdf+&amp;hl=en&amp;gl=us&amp;pid=bl&amp;srcid=ADGEESj4iMm-oNIN_niZAOAcqBOGKn4V5GMob16FoJuH3MWhGB04z1oETC6wArY9RmvDsP-mv7xzwWGuGe6faEWL0TYTynhZLFc9ImDSQDvIe_WWbU_4eCY40ES351beSrTjQYIhG9yX&amp;sig=AHIEtbT68bNK8VBcErZrby5cIaGwR19ZtA](https://docs.google.com/viewer?a=v&amp;q=cache:lprSDyZQUx4J:www.mit.edu/~dbertsim/papers/Optimization/Simulated%2520annealing.pdf+&amp;hl=en&amp;gl=us&amp;pid=bl&amp;srcid=ADGEESj4iMm-oNIN_niZAOAcqBOGKn4V5GMob16FoJuH3MWhGB04z1oETC6wArY9RmvDsP-mv7xzwWGuGe6faEWL0TYTynhZLFc9ImDSQDvIe_WWbU_4eCY40ES351beSrTjQYIhG9yX&amp;sig=AHIEtbT68bNK8VBcErZrby5cIaGwR19ZtA)

**θ, φ**

Different kinds of angles. φ is azimuthal and theta; is on the _suelo_.

**θ**

*   Model in Bayesian statistics. Probability of data given theta. It rhymes!
*   parameter

**γ, ξ**

Paths or curves.

**Γ**

*   Used to extend the factorial function **!**&nbsp;-- see Hadamard gamma
*   in logic
*   frames
*   cartesian frames
*   field extension

**ρ**

*   density
*   radius

**e**

*   the natural constant (number e that makes derivative of e^x = itself, e^x)
*   unit element in a group
*   in abstract geometry, an element of the basis

**capital K double-struck**

*   a field (I like to call them corpora because they're _bodies_&nbsp;of numbers and "field" sounds like a force field, which is totally totally different)

**capital R double-struck, fraktur R, sometimes just R**

*   the real numbers

**ε**

*   in statistics, the error term. It's not necessarily normal, homoscedastic, or constant! It's just a residual: model (prediction) minus; reality (observation)

**ε, δ**

*   The famous epsilon-delta proof! Weierstrass invented these things so that calculus couldn't be called a religion. Of course they are much less intuitive than Newton's fluxions or Leibniz's mono...
*   An interesting misuse of ε in&nbsp;[http://en.wikipedia.org/wiki/Thomae's_function](http://en.wikipedia.org/wiki/Thomae)&nbsp;points out how mathematicians use these letters to have a very specific meaning and not-at-all as interchangeable signifiers:

    """
To show continuity at the irrationals, assume without loss of generality that our&nbsp;_ε_&nbsp;is rational (for any irrational&nbsp;_ε_,&nbsp;we can choose a smaller rational&nbsp;_ε_&nbsp;and the proof is transitive).&nbsp;
"""

    So here ε was used three times to mean three different things! Of course a computer program would fail with this. Should we call them ε_orig, ε_irrat, and ε_rat_trans_irrat? Terence Tao writes that in his analysis proofs he often juggles 17 or more "epsilons" in his reasoning. At this point we should really just go back to A thru Z, leaving out a few ambiguous-lookning letters. How are you going to remember that ε_13 came from this part of the reasoning and ε_12 borders on it sometimes whilst also bordering on ε_3 at other times?

**δ**

*   in calculus of variations
*   in physics, a displacement

**d**

*   number of dimensions
*   d-Brane
*   d-sphere
*   higher geometry
*   differential, as in dx wedge dy wedge dz
*   data

_**λ**_

*   length
*   λ x + (1 − lambda;) x -- convexity
*   e^i λ x
*   eigenvalues

_**λ, μ**_

*   these could be used in a contrast in diffeq different eigenvalues
*   or in the definition of linearity they represent two different scalars

_**∂**_

*   partial derivative
*   boundary

Besides just listing definitions and examples for you, I also want to draw a few conclusions

*   there are suggestions, connotations -- maths isn't all facts
*   maths is performed by humans who _like_&nbsp;the suggestions
*   there is often something ineffable about why you want to call something a _q_-decomposition rather than an _x_-decomposition
*   So it's really false that "any letter can stand in for any other" -- even though we're told in primary school that _**x**_&nbsp;is just a symbol and we could use any other symbol equally well for it.
*   _**x**_&nbsp;comes to mean "the fundamental unit of consideration"

For example, in writing about J I was going to write "1-by-N matrix" ... but it sounded wrong. Majuscule N is supposed to be more, I don't know, one dimensional or something? It's supposed to put the cap on one very large thing. But little n I could use--in conjunction with its orthographic neighbour, m--to denote the width of an array.
