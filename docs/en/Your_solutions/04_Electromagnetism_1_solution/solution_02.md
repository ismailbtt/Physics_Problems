# Section 4 – Electromagnetism I

---

# Task 01 – Coulomb's Law

## Problem Statement

Four point charges of $+1.0\,\text{C}$ are placed at the corners of a square of side $1.0\,\text{m}$. Determine the magnitude and direction of the electric force acting on a charge $-2.0\,\text{C}$ placed at the center.

## Theory

The electric force between two point charges is given by Coulomb’s law:

$$
F = k \frac{|q_1 q_2|}{r^2}
$$

where $k = 9 \times 10^9 \,\text{N m}^2/\text{C}^2$.

The electric field at a point due to multiple charges is the vector sum of individual fields.

## Step-by-Step Solution

Distance from center to each corner:

$$
r = \frac{\sqrt{2}}{2}
$$

Force from one charge:

$$
F_1 = k \frac{(1)(2)}{r^2} = k \frac{2}{1/2} = 4k
$$

Each force points toward a corner (attractive force).

Due to symmetry, horizontal and vertical components cancel:

$$
\sum F_x = 0, \quad \sum F_y = 0
$$

## Final Result

$$
F_{\text{net}} = 0
$$

## Interpretation

The symmetry of the configuration ensures that forces cancel exactly. The charge at the center experiences no net force.

---

# Task 02 – Electric Potential

## Problem Statement

Charges $+1\,\text{C}, -2\,\text{C}, +3\,\text{C}, -4\,\text{C}$ are placed at the corners of a square. Determine the electric potential at the center.

## Theory

Electric potential:

$$
V = k \sum \frac{q_i}{r_i}
$$

## Step-by-Step Solution

All distances are equal:

$$
r = \frac{\sqrt{2}}{2}
$$

Sum of charges:

$$
q_{\text{total}} = 1 - 2 + 3 - 4 = -2
$$

Potential:

$$
V = k \frac{-2}{r} = -2k \cdot \frac{2}{\sqrt{2}} = -2\sqrt{2}k
$$

## Final Result

$$
V = -2\sqrt{2} \cdot 9 \times 10^9 \approx -2.54 \times 10^{10} \,\text{V}
$$

## Interpretation

Potential depends on algebraic sum of charges. Negative result indicates dominance of negative charges.

---

# Task 03 – Electrostatic Equilibrium

## Problem Statement

Find the equilibrium position of $q_3 = +1\,\text{C}$ between $q_1 = +4\,\text{C}$ and $q_2 = +9\,\text{C}$ separated by 2 m.

## Theory

Equilibrium condition:

$$
F_1 = F_2
$$

## Step-by-Step Solution

Let distance from $q_1$ be $x$, from $q_2$ be $2-x$:

$$
k \frac{4}{x^2} = k \frac{9}{(2-x)^2}
$$

$$
\frac{2}{x} = \frac{3}{2-x}
$$

$$
2(2-x) = 3x
$$

$$
4 - 2x = 3x
$$

$$
x = \frac{4}{5} = 0.8\,\text{m}
$$

## Final Result

$$
x = 0.8\,\text{m from } q_1
$$

## Interpretation

The equilibrium point lies closer to the smaller charge.

---

# Task 04 – Force Comparison

## Problem Statement

Compare electric and gravitational forces between an electron and a proton.

## Theory

$$
F_e = k \frac{e^2}{r^2}, \quad F_g = G \frac{m_e m_p}{r^2}
$$

## Step-by-Step Solution

Ratio:

$$
\frac{F_e}{F_g} = \frac{k e^2}{G m_e m_p}
$$

Substitute:

$$
\frac{F_e}{F_g} \approx 2.3 \times 10^{39}
$$

## Final Result

$$
F_e \gg F_g
$$

## Interpretation

Electromagnetic force dominates gravity at atomic scales.

---

# Task 05 – Field Levitation

## Problem Statement

Find the electric field required to levitate a proton.

## Theory

Force balance:

$$
qE = mg
$$

## Step-by-Step Solution

$$
E = \frac{mg}{q}
$$

$$
E = \frac{1.67 \times 10^{-27} \cdot 9.8}{1.6 \times 10^{-19}}
$$

$$
E \approx 1.02 \times 10^{-7} \,\text{N/C}
$$

## Final Result

$$
E \approx 1.0 \times 10^{-7} \,\text{N/C}
$$

## Interpretation

A very small electric field can counteract gravity for microscopic particles.

---

# Task 06 – Field of Two Charges

## Problem Statement

Two charges:

- $+q$ at $(-a,0)$  
- $+2q$ at $(a,0)$  

## Theory

Electric field:

$$
\vec{E} = k \frac{q}{r^3} \vec{r}
$$

## Step-by-Step Solution

General form:

$$
\vec{E}(x,y) = k \left[ \frac{q (x+a, y)}{((x+a)^2+y^2)^{3/2}} + \frac{2q (x-a, y)}{((x-a)^2+y^2)^{3/2}} \right]
$$

At $(0,y)$:

$$
E_x = kq \left( \frac{a}{(a^2+y^2)^{3/2}} - \frac{2a}{(a^2+y^2)^{3/2}} \right)
$$

$$
E_y = kq \left( \frac{y}{(a^2+y^2)^{3/2}} + \frac{2y}{(a^2+y^2)^{3/2}} \right)
$$

## Final Result

$$
E_x = -\frac{kqa}{(a^2+y^2)^{3/2}}, \quad E_y = \frac{3kqy}{(a^2+y^2)^{3/2}}
$$

## Interpretation

Field asymmetry arises due to unequal charges.

---

# Task 07 – Cyclotron Motion

## Problem Statement

Electron accelerated through 5000 V enters magnetic field $B = 0.1\,\text{T}$.

## Theory

$$
\frac{1}{2}mv^2 = eV, \quad r = \frac{mv}{eB}
$$

## Step-by-Step Solution

$$
v = \sqrt{\frac{2eV}{m}}
$$

$$
r = \frac{m}{eB} \sqrt{\frac{2eV}{m}}
$$

## Final Result

$$
r \approx 7.5 \times 10^{-3}\,\text{m}
$$

## Interpretation

Higher voltage increases radius due to higher velocity.

---

# Task 08 – Lorentz Force

## Problem Statement

Charge moves perpendicular to magnetic field.

## Theory

$$
F = qvB
$$

## Step-by-Step Solution

$$
F = 2 \times 10^{-19} \cdot 10^6 \cdot 0.5
$$

$$
F = 1 \times 10^{-13}\,\text{N}
$$

## Final Result

$$
F = 1.0 \times 10^{-13}\,\text{N}
$$

## Interpretation

Magnetic forces at particle level are small but significant for motion.

---

# Task 09 – Vector Lorentz Force

## Problem Statement

Find magnetic force magnitude.

## Theory

$$
\vec{F} = q \vec{v} \times \vec{B}
$$

## Step-by-Step Solution

Compute cross product:

$$
\vec{v} \times \vec{B} =
\begin{pmatrix}
2 & -4 & 1 \\
1 & 2 & -1
\end{pmatrix}
\Rightarrow (2, 3, 8)
$$

Magnitude:

$$
|\vec{F}| = q \sqrt{2^2 + 3^2 + 8^2}
$$

$$
|\vec{F}| = q \sqrt{77}
$$

## Final Result

$$
|\vec{F}| = (1.6 \times 10^{-19}) \sqrt{77}
$$

## Interpretation

Force depends on perpendicular components of velocity and field.

---

# Task 10 – Force on Wire

## Problem Statement

Wire in magnetic field.

## Theory

$$
F = BIL \sin \theta
$$

## Step-by-Step Solution

$$
F = 0.5 \cdot 10 \cdot 2 \sin \theta = 10 \sin \theta
$$

Cases:

a) $90^\circ$

$$
F = 10\,\text{N}
$$

b) $45^\circ$

$$
F = 10 \cdot \frac{\sqrt{2}}{2} \approx 7.07\,\text{N}
$$

c) $0^\circ$

$$
F = 0
$$

## Final Result

- $10\,\text{N}$  
- $7.07\,\text{N}$  
- $0$

## Interpretation

Magnetic force depends on orientation; maximum when perpendicular.