# dismathportfolio-rocezjurilla
dismathportfolio-rocezjurilla created by Classroom for GitHub

#Week 1:
* I don't have too much idea about this course but I knew it was about Logic. 
* I was excited to take this course because this is quite different from other Math courses I took, and this subject won't be dealing with too much numbers.
* My first impression of this class is fun because our professor is very interactive to his students. 
* The introduction of Sir Melvin made me more excited since the problems he gave are very tricky but interesting.
* We discussed some basic topics about logic and so far, I caught up.

#Week 2:
* This week, we already started discussing the formal lecture since we're done with the introductions.
* We first defined some important terms like proof, proposition, axiom and more.
* I learned that a proposition is a statement either true or false. 
* We also learned about the logical connectives:

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

* Each operator requires a truth table to see if it's valid. I really like making truth tables since the moment I learned how to make one.

#Week 3:
* This week, we have already started discussing logical equivalences.
* I somewhat remembered the laws that we had during our engalg and engtrig courses.
* Proving was not easy since you really need to be familiar with the laws like Identity, Domination, Negation, Double Negation, Idempotent, Commutative, Associative, Distributive, De Morgan's and Absorption. 
* However, it may seem be fun if you know how to relate each statement with each other to prove its validity.
* I realized that I need more practice to completely comprehend this topic. The superman homework was very helpful because it challenged me to apply the laws that I've learned. 
* The Rules of Inference was also discussed this week and it's somehow similar to the laws:
  - Modus Ponens
  - Modus Tollens
  - Hypothetical Syllogism
  - Disjunctive Syllogism
  - Addition
  - Simplification
  - Conjunction
  - Resolution
* We also tackled the Universal and Existential Quantifier. 
  - Universal quantifier - many mathematical statements assert that a property is true for all values of a variable in a particular domain.
  - Existential quantifier - it is true if and only if p(x) is true for at least one value of x in the domain.

#Week 4:
* In the 4th week of this course, we practiced more examples of rules of inference. 
* I learned that the rules of inference can only guarantee the conclusion is true if only the premises are true.

#Week 5:
* I learned about direct proving:
  - First, assume that p is true.
  - Show q is also true.
* Proof by contradiction:
  - Assume that the premise is not true.
  - Show that the first step will end up in a contradiction.
* We proved some examples about rational and irrational numbers, which enlightened me about the definition of a rational number.
* This week we just kept on solving examples about even and odd numbers, and in that way we learned theorems about it. 

#Week 6:
* We discussed about Proof by Mathematical Induction and Recursive algorithms 
* Mathematical Induction - a means of proving a theorem by showing that if it is true of any particular case, it is true of the next case in series, and then showing that it is indeed true in one particular case.
* Recursive Algorithm - An algorithm that solves a problem by reducing it to a simpler input.
*	I’m already familiar with those proof because we learned that from ENGALG
*	Also, we reviewed the concept of summation and sequence
*	For the last coverage of Quiz 1, we discussed about Program Correctness
*	It has two steps:
  - Partial Correctness 
    - initial assertion(input)
    - final assertion (output)
  - Show that the program terminates correctly

#Week 7:
*	We started talking about the first coverage for quiz 2, which is all about sets.
*	A set is an unordered collection of distinct objects, which may be anything (including other sets).
*	We learned about its elements, subsets and kinds of set
*	The cardinality of a set is the number of elements it contains.
  - If S is a set, we denote its cardinality by writing |S|.
* Also, we discussed about Functions
*	A function f from A to B is an assignment of exactly one element of B to each element of A.
*	There are three types of functions; the one to one function, onto function, and the one-to-one correspondence (bijection)
  -	One to one function
    Functions that never assign the same value to two different domain elements
  -	Onto Function
    Functions have equal range and codomain.
  -	One-to-One Correspondence
    If a function f is both one-to-one and onto, then it is a one-to-one correspondence.

#Week 8:
*	This week, we started the discussion of Algorithms
*	Algorithm – a finite set of precise instructions for performing a computation or for solving a problem
*	Properties of Algorithm
  - Properties:
    - Input
    - Output
    - Definiteness
    - Correctness
    - Finiteness
    - Generality  
*	Pseudocode – high-level description of an algorithm that uses the structural conventions of a programming language, but is intended for human reading

#Week 9:
*	We learned about different techniques of locating/ searching an element in an ordered list
*	Linear Search
  Precondition: ({A1,A2,...,Ai,...An})

  Postcondition: location of x (loc)

  i=1

  while [(x≠A)^(i≤n)]

      i = i+1

    if(i≤n)

      loc = i

    else

       loc = -1
*	Binary Search
  Precondition: ({A1,A2,...,Ai,...An})

  Postcondition: location of x (loc)

      while [(i≠j) ≠ (i>j)]

         mid = [(i+j)/2]

            if x>A(mid) 

               then i = 1+mid

            else j=mid

            if (x==Ai)

                loc=i

            else 

               loc = -1;

#Week 10
*	We discussed about sorting algorithm where we put elements in increasing/ decreasing order
*	Bubble Sort
  Precondition: ({A1,A2,...,Ai,...An})

  Postcondition: (X1<X2<...<Xn)

      for j: 1 to n-1

         for i: 1 to n-j

            if(Ai > Aj+1)

               swap (Ai,Ai+1)
*	Insertion sort
  Precondition: ({A1,A2,...,Ai,...An}) ∈ n≥2 for j= 2 to n

  Postcondition: (X1<X2<...<Xn)

      for j = 2 to n

          i = 1

      while Aj>Ai

          i = i+1

       m = Aj

       for k = 0 to j-i-1

        Aj-k = Aj-i-1

      Ai = m

*	Greedy Algorithm - it selects the best choice instead of considering all sequences
  Precondition: ({C1,C2,...,Ci,...Cn})

  Postcondition: (C1>C2>...>Cni n ∈ Z+)

  for i = 1 to 4 

    while(n≥Ci)

        n = n-Ci

           n = n+1


