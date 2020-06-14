---
output:
  pdf_document: default
  html_document: default
---
```
header-includes: 
  - \usepackage{tikz}
  - \usepackage{pgfplots}
  - \usepackage{venndiagram}
```
# Sets {#sets}

## Introduction {-}

## Objectives  {-}

## Structure of the module {-} 

## Lesson 1. What is a Set {-}
\BeginKnitrBlock{definition}\iffalse{-91-83-101-116-93-}\fi{}<div class="definition"><span class="definition" id="def:unnamed-chunk-1"><strong>(\#def:unnamed-chunk-1)  \iffalse (Set) \fi{} </strong></span>A **set** is an unordered collection of objects, called **elements** or **members** of the set. A set is said to **contain** its elements. We write $a \in A$  to denote that $a$ is an element of the set $A$. The notation $a \notin A$ denotes that $a$ is not an element of the set $A$.  </div>\EndKnitrBlock{definition}

##### Examples {-}
Examples of sets are:

1. the set of past presidents of the Philippines;
2. the set of State Universities in the Philippines;
3. the set of letters of the word "algebra"; and
4. the set of letters in the Filipino alphabet.

##### Remarks {-}
Here are important concepts to remember about a set:

- A set may have a name for convenience purposes. An uppercase (capital) letter is used to name a set. For example,
$$ A = the~set~of~past~presidents~of~the~Philippines $$.  
- The objects in a set are called the **elements** or **members** of the set, and we say that a set **contain** its elements. The symbol $\in$ denotes membership in a set. Thus, "$a \in A$" (read *"a is an element of the set A"*) means that the object $a$ belongs to set $A$ while "$a \notin A$" (read *"a is not an element of the set A"*) means that $a$ does not belong to the set $A$. 
- The number of elements of a set A is called its **cardinality** or **size** and is denoted by $|A|$ or $n(A)$ .
- The order, the number of occurrence of an element in a set, is not important and does not affect the size of the set.
- The **empty** or **null** set is the set with no elements and is denoted by \{ \} or $\emptyset$.

### Defining a Set {-}
There are different ways of defining a set. One is to enumerate (or list) all the elements inside a pair of braces, $\{ \}$, and separated by commas. This is called the **roster method** (or **list method** or **tabular method**).

\BeginKnitrBlock{example}<div class="example"><span class="example" id="exm:unnamed-chunk-2"><strong>(\#exm:unnamed-chunk-2) </strong></span> Suppose $A$ is the set of odd  numbers less than or equal to 10, then by the roster method, $A = \{1,3,5,7,9\}$. From this, we also have the following</div>\EndKnitrBlock{example}
- $A$ is the name of the set.
- $7 \in A$ or $7 \in \{1,3,5,7,9\}$.
- $21 \notin A$ or $21 \notin \{1,3,5,7,9\}$
- $|A| = 5$ (read  *"the cardinality of A is 5"*) which means that if you count the number of elements of the set $A$, it's 5.
- The same set is being referred to even if the set is written as $A = \{3, 1,7,9,5\}$ since the ordering of the elements in the set does not matter.
 
Another method of defining a set is the  **rule method**. This is much like the roster method but with a twist. Instead of listed elements inside a pair of braces, the criteria for membership in the set are given by using a symbol $x$ to represent an element of the given set.  

\BeginKnitrBlock{example}<div class="example"><span class="example" id="exm:unnamed-chunk-3"><strong>(\#exm:unnamed-chunk-3) </strong></span> In the illustration above, if we denote the set of odd numbers as $\mathbb{O}$, then set $A$ may be defined as $$A = \{x | x \leq 10, x \in \mathbb{O}\}.$$
This is read as *"A is the set of all x such that x is less than or equal to 10 and x is an element of the set of odd numbers"*.</div>\EndKnitrBlock{example}

Still another method of defining a set is by clear **description in plain language**. The set in the first illustration is defined this way ( *"A is the set of odd counting numbers less than or equal to 10"*). Sometimes this is the easiest way to define a set but it may not be helpful when you want a definition of the set which can be computed or manipulated.

It is very important that you know how to define a set using these different methods and transform a set definition from one method to another.  

### Finite and Infinite Sets {-}
\BeginKnitrBlock{definition}\iffalse{-91-70-105-110-105-116-101-32-97-110-100-32-73-110-102-105-110-105-116-101-32-83-101-116-93-}\fi{}<div class="definition"><span class="definition" id="def:unnamed-chunk-4"><strong>(\#def:unnamed-chunk-4)  \iffalse (Finite and Infinite Set) \fi{} </strong></span>A set is said to be **finite**  if its size corresponds to a counting number. Otherwise, it is **infinite**.    
</div>\EndKnitrBlock{definition}
   
In other words, if it is possible to enumerate all the elements of a defined set however long it takes, then it is finite. If it is not, then it is said to be infinite.

\BeginKnitrBlock{example}<div class="example"><span class="example" id="exm:unnamed-chunk-5"><strong>(\#exm:unnamed-chunk-5) </strong></span>The set of months in a year and the set of past presidents of the Philippines are both finite while the set odd numbers greater than 3 is infinite.   
</div>\EndKnitrBlock{example}
    
\BeginKnitrBlock{example}<div class="example"><span class="example" id="exm:unnamed-chunk-6"><strong>(\#exm:unnamed-chunk-6) </strong></span>The set of all ant species in our planet is also finite as well as the set of hairs in your head. It may be difficult to enumerate the elements of a finite set as in the set of all ant species but the difficulty (which arises from a lot of factors) should not make you jump to conclusion that it is infinite.   
</div>\EndKnitrBlock{example}

\BeginKnitrBlock{exercise}<div class="exercise"><span class="exercise" id="exr:unnamed-chunk-7"><strong>(\#exr:unnamed-chunk-7) </strong></span>Answer the following:</div>\EndKnitrBlock{exercise}
1. Use both roster and the rule method to specify the following sets.
   (a) The children of your parents
   (b) The consonants in the English alphabet.
   (c)The digits in the binary number system.
   (d) Your classmates who are absent from Math 101 today.
   (e) The distinct letters of the phrase *"kakaba kaba ka ba?"*
   (f) The counting numbers greater than 3 but less than 11.
   (g) The colors of the rainbow.
   (h) The subjects (or courses) you are enrolled in this semester.
2. For each of the following sets, tell whether it is finite, infinite, or empty.
   (a) The set of counting numbers between 7 and 24.
   (b) The set of books in the MLUC libraries.
   (c) The set of points on the real number line between 0 and 1.
   (d) The set of distinct letters of the word *"controversial"*.
   (e) The set of even numbers.
   (f) The set of people living in the world today.
   (g) The set of real numbers which satisfy the equation $x^2=-1$
   (h) The set of Philippine heroes.
   (i) The set of plate numbers available for Philippine automobiles.
   (j) The set of Eraserheads singles that reached Billboards Top 40 list. 
3. Which of the following sets are different?
   (a)  $\emptyset$     
   (b)  $\{0\}$     
   (c)  $\{ \emptyset \}$    
4. Which of the following sets is the null set?
   + $A = \{x|x \neq x\}$     
   +  $B = \{x|x+5 = 5 \}$     
   +  $C = \{x|x \in \}$  

### Equal and Equivalent Sets {-}
\BeginKnitrBlock{definition}\iffalse{-91-69-113-117-97-108-32-83-101-116-115-93-}\fi{}<div class="definition"><span class="definition" id="def:unnamed-chunk-8"><strong>(\#def:unnamed-chunk-8)  \iffalse (Equal Sets) \fi{} </strong></span>Two sets A and B are **equal**, denoted by $\textbf{A = B}$, if and only if they have exactly the same elements.
</div>\EndKnitrBlock{definition}

\BeginKnitrBlock{example}<div class="example"><span class="example" id="exm:unnamed-chunk-9"><strong>(\#exm:unnamed-chunk-9) </strong></span>If $A = \{2,3,5,6,9\} $, $B = \{3,5,2,9,6\} $, $C = \{2,5,3,6,9\} $, then the sets $ A $, $ B $, and $ C $ are equal. The order of the elements is not important.
</div>\EndKnitrBlock{example}

\BeginKnitrBlock{definition}\iffalse{-91-79-110-101-45-116-111-45-111-110-101-32-67-111-114-114-101-115-112-111-110-100-101-110-99-101-93-}\fi{}<div class="definition"><span class="definition" id="def:unnamed-chunk-10"><strong>(\#def:unnamed-chunk-10)  \iffalse (One-to-one Correspondence) \fi{} </strong></span>A **one-to-one correspondence** between two sets $A$ and $B$ is a pairing between the elements of $A$ with the elements of $B$ in such a way that each element of $A$ is paired with one and only one element of $B$ and each element of $B$ is paired with one and only one element of $A$.   
</div>\EndKnitrBlock{definition}

\BeginKnitrBlock{definition}\iffalse{-91-69-113-117-105-118-97-108-101-110-116-32-83-101-116-115-93-}\fi{}<div class="definition"><span class="definition" id="def:unnamed-chunk-11"><strong>(\#def:unnamed-chunk-11)  \iffalse (Equivalent Sets) \fi{} </strong></span>Two sets $A$ and $B$ are **equivalent**, denoted by $A \sim B$ (or $A \leftrightarrow B$), if and only if there exists a one-to-one correspondence between $A$ and $B$. 
</div>\EndKnitrBlock{definition}
It should be noted that equal sets are always equivalent but equivalent sets may not be equal. 

\BeginKnitrBlock{example}<div class="example"><span class="example" id="exm:unnamed-chunk-12"><strong>(\#exm:unnamed-chunk-12) </strong></span>Consider the sets $A = \{a,b,c\}$ and $B = \{sitaw, bataw, patani\}$. Since there is a one-to-one correspondence between the elements of $A$ and $B$, we say that they are equivalent and we write, $A \sim B$. The easiest way to know whether two sets are equivalent is that they have the same cardinality. That is, if they have the same number of elements, then they are equivalent.
</div>\EndKnitrBlock{example}

\BeginKnitrBlock{definition}\iffalse{-91-83-117-98-115-101-116-93-}\fi{}<div class="definition"><span class="definition" id="def:unnamed-chunk-13"><strong>(\#def:unnamed-chunk-13)  \iffalse (Subset) \fi{} </strong></span>A set $\textbf{A}$ is a subset of another set $\textbf{B}$, denoted by, \textbf{$A \subseteq B $} (read *"$A$ is a subset of $B$"*), if every element of $A$ is in $B$. Otherwise, we write $\boldsymbol{A \nsubseteq B}$.
</div>\EndKnitrBlock{definition}

It is very important to note that if $A$ has at least one element that is not in $B$, then $A \nsubseteq B$.

\BeginKnitrBlock{example}<div class="example"><span class="example" id="exm:unnamed-chunk-14"><strong>(\#exm:unnamed-chunk-14) </strong></span>Let $A = \{2,3,7\}$, $B=\{1,4,5 \}$ and $C = \{1,2,3,4,5,6\}$. It is clear that $A$ is not a subset of $C$ and $B$ is a subset of $C$. In symbols, we have $A \nsubseteq C$ and $B \subseteq C$.</div>\EndKnitrBlock{example}

##### Remarks {-}
- Remember that the null set $\emptyset$ is a set containing no elements that is why we may write it this form $\{ \}$. Since we can not find an element of $\emptyset$ that is not an element of any other set, say $A$, it follows that $\emptyset \subseteq A$. Thus, the null set $\emptyset$ is considered a subset of any set. 
- Any set $A$ is a subset of itself because all the elements $A$ are found in the set itself.
- For any set $A$, the null set $\emptyset$ and the set $A$ itself are called **trivial subsets** of $A$.
- A set $A$ is a proper subset of a set $B$ if $A \subseteq B$ and $A \neq B$. It means that while $A \subseteq B$, their cardinality (or their number of elements) are not the same. More specifically, $A$ is a proper subset of $B$ is denoted by $A \subset B$.
- *Two sets $A$ and $B$ are equal if and only if $A \subseteq B$ and $B \subseteq A$*. This is the formal definition of equal sets. To prove that two sets are equal (that is, they have exactly the same element as in [Definition 3]), we must show that one is a subset of the other.   

### Venn Diagrams {-}
The **Venn diagram** (or **Venn-Euler diagram**) is a pictorial representation of set relations and operations after the Cambridge logician John Venn (1834-1923). This set representation is very useful in helping you concretize abstract ideas on sets.  

In the Venn diagram, the largest set in consideration is the universal set $U$ and represented by a rectangle. The subsets of $U$ are drawn as circles inside the rectangle as in the figure below. Also, in the figure, we can see the relationship that $A \subseteq B$.

<div class="figure" style="text-align: center">
<img src="Sets_files/figure-html/unnamed-chunk-15-1.png" alt="Venn diagram" width="50%" />
<p class="caption">(\#fig:unnamed-chunk-15)Venn diagram</p>
</div>

\BeginKnitrBlock{exercise}<div class="exercise"><span class="exercise" id="exr:unnamed-chunk-16"><strong>(\#exr:unnamed-chunk-16) </strong></span>Do the following</div>\EndKnitrBlock{exercise}
1. Which of the following sets are equal? 
    + $A = \{a,b,c\}$
    + $B = \{a,a,b,c \}$
    + $C = \{c,a,b \}$  
    + $D = \{c, b, c, a, a\}$ 
2. Which of the following sets are equal?
    + $A = \{x|x~ is~a~ letter~ in~ the~ word~``great"\}$ 
    + $B =$ set of distinct letters of the word "garter" 
    + $C = \{x|x~is~a~letter~in~the~word~"greater"\}$
    + $D = \{r, e, g,a,t\}$
3. State which of the following is correct or incorrect.
    (a) $\{0\} \in S$  
    (b) $\emptyset \in S$  
    (c) $\{\emptyset \subseteq S \}$
    (d) $0 \in S$ 
    (e) $0 \subseteq S$
4. If $A = \{a,b,c \}$ and $B = \{a,b,c,d\}$, which of the following are true?
    (a) $A \in B$
    (b) $A \subseteq B$ 
    (c) $a \in A$
    (d) $b \in B$ 
    (e) $b \subseteq B$
    (f) $\emptyset \in B$
    (g) $\emptyset \subseteq A$
    (h) $a \in B$
    (i) $B \subseteq A$
5. $T = \{\emptyset ,\{\emptyset\} \}$. State whether each of the following is correct or incorrect.
    (a) $\{\emptyset\} \in T$ 
    (b) $\emptyset \in T$ 
    (c) $\{\emptyset \} \subseteq T$
    (d) $\emptyset \subseteq T$ 
    (e) $\{\{\emptyset\}\} \in T$
    (f) $\{\{\emptyset\}\} \subseteq T$ 
6. Does every set have a proper subset?
7. Are two empty sets equal?
8. If $A$ is a subset of the null set, show that $A = \emptyset$.
9. The set containing all the subsets of any set is called the **power set** of S. Give the power set of each of the following sets. Given a finite set $S$ with $n$ elements, what can you conclude about the number of elements of the power set of $S$?
    (a) $A = \emptyset$   
    (b) $B = \{a \}$ 
    (c) $C = \{a,b \}$ 
    (d) $D = \{a,b,c \}$
10. If $a\in X$, $b \in Y$, $X \subseteq Z$ and $Y \subseteq Z$,   
    (a) Is $a \in Z$? 
    (b) Is $b \in Z$? 
    (c) Is $a \in Y$? 
    (d) Can there be an element in $Z$ which is an element of both $X$ and $Y$? 
    (e) Can there be an element in $Z$ which is an element of $X$ but not $Y$?
    (f) Can there be an element in $Z$ which is neither an element of $X$ nor of $Y$?



## Set operations {-}
It is possible to manipulate sets so that we can form a new set. These valid ways of manipulating sets to form new ones are called set operations and they are: union, intersection, difference, complement, and cross-product.  

### Set Intersection {-}
\BeginKnitrBlock{definition}\iffalse{-91-73-110-116-101-114-115-101-99-116-105-111-110-93-}\fi{}<div class="definition"><span class="definition" id="def:unnamed-chunk-17"><strong>(\#def:unnamed-chunk-17)  \iffalse (Intersection) \fi{} </strong></span>Let $A$ and $B$ be subsets of the universal set $U$. The **intersection** of the two sets $A$ and $B$, denoted by $ A \cap B $, (read: "A intersection B") is the set whose elements belong to both $A$ and $B$. That is,  
$$A \cap B = \{x|x \in A~and~x\in B\}.$$
If the intersection of the sets is $\emptyset$, then they are said to be **disjoint**.  
</div>\EndKnitrBlock{definition}

In other words, the intersection of two sets is the set (take note: the intersection is a set) of all elements that are common to both sets.

The Venn diagram is very useful in graphically illustrating $A \cap B$ as shown in the following figures below.



## Sets in Python {-}

### Set representations {-}


### Set operations {-}

##### Exercises {-}



