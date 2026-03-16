# Problem Set 01 – Solutions  
## Section 1: Mechanics I

---

# Task 1 – Projectile Motion

## Problem Statement

A projectile is fired from the ground with an initial velocity of $100 \text{ m/s}$ at an angle of $37^\circ$ above the horizontal. Air resistance is neglected.

Tasks:

- Derive the differential equations of motion in horizontal and vertical directions.
- Determine the time of flight.
- Determine the maximum height.
- Determine the range.

---

## Theory

Projectile motion is governed by **Newton’s Second Law**. The only force acting on the projectile is gravity.

The gravitational force is

$$
\vec F = m\vec g
$$

Acceleration is therefore constant and directed downward:

$$
\vec a = (0,-g)
$$

The motion separates into independent components:

- horizontal motion: constant velocity
- vertical motion: uniformly accelerated motion

---

## Step-by-Step Solution

### Differential Equations of Motion

Newton's second law gives

$$
m\frac{d^2\vec r}{dt^2} = m\vec g
$$

Therefore

$$
\frac{d^2\vec r}{dt^2} = (0,-g)
$$

Separating into components:

Horizontal motion

$$
\frac{d^2 x}{dt^2} = 0
$$

Vertical motion

$$
\frac{d^2 y}{dt^2} = -g
$$

---

### Velocity Components

The initial velocity is

$$
v_0 = 100 \text{ m/s}
$$

Launch angle

$$
\theta = 37^\circ
$$

Horizontal component

$$
v_{0x} = v_0 \cos\theta
$$

Vertical component

$$
v_{0y} = v_0 \sin\theta
$$

Using

$$
\sin 37^\circ \approx 0.6
$$

$$
\cos 37^\circ \approx 0.8
$$

Therefore

$$
v_{0x} = 80 \text{ m/s}
$$

$$
v_{0y} = 60 \text{ m/s}
$$

---

### Time of Flight

Vertical motion equation

$$
y(t)=v_{0y}t-\frac{1}{2}gt^2
$$

The projectile returns to ground when

$$
y(t)=0
$$

Thus

$$
0=v_{0y}t-\frac{1}{2}gt^2
$$

Factorizing

$$
t(v_{0y}-\frac{1}{2}gt)=0
$$

Non-trivial solution

$$
t=\frac{2v_{0y}}{g}
$$

Substituting values

$$
t=\frac{2\cdot 60}{9.81}
$$

$$
t \approx 12.23 \text{ s}
$$

---

### Maximum Height

Maximum height occurs when vertical velocity becomes zero.

Velocity equation

$$
v_y = v_{0y}-gt
$$

Setting

$$
v_y=0
$$

gives

$$
t_{max}=\frac{v_{0y}}{g}
$$

Substituting

$$
t_{max}=\frac{60}{9.81}
$$

$$
t_{max} \approx 6.12 \text{ s}
$$

Height equation

$$
y(t)=v_{0y}t-\frac{1}{2}gt^2
$$

Substituting

$$
y_{max} = \frac{v_{0y}^2}{2g}
$$

$$
y_{max}=\frac{60^2}{2\cdot9.81}
$$

$$
y_{max} \approx 183.5 \text{ m}
$$

---

### Range

Horizontal motion

$$
x=v_{0x}t
$$

Using the time of flight

$$
R=v_{0x}t
$$

Substituting

$$
R=80 \cdot 12.23
$$

$$
R \approx 978.4 \text{ m}
$$

---

## Final Result

Time of flight

$$
t \approx 12.23 \text{ s}
$$

Maximum height

$$
y_{max} \approx 183.5 \text{ m}
$$

Range

$$
R \approx 978 \text{ m}
$$

---

## Interpretation

Projectile motion separates into independent horizontal and vertical components. The horizontal velocity remains constant while the vertical motion follows uniformly accelerated motion under gravity.

---

# Task 2 – Range Optimization

## Problem Statement

Show analytically that the range

$$
R(\theta)=\frac{v_0^2\sin(2\theta)}{g}
$$

is maximized at

$$
\theta=45^\circ
$$

---

## Theory

To find the maximum of a function, its derivative with respect to the variable must be zero.

---

## Step-by-Step Solution

Range function

$$
R(\theta)=\frac{v_0^2}{g}\sin(2\theta)
$$

Derivative

$$
\frac{dR}{d\theta}=\frac{v_0^2}{g}\cdot2\cos(2\theta)
$$

Setting derivative to zero

$$
\cos(2\theta)=0
$$

This occurs when

$$
2\theta=90^\circ
$$

Therefore

$$
\theta=45^\circ
$$

---

## Final Result

Maximum range occurs at

$$
\theta = 45^\circ
$$

---

## Interpretation

A launch angle of $45^\circ$ balances vertical and horizontal velocity components, maximizing horizontal displacement.

---

# Task 3 – Path Intersection

## Problem Statement

Alice moves along

$$
A(t)=(2+t,\,8-3t)
$$

Bob moves along

$$
B(t)=(2t-1,\,2t+2)
$$

Determine whether their paths intersect and if they collide.

---

## Theory

Two objects collide if their **positions are equal at the same time**.

---

## Step-by-Step Solution

Equate coordinates.

For $x$ coordinate

$$
2+t = 2t-1
$$

Solving

$$
t=3
$$

Now test $y$ coordinate.

Alice

$$
y_A = 8-3t
$$

Bob

$$
y_B = 2t+2
$$

Substitute $t=3$

$$
y_A = -1
$$

$$
y_B = 8
$$

The coordinates are different.

---

## Final Result

The paths intersect geometrically but the objects **do not collide** because they reach the intersection at different times.

---

## Interpretation

Even if trajectories cross in space, a collision occurs only if the time parameter is identical.

---

# Task 4 – Vector Calculus

## Problem Statement

The position vector is

$$
\vec r(t) = (3t^2)\hat i + (5t-8t^2)\hat j
$$

Find velocity and acceleration.

---

## Theory

Velocity is the first derivative of position.

Acceleration is the second derivative.

---

## Step-by-Step Solution

Velocity

$$
\vec v(t)=\frac{d\vec r}{dt}
$$

$$
\vec v(t)=(6t)\hat i + (5-16t)\hat j
$$

Acceleration

$$
\vec a(t)=\frac{d\vec v}{dt}
$$

$$
\vec a(t)=6\hat i-16\hat j
$$

---

## Final Result

Velocity

$$
\vec v(t)=(6t,\,5-16t)
$$

Acceleration

$$
\vec a(t)=(6,-16)
$$

---

## Interpretation

The constant acceleration indicates uniformly accelerated motion.

---

# Task 5 – Relative Velocity

## Problem Statement

River velocity

$$
2 \text{ m/s east}
$$

Boat speed relative to water

$$
5 \text{ m/s}
$$

River width

$$
200 \text{ m}
$$

---

## Theory

Relative velocity addition:

$$
\vec v_{ground}=\vec v_{boat}+\vec v_{river}
$$

To move directly north, eastward components must cancel.

---

## Step-by-Step Solution

Let boat head at angle $\theta$ west of north.

East component

$$
5\sin\theta
$$

Condition for cancellation

$$
5\sin\theta = 2
$$

$$
\sin\theta = 0.4
$$

$$
\theta \approx 23.6^\circ
$$

Northward velocity

$$
v_N = 5\cos\theta
$$

$$
v_N \approx 4.58 \text{ m/s}
$$

Time to cross

$$
t=\frac{200}{4.58}
$$

$$
t \approx 43.7 \text{ s}
$$

---

## Final Result

Heading angle

$$
23.6^\circ
$$

Crossing time

$$
43.7 \text{ s}
$$

---

## Interpretation

The boat must aim upstream to cancel the river drift.

---

# Task 6 – Variable Velocity

## Problem Statement

Velocity

$$
v(t)=t^2+2t-5
$$

Initial position

$$
x(0)=4
$$

Find position and acceleration at $t=3$.

---

## Theory

Position is obtained by integrating velocity.

Acceleration is the derivative of velocity.

---

## Step-by-Step Solution

Position

$$
x(t)=\int v(t)dt
$$

$$
x(t)=\frac{t^3}{3}+t^2-5t+C
$$

Using $x(0)=4$

$$
C=4
$$

Thus

$$
x(t)=\frac{t^3}{3}+t^2-5t+4
$$

Evaluate at $t=3$

$$
x(3)=9+9-15+4
$$

$$
x(3)=7
$$

Acceleration

$$
a(t)=2t+2
$$

$$
a(3)=8
$$

---

## Final Result

Position

$$
x(3)=7
$$

Acceleration

$$
a(3)=8
$$

---

## Interpretation

The velocity grows quadratically while acceleration increases linearly.

---

# Task 7 – Elimination of Time

## Problem Statement

Parametric equations

$$
x(t)=2t^2
$$

$$
y(t)=3t^3
$$

---

## Theory

Eliminating time produces the trajectory equation.

---

## Step-by-Step Solution

Solve for $t$ from $x$.

$$
t=\sqrt{\frac{x}{2}}
$$

Substitute into $y$.

$$
y=3\left(\frac{x}{2}\right)^{3/2}
$$

Velocity

$$
\vec v(t)=(4t,9t^2)
$$

Speed

$$
|\vec v|=\sqrt{16t^2+81t^4}
$$

Acceleration

$$
\vec a(t)=(4,18t)
$$

Magnitude

$$
|\vec a|=\sqrt{16+324t^2}
$$

---

## Final Result

Trajectory

$$
y=3\left(\frac{x}{2}\right)^{3/2}
$$

Acceleration is not constant.

---

## Interpretation

Acceleration changes because its magnitude depends on time.

---

# Task 8 – Circular Motion

## Problem Statement

Find centripetal acceleration at Earth's equator.

Earth radius

$$
R=6.378\times10^6 \text{ m}
$$

---

## Theory

Centripetal acceleration

$$
a=\frac{v^2}{R}
$$

Velocity due to Earth rotation

$$
v=\frac{2\pi R}{T}
$$

---

## Step-by-Step Solution

Earth rotation period

$$
T=86400 \text{ s}
$$

Velocity

$$
v \approx 463 \text{ m/s}
$$

Acceleration

$$
a=\frac{463^2}{6.378\times10^6}
$$

$$
a \approx 0.034 \text{ m/s}^2
$$

---

## Final Result

$$
a \approx 0.034 \text{ m/s}^2
$$

---

## Interpretation

Earth's rotation slightly reduces the effective weight at the equator.

---

# Task 9 – Momentum Comparison

## Problem Statement

Compare momentum of:

- fly: $2$ g at $10$ m/s  
- tennis ball: $60$ g at $1$ m/s

---

## Theory

Momentum

$$
p=mv
$$

---

## Step-by-Step Solution

Fly

$$
m=0.002 \text{ kg}
$$

$$
p=0.002\times10
$$

$$
p=0.02
$$

Tennis ball

$$
m=0.06
$$

$$
p=0.06\times1
$$

$$
p=0.06
$$

---

## Final Result

The tennis ball has greater momentum.

---

## Interpretation

Momentum depends on both mass and velocity. Larger mass dominates in this case.

---

# Task 10 – Kinematics

## Problem Statement

Position

$$
\vec r(t)=(a\cos(\omega t),b\sin(\omega t),bt)
$$

---

## Theory

The first two coordinates describe an ellipse while the third produces vertical motion.

---

## Step-by-Step Solution

Trajectory equation

$$
\frac{x^2}{a^2}+\frac{y^2}{b^2}=1
$$

Velocity

$$
\vec v(t)=(-a\omega\sin(\omega t),b\omega\cos(\omega t),b)
$$

Acceleration

$$
\vec a(t)=(-a\omega^2\cos(\omega t),-b\omega^2\sin(\omega t),0)
$$

---

## Final Result

The trajectory is a **helical curve around an elliptical cylinder**.

---

## Interpretation

The motion combines periodic motion in the plane with uniform vertical motion, producing a three-dimensional helix.