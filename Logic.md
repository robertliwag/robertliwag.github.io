# Propositional Logic {#logic}



## Introduction 

## Objectives 

## Structure of the module

## Lesson 1. Proposition {-}
\BeginKnitrBlock{definition}<div class="definition"><span class="definition" id="def:unnamed-chunk-2"><strong>(\#def:unnamed-chunk-2) </strong></span>A **proposition** is a statement that is either true or false, but not both.</div>\EndKnitrBlock{definition}

    
    
\BeginKnitrBlock{example}<div class="example"><span class="example" id="exm:unnamed-chunk-3"><strong>(\#exm:unnamed-chunk-3) </strong></span>The following are propositions

- Today is Thursday.
- It is raining.
- The student is in the prescribed uniform.</div>\EndKnitrBlock{example}

\BeginKnitrBlock{example}<div class="example"><span class="example" id="exm:unnamed-chunk-4"><strong>(\#exm:unnamed-chunk-4) </strong></span>The following are not propositions

- Java is the best programming language. 
- How are you doin'?
- Go home! </div>\EndKnitrBlock{example}


\BeginKnitrBlock{exercise}<div class="exercise"><span class="exercise" id="exr:unnamed-chunk-5"><strong>(\#exr:unnamed-chunk-5) </strong></span>Which of these are propositions?
  
- $2 + 2 = 5$.
- Every integer is divisible by 3.
- This University is world-class.</div>\EndKnitrBlock{exercise}

##### Remarks: {-}

- Propositions are usually denoted by a letter such as $p$, $q$, $r$, $s$, ...
- Propositions are declarative statements.
- The **truth value** of a proposition is true, denoted by **T**, if it is a true proposition, and false, denoted by **F**, if it is a false proposition.
- The area of logic that deals with propositions is called **propositional calculus** or **propositional logic**.
- Combining propositions using **logical operators** (or  **connectives**) forms new proposition called **compound proposition**.

### Negation {-}
\BeginKnitrBlock{definition}<div class="definition"><span class="definition" id="def:unnamed-chunk-6"><strong>(\#def:unnamed-chunk-6) </strong></span>Let $p$ be a proposition. The **negation of $p$**, denoted by **$\neg p$**, is the statement: "It is not the case that $p$". 
The truth value of the negation of **p**, $\neg p$, is the opposite of the truth value of $p$.</div>\EndKnitrBlock{definition}

##### Remarks: {-}

- $\neg p$, the negation of proposition $p$, is also a proposition. 
- The proposition $\neg p$ is read as "not $p$."

##### Examples {-}
1. $p:$ "Today is Monday." Its negation, 
	$\neg p :$  "Today is not Monday"  
	is also a proposition. And this can also be stated as
	$\neg p:$ "It is not the case that today is Monday."
2. Let a proposition be: "Johnley's PC runs Linux." Its negation is: "It is not the case that Johnley's PC runs Linux" or "Johnley's PC does not run Linux."
3. Find the negation of the proposition: "Amika's phablet has at least 32GB of memory." The negation can be expressed in any of the following: 
  - "It is not the case that Amika's phablet has at least 32GB of memory" or 
  - "Amika's phablet does not have at least 32GB of memory" or more precisely, "Amika's phablet has less than 32GB of memory."

The **truth table** for the negation operator is

|$\boldsymbol{p}$ |$\boldsymbol{\neg p}$|
|:----:|:----:|
| T   |  F  |
| F   |  T  |

##### Pahabol: {-}
- Negation is a unary operator. That is, it takes only one proposition to create a new proposition.
- $p$ is to a set $A$, as $\neg p$ is to $A^c$. So, consider the domain of the proposition or the universal set of the discourse.
- Try this. What is the negation of the following quantitative phrases: 
  - at most 
  - none 
  - every 
  - less than

## Lesson 2. Logical Operators (Connectives) {-}
 
- Connectives are used to create a compound proposition from two or more propositions.
  - **And** or logical **conjunction** (denoted  $\wedge$)
  - **Or**  or logical  **disjunction**  (denoted   $\vee$)
  -	**Negation** (denoted  $\neg$ or !)
  - **XOR** or **exclusive or** (denoted   $\oplus$)
  -	**Conditional** (denoted $\Rightarrow$ or $\rightarrow$)
  - **Biconditional** (denoted $\Leftrightarrow$ or $\leftrightarrow$)
- The meaning (semantics) of the logical connectives is defined by truth tables. 

### Conjunction (Logical And) {-}

\BeginKnitrBlock{definition}\iffalse{-91-67-111-110-106-117-110-99-116-105-111-110-93-}\fi{}<div class="definition"><span class="definition" id="def:unnamed-chunk-7"><strong>(\#def:unnamed-chunk-7)  \iffalse (Conjunction) \fi{} </strong></span>Let $p$ and $q$ be propositions. The **conjunction of $p$ and $q$**, denoted by $p \wedge q$, is the proposition "$p$ and $q$".</div>\EndKnitrBlock{definition}

##### Remarks: {-}
- The logical connective \textbf{And} is true only when both of the propositions are true. It is false, otherwise.
- The **And** is a binary operator.
- The symbol used is $\wedge$.

Its truth table is given by

|$\boldsymbol{p}$ |$\boldsymbol{q}$| $\boldsymbol{p \wedge q}$
|:----:|:----:|:----:|
| T   |  T  |  T  |
| T   |  F  |  F  |
| F   |  T  |  F  |
| F   |  F  |  F  |


##### Examples {-}

1. It is raining **and** my dog is a bitch.
2. $(2+3 = 5)$ **and** $(1<2)$.
3. My dog, Dino, is dead **and** my dog, dino, is not dead. 

##### Try this. {-}
Find the conjunction of the following propositions: "Amaya's PC has more than 64 GB free hard disk space" and "The processor speed of Amaya's PC is more than 1 GHz."

### Disjunction (Logical Or) {-}
\BeginKnitrBlock{definition}\iffalse{-91-68-105-115-106-117-110-99-116-105-111-110-93-}\fi{}<div class="definition"><span class="definition" id="def:unnamed-chunk-8"><strong>(\#def:unnamed-chunk-8)  \iffalse (Disjunction) \fi{} </strong></span>Let $p$ and $q$ be propositions. The **disjunction** of $p$ and $q$, denoted by $p \vee q$, is the proposition "$p$ or $q$"</div>\EndKnitrBlock{definition}

##### Remarks {-}
- The logical connective **OR** is true if one or both of the propositions are true.
- The symbol used is $\vee$. 
- It is a binary operator.
- There are two ways the word or is used in the English language. 
  - **Inclusive Or**. For instance, the statement: "Those who have taken the courses Algebra or Trigonometry may enrol Discrete Math." 
    - Those who have taken Algebra only may enrol Discrete math;
    - Those who have taken Trigonometry only may enrol;
    - Those who have taken both may enrol.
  - **Exclusive Or**. This is true only if one of the operands is true. For instance, in restaurants, "Group Meal A comes with free soft drinks or Iced tea." This means 
    - You get free soft drinks when you order Group Meal A;
    - You get free Iced tea when you order Group Meal A;
    - You can't have both free soft drinks and Iced tea when you order Group Meal A.

##### Truth table {-}

|$\boldsymbol{p}$ |$\boldsymbol{q}$| $\boldsymbol{p \vee q}$|
|:----:|:----:|:----:|
| T   |  T  | T   |
| T   |  F  | T   |
| F   |  T  | T   |
| F   |  F  | F   |

##### Examples {-}
- It is not raining **or** it is my second lab class.
- $(2+3=4) \vee (2<5)$.
- It is marriage **or** happiness.

	
### Logical Exclusive Or {-}

\BeginKnitrBlock{definition}\iffalse{-91-69-120-99-108-117-115-105-118-101-32-79-114-93-}\fi{}<div class="definition"><span class="definition" id="def:unnamed-chunk-9"><strong>(\#def:unnamed-chunk-9)  \iffalse (Exclusive Or) \fi{} </strong></span>Let $p$ and $q$ be propositions. The **exclusive or of $p$ and $q$**, denoted by $p \oplus q$, is the proposition that is true when exactly one of $p$ and $q$ is true and is false otherwise.</div>\EndKnitrBlock{definition}

##### Remarks {-}
- The symbol used is $\oplus$.
- This is a binary operator.
- This is also known as **XOR** operator.

##### Examples {-}
- The circuit is either on or off but not both.
- Let $ab < 0$, then either $a < 0$ or $b < 0$ but not both.
- It is freedom or death.

##### Truth table {-}
|$\boldsymbol{p}$ |$\boldsymbol{q}$| $\boldsymbol{p \oplus q}$|
|:----:|:----:|:----:|
| T   |  T  | F   |
| T   |  F  | T   |
| F   |  T  | T   |
| F   |  F  | F   |

### Conditional Statement {-}
\BeginKnitrBlock{definition}\iffalse{-91-67-111-110-100-105-116-105-111-110-97-108-32-115-116-97-116-101-109-101-110-116-93-}\fi{}<div class="definition"><span class="definition" id="def:unnamed-chunk-10"><strong>(\#def:unnamed-chunk-10)  \iffalse (Conditional statement) \fi{} </strong></span>Let $p$ and $q$ be propositions. The **conditional statement** $$p \rightarrow q$$ is the proposition "if $p$, then $q$." In the conditional statement $p \rightarrow q$, $p$ is called the **hypothesis** (or **antecedent** or **premise**) and $q$ is called the **conclusion** (or **consequence**).</div>\EndKnitrBlock{definition}

##### Remarks {-}
- $p \rightarrow q$ is read as "$p$ implies $q$"
- This statement is also called an **implication**.
- It is a binary operator
- The statement $p \rightarrow q$ is false when $p$ is true and $q$ is false, and true otherwise.

##### Truth table {-}
|$\boldsymbol{p}$ |$\boldsymbol{q}$| $\boldsymbol{p \rightarrow q}$|
|:----:|:----:|:----:|
| T   |  T  | T   |
| T   |  F  | F   |
| F   |  T  | T   |
| F   |  F  | T   |

##### variants of $p \rightarrow q$ {-}
- If $p$ then $q$.
- If $p$, $q$.
- $p$ only if $q$.
- $q$ if $p$.
- $q$ when $p$.
- $q$ whenever $p$.
- $q$ follows from $p$.
- $q$ unless $\neg p$
- "$p$ is a **sufficient condition** for $q$"
- "a sufficient condition for $q$ is $p$"
- "$q$ is a **necessary condition** for $p$"
- "a necessary condition for $p$ is $q$"


##### Examples {-}

1. If you buy air ticket in advance, it is cheaper.
2. If $x$ is an  integer, then $x^2 \geq 0$.
3. Kapag umulan, basa ang lupa.
4. If the sprinklers operate, the grass gets wet.
5. Pagputi ng uwak, mamahalin kita.
6. If $2+2=5$, then all unicorns are pink.

##### Try this. {-} 
Which of the following implications is true?

1. If $-1$ is a positive number, then $2+2 = 5$. 
  - True. The premise is false, so, no matter what the conclusion is, the implication holds.
2. If $-1$ is a positive number, then $2+2 =5$ 
  - Isu met lang a. True!
3. If $sin(x) = 0$, then $x = 0$
  - False. Although $sin(0) = 0$, there are other values of $x$ that makes $sin(x) = 0$.
  
### Biconditional Statement {-}
\BeginKnitrBlock{definition}\iffalse{-91-66-105-99-111-110-100-105-116-105-111-110-97-108-32-115-116-97-116-101-109-101-110-116-93-}\fi{}<div class="definition"><span class="definition" id="def:unnamed-chunk-11"><strong>(\#def:unnamed-chunk-11)  \iffalse (Biconditional statement) \fi{} </strong></span>Let $p$ and $q$ be propositions. The biconditional statement $p \leftrightarrow q$ is the proposition "$p$ if and only if $q$". The biconditional statement $p \leftrightarrow q$ is true when $p$ and $q$ have the same truth values, and is false otherwise.</div>\EndKnitrBlock{definition}

##### Remarks {-}
- $p \leftrightarrow q$ can be equivalently read as
  - "$p$ is necessary and sufficient for $q$"
  - "if $p$ then $q$, and conversely"
  - "$p$ iff $q$"
  - "if $p$ then $q$, and conversely.
- The simplest way to remember the truth value of a biconditional statement is contained in the definition: true only when both $p$ and $q$ have the same truth values.

##### Truth table {-}
|$\boldsymbol{p}$ |$\boldsymbol{q}$| $\boldsymbol{p \leftrightarrow q}$|
|:----:|:----:|:----:|
| T   |  T  | T   |
| T   |  F  | F   |
| F   |  T  | F   |
| F   |  F  | T   |

- However, we can look at $p \leftrightarrow q$ as "$p \rightarrow q$ and $p \leftarrow q$", thus, the use of the double-sided arrow, $\leftrightarrow$.  (note: $p \rightarrow q$ is the same as $q \rightarrow p$).
- Therefore, $p \leftrightarrow q \equiv (p \rightarrow q) \wedge (q \rightarrow p)$. 
- Using the right-hand side of the above gives the same table.
- Formal definition of mathematical concepts are  biconditional although may not be explicitly stated.

##### Examples {-}
- For any number $x$, $x > 0$ if and only if $x^2$ is positive.
- The alarm goes off iff a burglar breaks in.
- You may have the dessert iff you eat your meal.



##### Try this. {-}
Complete the following truth table to verify the identity $p \leftrightarrow q \equiv (p \rightarrow q) \wedge (q \rightarrow p)$.

|$\boldsymbol{p}$ |$\boldsymbol{q}$| $\boldsymbol{p \rightarrow q}$| $\boldsymbol{q \rightarrow p}$| $\boldsymbol{(p \rightarrow q) \wedge (q \rightarrow p)}$|
|:----:|:----:|:----:|:----:|:----|
| T   |  T  | T   |     |     |
| T   |  F  | F   |     |     |
| F   |  T  | F   |     |     |
| F   |  F  | T   |     |     | 

### Operator Precedence {-}

- As in arithmetic, rules of ordering are imposed on the use of logical operators in compound propositions.
- It is, however, preferable to use parentheses to remove the ambiguity in the expression and facilitate readability. For instance, \[\neg p \vee q \wedge \neg r \equiv (\neg p) \vee (q \wedge (\neg r)) \]
- When no parentheses are used, the precedence heirarchy is used
  + Negation ($\neg$)
  + Conjunction ($\wedge$)
  + Disjunction ($\vee$)
  + Conditional ($\rightarrow$)
  + Biconditional ($\leftrightarrow$)
  
  
##### Examples {-}







## Lesson 3. Using Python {-} 
