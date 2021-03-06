Showing properties now of vector math and vector proofs.
![lesson_14_1](lesson_14_1.jpeg)

## Length:
The length or magnitude or norm of the vector a is denoted by ‖a‖ or, less commonly, |a|, which is not to be confused with the absolute value (a scalar "norm").

The length of the vector a can be computed with the Euclidean norm:

\left\|\mathbf{a}\right\|=\sqrt{{a_1}^2+{a_2}^2+{a_3}^2}

which is a consequence of the Pythagorean theorem since the basis vectors e1, e2, e3 are orthogonal unit vectors.
This happens to be equal to the square root of the dot product, discussed below, of the vector with itself:

\left\|\mathbf{a}\right\|=\sqrt{\mathbf{a}\cdot\mathbf{a}}.


## Dot product
The dot product between two vectors is based on the projection of one vector onto another. Let's imagine two vectors a and b and we want to calculate how much of a is pointing in the same direction as the vector b. We want a quantity that would be positive if the two vectors are pointing in similar directions, zero if they are perpendicular, and negative if the two vectors are pointing in nearly opposite directions. We will define the dot product between the vectors to capture these quantities.

But first, notice that the question “how much of a is pointing in the same direction as the vector b” does not have anything to do with the magnitude (or length) of b; it is based only on its direction.

The dot product of a with unit vector u, denoted a⋅u, is defined to be the projection of a in the direction of u, or the amount that a is pointing in the same direction as unit vector u. 

### Commutative, distributive and Associative properties of vectors:
![lesson_14_2](lesson_14_2.jpeg)

Additional notes:
![lesson_14_3](lesson_14_3.jpeg)

More notes on dot product and length of vectors:
![lesson_14_4](lesson_14_4.jpeg)

### Commutative property
In mathematics, a binary operation is commutative if changing the order of the operands does not change the result. It is a fundamental property of many binary operations, and many mathematical proofs depend on it. Most familiar as the name of the property that says "3 + 4 = 4 + 3" or "2 × 5 = 5 × 2", the property can also be used in more advanced settings. The name is needed because there are operations, such as division and subtraction, that do not have it (for example, "3 − 5 ≠ 5 − 3"), such operations are not commutative, or noncommutative operations. The idea that simple operations, such as multiplication and addition of numbers, are commutative was for many years implicitly assumed and the property was not named until the 19th century when mathematics started to become formalized.


### Associative property

The **associative property** states that you can add or multiply regardless of how the numbers are grouped. By 'grouped' we mean 'how you use parenthesis'. In other words, if you are adding or multiplying it does not matter where you put the parenthesis

In mathematics, the associative property is a property of some binary operations. In propositional logic, associativity is a valid rule of replacement for expressions in logical proofs.
Within an expression containing two or more occurrences in a row of the same associative operator, the order in which the operations are performed does not matter as long as the sequence of the operands is not changed. That is, rearranging the parentheses in such an expression will not change its value. Consider the following equations:

```
(2 + 3) + 4 = 2 + (3 + 4) = 9 \,
2 \times (3 \times 4) = (2 \times 3) \times 4 = 24 .
```

Even though the parentheses were rearranged, the values of the expressions were not altered. Since this holds true when performing addition and multiplication on any real numbers, it can be said that "addition and multiplication of real numbers are associative operations".

**Associativity is not to be confused with commutativity, which addresses whether a × b = b × a.**

The associative property states that you can add or multiply regardless of how the numbers are grouped. By 'grouped' we mean 'how you use parenthesis'. In other words, if you are adding or multiplying it does not matter where you put the parenthesis. Add some parenthesis any where you like!.

Definition: The associative property states that you can add or multiply regardless of how the numbers are grouped. By 'grouped' we mean 'how you use parenthesis'. In other words, if you are adding or multiplying it does not matter where you put the parenthesis. Add some parenthesis any where you like!.

a • b) •c = (a • b) •c
So multiplication is associative

But division is not.


### Distributive property

As generally used in math class, the distributive property is the ability of one operation to "distribute" over another operation contained inside a set of parenthesis. Most commonly, this refers to the property of multiplication distributing over addition or subtraction, such that x(a+b) = xa + xb.

When we say that multiplication distributes over addition, it means we can distribute the factor outside the set of parenthesis to each item inside, and then add the results. For example, 4(3+7) is equivalent to 4*3 + 4*7 because the multiplication by four was distributed across the addition inside the parenthesis.

Not every operation is distributive. For example, division is not distributive over addition. If we are given 20/(3+7) the true result is 2, but distributing would give you 20/3 + 20/7, which is around 10 and very incorrect!
