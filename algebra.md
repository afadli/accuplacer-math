# 📚 Community College Algebra Placement Test: Comprehensive Cheat Sheet with Examples

This cheat sheet covers the essential intermediate algebra topics frequently tested on community college math placement exams.

---

## 1. Linear Equations & Inequalities

### Key Concepts
* **Solving Inequalities:** Remember to **flip the inequality sign** ($<$ to $>$, or vice versa) whenever you multiply or divide both sides by a negative number.
* **Absolute Value Equations:** If $|x - a| = c$, then split it into two separate equations: $x - a = c$ OR $x - a = -c$.

---

### Worked Examples

#### Example 1.1: Solving an Inequality with a Negative
**Problem:** Solve $-3x + 5 > 14$
* **Subtract 5:** $-3x > 9$
* **Divide by $-3$ (and flip sign):** $x < \frac{9}{-3} \implies \mathbf{x < -3}$

#### Example 1.2: Absolute Value Equation
**Problem:** Solve $|2x - 1| = 7$
* **Split into two cases:** 
  1. $2x - 1 = 7 \implies 2x = 8 \implies x = 4$
  2. $2x - 1 = -7 \implies 2x = -6 \implies x = -3$
* **Answer:** $\mathbf{x = 4 \text{ or } x = -3}$

---

## 2. Systems of Linear Equations

### Key Concepts
* **Substitution Method:** Solve one equation for one variable, then substitute that expression into the other equation.
* **Elimination (Addition) Method:** Multiply equations by constants so that one variable's coefficients are opposites, then add the equations together to eliminate it.

---

### Worked Examples

#### Example 2.1: Elimination Method
**Problem:** Solve the system:
$\begin{cases} 2x + y = 7 \\ 3x - y = 8 \end{cases}$
* **Add equations directly** (since $+y$ and $-y$ eliminate each other):
  $$(2x + 3x) + (y - y) = 7 + 8 \implies 5x = 15 \implies x = 3$$
* **Substitute back to find $y$:** $2(3) + y = 7 \implies 6 + y = 7 \implies y = 1$
* **Answer:** $\mathbf{(3, 1)}$

---

## 3. Exponents & Polynomial Factoring

### Key Concepts
* **Negative Exponents:** $x^{-n} = \frac{1}{x^n}$ and $\frac{1}{x^{-n}} = x^n$
* **Rational (Fractional) Exponents:** $x^{m/n} = \sqrt[n]{x^m}$
* **Factoring by Grouping (4 terms):** Group terms in pairs, factor out the GCF from each pair, then factor out the common binomial.

---

### Worked Examples

#### Example 3.1: Simplifying Negative Exponents
**Problem:** Simplify $\frac{4x^{-2}y^3}{2x^3y^{-1}}$
* **Coefficients:** $\frac{4}{2} = 2$
* **$x$ terms:** $x^{-2 - 3} = x^{-5} = \frac{1}{x^5}$ (move to denominator)
* **$y$ terms:** $y^{3 - (-1)} = y^{3 + 1} = y^4$ (stays in numerator)
* **Answer:** $\mathbf{\frac{2y^4}{x^5}}$

#### Example 3.2: Factoring by Grouping
**Problem:** Factor $2x^3 - 4x^2 + 3x - 6$ completely.
* **Group in pairs:** $(2x^3 - 4x^2) + (3x - 6)$
* **Factor GCF from each:** $2x^2(x - 2) + 3(x - 2)$
* **Factor out common binomial $(x - 2)$:** $\mathbf{(2x^2 + 3)(x - 2)}$

---

## 4. Rational Expressions & Equations

### Key Concepts
* **Domain Restrictions:** Set any denominator equal to $0$ and solve. Those values are **excluded** from the domain because division by zero is undefined.
* **Solving Rational Equations:** Clear fractions by multiplying every term by the Least Common Denominator (LCD).

---

### Worked Examples

#### Example 4.1: Domain Restriction
**Problem:** What is the domain of $f(x) = \frac{5}{x^2 - 9}$?
* **Set denominator to zero:** $x^2 - 9 = 0 \implies (x - 3)(x + 3) = 0$
* **Solve:** $x = 3$ or $x = -3$
* **Answer:** All real numbers **except $x \neq 3$ and $x \neq -3$**.

---

## 5. Radical Expressions & Complex Numbers

### Key Concepts
* **Simplifying Radicals:** Break down numbers into prime factors looking for perfect squares (e.g., $\sqrt{50} = \sqrt{25 \times 2} = 5\sqrt{2}$).
* **Complex Numbers ($i$):** Remember that $i = \sqrt{-1}$ and $i^2 = -1$. Always combine real parts with real parts and imaginary parts with imaginary parts.

---

### Worked Examples

#### Example 5.1: Operating with Complex Numbers
**Problem:** Simplify $(3 + 2i) - (1 - 4i)$
* **Distribute the negative:** $3 + 2i - 1 + 4i$
* **Combine real parts:** $3 - 1 = 2$
* **Combine imaginary parts:** $2i + 4i = 6i$
* **Answer:** $\mathbf{2 + 6i}$

---

## 6. Functions: Domain, Range & Transformations

### Key Concepts
* **Evaluating Functions:** If given $f(x) = x^2 - 3x$, find $f(-2)$ by replacing every $x$ with $(-2)$: $(-2)^2 - 3(-2) = 4 + 6 = 10$.
* **Horizontal Shifts:** $f(x - c)$ shifts the graph **right** by $c$ units; $f(x + c)$ shifts it **left** by $c$ units.
* **Vertical Shifts:** $f(x) + c$ shifts the graph **up** by $c$ units; $f(x) - c$ shifts it **down** by $c$ units.