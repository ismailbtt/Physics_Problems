# Section 4 – Electromagnetism I

## Contents

1. Coulomb's Law
2. Electric Potential
3. Electrostatic Equilibrium
4. Force Comparison
5. Field Levitation
6. Field at a Point from a System of Charges
7. Cyclotron Motion
8. Lorentz Force
9. Vector Lorentz Force
10. Lorentz Force Acting on a Wire

---

# Task 01 – Coulomb's Law

## Problem Statement

Four point charges of $+1.0\,\mathrm{C}$ are placed at the corners of a square of side $1.0\,\mathrm{m}$. Determine the magnitude and direction of the electric force acting on a charge of $-2.0\,\mathrm{C}$ placed at the center of the square.

## Theory

The electric force between two point charges is given by Coulomb's law:

$$
F = k \frac{|q_1 q_2|}{r^2}
$$

where

- $k = 8.99 \times 10^9\,\mathrm{N\,m^2/C^2}$
- $q_1$ and $q_2$ are the charges
- $r$ is the distance between them

The electric field at the center due to a symmetric configuration of identical charges can cancel by vector addition.

## Step-by-Step Solution

The square has side length

$$
a = 1.0\,\mathrm{m}
$$

The distance from the center of the square to any corner is half the diagonal:

$$
r = \frac{a\sqrt{2}}{2} = \frac{1.0\sqrt{2}}{2} = \frac{1}{\sqrt{2}}\,\mathrm{m}
$$

Each corner charge produces an electric field at the center directed along the line from the charge to the center. Since all four corner charges are equal and placed symmetrically, the fields cancel pairwise.

Therefore, the net electric field at the center is

$$
\vec E_{\text{net}} = \vec 0
$$

The force on the central charge is

$$
\vec F = q \vec E_{\text{net}}
$$

Thus,

$$
\vec F = (-2.0\,\mathrm{C}) \cdot \vec 0 = \vec 0
$$

## Final Result

The magnitude of the electric force is

$$
F = 0\,\mathrm{N}
$$

The direction is undefined, because the net force is zero.

## Interpretation

Although each corner charge individually attracts the negative charge at the center, the arrangement is perfectly symmetric. The forces balance exactly, so no net motion occurs.

---

# Task 02 – Electric Potential

## Problem Statement

Point charges of $+1\,\mathrm{C}$, $-2\,\mathrm{C}$, $+3\,\mathrm{C}$, and $-4\,\mathrm{C}$ are placed at the corners of a square of side $1.0\,\mathrm{m}$ in that order. Determine the electric potential at the center of the square.

## Theory

The electric potential due to a point charge is

$$
V = k \frac{q}{r}
$$

Electric potential is a scalar quantity, so the total potential is the algebraic sum of the contributions from all charges:

$$
V_{\text{net}} = \sum_i k \frac{q_i}{r_i}
$$

## Step-by-Step Solution

All four charges are at the same distance from the center. For a square of side $a = 1.0\,\mathrm{m}$, that distance is

$$
r = \frac{a\sqrt{2}}{2} = \frac{1}{\sqrt{2}}\,\mathrm{m}
$$

The sum of the charges is

$$
q_{\text{tot}} = 1 - 2 + 3 - 4 = -2\,\mathrm{C}
$$

Therefore, the potential at the center is

$$
V = k \frac{q_{\text{tot}}}{r}
$$

Substituting $r = 1/\sqrt{2}$ gives

$$
V = k \frac{-2}{1/\sqrt{2}} = -2\sqrt{2}\,k
$$

Now insert the value of $k$:

$$
V = -2\sqrt{2}(8.99 \times 10^9)\,\mathrm{V}
$$

$$
V \approx -2.54 \times 10^{10}\,\mathrm{V}
$$

## Final Result

The electric potential at the center is

$$
V \approx -2.54 \times 10^{10}\,\mathrm{V}
$$

## Interpretation

The potential is negative because the total algebraic charge contribution is negative. Since potential is a scalar, only the charge values and distances matter, not the directions from the center.

---

# Task 03 – Electrostatic Equilibrium

## Problem Statement

Two positive charges, $q_1 = +4\,\mathrm{C}$ and $q_2 = +9\,\mathrm{C}$, are separated by a distance of $2\,\mathrm{m}$. Find the equilibrium position of a third charge $q_3 = +1\,\mathrm{C}$ placed on the line joining them.

## Theory

For equilibrium, the net force on $q_3$ must vanish:

$$
\vec F_{\text{net}} = \vec 0
$$

Because all charges are positive, the third charge is repelled by both fixed charges. Between the two charges, these repulsive forces act in opposite directions, so equilibrium is possible there.

Using Coulomb's law, the magnitudes of the two forces must be equal.

## Step-by-Step Solution

Let the equilibrium point lie between the charges, at distance $x$ from $q_1 = +4\,\mathrm{C}$. Then the distance from $q_2 = +9\,\mathrm{C}$ is

$$
2 - x
$$

The force due to $q_1$ on $q_3$ is

$$
F_1 = k \frac{q_1 q_3}{x^2}
$$

The force due to $q_2$ on $q_3$ is

$$
F_2 = k \frac{q_2 q_3}{(2-x)^2}
$$

Equilibrium requires

$$
F_1 = F_2
$$

Thus,

$$
k \frac{q_1 q_3}{x^2} = k \frac{q_2 q_3}{(2-x)^2}
$$

Canceling $k$ and $q_3$ gives

$$
\frac{4}{x^2} = \frac{9}{(2-x)^2}
$$

Taking the square root of both sides:

$$
\frac{2}{x} = \frac{3}{2-x}
$$

Cross-multiplication gives

$$
2(2-x) = 3x
$$

$$
4 - 2x = 3x
$$

$$
4 = 5x
$$

$$
x = 0.8\,\mathrm{m}
$$

## Final Result

The equilibrium position is

$$
x = 0.8\,\mathrm{m}
$$

from the $+4\,\mathrm{C}$ charge, which is also

$$
2 - x = 1.2\,\mathrm{m}
$$

from the $+9\,\mathrm{C}$ charge.

## Interpretation

The equilibrium point lies closer to the smaller charge. This is necessary because the stronger charge $+9\,\mathrm{C}$ must act from a greater distance in order for the two repulsive forces to balance.

---

# Task 04 – Force Comparison

## Problem Statement

Calculate the magnitude of the electric force and the gravitational force between an electron and a proton in a hydrogen atom, assuming the average separation is

$$
r \approx 5.3 \times 10^{-11}\,\mathrm{m}
$$

Also determine the ratio

$$
\frac{F_e}{F_g}
$$

## Theory

The electric force between an electron and a proton is

$$
F_e = k \frac{e^2}{r^2}
$$

The gravitational force between them is

$$
F_g = G \frac{m_e m_p}{r^2}
$$

where

- $e = 1.60 \times 10^{-19}\,\mathrm{C}$
- $m_e = 9.11 \times 10^{-31}\,\mathrm{kg}$
- $m_p = 1.67 \times 10^{-27}\,\mathrm{kg}$
- $k = 8.99 \times 10^9\,\mathrm{N\,m^2/C^2}$
- $G = 6.67 \times 10^{-11}\,\mathrm{N\,m^2/kg^2}$

## Step-by-Step Solution

### Electric force

$$
F_e = k \frac{e^2}{r^2}
$$

Substitute the values:

$$
F_e = 8.99 \times 10^9 \cdot \frac{(1.60 \times 10^{-19})^2}{(5.3 \times 10^{-11})^2}
$$

Compute the numerator:

$$
(1.60 \times 10^{-19})^2 = 2.56 \times 10^{-38}
$$

Compute the denominator:

$$
(5.3 \times 10^{-11})^2 = 2.809 \times 10^{-21}
$$

Therefore,

$$
F_e = 8.99 \times 10^9 \cdot \frac{2.56 \times 10^{-38}}{2.809 \times 10^{-21}}
$$

$$
F_e \approx 8.2 \times 10^{-8}\,\mathrm{N}
$$

### Gravitational force

$$
F_g = G \frac{m_e m_p}{r^2}
$$

Substitute the values:

$$
F_g = 6.67 \times 10^{-11} \cdot \frac{(9.11 \times 10^{-31})(1.67 \times 10^{-27})}{(5.3 \times 10^{-11})^2}
$$

First compute the mass product:

$$
(9.11 \times 10^{-31})(1.67 \times 10^{-27}) \approx 1.52 \times 10^{-57}
$$

Thus,

$$
F_g = 6.67 \times 10^{-11} \cdot \frac{1.52 \times 10^{-57}}{2.809 \times 10^{-21}}
$$

$$
F_g \approx 3.6 \times 10^{-47}\,\mathrm{N}
$$

### Ratio of forces

$$
\frac{F_e}{F_g} = \frac{k e^2 / r^2}{G m_e m_p / r^2}
$$

The factor $r^2$ cancels:

$$
\frac{F_e}{F_g} = \frac{k e^2}{G m_e m_p}
$$

Substituting the constants gives

$$
\frac{F_e}{F_g} \approx 2.3 \times 10^{39}
$$

## Final Result

The electric force is

$$
F_e \approx 8.2 \times 10^{-8}\,\mathrm{N}
$$

The gravitational force is

$$
F_g \approx 3.6 \times 10^{-47}\,\mathrm{N}
$$

The ratio is

$$
\frac{F_e}{F_g} \approx 2.3 \times 10^{39}
$$

## Interpretation

At atomic scales, the electric interaction between charged particles is overwhelmingly stronger than gravity. In the hydrogen atom, the electric force exceeds the gravitational force by about $39$ orders of magnitude.

---

# Task 05 – Field Levitation

## Problem Statement

Determine the electric field strength required to make a proton levitate against Earth's gravity near the Earth's surface.

Given:

- $m_p \approx 1.67 \times 10^{-27}\,\mathrm{kg}$
- $e \approx 1.6 \times 10^{-19}\,\mathrm{C}$
- $g \approx 9.8\,\mathrm{m/s^2}$

## Theory

A proton levitates when the upward electric force balances the downward gravitational force.

The electric force is

$$
F_e = qE
$$

The gravitational force is

$$
F_g = mg
$$

For equilibrium:

$$
qE = mg
$$

Thus,

$$
E = \frac{mg}{q}
$$

## Step-by-Step Solution

For a proton, the charge is

$$
q = e = 1.6 \times 10^{-19}\,\mathrm{C}
$$

Therefore,

$$
E = \frac{m_p g}{e}
$$

Substitute the values:

$$
E = \frac{(1.67 \times 10^{-27})(9.8)}{1.6 \times 10^{-19}}
$$

Compute the numerator:

$$
1.67 \times 10^{-27} \cdot 9.8 = 1.6366 \times 10^{-26}
$$

Then

$$
E = \frac{1.6366 \times 10^{-26}}{1.6 \times 10^{-19}}
$$

$$
E \approx 1.02 \times 10^{-7}\,\mathrm{N/C}
$$

## Final Result

The required electric field strength is

$$
E \approx 1.0 \times 10^{-7}\,\mathrm{N/C}
$$

The field must point upward so that the electric force on the positive proton is upward.

## Interpretation

Because the proton has extremely small mass, only a very weak electric field is needed to balance its weight. This illustrates how easily electric forces can dominate gravitational forces for elementary particles.

---

# Task 06 – Field at a Point from a System of Charges

## Problem Statement

Two point charges are given:

- $+q$ at point $(-a,0)$
- $+2q$ at point $(a,0)$

Determine:

1. The field vector $\vec E(0,y)$, $\vec E(x,0)$, and in general $\vec E(x,y)$
2. The conditions for which $E_x = 0$, $E_y = 0$, and $\vec E = 0$
3. The field for $a = 0.2\,\mathrm{m}$, $y = 0.3\,\mathrm{m}$, $q = 2\,\mu\mathrm{C}$
4. The limit $y \gg a$

## Theory

The electric field due to a point charge $Q$ located at position $\vec r_0$ is

$$
\vec E(\vec r) = kQ \frac{\vec r - \vec r_0}{|\vec r - \vec r_0|^3}
$$

The total field from multiple charges is obtained by vector superposition:

$$
\vec E_{\text{net}} = \sum_i \vec E_i
$$

## Step-by-Step Solution

### 1. General field $\vec E(x,y)$

Let the observation point be $(x,y)$.

For the charge $+q$ at $(-a,0)$, the displacement vector from the charge to the point is

$$
\vec r_1 = (x+a)\hat i + y\hat j
$$

with magnitude

$$
r_1 = \sqrt{(x+a)^2 + y^2}
$$

For the charge $+2q$ at $(a,0)$, the displacement vector is

$$
\vec r_2 = (x-a)\hat i + y\hat j
$$

with magnitude

$$
r_2 = \sqrt{(x-a)^2 + y^2}
$$

Thus the total electric field is

$$
\vec E(x,y) = kq \frac{(x+a)\hat i + y\hat j}{\left[(x+a)^2 + y^2\right]^{3/2}} + 2kq \frac{(x-a)\hat i + y\hat j}{\left[(x-a)^2 + y^2\right]^{3/2}}
$$

Therefore, the components are

$$
E_x = kq \frac{x+a}{\left[(x+a)^2 + y^2\right]^{3/2}} + 2kq \frac{x-a}{\left[(x-a)^2 + y^2\right]^{3/2}}
$$

$$
E_y = kq \frac{y}{\left[(x+a)^2 + y^2\right]^{3/2}} + 2kq \frac{y}{\left[(x-a)^2 + y^2\right]^{3/2}}
$$

### 2. Field on the $y$-axis: $\vec E(0,y)$

Set $x = 0$.

Then both distances are equal:

$$
r_1 = r_2 = \sqrt{a^2 + y^2}
$$

Hence

$$
\vec E(0,y) = kq \frac{a\hat i + y\hat j}{(a^2+y^2)^{3/2}} + 2kq \frac{-a\hat i + y\hat j}{(a^2+y^2)^{3/2}}
$$

Combining terms gives

$$
\vec E(0,y) = \frac{kq}{(a^2+y^2)^{3/2}} \left(-a\hat i + 3y\hat j\right)
$$

Thus,

$$
E_x(0,y) = -\frac{kqa}{(a^2+y^2)^{3/2}}
$$

$$
E_y(0,y) = \frac{3kqy}{(a^2+y^2)^{3/2}}
$$

### 3. Field on the $x$-axis: $\vec E(x,0)$

Set $y = 0$.

Then the field has no $y$-component:

$$
E_y(x,0) = 0
$$

The $x$-component is

$$
E_x(x,0) = kq \frac{x+a}{|x+a|^3} + 2kq \frac{x-a}{|x-a|^3}
$$

Therefore,

$$
\vec E(x,0) = \left[kq \frac{x+a}{|x+a|^3} + 2kq \frac{x-a}{|x-a|^3}\right]\hat i
$$

This form automatically includes the correct sign in each spatial region.

### 4. Conditions for $E_y = 0$

From the general expression,

$$
E_y = kq\,y \left[\frac{1}{\left[(x+a)^2+y^2\right]^{3/2}} + \frac{2}{\left[(x-a)^2+y^2\right]^{3/2}}\right]
$$

The bracket is always positive, so the only way to have $E_y = 0$ is

$$
y = 0
$$

Thus, $E_y = 0$ only on the $x$-axis.

### 5. Conditions for $E_x = 0$

In general, $E_x = 0$ must satisfy

$$
\frac{x+a}{\left[(x+a)^2+y^2\right]^{3/2}} + 2\frac{x-a}{\left[(x-a)^2+y^2\right]^{3/2}} = 0
$$

A simple exact solution occurs on the $x$-axis, where $y = 0$. Then

$$
\frac{x+a}{|x+a|^3} + 2\frac{x-a}{|x-a|^3} = 0
$$

The only physical solution lies between the charges, where $-a < x < a$. In that region,

$$
\frac{1}{(x+a)^2} = \frac{2}{(a-x)^2}
$$

Taking square roots:

$$
\frac{1}{x+a} = \frac{\sqrt{2}}{a-x}
$$

Thus,

$$
a - x = \sqrt{2}(x+a)
$$

Solving for $x$:

$$
a - x = \sqrt{2}x + \sqrt{2}a
$$

$$
a(1-\sqrt{2}) = x(1+\sqrt{2})
$$

$$
x = a \frac{1-\sqrt{2}}{1+\sqrt{2}}
$$

A simplified equivalent form is

$$
x = (2\sqrt{2} - 3)a
$$

Since $2\sqrt{2} - 3 \approx -0.1716$, the zero lies slightly to the left of the origin.

### 6. Condition for zero field $\vec E = 0$

For the full field to vanish, both components must vanish simultaneously.

Since $E_y = 0$ requires $y = 0$, the zero-field point must lie on the $x$-axis. Then $E_x = 0$ gives the unique point

$$
x = (2\sqrt{2} - 3)a
$$

Therefore,

$$
\vec E = 0 \quad \text{at} \quad \left((2\sqrt{2}-3)a,\ 0\right)
$$

### 7. Numerical evaluation for $a = 0.2\,\mathrm{m}$, $y = 0.3\,\mathrm{m}$, $q = 2\,\mu\mathrm{C}$

The point specified is $(0,y)$, so use the expression for $\vec E(0,y)$.

First,

$$
q = 2 \times 10^{-6}\,\mathrm{C}
$$

and

$$
a^2 + y^2 = 0.2^2 + 0.3^2 = 0.04 + 0.09 = 0.13
$$

Thus,

$$
(a^2+y^2)^{3/2} = (0.13)^{3/2} \approx 0.0469
$$

Also,

$$
kq = (8.99 \times 10^9)(2 \times 10^{-6}) \approx 1.798 \times 10^4
$$

Now compute the components:

$$
E_x = -\frac{kqa}{(a^2+y^2)^{3/2}} = -\frac{(1.798 \times 10^4)(0.2)}{0.0469}
$$

$$
E_x \approx -7.67 \times 10^4\,\mathrm{N/C}
$$

Similarly,

$$
E_y = \frac{3kqy}{(a^2+y^2)^{3/2}} = \frac{3(1.798 \times 10^4)(0.3)}{0.0469}
$$

$$
E_y \approx 3.45 \times 10^5\,\mathrm{N/C}
$$

Therefore,

$$
\vec E(0,0.3) \approx \left(-7.67 \times 10^4 \hat i + 3.45 \times 10^5 \hat j\right)\,\mathrm{N/C}
$$

Its magnitude is

$$
|\vec E| = \sqrt{E_x^2 + E_y^2}
$$

$$
|\vec E| \approx \sqrt{(7.67 \times 10^4)^2 + (3.45 \times 10^5)^2}
$$

$$
|\vec E| \approx 3.53 \times 10^5\,\mathrm{N/C}
$$

The direction relative to the positive $x$-axis is in the second quadrant. The angle above the negative $x$-axis is

$$
\theta = \tan^{-1}\left(\frac{|E_y|}{|E_x|}\right) \approx \tan^{-1}(4.50) \approx 77.4^\circ
$$

Equivalently, measured from the positive $x$-axis,

$$
\theta \approx 102.6^\circ
$$

### 8. Limit $y \gg a$

From

$$
\vec E(0,y) = \frac{kq}{(a^2+y^2)^{3/2}} \left(-a\hat i + 3y\hat j\right)
$$

if $y \gg a$, then

$$
(a^2+y^2)^{3/2} \approx y^3
$$

Hence

$$
\vec E(0,y) \approx kq \left(-\frac{a}{y^3}\hat i + \frac{3}{y^2}\hat j\right)
$$

The dominant term is

$$
\vec E(0,y) \approx \frac{3kq}{y^2}\hat j
$$

## Final Result

The general field is

$$
\vec E(x,y) = kq \frac{(x+a)\hat i + y\hat j}{\left[(x+a)^2 + y^2\right]^{3/2}} + 2kq \frac{(x-a)\hat i + y\hat j}{\left[(x-a)^2 + y^2\right]^{3/2}}
$$

On the $y$-axis,

$$
\vec E(0,y) = \frac{kq}{(a^2+y^2)^{3/2}} \left(-a\hat i + 3y\hat j\right)
$$

On the $x$-axis,

$$
\vec E(x,0) = \left[kq \frac{x+a}{|x+a|^3} + 2kq \frac{x-a}{|x-a|^3}\right]\hat i
$$

The zero-field point is

$$
\left((2\sqrt{2}-3)a,\ 0\right)
$$

For $a = 0.2\,\mathrm{m}$, $y = 0.3\,\mathrm{m}$, $q = 2\,\mu\mathrm{C}$,

$$
\vec E \approx \left(-7.67 \times 10^4 \hat i + 3.45 \times 10^5 \hat j\right)\,\mathrm{N/C}
$$

with magnitude

$$
|\vec E| \approx 3.53 \times 10^5\,\mathrm{N/C}
$$

## Interpretation

Far from the two charges, the field behaves mainly like the field of a single total charge $3q$ located near the origin, with a smaller horizontal correction reflecting the asymmetry of the charge distribution.

---

# Task 07 – Cyclotron Motion

## Problem Statement

An electron is accelerated from rest through a potential difference of $5000\,\mathrm{V}$. It then enters a region of uniform magnetic field $B = 0.1\,\mathrm{T}$ perpendicular to its velocity. Determine the radius of its circular path.

## Theory

A charged particle accelerated through a potential difference $V$ gains kinetic energy

$$
qV = \frac{1}{2}mv^2
$$

When it enters a magnetic field perpendicular to its velocity, the magnetic force provides the centripetal force:

$$
qvB = \frac{mv^2}{r}
$$

Thus,

$$
r = \frac{mv}{qB}
$$

## Step-by-Step Solution

### 1. Determine the speed after acceleration

Since the electron starts from rest,

$$
eV = \frac{1}{2}m_ev^2
$$

Solve for $v$:

$$
v = \sqrt{\frac{2eV}{m_e}}
$$

Substitute the values:

- $e = 1.60 \times 10^{-19}\,\mathrm{C}$
- $m_e = 9.11 \times 10^{-31}\,\mathrm{kg}$
- $V = 5000\,\mathrm{V}$

$$
v = \sqrt{\frac{2(1.60 \times 10^{-19})(5000)}{9.11 \times 10^{-31}}}
$$

$$
v \approx 4.19 \times 10^7\,\mathrm{m/s}
$$

### 2. Determine the radius

Now use

$$
r = \frac{m_ev}{eB}
$$

Substitute:

$$
r = \frac{(9.11 \times 10^{-31})(4.19 \times 10^7)}{(1.60 \times 10^{-19})(0.1)}
$$

$$
r \approx 2.38 \times 10^{-3}\,\mathrm{m}
$$

## Final Result

The radius of the circular path is

$$
r \approx 2.4 \times 10^{-3}\,\mathrm{m}
$$

## Interpretation

The electron follows a very small circular path because its mass is tiny. Even a moderate magnetic field can strongly bend the trajectory of a light charged particle.

---

# Task 08 – Lorentz Force

## Problem Statement

A charged particle with charge

$$
q = 2 \times 10^{-19}\,\mathrm{C}
$$

and mass

$$
m = 4 \times 10^{-27}\,\mathrm{kg}
$$

enters a magnetic field of

$$
B = 0.5\,\mathrm{T}
$$

with speed

$$
v = 10^6\,\mathrm{m/s}
$$

perpendicular to the field. Determine the magnitude of the Lorentz force.

## Theory

The magnetic part of the Lorentz force is

$$
F = qvB\sin\theta
$$

If the velocity is perpendicular to the magnetic field, then

$$
\theta = 90^\circ
$$

and

$$
\sin 90^\circ = 1
$$

Thus,

$$
F = qvB
$$

## Step-by-Step Solution

Substitute the given values:

$$
F = (2 \times 10^{-19})(10^6)(0.5)
$$

First multiply the numerical factors:

$$
2 \cdot 0.5 = 1
$$

Thus,

$$
F = 1 \times 10^{-19+6} = 1 \times 10^{-13}\,\mathrm{N}
$$

## Final Result

The magnitude of the Lorentz force is

$$
F = 1.0 \times 10^{-13}\,\mathrm{N}
$$

## Interpretation

Since the motion is perpendicular to the magnetic field, the magnetic force is maximal. This force changes the direction of motion but does not change the particle's speed.

---

# Task 09 – Vector Lorentz Force

## Problem Statement

A proton moves with velocity

$$
\vec v = (2\hat i - 4\hat j + \hat k)\,\mathrm{m/s}
$$

in a region where the magnetic field is

$$
\vec B = (\hat i + 2\hat j - \hat k)\,\mathrm{T}
$$

Determine the magnitude of the magnetic force experienced by the proton.

## Theory

The magnetic force on a charged particle is

$$
\vec F = q\,\vec v \times \vec B
$$

Its magnitude is

$$
|\vec F| = q\,|\vec v \times \vec B|
$$

For a proton,

$$
q = e = 1.60 \times 10^{-19}\,\mathrm{C}
$$

## Step-by-Step Solution

Compute the cross product:

$$
\vec v \times \vec B =
\begin{pmatrix}
\hat i & \hat j & \hat k \\
2 & -4 & 1 \\
1 & 2 & -1 \\
\end{pmatrix}
$$

Expanding by components:

$$
\vec v \times \vec B =
\left[(-4)(-1) - (1)(2)\right]\hat i
-
\left[(2)(-1) - (1)(1)\right]\hat j
+
\left[(2)(2) - (-4)(1)\right]\hat k
$$

$$
\vec v \times \vec B = (4 - 2)\hat i - (-2 - 1)\hat j + (4 + 4)\hat k
$$

$$
\vec v \times \vec B = 2\hat i + 3\hat j + 8\hat k
$$

Now compute its magnitude:

$$
|\vec v \times \vec B| = \sqrt{2^2 + 3^2 + 8^2}
$$

$$
|\vec v \times \vec B| = \sqrt{4 + 9 + 64} = \sqrt{77}
$$

$$
|\vec v \times \vec B| \approx 8.77
$$

Therefore,

$$
|\vec F| = e\sqrt{77}
$$

$$
|\vec F| = (1.60 \times 10^{-19})(8.77)
$$

$$
|\vec F| \approx 1.40 \times 10^{-18}\,\mathrm{N}
$$

## Final Result

The magnitude of the magnetic force is

$$
|\vec F| \approx 1.4 \times 10^{-18}\,\mathrm{N}
$$

## Interpretation

The force depends on the vector product, so only the component of motion perpendicular to the magnetic field contributes. Even though the speed components are small in SI units, the magnetic interaction is nonzero because $\vec v$ and $\vec B$ are not parallel.

---

# Task 10 – Lorentz Force Acting on a Wire

## Problem Statement

A straight wire of length $2.0\,\mathrm{m}$ carries a current of $10\,\mathrm{A}$ and is placed in a uniform magnetic field of magnitude $0.5\,\mathrm{T}$. Determine the magnetic force on the wire when the angle between the wire and the magnetic field is:

a) $90^\circ$

b) $45^\circ$

c) $0^\circ$

## Theory

The magnetic force on a straight current-carrying wire in a uniform magnetic field is

$$
F = ILB\sin\theta
$$

where

- $I$ is the current
- $L$ is the wire length
- $B$ is the magnetic field
- $\theta$ is the angle between the wire and the field

## Step-by-Step Solution

Given:

$$
I = 10\,\mathrm{A}
$$

$$
L = 2.0\,\mathrm{m}
$$

$$
B = 0.5\,\mathrm{T}
$$

Thus,

$$
ILB = 10 \cdot 2.0 \cdot 0.5 = 10
$$

So the force becomes

$$
F = 10\sin\theta
$$

### a) $\theta = 90^\circ$

$$
F = 10\sin 90^\circ
$$

$$
F = 10 \cdot 1 = 10\,\mathrm{N}
$$

### b) $\theta = 45^\circ$

$$
F = 10\sin 45^\circ
$$

Since

$$
\sin 45^\circ = \frac{\sqrt{2}}{2}
$$

then

$$
F = 10 \cdot \frac{\sqrt{2}}{2}
$$

$$
F \approx 7.07\,\mathrm{N}
$$

### c) $\theta = 0^\circ$

$$
F = 10\sin 0^\circ
$$

$$
F = 10 \cdot 0 = 0\,\mathrm{N}
$$

## Final Result

The magnetic force on the wire is

### a) For $90^\circ$

$$
F = 10\,\mathrm{N}
$$

### b) For $45^\circ$

$$
F \approx 7.1\,\mathrm{N}
$$

### c) For $0^\circ$

$$
F = 0\,\mathrm{N}
$$

## Interpretation

The magnetic force on a wire depends on orientation. It is maximum when the wire is perpendicular to the magnetic field and zero when the wire is parallel to the field.