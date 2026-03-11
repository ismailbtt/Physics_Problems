# Section 0: Mathematical Foundations

# Problem Set 01 – Solutions

# Task 01 – Vector Algebra in Three Dimensions

## Problem Statement

Given two vectors in three-dimensional space,

$$
\vec{a} = \begin{pmatrix}
2 \\
1 \\
-3
\end{pmatrix}
\qquad
\vec{b} = \begin{pmatrix}
4 \\
-2 \\
1
\end{pmatrix}
$$

determine:

1. the magnitude of each vector,
2. the dot product $ \vec{a} \cdot \vec{b} $,
3. the cross product $ \vec{a} \times \vec{b} $,
4. the angle between the two vectors.

## Theory

For a vector

$$
\vec{v} = \begin{pmatrix}
v_1 \\
v_2 \\
v_3
\end{pmatrix}
$$

its magnitude is

$$
|\vec{v}| = \sqrt{v_1^2 + v_2^2 + v_3^2}
$$

The dot product of two vectors is

$$
\vec{a} \cdot \vec{b} = a_1 b_1 + a_2 b_2 + a_3 b_3
$$

The cross product in three dimensions is

$$
\vec{a} \times \vec{b} =
\begin{pmatrix}
a_2 b_3 - a_3 b_2 \\
a_3 b_1 - a_1 b_3 \\
a_1 b_2 - a_2 b_1
\end{pmatrix}
$$

The angle $ \theta $ between two vectors satisfies

$$
\cos \theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|}
$$

## Step-by-Step Solution

### 1. Magnitudes of the vectors

For $ \vec{a} = (2,1,-3) $,

$$
|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2}
$$

$$
|\vec{a}| = \sqrt{4 + 1 + 9}
$$

$$
|\vec{a}| = \sqrt{14}
$$

For $ \vec{b} = (4,-2,1) $,

$$
|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2}
$$

$$
|\vec{b}| = \sqrt{16 + 4 + 1}
$$

$$
|\vec{b}| = \sqrt{21}
$$

### 2. Dot product

$$
\vec{a} \cdot \vec{b} = 2 \cdot 4 + 1 \cdot (-2) + (-3) \cdot 1
$$

$$
\vec{a} \cdot \vec{b} = 8 - 2 - 3
$$

$$
\vec{a} \cdot \vec{b} = 3
$$

### 3. Cross product

Using the component formula,

$$
\vec{a} \times \vec{b} =
\begin{pmatrix}
1 \cdot 1 - (-3)(-2) \\
(-3)\cdot 4 - 2 \cdot 1 \\
2 \cdot (-2) - 1 \cdot 4
\end{pmatrix}
$$

$$
\vec{a} \times \vec{b} =
\begin{pmatrix}
1 - 6 \\
-12 - 2 \\
-4 - 4
\end{pmatrix}
$$

$$
\vec{a} \times \vec{b} =
\begin{pmatrix}
-5 \\
-14 \\
-8
\end{pmatrix}
$$

### 4. Angle between the vectors

From the dot product relation,

$$
\cos \theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|}
$$

Substituting the values,

$$
\cos \theta = \frac{3}{\sqrt{14}\sqrt{21}}
$$

$$
\cos \theta = \frac{3}{\sqrt{294}}
$$

Therefore,

$$
\theta = \cos^{-1}\left(\frac{3}{\sqrt{294}}\right)
$$

Numerically,

$$
\theta \approx 79.9^\circ
$$

## Final Result

$$
|\vec{a}| = \sqrt{14}
$$

$$
|\vec{b}| = \sqrt{21}
$$

$$
\vec{a} \cdot \vec{b} = 3
$$

$$
\vec{a} \times \vec{b} =
\begin{pmatrix}
-5 \\
-14 \\
-8
\end{pmatrix}
$$

$$
\theta = \cos^{-1}\left(\frac{3}{\sqrt{294}}\right) \approx 79.9^\circ
$$

## Interpretation

The positive dot product shows that the angle between the vectors is less than $90^\circ$, so the vectors point partly in the same general direction. The cross product gives a vector perpendicular to both original vectors, with direction determined by the right-hand rule.

---

# Task 02 – Solving a System of Two Linear Equations

## Problem Statement

Find the values of $x$ and $y$ satisfying the system

$$
2x + 3y = 12
$$

and

$$
x - y = 1
$$

## Theory

A system of two linear equations can be solved by substitution or elimination. The goal is to find values of the variables that satisfy both equations simultaneously.

## Step-by-Step Solution

From the second equation,

$$
x - y = 1
$$

solve for $x$:

$$
x = y + 1
$$

Substitute this expression into the first equation:

$$
2(y + 1) + 3y = 12
$$

Expand:

$$
2y + 2 + 3y = 12
$$

Combine like terms:

$$
5y + 2 = 12
$$

Subtract $2$ from both sides:

$$
5y = 10
$$

Hence,

$$
y = 2
$$

Now substitute into

$$
x = y + 1
$$

to obtain

$$
x = 2 + 1 = 3
$$

## Final Result

$$
x = 3
\qquad
y = 2
$$

## Interpretation

The ordered pair $ (3,2) $ is the unique intersection point of the two straight lines represented by the equations.

---

# Task 03 – Proportionality in the Law of Gravitation

## Problem Statement

The gravitational force between two masses is given by

$$
F = G \frac{m_1 m_2}{r^2}
$$

Determine the factor by which the force changes if:

1. the distance $r$ is doubled,
2. both masses $m_1$ and $m_2$ are halved.

## Theory

In proportional reasoning, the dependence of a quantity on each variable can be tracked separately.

From the formula,

$$
F \propto \frac{m_1 m_2}{r^2}
$$

This means:

- halving one mass multiplies the force by $ \frac{1}{2} $,
- halving both masses multiplies the force by $ \frac{1}{4} $,
- doubling the distance multiplies the force by $ \frac{1}{2^2} = \frac{1}{4} $.

The total effect is the product of these factors.

## Step-by-Step Solution

Let the original force be

$$
F = G \frac{m_1 m_2}{r^2}
$$

After the change,

$$
m_1' = \frac{m_1}{2}
\qquad
m_2' = \frac{m_2}{2}
\qquad
r' = 2r
$$

The new force is

$$
F' = G \frac{m_1' m_2'}{(r')^2}
$$

Substitute the changed quantities:

$$
F' = G \frac{\left(\frac{m_1}{2}\right)\left(\frac{m_2}{2}\right)}{(2r)^2}
$$

Simplify the numerator:

$$
F' = G \frac{\frac{m_1 m_2}{4}}{4r^2}
$$

$$
F' = G \frac{m_1 m_2}{16r^2}
$$

Compare with the original formula:

$$
F = G \frac{m_1 m_2}{r^2}
$$

Thus,

$$
F' = \frac{1}{16} F
$$

## Final Result

The gravitational force becomes

$$
\frac{1}{16}
$$

of its original value.

## Interpretation

The force decreases strongly because both changes reduce the force: halving the masses reduces it by a factor of $4$, and doubling the distance reduces it by another factor of $4$. Combined, the force is reduced by a factor of $16$.

---

# Task 04 – Rearranging the Pendulum Formula

## Problem Statement

The period of a simple pendulum is

$$
T = 2\pi \sqrt{\frac{L}{g}}
$$

Rearrange the equation to make $g$ the subject.

## Theory

To isolate a variable in an equation containing a square root, the standard procedure is:

1. divide away multiplicative constants,
2. square both sides,
3. solve algebraically for the desired variable.

## Step-by-Step Solution

Start from

$$
T = 2\pi \sqrt{\frac{L}{g}}
$$

Divide both sides by $2\pi$:

$$
\frac{T}{2\pi} = \sqrt{\frac{L}{g}}
$$

Square both sides:

$$
\left(\frac{T}{2\pi}\right)^2 = \frac{L}{g}
$$

Rewrite the left-hand side:

$$
\frac{T^2}{4\pi^2} = \frac{L}{g}
$$

Now solve for $g$. Multiply both sides by $g$:

$$
g \frac{T^2}{4\pi^2} = L
$$

Multiply both sides by $ \frac{4\pi^2}{T^2} $:

$$
g = \frac{4\pi^2 L}{T^2}
$$

## Final Result

$$
g = \frac{4\pi^2 L}{T^2}
$$

## Interpretation

The acceleration due to gravity is directly proportional to the pendulum length and inversely proportional to the square of the period. A longer period corresponds to a smaller value of $g$ if the length is unchanged.

---

# Task 05 – Trigonometric Components of a Vector

## Problem Statement

A vector $ \vec{A} $ has magnitude $15$ and makes an angle of $60^\circ$ with the horizontal axis. Determine its horizontal and vertical components.

## Theory

For a vector of magnitude $A$ making an angle $ \theta $ with the positive horizontal axis,

$$
A_x = A \cos \theta
$$

and

$$
A_y = A \sin \theta
$$

These formulas decompose the vector into perpendicular components.

## Step-by-Step Solution

Given

$$
A = 15
\qquad
\theta = 60^\circ
$$

### Horizontal component

$$
A_x = 15 \cos 60^\circ
$$

Since

$$
\cos 60^\circ = \frac{1}{2}
$$

it follows that

$$
A_x = 15 \cdot \frac{1}{2} = \frac{15}{2}
$$

$$
A_x = 7.5
$$

### Vertical component

$$
A_y = 15 \sin 60^\circ
$$

Since

$$
\sin 60^\circ = \frac{\sqrt{3}}{2}
$$

it follows that

$$
A_y = 15 \cdot \frac{\sqrt{3}}{2}
$$

$$
A_y = \frac{15\sqrt{3}}{2}
$$

Numerically,

$$
A_y \approx 12.99
$$

## Final Result

$$
A_x = 7.5
$$

$$
A_y = \frac{15\sqrt{3}}{2} \approx 12.99
$$

## Interpretation

The vector has a relatively small horizontal component and a larger vertical component because the angle $60^\circ$ is closer to the vertical direction than to the horizontal.

---

# Task 06 – Local Extrema of a Quadratic Function

## Problem Statement

Consider the function

$$
f(x) = 3x^2 - 12x + 7
$$

Determine whether the function has a local maximum or local minimum, and find its location.

## Theory

A quadratic function of the form

$$
f(x) = ax^2 + bx + c
$$

has a turning point at

$$
x = -\frac{b}{2a}
$$

If $a > 0$, the parabola opens upward and the turning point is a minimum. If $a < 0$, it opens downward and the turning point is a maximum.

The same result follows from calculus:

$$
f'(x) = 0
$$

locates critical points, and

$$
f''(x)
$$

determines whether the point is a minimum or maximum.

## Step-by-Step Solution

Given

$$
f(x) = 3x^2 - 12x + 7
$$

Differentiate:

$$
f'(x) = 6x - 12
$$

Set the derivative equal to zero:

$$
6x - 12 = 0
$$

$$
6x = 12
$$

$$
x = 2
$$

Now evaluate the function at $x = 2$:

$$
f(2) = 3(2)^2 - 12(2) + 7
$$

$$
f(2) = 3 \cdot 4 - 24 + 7
$$

$$
f(2) = 12 - 24 + 7
$$

$$
f(2) = -5
$$

Check the second derivative:

$$
f''(x) = 6
$$

Since

$$
f''(x) = 6 > 0
$$

the critical point is a local minimum.

## Final Result

The function has a local minimum at

$$
x = 2
$$

with value

$$
f(2) = -5
$$

So the minimum point is

$$
(2,-5)
$$

There is no local maximum.

## Interpretation

Because the coefficient of $x^2$ is positive, the parabola opens upward. Therefore its turning point is the lowest point on the graph.

---

# Task 07 – Motion of a Fly Between a Bicycle and a Wall

## Problem Statement

A bicycle is $10$ m from a wall and moves toward it at a constant speed of $1$ m/s. A fly starts from the bicycle's front wheel and flies toward the wall at $2$ m/s. Each time the fly reaches the wall or the bicycle, it instantly reverses direction. Determine the total distance traveled by the fly before the bicycle reaches the wall and the fly is crushed.

## Theory

Problems of repeated back-and-forth motion can often be solved without summing infinitely many separate segments. Instead:

1. determine the total time available before the event ends,
2. multiply that time by the fly's constant speed.

This method avoids constructing the full infinite series explicitly.

## Step-by-Step Solution

### 1. Time until the bicycle reaches the wall

The bicycle starts $10$ m from the wall and moves at $1$ m/s. Therefore the time to reach the wall is

$$
t = \frac{\text{distance}}{\text{speed}} = \frac{10}{1} = 10 \text{ s}
$$

### 2. Distance traveled by the fly

The fly moves continuously during these $10$ s at speed $2$ m/s. Hence its total distance is

$$
d = vt
$$

$$
d = 2 \cdot 10
$$

$$
d = 20 \text{ m}
$$

## Final Result

The fly travels a total distance of

$$
20 \text{ m}
$$

## Interpretation

Although the fly makes infinitely many trips, the total travel time is finite. Since the bicycle reaches the wall in $10$ s, the fly simply flies for $10$ s at $2$ m/s, giving a finite total distance of $20$ m.

---

# Task 08 – Area Under the Curve of $\sin x$

## Problem Statement

Calculate the area under the curve

$$
f(x) = \sin x
$$

from

$$
x = 0
\qquad
\text{to}
\qquad
x = \pi
$$

## Theory

The definite integral of a function over an interval gives the signed area between the curve and the horizontal axis. Since $ \sin x \geq 0 $ on the interval $[0,\pi]$, the signed area is equal to the ordinary geometric area.

An antiderivative of $ \sin x $ is

$$
\int \sin x \, dx = -\cos x + C
$$

## Step-by-Step Solution

The required area is

$$
\int_0^\pi \sin x \, dx
$$

Evaluate the antiderivative at the bounds:

$$
\int_0^\pi \sin x \, dx = \left[-\cos x\right]_0^\pi
$$

Substitute the upper and lower limits:

$$
\left[-\cos x\right]_0^\pi = -\cos \pi - (-\cos 0)
$$

Using

$$
\cos \pi = -1
\qquad
\cos 0 = 1
$$

gives

$$
-\cos \pi - (-\cos 0) = -(-1) - (-1)
$$

$$
= 1 + 1
$$

$$
= 2
$$

## Final Result

$$
\int_0^\pi \sin x \, dx = 2
$$

## Interpretation

The total area under one arch of the sine curve from $0$ to $\pi$ is $2$ square units. This interval corresponds exactly to the positive half-wave of the sine function.

---

# Task 09 – Optimization of a Rectangle Under a Parabola

## Problem Statement

A rectangle is inscribed under the curve

$$
y = 3 - x^2
$$

in the first quadrant. Determine the dimensions of the rectangle of maximum area.

## Theory

If the top-right corner of the rectangle lies on the curve at $ (x,y) $, then in the first quadrant:

- the width of the rectangle is $x$,
- the height is $y = 3 - x^2$.

The area becomes a function of one variable:

$$
A(x) = x(3 - x^2)
$$

Optimization requires:

1. compute the derivative,
2. find critical points,
3. determine which critical point gives the maximum area.

## Step-by-Step Solution

### 1. Express the area as a function of $x$

$$
A(x) = x(3 - x^2)
$$

Expand:

$$
A(x) = 3x - x^3
$$

### 2. Find the critical points

Differentiate:

$$
A'(x) = 3 - 3x^2
$$

Set the derivative equal to zero:

$$
3 - 3x^2 = 0
$$

$$
1 - x^2 = 0
$$

$$
x^2 = 1
$$

$$
x = 1
$$

Only the positive root is relevant because the rectangle is in the first quadrant.

### 3. Find the corresponding height

Substitute $x = 1$ into the curve equation:

$$
y = 3 - x^2
$$

$$
y = 3 - 1^2 = 2
$$

### 4. Verify that this gives a maximum

Differentiate again:

$$
A''(x) = -6x
$$

At $x = 1$,

$$
A''(1) = -6 < 0
$$

Therefore the area is maximized at this point.

## Final Result

The rectangle of maximum area has dimensions

$$
\text{width} = 1
$$

and

$$
\text{height} = 2
$$

Its maximum area is

$$
A_{\max} = 1 \cdot 2 = 2
$$

## Interpretation

As the rectangle becomes wider, its height decreases because the top edge must remain below the parabola. The optimal rectangle balances these competing effects, producing maximum area at width $1$ and height $2$.

---

# Task 10 – Infinite Series and Final Position of an Ant

## Problem Statement

An ant starts at the origin and moves according to the pattern:

- $1$ m east,
- $ \frac{1}{2} $ m north,
- $ \frac{1}{3} $ m west,
- $ \frac{1}{4} $ m south,
- $ \frac{1}{5} $ m east,

and so on.

Determine its final position.

## Theory

The motion alternates between horizontal and vertical directions:

- odd reciprocals with indices $1,3,5,\dots$ contribute to horizontal motion,
- even reciprocals with indices $2,4,6,\dots$ contribute to vertical motion.

The directions alternate:

- horizontal: east, west, east, west, ...
- vertical: north, south, north, south, ...

Thus the final coordinates are determined by two alternating series.

The alternating harmonic series is

$$
\sum_{n=1}^{\infty} \frac{(-1)^{n+1}}{n} = \ln 2
$$

## Step-by-Step Solution

### 1. Horizontal displacement

The horizontal terms are

$$
1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \cdots
$$

This is the well-known series

$$
1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \cdots = \frac{\pi}{4}
$$

Therefore the total horizontal displacement is

$$
x = \frac{\pi}{4}
$$

### 2. Vertical displacement

The vertical terms are

$$
\frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \cdots
$$

Factor out $ \frac{1}{2} $:

$$
\frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \cdots
=
\frac{1}{2} \left(1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \cdots \right)
$$

The series in parentheses is the alternating harmonic series, so

$$
1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \cdots = \ln 2
$$

Hence

$$
y = \frac{1}{2} \ln 2
$$

### 3. Final position vector

The final position of the ant is therefore

$$
\begin{pmatrix}
x \\
y
\end{pmatrix}
=
\begin{pmatrix}
\frac{\pi}{4} \\
\frac{1}{2}\ln 2
\end{pmatrix}
$$

Numerically,

$$
\frac{\pi}{4} \approx 0.785
\qquad
\frac{1}{2}\ln 2 \approx 0.347
$$

## Final Result

The ant approaches the final position

$$
\left(\frac{\pi}{4}, \frac{1}{2}\ln 2\right)
$$

## Interpretation

Although the ant makes infinitely many moves, the lengths decrease as reciprocal numbers and the alternating pattern causes the sums to converge. The final point lies east and north of the origin, at finite coordinates determined by convergent infinite series.