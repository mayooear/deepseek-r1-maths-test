# **Complete Mark‐by‐Mark Scheme (Questions 1–9)**

Below is a full, collated record of the point‐by‐point mark allocations and comments. The final total is out of **75**.

---

## **Question 1**  
*(2 marks each, total 4)*

1. **(a)** Plane \(x=1\) intersects \(z = x^2 + 2y\) giving \(z = 1 + 2y\).  
   - **Marks:**  
     - M1 for a correct straight‐line sketch in \(y\text{-}z\) plane.  
     - A1 for correct slope and intercept.  

2. **(b)** Plane \(y=1\) intersects \(z = x^2 + 2y\) giving \(z = x^2 + 2\).  
   - **Marks:**  
     - M1 for a correct parabola sketch in \(x\text{-}z\) plane.  
     - A1 for correct shape (∪‐shaped) and vertex at \((x,z) = (0,2)\).  

**Awarded**: 4 / 4.

---

## **Question 2**  
*(a 4 marks, b 2 marks; total 6)*

### (a)
- **Mark scheme** typically:
  1. (M1) Differentiate \(y=\sqrt{1 + x^2}\) correctly for \(\mathrm{d}y/\mathrm{d}x\).  
  2. (A1) Form the surface‐area integral \(A = 2\pi \int y\sqrt{1+(y')^2}\,\mathrm{d}x\).  
  3. (M1) Correct simplification of the integrand.  
  4. (A1) Identify the integer \(k\) (in practice \(k=2\)).

- **Student** obtains
  \[
     A \;=\; 2\pi \int_{0}^{1} \sqrt{1 + 2\,x^2}\,\mathrm{d}x,\quad \text{hence } k=2.
  \]
  which is consistent with the required formula (despite a possible typo in “\(x^{-2}\)” in the original statement).

**Marks**: 4 / 4.

### (b)
- The problem states that the required surface area is \(8\) cm² (± 1%) and the manufacturing tolerance is ± 0.5%.  
- They conclude **all** produced components stay within the ± 1% band.

- **Mark scheme** typically:
  - (M1) Some check that 8 ± 0.5% is indeed within 8 ± 1%.  
  - (A1) Conclude “yes, they are all suitable.”

- **Student** only gives the “yes” statement without explicit numeric check.

**Marks**: 1 / 2.  

**Total for Q 2**: 5 / 6.

---

## **Question 3**  
*(a 3 marks, b (2+2); total 7)*

### (a)
- **Cross product** \(\mathbf{a}\times\mathbf{b}=(2,6,-11)\).  
- Solve for \(p=7,\,q=4\).  
- **Marks**: B1/M1/A1 → **3 / 3**.

### (b)(i)
- Tetrahedron volume \(=\frac{1}{6}\bigl|(\mathbf{a}\times\mathbf{b})\cdot\mathbf{c}\bigr|=7\).  
- Hence \(\lvert2\,d+6\,e-11\,f\rvert=42\). So \(2d+6e-11f=\pm42\).  
- **Marks**: 2 / 2.

### (b)(ii)
- Explains geometrical meaning: the set of such \(C\) are two **parallel planes** in 3D.  
- **Marks**: 2 / 2.

**Total for Q 3**: 7 / 7.

---

## **Question 4**  
*(7 marks total)*

The sequence is \(A_n = \frac{I_{n+2}}{I_n}\), where \(I_n=\int_{0}^{\frac{\pi}{2}}\cos^n x\,\mathrm{d}x\).  
Via reduction formula \(I_{n+2}=\frac{n+1}{n+2}\,I_n\), so \(A_n=\tfrac{n+1}{n+2}\).

- Show it **increases**: \(A_{n+1}-A_n>0\).  
- Show it **converges** to \(1\).  

**Marks**: 7 / 7.

---

## **Question 5**  
*(a (2+2), b (2+4); total 10)*

### (a)(i)
Cayley table under “\(\times_{32}\)” for \(\{1,9,17,25\}\).  
- **Marks:** B1 for partial correctness (any two correct “bold” entries), B1 for all correct.  
- Student’s table is fully correct → **2 / 2**.

### (a)(ii)
Cyclic vs Klein group.  
- They observe 9 or 25 has order 4, so group is \(C_4\).  
- **Marks:** 2 / 2.

### (b)(i)
Odd quadratic residues mod 32.  
- Correct set \(\{1,\,9,\,17,\,25\}\).  
- **Marks:** 2 / 2.

### (b)(ii)
Show \(n^6 + 3n^4 + 7n^2\equiv 11 \pmod{32}\) for odd \(n\).  
- By testing the four possible values of \(n^2\) modulo 32, each time it yields 11.  
- **Marks:** 4 / 4.

**Total Q 5**: 10 / 10.

---

## **Question 6**  
*(a 6, b 2, c 3; total 11)*

### (a)  
**Hessian determinant**:
\[
  \frac{\partial^2 z}{\partial x^2} \;=\; \frac{2\,y}{x^3}, 
  \quad \frac{\partial^2 z}{\partial y^2} \;=\; -\,x\sin y,
  \quad \frac{\partial^2 z}{\partial x\partial y}\;=\;\cos y \;-\;\tfrac{1}{x^2},
\]
so
\[
  \det(H)\;=\;\bigl(\tfrac{2\,y}{x^3}\bigr)\bigl(-\,x\sin y\bigr)\;-\;\bigl(\cos y - \tfrac{1}{x^2}\bigr)^2
  \;=\; -\,\frac{2\,y\,\sin y}{x^2}\;-\;\bigl(\cos y - \tfrac{1}{x^2}\bigr)^{2}.
\]
- **Marks:** 6 / 6.

### (b)  
**Nature of the stationary point**: determinant < 0 → **saddle**.  
- **Marks:** 2 / 2.

### (c)  
Solving \(\partial z/\partial x=0\) and \(\partial z/\partial y=0\) leads to \(\tan y=-y\).  
Hence \(y+\tan y=0\).  
- **Marks:** 3 / 3.

**Total Q 6**: 11 / 11.

---

## **Question 7**  
*(a 1, b (3+2+1), c (1+2); total 10)*

### (a)  
\(\alpha+\beta=1,\;\alpha\beta=-1\).  
- **1 / 1**.

### (b)(i)  
\(S_2=\alpha^2+\beta^2=3,\;S_3=\alpha^3+\beta^3=4.\)  
- **3 / 3**.

### (b)(ii)  
Recurrence \(S_{n+2}=S_{n+1}+S_{n}\).  
- **2 / 2**.

### (b)(iii)  
All \(S_n\) are integers by induction from integer initial data.  
- **1 / 1**.

### (c)(i)  
\(T_n=\alpha^n\) alone omits \(\beta^n\), so not equal to \(S_n\).  
- **1 / 1**.

### (c)(ii)  
Modified formula for \(T_n\) to get \(S_n\); e.g. \(T_n=\alpha^n + (-1)^n\,\alpha^{-n}\).  
- **2 / 2**.

**Total Q 7**: 10 / 10.

---

## **Question 8**  
*(a (2+1), b (4+2); total 9)*

### (a)(i)  
Factor \(2121_n\) as \((n^2+1)(2n+1)\).  
- M1 for the attempt, A1 for fully correct factorization.  
- **2 / 2**.

### (a)(ii)  
Hence composite, since both factors > 1.  
- B1 for the “non‐primeness” justification.  
- **1 / 1**.

### (b)(i)  
Show \(\gcd\bigl(n^2+1,\;2n+1\bigr)\in\{1,5\}\). Typically uses linear combination or modular argument.  
- Usually 4 steps: M1–A1–M1–A1.  
- **4 / 4**.

### (b)(ii)  
Find \(n\) with gcd = 5, e.g. \(n=7\).  
- M1 for the congruence reasoning, A1 for final \(n=7\).  
- **2 / 2**.

**Total Q 8**: 9 / 9.

---

## **Question 9**  
*(a 2, b 2, c 3, d 1, e 3; total 11)*

### (a)  
**Identity**: solve \(\frac{a+b}{ab+1}=a\). Yields \(b=0\).  
- M1, A1 → **2 / 2**.

### (b)  
**Inverse** of \(x\) is \(-x\), since \(\frac{x+(-x)}{x(-x)+1}=0\).  
- M1, A1 → **2 / 2**.

### (c)  
**Associativity**: show \((a\oplus b)\oplus c = a\oplus (b\oplus c)\).  
- 3 steps (M1, M1, A1).  
- **3 / 3**.

### (d)  
\(\bigl(C,\oplus\bigr)\) not a group: closure fails if \(ab+1=0\).  
- B1 → **1 / 1**.

### (e)  
A **3‐element subgroup**: \(\{0,\,a,\,-a\}\) with suitable \(a\neq 0\). Typically solutions like \(a=\pm i\sqrt3\).  
- B1, M1, A1 → **3 / 3**.

**Total Q 9**: 11 / 11.

---

## **Final Score Computation**

- **Q 1**: 4/4  
- **Q 2**: 5/6  
- **Q 3**: 7/7  
- **Q 4**: 7/7  
- **Q 5**: 10/10  
- **Q 6**: 11/11  
- **Q 7**: 10/10  
- **Q 8**: 9/9  
- **Q 9**: 11/11  

Summing:  
\[
  4 + 5 + 7 + 7 + 10 + 11 + 10 + 9 + 11 = 74
\]
So the **final total** is **74 out of 75**.
