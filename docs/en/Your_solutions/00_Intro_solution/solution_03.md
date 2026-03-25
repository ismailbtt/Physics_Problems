# Task 01 – Gravitational Dependence of a Simple Pendulum

## Problem Statement

A simple pendulum has a period of $4 \ \mathrm{s}$ on Earth.

Determine:

1. its period on the Moon, where the gravitational acceleration is approximately $g_{\text{Moon}} = \frac{1}{6} g_{\text{Earth}}$,
2. the required length of a simple pendulum that has a period of exactly $1 \ \mathrm{s}$ on Earth.

## Theory

For small oscillations, the period of a simple pendulum is

$$
T = 2\pi \sqrt{\frac{L}{g}}
$$

where:

- $T$ is the period,
- $L$ is the pendulum length,
- $g$ is the gravitational acceleration.

At fixed length, the period depends on gravity as

$$
T \propto \frac{1}{\sqrt{g}}
$$

Thus, if gravity decreases, the pendulum oscillates more slowly.

## Step-by-Step Solution

### 1. Period on the Moon

For the same pendulum length,

$$
\frac{T_{\text{Moon}}}{T_{\text{Earth}}} = \sqrt{\frac{g_{\text{Earth}}}{g_{\text{Moon}}}}
$$

Since

$$
g_{\text{Moon}} = \frac{1}{6} g_{\text{Earth}}
$$

it follows that

$$
\frac{T_{\text{Moon}}}{T_{\text{Earth}}} = \sqrt{\frac{g_{\text{Earth}}}{g_{\text{Earth}}/6}} = \sqrt{6}
$$

Therefore,

$$
T_{\text{Moon}} = T_{\text{Earth}} \sqrt{6}
$$

Substituting $T_{\text{Earth}} = 4 \ \mathrm{s}$,

$$
T_{\text{Moon}} = 4\sqrt{6} \ \mathrm{s}
$$

Numerically,

$$
T_{\text{Moon}} \approx 4 \cdot 2.449 = 9.80 \ \mathrm{s}
$$

### 2. Length for a period of $1 \ \mathrm{s}$ on Earth

Starting from

$$
T = 2\pi \sqrt{\frac{L}{g}}
$$

solve for $L$:

$$
\frac{T}{2\pi} = \sqrt{\frac{L}{g}}
$$

Squaring both sides gives

$$
\left( \frac{T}{2\pi} \right)^2 = \frac{L}{g}
$$

Hence,

$$
L = g \left( \frac{T}{2\pi} \right)^2
$$

Using $T = 1 \ \mathrm{s}$ and $g = 9.81 \ \mathrm{m/s^2}$,

$$
L = 9.81 \left( \frac{1}{2\pi} \right)^2
$$

$$
L = \frac{9.81}{4\pi^2}
$$

Numerically,

$$
L \approx \frac{9.81}{39.478} \approx 0.248 \ \mathrm{m}
$$

## Final Result

The period on the Moon is

$$
T_{\text{Moon}} = 4\sqrt{6} \ \mathrm{s} \approx 9.80 \ \mathrm{s}
$$

The required pendulum length for a period of $1 \ \mathrm{s}$ on Earth is

$$
L \approx 0.248 \ \mathrm{m}
$$

## Interpretation

The pendulum swings more slowly on the Moon because the restoring effect of gravity is weaker. Since the period varies as $1/\sqrt{g}$, reducing gravity by a factor of $6$ increases the period by a factor of $\sqrt{6}$.

A pendulum with a period of $1 \ \mathrm{s}$ on Earth must be relatively short, about $25 \ \mathrm{cm}$. This illustrates the direct relation between oscillation period and pendulum length.
# Task 02 – Harmonic Motion of a Mass-Spring System

## Problem Statement

A mass of $10 \ \mathrm{kg}$ is attached to a spring and oscillates according to

$$
x(t) = 0.2 \cos(10\pi t)
$$

where $x$ is measured in meters.

Determine:

1. the spring constant $k$,
2. the total mechanical energy of the system.

## Theory

For simple harmonic motion of a mass-spring system,

$$
x(t) = A \cos(\omega t + \phi)
$$

where:

- $A$ is the amplitude,
- $\omega$ is the angular frequency,
- $\phi$ is the phase constant.

The relation between angular frequency and spring constant is

$$
\omega = \sqrt{\frac{k}{m}}
$$

Thus,

$$
k = m\omega^2
$$

The total mechanical energy of the oscillator is constant and equals

$$
E = \frac{1}{2} k A^2
$$

## Step-by-Step Solution

### 1. Identification of amplitude and angular frequency

From

$$
x(t) = 0.2 \cos(10\pi t)
$$

the amplitude is

$$
A = 0.2 \ \mathrm{m}
$$

and the angular frequency is

$$
\omega = 10\pi \ \mathrm{rad/s}
$$

### 2. Spring constant

Using

$$
k = m\omega^2
$$

with $m = 10 \ \mathrm{kg}$,

$$
k = 10(10\pi)^2
$$

$$
k = 10 \cdot 100\pi^2
$$

$$
k = 1000\pi^2 \ \mathrm{N/m}
$$

Numerically,

$$
k \approx 1000 \cdot 9.8696 = 9869.6 \ \mathrm{N/m}
$$

### 3. Total mechanical energy

The total energy is

$$
E = \frac{1}{2}kA^2
$$

Substitute $k = 1000\pi^2 \ \mathrm{N/m}$ and $A = 0.2 \ \mathrm{m}$:

$$
E = \frac{1}{2}(1000\pi^2)(0.2)^2
$$

Since

$$
(0.2)^2 = 0.04
$$

then

$$
E = \frac{1}{2}(1000\pi^2)(0.04)
$$

$$
E = 20\pi^2 \ \mathrm{J}
$$

Numerically,

$$
E \approx 20 \cdot 9.8696 = 197.4 \ \mathrm{J}
$$

## Final Result

The spring constant is

$$
k = 1000\pi^2 \ \mathrm{N/m} \approx 9.87 \times 10^3 \ \mathrm{N/m}
$$

The total mechanical energy is

$$
E = 20\pi^2 \ \mathrm{J} \approx 197.4 \ \mathrm{J}
$$

## Interpretation

The oscillator has a high angular frequency, which implies a stiff spring. The total mechanical energy is constant because no damping or friction is present in the model. During the motion, energy continuously changes form between kinetic and elastic potential energy, while the sum remains equal to $197.4 \ \mathrm{J}$.
# Task 03 – Speed of a Pendulum Bob from Energy Conservation

## Problem Statement

A pendulum of length $1.0 \ \mathrm{m}$ is released from an initial angle of $15^\circ$.

Determine the speed of the pendulum bob at the bottom of the swing.

## Theory

If air resistance and pivot friction are neglected, mechanical energy is conserved.

When the pendulum is released from rest, the initial energy is purely gravitational potential energy. At the bottom of the swing, that potential energy has been converted into kinetic energy.

The change in height between the release point and the bottom is

$$
h = L(1 - \cos \theta)
$$

Hence,

$$
mgh = \frac{1}{2}mv^2
$$

and therefore

$$
v = \sqrt{2gh}
$$

## Step-by-Step Solution

### 1. Vertical drop of the bob

The pendulum length is

$$
L = 1.0 \ \mathrm{m}
$$

The initial angle is

$$
\theta = 15^\circ
$$

Thus the vertical drop is

$$
h = L(1 - \cos \theta)
$$

Substituting the values,

$$
h = 1.0(1 - \cos 15^\circ)
$$

Using

$$
\cos 15^\circ \approx 0.9659
$$

gives

$$
h \approx 1.0(1 - 0.9659) = 0.0341 \ \mathrm{m}
$$

### 2. Use conservation of energy

Set initial potential energy equal to final kinetic energy:

$$
mgh = \frac{1}{2}mv^2
$$

The mass cancels, so

$$
v = \sqrt{2gh}
$$

Substitute $g = 9.81 \ \mathrm{m/s^2}$ and $h = 0.0341 \ \mathrm{m}$:

$$
v = \sqrt{2 \cdot 9.81 \cdot 0.0341}
$$

$$
v = \sqrt{0.669}
$$

$$
v \approx 0.818 \ \mathrm{m/s}
$$

Using the equivalent direct formula,

$$
v = \sqrt{2gL(1-\cos\theta)}
$$

also gives the same result.

## Final Result

The speed of the pendulum bob at the bottom is

$$
v \approx 0.82 \ \mathrm{m/s}
$$

## Interpretation

The initial angle is relatively small, so the change in height is modest. As a result, the bob reaches the lowest point with a speed below $1 \ \mathrm{m/s}$. The result follows directly from the conversion of gravitational potential energy into kinetic energy.
# Task 04 – Energy and Momentum in a Collision

## Problem Statement

A block of mass $0.5 \ \mathrm{kg}$ slides down a frictionless track from a height of $3.0 \ \mathrm{m}$. At the bottom, it collides and sticks to a second block of mass $1.5 \ \mathrm{kg}$, initially at rest.

Determine the speed of the combined mass immediately after the collision.

## Theory

The motion contains two stages:

1. conversion of gravitational potential energy into kinetic energy during the slide,
2. a perfectly inelastic collision at the bottom.

For the slide,

$$
mgh = \frac{1}{2}mv^2
$$

which gives

$$
v = \sqrt{2gh}
$$

For the collision, linear momentum is conserved:

$$
m_1 v_1 + m_2 v_2 = (m_1 + m_2)v_f
$$

Since the second block is initially at rest, $v_2 = 0$.

## Step-by-Step Solution

### 1. Speed of the first block before collision

The first block starts from height

$$
h = 3.0 \ \mathrm{m}
$$

On a frictionless track, mechanical energy is conserved:

$$
mgh = \frac{1}{2}mv^2
$$

Thus,

$$
v_1 = \sqrt{2gh}
$$

Substitute $g = 9.81 \ \mathrm{m/s^2}$:

$$
v_1 = \sqrt{2 \cdot 9.81 \cdot 3.0}
$$

$$
v_1 = \sqrt{58.86}
$$

$$
v_1 \approx 7.67 \ \mathrm{m/s}
$$

### 2. Apply conservation of momentum in the collision

Let:

- $m_1 = 0.5 \ \mathrm{kg}$,
- $m_2 = 1.5 \ \mathrm{kg}$,
- $v_2 = 0$.

Then

$$
m_1 v_1 = (m_1 + m_2)v_f
$$

So,

$$
v_f = \frac{m_1 v_1}{m_1 + m_2}
$$

Substitute the values:

$$
v_f = \frac{0.5 \cdot 7.67}{0.5 + 1.5}
$$

$$
v_f = \frac{3.835}{2.0}
$$

$$
v_f \approx 1.92 \ \mathrm{m/s}
$$

## Final Result

The speed of the combined mass immediately after the collision is

$$
v_f \approx 1.92 \ \mathrm{m/s}
$$

## Interpretation

Before the collision, the first block converts gravitational potential energy into kinetic energy. During the collision, momentum is conserved, but kinetic energy is not conserved because the blocks stick together. Part of the kinetic energy is transformed into internal energy, deformation, and heat.
# Task 05 – Inelastic Collision of a Runner and a Cart

## Problem Statement

A runner of mass $70 \ \mathrm{kg}$ moving at $3 \ \mathrm{m/s}$ jumps onto a stationary cart of mass $140 \ \mathrm{kg}$.

Determine:

1. the final speed of the cart with the runner,
2. whether kinetic energy is conserved.

## Theory

When two bodies stick together after impact, the collision is perfectly inelastic.

In such a collision, linear momentum is conserved:

$$
m_1 v_1 + m_2 v_2 = (m_1 + m_2)v_f
$$

However, kinetic energy is generally not conserved.

Kinetic energy is computed from

$$
K = \frac{1}{2}mv^2
$$

## Step-by-Step Solution

### 1. Final speed from momentum conservation

Take:

- runner mass: $m_1 = 70 \ \mathrm{kg}$,
- runner speed: $v_1 = 3 \ \mathrm{m/s}$,
- cart mass: $m_2 = 140 \ \mathrm{kg}$,
- cart speed: $v_2 = 0$.

Momentum conservation gives

$$
70 \cdot 3 + 140 \cdot 0 = (70 + 140)v_f
$$

$$
210 = 210v_f
$$

Thus,

$$
v_f = 1.0 \ \mathrm{m/s}
$$

### 2. Initial kinetic energy

Initially only the runner is moving, so

$$
K_i = \frac{1}{2}m_1 v_1^2
$$

$$
K_i = \frac{1}{2} \cdot 70 \cdot 3^2
$$

$$
K_i = 35 \cdot 9 = 315 \ \mathrm{J}
$$

### 3. Final kinetic energy

After the collision, the combined mass is

$$
m_1 + m_2 = 210 \ \mathrm{kg}
$$

and it moves with speed $v_f = 1.0 \ \mathrm{m/s}$:

$$
K_f = \frac{1}{2}(210)(1.0)^2
$$

$$
K_f = 105 \ \mathrm{J}
$$

### 4. Compare kinetic energies

The change in kinetic energy is

$$
\Delta K = K_f - K_i = 105 - 315 = -210 \ \mathrm{J}
$$

So kinetic energy decreases by $210 \ \mathrm{J}$.

## Final Result

The final speed of the runner and cart is

$$
v_f = 1.0 \ \mathrm{m/s}
$$

Kinetic energy is **not** conserved:

$$
K_i = 315 \ \mathrm{J}, \qquad K_f = 105 \ \mathrm{J}
$$

## Interpretation

Momentum is conserved because the collision occurs over a short time and external horizontal forces are neglected. Kinetic energy is not conserved because the collision is perfectly inelastic: the runner and cart move together afterward. The missing kinetic energy is transformed into internal energy, sound, and deformation.
# Task 06 – Energy Dissipation in Repeated Bounces

## Problem Statement

A tennis ball is dropped from a height of $2.0 \ \mathrm{m}$. After each bounce, it loses $30\%$ of its mechanical energy.

Determine the height reached after the second bounce.

## Theory

At the highest point of a bounce, the ball's mechanical energy is purely gravitational potential energy:

$$
E = mgh
$$

If the ball retains only $70\%$ of its energy after each bounce, then the height after each bounce is also multiplied by $0.70$, because $m$ and $g$ remain constant:

$$
h_{\text{new}} = 0.70 \, h_{\text{old}}
$$

## Step-by-Step Solution

### 1. Initial height

The ball is initially dropped from

$$
h_0 = 2.0 \ \mathrm{m}
$$

### 2. Height after the first bounce

The ball retains $70\%$ of its energy, so

$$
h_1 = 0.70 h_0
$$

$$
h_1 = 0.70 \cdot 2.0 = 1.4 \ \mathrm{m}
$$

### 3. Height after the second bounce

Again, the ball retains $70\%$ of the mechanical energy from the previous bounce:

$$
h_2 = 0.70 h_1
$$

$$
h_2 = 0.70 \cdot 1.4
$$

$$
h_2 = 0.98 \ \mathrm{m}
$$

Equivalently,

$$
h_2 = (0.70)^2 h_0
$$

$$
h_2 = 0.49 \cdot 2.0 = 0.98 \ \mathrm{m}
$$

## Final Result

The ball rises to

$$
h_2 = 0.98 \ \mathrm{m}
$$

after the second bounce.

## Interpretation

Because gravitational potential energy at the top is proportional to height, the same percentage loss in energy corresponds directly to the same percentage reduction in bounce height. After two bounces, the ball reaches less than half of its original height.
# Task 07 – Dynamics with Friction for Two Blocks

## Problem Statement

A $5 \ \mathrm{kg}$ block is placed on a $10 \ \mathrm{kg}$ block. A horizontal force of $45 \ \mathrm{N}$ is applied to the $10 \ \mathrm{kg}$ block, while the $5 \ \mathrm{kg}$ block is tied to a wall. The coefficient of kinetic friction between all moving surfaces is $0.2$.

Determine the acceleration of the $10 \ \mathrm{kg}$ block.

## Theory

The lower block moves relative to:

1. the ground,
2. the upper block.

Thus two kinetic friction forces oppose its motion.

Kinetic friction has magnitude

$$
f_k = \mu_k N
$$

Newton's second law for the lower block is

$$
\sum F_x = ma
$$

## Step-by-Step Solution

### 1. Friction between the upper and lower blocks

The upper block has mass

$$
m_1 = 5 \ \mathrm{kg}
$$

Its normal force on the lower block is

$$
N_{12} = m_1 g
$$

Therefore the kinetic friction between the two blocks is

$$
f_{12} = \mu_k N_{12}
$$

$$
f_{12} = 0.2 \cdot 5 \cdot 9.81
$$

$$
f_{12} = 9.81 \ \mathrm{N}
$$

This force acts opposite the motion of the lower block.

### 2. Friction between the lower block and the ground

The lower block supports both masses, so the normal force from the ground is

$$
N_g = (m_1 + m_2)g
$$

where

$$
m_2 = 10 \ \mathrm{kg}
$$

Hence,

$$
N_g = (5 + 10)9.81 = 147.15 \ \mathrm{N}
$$

The ground friction is

$$
f_g = \mu_k N_g
$$

$$
f_g = 0.2 \cdot 147.15
$$

$$
f_g = 29.43 \ \mathrm{N}
$$

### 3. Net force on the lower block

The applied force is

$$
F = 45 \ \mathrm{N}
$$

Both friction forces act in the opposite direction, so the net horizontal force on the lower block is

$$
F_{\text{net}} = F - f_{12} - f_g
$$

$$
F_{\text{net}} = 45 - 9.81 - 29.43
$$

$$
F_{\text{net}} = 5.76 \ \mathrm{N}
$$

### 4. Acceleration of the lower block

Apply Newton's second law to the $10 \ \mathrm{kg}$ block:

$$
F_{\text{net}} = m_2 a
$$

Thus,

$$
a = \frac{F_{\text{net}}}{m_2}
$$

$$
a = \frac{5.76}{10}
$$

$$
a = 0.576 \ \mathrm{m/s^2}
$$

## Final Result

The acceleration of the $10 \ \mathrm{kg}$ block is

$$
a \approx 0.58 \ \mathrm{m/s^2}
$$

## Interpretation

The applied force must overcome two separate friction forces: one from the ground and one from sliding beneath the upper block tied to the wall. Most of the applied force is consumed by friction, so the remaining net force and resulting acceleration are relatively small.
# Task 08 – Work of a Variable Force

## Problem Statement

Given the one-dimensional force

$$
F(x) = -kx
$$

determine:

1. the equation of motion and its solution,
2. the work done during the displacement from $0$ to $x_0$,
3. the corresponding potential energy,
4. the verification of the relation $F = -\frac{dU}{dx}$,
5. the form of the graphs of $F(x)$ and $U(x)$.

## Theory

The force

$$
F(x) = -kx
$$

is the restoring force of an ideal spring. It is proportional to displacement and directed toward the equilibrium position.

Using Newton's second law,

$$
m\frac{d^2x}{dt^2} = F(x)
$$

gives the differential equation

$$
m\frac{d^2x}{dt^2} = -kx
$$

or equivalently

$$
\frac{d^2x}{dt^2} + \frac{k}{m}x = 0
$$

This is the equation of simple harmonic motion.

For a variable force, the work over an interval is defined by

$$
W = \int_{x_1}^{x_2} F(x)\,dx
$$

If the force is conservative, one can define a potential energy function $U(x)$ such that

$$
F(x) = -\frac{dU}{dx}
$$

## Step-by-Step Solution

### 1. Equation of motion

Starting from Newton's second law,

$$
m\ddot{x} = -kx
$$

Dividing by $m$ gives

$$
\ddot{x} + \frac{k}{m}x = 0
$$

Define

$$
\omega = \sqrt{\frac{k}{m}}
$$

Then the equation becomes

$$
\ddot{x} + \omega^2 x = 0
$$

### 2. General solution of the motion

The general solution of the differential equation is

$$
x(t) = A \cos(\omega t) + B \sin(\omega t)
$$

where $A$ and $B$ are constants determined by initial conditions.

An equivalent amplitude-phase form is

$$
x(t) = C \cos(\omega t + \phi)
$$

where $C$ is the amplitude and $\phi$ is the phase constant.

### 3. Work done during the displacement from $0$ to $x_0$

The work done by the force is

$$
W_{0 \to x_0} = \int_0^{x_0} (-kx)\,dx
$$

Factor out the constant $-k$:

$$
W_{0 \to x_0} = -k \int_0^{x_0} x\,dx
$$

Integrating,

$$
W_{0 \to x_0} = -k \left[ \frac{x^2}{2} \right]_0^{x_0}
$$

Therefore,

$$
W_{0 \to x_0} = -\frac{1}{2}k x_0^2
$$

### 4. Interpretation in terms of potential energy

For a conservative force,

$$
W_{0 \to x_0} = -(U(x_0) - U(0))
$$

Choose the reference level

$$
U(0) = 0
$$

Then

$$
-\frac{1}{2}k x_0^2 = -U(x_0)
$$

which gives

$$
U(x) = \frac{1}{2}kx^2
$$

### 5. Verification of the relation $F = -\frac{dU}{dx}$

Differentiate the potential energy:

$$
\frac{dU}{dx} = \frac{d}{dx}\left( \frac{1}{2}kx^2 \right)
$$

$$
\frac{dU}{dx} = kx
$$

Thus,

$$
-\frac{dU}{dx} = -kx
$$

Hence,

$$
F(x) = -\frac{dU}{dx}
$$

which is exactly the original force law.

### 6. Graphs of $F(x)$ and $U(x)$

The force

$$
F(x) = -kx
$$

is a straight line through the origin with negative slope.

The potential energy

$$
U(x) = \frac{1}{2}kx^2
$$

is an upward-opening parabola with minimum at $x=0$.

Thus:

- $F(x)$ is negative for $x>0$ and positive for $x<0$,
- $U(x)$ is always non-negative if $U(0)=0$,
- the equilibrium point $x=0$ is a stable minimum of the potential.

## Final Result

The equation of motion is

$$
m\ddot{x} + kx = 0
$$

The general solution is

$$
x(t) = A \cos\left( \sqrt{\frac{k}{m}}\, t \right) + B \sin\left( \sqrt{\frac{k}{m}}\, t \right)
$$

The work done during the displacement from $0$ to $x_0$ is

$$
W_{0 \to x_0} = -\frac{1}{2}k x_0^2
$$

The corresponding potential energy is

$$
U(x) = \frac{1}{2}kx^2
$$

The force-potential relation is

$$
F(x) = -\frac{dU}{dx}
$$

The graphs are:

- a linear function with negative slope for $F(x)$,
- an upward-opening parabola for $U(x)$.

## Interpretation

The force always points toward the equilibrium position, so it is a restoring force. A displacement away from equilibrium stores energy in the form of elastic potential energy.

The negative sign in the work expression

$$
W_{0 \to x_0} = -\frac{1}{2}k x_0^2
$$

shows that the force opposes the displacement away from equilibrium. The potential energy grows quadratically with displacement, which is the characteristic feature of harmonic motion.
# Task 09 – Vertical Throw with Linear Drag

## Problem Statement

The motion is described by

$$
m\frac{dv}{dt} = -mg - kv
$$

with initial conditions

$$
v(0) = v_0, \qquad x(0) = 10
$$

Determine:

1. the analytical solution for $v(t)$ and $x(t)$,
2. the maximum height,
3. the comparison with motion without drag,
4. a numerical simulation in Python.

## Theory

The differential equation

$$
m\frac{dv}{dt} = -mg - kv
$$

contains two forces:

- gravity: $-mg$,
- linear drag: $-kv$.

This is a first-order linear differential equation for the velocity.

After solving for $v(t)$, the position is obtained from

$$
\frac{dx}{dt} = v(t)
$$

The maximum height occurs when the upward velocity becomes zero:

$$
v(t_{\max}) = 0
$$

## Step-by-Step Solution

### 1. Rewrite the differential equation

Divide both sides by $m$:

$$
\frac{dv}{dt} + \frac{k}{m}v = -g
$$

Introduce the constant

$$
\beta = \frac{k}{m}
$$

Then the equation becomes

$$
\frac{dv}{dt} + \beta v = -g
$$

### 2. Solve for the velocity

This is a linear first-order equation. Its solution is

$$
v(t) = Ce^{-\beta t} - \frac{g}{\beta}
$$

Use the initial condition $v(0) = v_0$:

$$
v_0 = C - \frac{g}{\beta}
$$

Thus,

$$
C = v_0 + \frac{g}{\beta}
$$

Therefore,

$$
v(t) = \left( v_0 + \frac{g}{\beta} \right)e^{-\beta t} - \frac{g}{\beta}
$$

Since $\beta = \frac{k}{m}$, this can also be written as

$$
v(t) = \left( v_0 + \frac{mg}{k} \right)e^{-kt/m} - \frac{mg}{k}
$$

### 3. Solve for the position

Use

$$
\frac{dx}{dt} = v(t)
$$

Integrate:

$$
x(t) = x(0) + \int_0^t v(\tau)\,d\tau
$$

Substitute the velocity function:

$$
x(t) = 10 + \int_0^t \left[ \left( v_0 + \frac{g}{\beta} \right)e^{-\beta \tau} - \frac{g}{\beta} \right] d\tau
$$

Compute the integral term by term:

$$
\int_0^t e^{-\beta \tau} d\tau = \frac{1 - e^{-\beta t}}{\beta}
$$

Thus,

$$
x(t) = 10 + \left( v_0 + \frac{g}{\beta} \right)\frac{1 - e^{-\beta t}}{\beta} - \frac{g}{\beta}t
$$

In terms of $k$ and $m$,

$$
x(t) = 10 + \frac{m}{k}\left( v_0 + \frac{mg}{k} \right)\left( 1 - e^{-kt/m} \right) - \frac{mg}{k}t
$$

### 4. Determine the time of maximum height

At the highest point,

$$
v(t_{\max}) = 0
$$

Therefore,

$$
\left( v_0 + \frac{g}{\beta} \right)e^{-\beta t_{\max}} - \frac{g}{\beta} = 0
$$

Move the second term to the other side:

$$
\left( v_0 + \frac{g}{\beta} \right)e^{-\beta t_{\max}} = \frac{g}{\beta}
$$

Hence,

$$
e^{-\beta t_{\max}} = \frac{g/\beta}{v_0 + g/\beta}
$$

Taking the natural logarithm:

$$
t_{\max} = \frac{1}{\beta}\ln\left( \frac{v_0 + g/\beta}{g/\beta} \right)
$$

So,

$$
t_{\max} = \frac{1}{\beta}\ln\left( 1 + \frac{\beta v_0}{g} \right)
$$

or equivalently,

$$
t_{\max} = \frac{m}{k}\ln\left( 1 + \frac{k v_0}{mg} \right)
$$

### 5. Maximum height

Substitute $t_{\max}$ into $x(t)$:

$$
x_{\max} = 10 + \left( v_0 + \frac{g}{\beta} \right)\frac{1 - e^{-\beta t_{\max}}}{\beta} - \frac{g}{\beta}t_{\max}
$$

Using

$$
e^{-\beta t_{\max}} = \frac{g/\beta}{v_0 + g/\beta}
$$

one obtains

$$
1 - e^{-\beta t_{\max}} = \frac{v_0}{v_0 + g/\beta}
$$

Therefore,

$$
\left( v_0 + \frac{g}{\beta} \right)\frac{1 - e^{-\beta t_{\max}}}{\beta} = \frac{v_0}{\beta}
$$

Hence,

$$
x_{\max} = 10 + \frac{v_0}{\beta} - \frac{g}{\beta}t_{\max}
$$

Finally,

$$
x_{\max} = 10 + \frac{v_0}{\beta} - \frac{g}{\beta^2}\ln\left( 1 + \frac{\beta v_0}{g} \right)
$$

In terms of $k$ and $m$,

$$
x_{\max} = 10 + \frac{m v_0}{k} - \frac{m^2 g}{k^2}\ln\left( 1 + \frac{k v_0}{mg} \right)
$$

### 6. Comparison with motion without drag

Without drag, the equation becomes

$$
m\frac{dv}{dt} = -mg
$$

Then

$$
v(t) = v_0 - gt
$$

and

$$
x(t) = 10 + v_0 t - \frac{1}{2}gt^2
$$

The time to reach maximum height is

$$
t_{\max}^{(0)} = \frac{v_0}{g}
$$

The maximum height is

$$
x_{\max}^{(0)} = 10 + \frac{v_0^2}{2g}
$$

Since drag opposes the upward motion, the real trajectory with drag has:

- smaller maximum height,
- shorter ascent time,
- asymptotic approach of velocity to terminal value during descent.
### 7. Numerical simulation in Python

The following script computes and plots the position and velocity for chosen values of $m$, $k$, and $v_0$.

# Task 10 – Force Field and Power from a Given Trajectory

## Problem Statement

A particle of mass $m = 0.5 \ \mathrm{kg}$ moves according to

$$
x = 5t^2 - t, \qquad y = 2t^3, \qquad z = -3t + 2
$$

Determine the time dependence of:

1. velocity,
2. momentum,
3. acceleration,
4. force,
5. power transferred by the field.

## Theory

If the position vector is

$$
\vec r(t) = \bigl( x(t), y(t), z(t) \bigr)
$$

then:

- velocity is

$$
\vec v(t) = \frac{d\vec r}{dt}
$$

- acceleration is

$$
\vec a(t) = \frac{d\vec v}{dt}
$$

- momentum is

$$
\vec p(t) = m\vec v(t)
$$

- force is

$$
\vec F(t) = m\vec a(t)
$$

- instantaneous power is

$$
P(t) = \vec F(t) \cdot \vec v(t)
$$

## Step-by-Step Solution

### 1. Position vector

$$
\vec r(t) = \bigl( 5t^2 - t,\ 2t^3,\ -3t + 2 \bigr)
$$

### 2. Velocity

$$
\vec v(t) = \bigl( 10t - 1,\ 6t^2,\ -3 \bigr)
$$

### 3. Momentum

$$
\vec p(t) = \bigl( 5t - 0.5,\ 3t^2,\ -1.5 \bigr)
$$

### 4. Acceleration

$$
\vec a(t) = \bigl( 10,\ 12t,\ 0 \bigr)
$$

### 5. Force

$$
\vec F(t) = \bigl( 5,\ 6t,\ 0 \bigr)
$$

### 6. Power

$$
P(t) = 36t^3 + 50t - 5
$$

## Final Result

$$
\vec v(t) = (10t - 1,\ 6t^2,\ -3)
$$

$$
\vec p(t) = (5t - 0.5,\ 3t^2,\ -1.5)
$$

$$
\vec a(t) = (10,\ 12t,\ 0)
$$

$$
\vec F(t) = (5,\ 6t,\ 0)
$$

$$
P(t) = 36t^3 + 50t - 5
$$

## Interpretation

The motion is non-uniform, with time-dependent acceleration and power. The cubic term in power dominates at large times.
# Task 11 – Dynamics with a Time-Dependent Force

## Problem Statement

A particle of mass $m = 3 \ \mathrm{kg}$ moves under the force

$$
\vec F(t) = (15t,\ 3t - 12,\ -6t^2)
$$

with initial conditions

$$
\vec r(0) = (5,\ 2,\ -3), \qquad \vec v(0) = (2,\ 0,\ 1)
$$

Find $\vec v(t)$ and $\vec r(t)$.

## Theory

$$
\vec a(t) = \frac{\vec F(t)}{m}
$$

Velocity and position are obtained by integration.

## Step-by-Step Solution

### 1. Acceleration

$$
\vec a(t) = (5t,\ t - 4,\ -2t^2)
$$

### 2. Velocity

$$
\vec v(t) = \left( 2 + \frac{5}{2}t^2,\ \frac{1}{2}t^2 - 4t,\ 1 - \frac{2}{3}t^3 \right)
$$

### 3. Position

$$
\vec r(t) = \left( 5 + 2t + \frac{5}{6}t^3,\ 2 + \frac{1}{6}t^3 - 2t^2,\ -3 + t - \frac{1}{6}t^4 \right)
$$

## Final Result

$$
\vec v(t) = \left( 2 + \frac{5}{2}t^2,\ \frac{1}{2}t^2 - 4t,\ 1 - \frac{2}{3}t^3 \right)
$$

$$
\vec r(t) = \left( 5 + 2t + \frac{5}{6}t^3,\ 2 + \frac{1}{6}t^3 - 2t^2,\ -3 + t - \frac{1}{6}t^4 \right)
$$

## Interpretation

The motion is polynomial in time because the force depends on time. Each integration increases the order of the polynomial.
# Task 12 – Work and Energy with a Constant Force

## Problem Statement

A body of mass $m = 2 \ \mathrm{kg}$ is acted on by

$$
\vec F = (6,\ 2)
$$

with initial conditions

$$
\vec v(0) = (1,\ -1), \qquad \vec r(0) = (0,\ 0)
$$

Determine motion and verify the work-energy theorem.

## Theory

$$
\vec a = \frac{\vec F}{m}
$$

$$
\vec v(t) = \vec v_0 + \vec a t
$$

$$
\vec r(t) = \vec r_0 + \vec v_0 t + \frac{1}{2}\vec a t^2
$$

$$
W = \vec F \cdot \Delta \vec r
$$

## Step-by-Step Solution

### 1. Acceleration

$$
\vec a = (3,\ 1)
$$

### 2. Velocity

$$
\vec v(t) = (1 + 3t,\ -1 + t)
$$

### 3. Position

$$
\vec r(t) = \left( t + \frac{3}{2}t^2,\ -t + \frac{1}{2}t^2 \right)
$$

### 4. Work at $t=3$

$$
\Delta \vec r = (16.5,\ 1.5)
$$

$$
W = 102 \ \mathrm{J}
$$

### 5. Energy check

$$
\Delta K = 102 \ \mathrm{J}
$$

## Final Result

$$
\vec a = (3,\ 1)
$$

$$
\vec v(t) = (1 + 3t,\ -1 + t)
$$

$$
\vec r(t) = \left( t + \frac{3}{2}t^2,\ -t + \frac{1}{2}t^2 \right)
$$

$$
W = 102 \ \mathrm{J}
$$

$$
W = \Delta K
$$

## Interpretation

The work-energy theorem is satisfied exactly, confirming consistency between dynamics and energy methods.