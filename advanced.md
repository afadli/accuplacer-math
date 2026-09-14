# 📚 ACCUPLACER Next-Generation Advanced Algebra and Functions (AAF): Comprehensive Cheat Sheet with Examples

This cheat sheet covers all core content domains tested on the **ACCUPLACER Next-Generation Advanced Algebra and Functions** exam. Each section includes key rules, formulas, and fully worked-out examples modeled directly after the official College Board sample questions.

---

## 1. Linear Equations & Applications

### Key Concepts
* **Slope-Intercept Form:** $y = mx + b$, where $m$ is the slope and $b$ is the $y$-intercept.
* **Slope Formula:** Given two points $(x_1, y_1)$ and $(x_2, y_2)$:
  $$m = \frac{y_2 - y_1}{x_2 - x_1}$$
* **Parallel & Perpendicular Slopes:**
  * **Parallel lines** have the *same slope* ($m_1 = m_2$).
  * **Perpendicular lines** have *negative reciprocal slopes* ($m_1 \times m_2 = -1 \implies m_2 = -\frac{1}{m_1}$).

---

### Worked Examples

#### Example 1.1: Evaluating Functions
**Problem:** Function $g$ is defined by $g(x) = 3(x + 8)$. What is the value of $g(12)$?
* **Substitute:** Replace $x$ with $12$.
  $$g(12) = 3(12 + 8)$$
* **Simplify inside parentheses:** $12 + 8 = 20$
* **Multiply:** $3 \times 20 = \mathbf{60}$

#### Example 1.2: Perpendicular Lines
**Problem:** Which equation represents a line passing through $(0,0)$ and perpendicular to a line with a slope of $-\frac{4}{5}$?
* **Find the perpendicular slope:** The negative reciprocal of $-\frac{4}{5}$ is $+\frac{5}{4}$.
* **Write the equation:** Since it passes through the origin $(0,0)$, the $y$-intercept $b = 0$.
* **Answer:** $y = \mathbf{\frac{5}{4}x}$

---

## 2. Factoring & Polynomials

### Key Concepts
* **Difference of Squares:** $a^2 - b^2 = (a - b)(a + b)$
* **Perfect Square Trinomials:** $a^2 + 2ab + b^2 = (a + b)^2$
* **Polynomial Multiplication:** Multiply every term in the first polynomial by every term in the second polynomial (FOIL for binomials).

---

### Worked Examples

#### Example 2.1: Factoring Expressions
**Problem:** Which expression is equivalent to $3x^2 + 6x - 24$?
* **Factor out the Greatest Common Factor (GCF):** $3(x^2 + 2x - 8)$
* **Factor the quadratic inside:** Find two numbers that multiply to $-8$ and add to $2$ ($+4$ and $-2$).
  $$x^2 + 2x - 8 = (x + 4)(x - 2)$$
* **Answer:** $\mathbf{3(x + 4)(x - 2)}$

#### Example 2.2: Multiplying Polynomials
**Problem:** Which expression is equivalent to $(x + 7)(x^2 - 3x + 2)$?
* **Distribute $x$:** $x(x^2 - 3x + 2) = x^3 - 3x^2 + 2x$
* **Distribute $7$:** $7(x^2 - 3x + 2) = 7x^2 - 21x + 14$
* **Combine like terms:** 
  $$x^3 + (-3x^2 + 7x^2) + (2x - 21x) + 14 = \mathbf{x^3 + 4x^2 - 19x + 14}$$

---

## 3. Quadratic Equations & Functions

### Key Concepts
* **Standard Form:** $f(x) = ax^2 + bx + c$
* **Vertex Form:** $f(x) = a(x - h)^2 + k$, where $(h, k)$ is the vertex.
* **Quadratic Formula:** For $ax^2 + bx + c = 0$:
  $$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$
* **Discriminant ($b^2 - 4ac$):** Determines number of real solutions (Positive = 2, Zero = 1, Negative = 0).

---

### Worked Examples

#### Example 3.1: Solving Quadratic Equations
**Problem:** What value(s) of $x$ satisfy $x^2 + 5x - 9 = 5$?
* **Set equation to zero:** Subtract $5$ from both sides $\implies x^2 + 5x - 14 = 0$
* **Factor:** Find factors of $-14$ that add to $5$ ($+7$ and $-2$).
  $$(x + 7)(x - 2) = 0$$
* **Set each factor to zero:** $x + 7 = 0 \implies x = -7$, or $x - 2 = 0 \implies x = 2$.
* **Answer:** $\mathbf{x = 2 \text{ or } x = -7}$

#### Example 3.2: Unique Solutions
**Problem:** For which equation is $x = 6$ the *only* solution?
* **Test options:** 
  * $(x - 6)^2 = 0 \implies x - 6 = 0 \implies x = 6$ (Multiplicity of 2, exactly one distinct solution).
* **Answer:** $\mathbf{(x - 6)^2 = 0}$

---

## 4. Radical & Rational Equations

### Key Concepts
* **Radical Equations:** Isolate the radical, square both sides to eliminate it, and **always check for extraneous solutions**.
* **Rational Equations:** Clear denominators by multiplying the entire equation by the Least Common Denominator (LCD). Watch out for excluded values where the denominator equals zero.

---

### Worked Examples

#### Example 4.1: Solving Radical Equations
**Problem:** What, if any, is a real solution to $\sqrt{5x + 1} + 9 = 3$?
* **Isolate the radical:** Subtract $9$ from both sides $\implies \sqrt{5x + 1} = -6$
* **Analyze:** A principal square root ($\sqrt{\dots}$) can never equal a negative number in real numbers.
* **Answer:** **There is no real solution.**

---

## 5. Exponential & Logarithmic Equations

### Key Concepts
* **Exponent Rules:** 
  * $x^a \cdot x^b = x^{a+b}$
  * $(x^a)^b = x^{a \cdot b}$
  * $x^{-a} = \frac{1}{x^a}$
* **Logarithmic Form Conversion:** 
  $$b^x = y \iff \log_b(y) = x$$

---

### Worked Examples

#### Example 5.1: Exponential Growth Word Problem
**Problem:** A biologist puts an initial population of $500$ bacteria into a growth plate. The population doubles every 4 hours. Which equation gives the expected number $n$ after $x$ days? ($24 \text{ hours} = 1 \text{ day}$)
* **Determine doubling rate per day:** In 1 day (24 hours), it doubles $24 \div 4 = 6$ times.
* **Formulate equation:** After $x$ days, it doubles $6x$ times.
* **Answer:** $n = 500(2)^{\mathbf{6x}}$

#### Example 5.2: Converting to Logarithmic Form
**Problem:** Which equation is equivalent to $25^x = 7$?
* **Apply definition:** $b^x = y \iff \log_b(y) = x$
* **Convert:** $\log_{25}(7) = x$ or using base change rules: $x = \log_{25}(7)$.

---

## 6. Geometry & Trigonometry Concepts

### Key Concepts
* **Surface Area of Rectangular Prism:** $\text{SA} = 2(lw + lh + wh)$
* **Right Triangle Trig Ratios (SOH-CAH-TOA):**
  * $\sin(\theta) = \frac{\text{Opposite}}{\text{Hypotenuse}}$
  * $\cos(\theta) = \frac{\text{Adjacent}}{\text{Hypotenuse}}$
  * $\tan(\theta) = \frac{\text{Opposite}}{\text{Adjacent}}$

---

### Worked Examples

#### Example 6.1: Surface Area Calculation
**Problem:** What is the surface area of a right rectangular prism with length $4\text{ cm}$, width $9\text{ cm}$, and height $3\text{ cm}$?
* **Plug into formula:** $\text{SA} = 2(lw + lh + wh)$
  * $lw = 4 \times 9 = 36$
  * $lh = 4 \times 3 = 12$
  * $wh = 9 \times 3 = 27$
* **Calculate sum:** $36 + 12 + 27 = 75$
* **Multiply by 2:** $2 \times 75 = \mathbf{150\text{ cm}^2}$