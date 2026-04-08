# Section 3 – Waves

## Task 1 – Wave Properties

## Problem Statement

A sound wave in air has a frequency of $440 \ \text{Hz}$. If the speed of sound in air is $343 \ \text{m/s}$, determine its wavelength. Then determine its wavelength in water, where the speed of sound is $1482 \ \text{m/s}$.

## Theory

For a wave with speed $v$, frequency $f$, and wavelength $\lambda$, the basic relation is

$$
v = f \lambda
$$

Therefore,

$$
\lambda = \frac{v}{f}
$$

When a wave passes from one medium to another, its frequency remains constant, while its speed and wavelength change.

## Step-by-Step Solution

### Wavelength in Air

Use

$$
\lambda_{\text{air}} = \frac{v_{\text{air}}}{f}
$$

Substitute the values:

$$
\lambda_{\text{air}} = \frac{343}{440} \ \text{m}
$$

This gives

$$
\lambda_{\text{air}} \approx 0.780 \ \text{m}
$$

### Wavelength in Water

The frequency remains the same, so

$$
\lambda_{\text{water}} = \frac{v_{\text{water}}}{f}
$$

Substitute the values:

$$
\lambda_{\text{water}} = \frac{1482}{440} \ \text{m}
$$

Hence,

$$
\lambda_{\text{water}} \approx 3.37 \ \text{m}
$$

## Final Result

In air:

$$
\lambda_{\text{air}} \approx 0.780 \ \text{m}
$$

In water:

$$
\lambda_{\text{water}} \approx 3.37 \ \text{m}
$$

## Interpretation

The wave has a much larger wavelength in water because the speed of sound is much greater there. The frequency is fixed by the source, so the wavelength must increase when the speed increases.

---

## Task 2 – String Harmonics

## Problem Statement

A guitar string is $64 \ \text{cm}$ long and has a fundamental frequency of $330 \ \text{Hz}$. Determine the speed of the wave on the string.

## Theory

For a string fixed at both ends, the fundamental mode has one antinode and satisfies

$$
L = \frac{\lambda_1}{2}
$$

Thus,

$$
\lambda_1 = 2L
$$

The wave speed is then

$$
v = f \lambda
$$

## Step-by-Step Solution

Convert the length to meters:

$$
L = 64 \ \text{cm} = 0.64 \ \text{m}
$$

For the fundamental mode,

$$
\lambda_1 = 2L = 2(0.64) = 1.28 \ \text{m}
$$

Now use the wave relation:

$$
v = f \lambda_1
$$

Substitute the values:

$$
v = 330 \times 1.28 \ \text{m/s}
$$

Therefore,

$$
v = 422.4 \ \text{m/s}
$$

## Final Result

$$
v = 422.4 \ \text{m/s}
$$

## Interpretation

The wave speed on the string is determined by the string tension and linear mass density. The frequency alone does not fix the speed unless the boundary condition and wavelength are also known.

---

## Task 3 – Superposition Principle

## Problem Statement

Two waves are described by

$$
y_1(x,t) = A \sin(kx - \omega t)
$$

and

$$
y_2(x,t) = A \sin(kx + \omega t)
$$

Determine the resulting standing wave and identify the node positions.

## Theory

The total displacement is the sum of the two waves:

$$
y(x,t) = y_1(x,t) + y_2(x,t)
$$

A useful trigonometric identity is

$$
\sin(\alpha - \beta) + \sin(\alpha + \beta) = 2 \sin \alpha \cos \beta
$$

A standing wave forms when two waves of equal amplitude and frequency travel in opposite directions.

## Step-by-Step Solution

Add the two waves:

$$
y(x,t) = A \sin(kx - \omega t) + A \sin(kx + \omega t)
$$

Factor out $A$:

$$
y(x,t) = A \left[ \sin(kx - \omega t) + \sin(kx + \omega t) \right]
$$

Apply the trigonometric identity with

$$
\alpha = kx
$$

and

$$
\beta = \omega t
$$

Then

$$
y(x,t) = 2A \sin(kx) \cos(\omega t)
$$

This is the equation of a standing wave.

### Node Positions

Nodes occur where the displacement is always zero, so the spatial factor must vanish:

$$
\sin(kx) = 0
$$

This occurs when

$$
kx = n\pi
$$

where $n = 0, 1, 2, 3, \dots$

Using

$$
k = \frac{2\pi}{\lambda}
$$

gives

$$
\frac{2\pi}{\lambda} x = n\pi
$$

Hence,

$$
x = \frac{n\lambda}{2}
$$

## Final Result

Standing wave:

$$
y(x,t) = 2A \sin(kx) \cos(\omega t)
$$

Node positions:

$$
x = \frac{n\lambda}{2}
\quad \text{for} \quad
n = 0, 1, 2, 3, \dots
$$

## Interpretation

The amplitude of oscillation depends on position through the factor $2A \sin(kx)$. At nodes, the displacement is always zero. Between nodes, the string oscillates with maximum amplitude at antinodes.

---

## Task 4 – Phase Difference

## Problem Statement

Determine the phase difference between two points on a wave separated by a distance of $\lambda/3$.

## Theory

For a sinusoidal wave, the phase difference corresponding to a distance $\Delta x$ is

$$
\Delta \phi = k \Delta x
$$

where

$$
k = \frac{2\pi}{\lambda}
$$

Therefore,

$$
\Delta \phi = \frac{2\pi}{\lambda} \Delta x
$$

## Step-by-Step Solution

Given

$$
\Delta x = \frac{\lambda}{3}
$$

Substitute into the phase relation:

$$
\Delta \phi = \frac{2\pi}{\lambda} \cdot \frac{\lambda}{3}
$$

The wavelengths cancel:

$$
\Delta \phi = \frac{2\pi}{3}
$$

## Final Result

$$
\Delta \phi = \frac{2\pi}{3} \ \text{rad}
$$

## Interpretation

A separation of one full wavelength corresponds to a phase difference of $2\pi$. Therefore, a separation of one-third of a wavelength corresponds to one-third of a full phase cycle.

---

## Task 5 – Echo Ranging

## Problem Statement

A person shouts toward a cliff and hears the echo $1 \ \text{s}$ later. Determine the distance to the cliff. The speed of sound is $343 \ \text{m/s}$.

## Theory

The echo time is the time for the sound to travel to the cliff and back. Therefore, the total distance traveled by the sound is

$$
d_{\text{total}} = vt
$$

The one-way distance to the cliff is half of this:

$$
d = \frac{vt}{2}
$$

## Step-by-Step Solution

Given

$$
v = 343 \ \text{m/s}
$$

and

$$
t = 1 \ \text{s}
$$

The total distance traveled by the sound is

$$
d_{\text{total}} = 343 \times 1 = 343 \ \text{m}
$$

The distance to the cliff is

$$
d = \frac{343}{2} = 171.5 \ \text{m}
$$

## Final Result

$$
d = 171.5 \ \text{m}
$$

## Interpretation

The sound wave travels the distance twice: once to the cliff and once back to the observer. This is why the measured time must be divided by two.

---

## Task 6 – Wave Equation Parameters

## Problem Statement

A wave is described by

$$
y(x,t) = 0.05 \sin(2\pi x - 50\pi t)
$$

where $x$ and $y$ are in meters and $t$ is in seconds. Determine:

1. Amplitude $A$
2. Wavelength $\lambda$
3. Frequency $f$
4. Wave speed $v$

## Theory

The standard form of a traveling wave is

$$
y(x,t) = A \sin(kx - \omega t)
$$

where

$$
k = \frac{2\pi}{\lambda}
$$

and

$$
\omega = 2\pi f
$$

The wave speed is

$$
v = \frac{\omega}{k} = f\lambda
$$

## Step-by-Step Solution

Compare the given equation

$$
y(x,t) = 0.05 \sin(2\pi x - 50\pi t)
$$

with the standard form

$$
y(x,t) = A \sin(kx - \omega t)
$$

This gives:

$$
A = 0.05 \ \text{m}
$$

$$
k = 2\pi \ \text{rad/m}
$$

$$
\omega = 50\pi \ \text{rad/s}
$$

### a) Amplitude

$$
A = 0.05 \ \text{m}
$$

### b) Wavelength

Use

$$
k = \frac{2\pi}{\lambda}
$$

Substitute $k = 2\pi$:

$$
2\pi = \frac{2\pi}{\lambda}
$$

Hence,

$$
\lambda = 1 \ \text{m}
$$

### c) Frequency

Use

$$
\omega = 2\pi f
$$

Substitute $\omega = 50\pi$:

$$
50\pi = 2\pi f
$$

Therefore,

$$
f = 25 \ \text{Hz}
$$

### d) Wave Speed

Use either

$$
v = f\lambda
$$

or

$$
v = \frac{\omega}{k}
$$

Using $f = 25 \ \text{Hz}$ and $\lambda = 1 \ \text{m}$:

$$
v = 25 \times 1 = 25 \ \text{m/s}
$$

## Final Result

Amplitude:

$$
A = 0.05 \ \text{m}
$$

Wavelength:

$$
\lambda = 1 \ \text{m}
$$

Frequency:

$$
f = 25 \ \text{Hz}
$$

Wave speed:

$$
v = 25 \ \text{m/s}
$$

## Interpretation

All wave parameters can be read directly from the standard sinusoidal form once the coefficients of $x$ and $t$ are identified as the wave number and angular frequency.

---

## Task 7 – Standing Wave Modes

## Problem Statement

A standing wave with four antinodes is produced on a string of length $L = 80 \ \text{cm}$. Determine the wavelength.

## Theory

For a string fixed at both ends, the standing-wave condition is

$$
L = n \frac{\lambda}{2}
$$

where $n$ is the number of half-wavelength segments on the string. For a fixed string, the number of antinodes equals $n$.

## Step-by-Step Solution

The string has four antinodes, so

$$
n = 4
$$

The length is

$$
L = 80 \ \text{cm} = 0.80 \ \text{m}
$$

Use the standing-wave condition:

$$
L = n \frac{\lambda}{2}
$$

Substitute the values:

$$
0.80 = 4 \frac{\lambda}{2}
$$

Simplify:

$$
0.80 = 2\lambda
$$

Therefore,

$$
\lambda = 0.40 \ \text{m}
$$

## Final Result

$$
\lambda = 0.40 \ \text{m}
$$

## Interpretation

Four antinodes mean that the string contains four half-wavelength segments. Thus the full wavelength is shorter than the string length.

---

## Task 8 – Traveling Wave Condition

## Problem Statement

Determine which of the following functions satisfy the wave equation

$$
\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y}{\partial t^2}
$$

The candidate functions are:

a) $y(x,t) = A \cos(kx^2 - \omega t)$

b) $y(x,t) = A(x-vt)^2$

c) $y(x,t) = A \log(x+vt)$

## Theory

A function of the form

$$
y(x,t) = f(x-vt)
$$

or

$$
y(x,t) = f(x+vt)
$$

is a traveling-wave solution of the one-dimensional wave equation, provided the necessary derivatives exist.

If

$$
\xi = x \mp vt
$$

then

$$
\frac{\partial^2 y}{\partial x^2} = f''(\xi)
$$

and

$$
\frac{\partial^2 y}{\partial t^2} = v^2 f''(\xi)
$$

Therefore,

$$
\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2} \frac{\partial^2 y}{\partial t^2}
$$

## Step-by-Step Solution

### a) $y(x,t) = A \cos(kx^2 - \omega t)$

This function depends on $x^2$, not on the combination $x \mp vt$. Therefore it does not preserve a fixed waveform translated at constant speed.

Hence it does not satisfy the standard wave equation.

### b) $y(x,t) = A(x-vt)^2$

This has the form

$$
y(x,t) = f(x-vt)
$$

with

$$
f(\xi) = A\xi^2
$$

Therefore it satisfies the wave equation.

A direct check gives

$$
\frac{\partial^2 y}{\partial x^2} = 2A
$$

and

$$
\frac{\partial^2 y}{\partial t^2} = 2Av^2
$$

so indeed

$$
\frac{1}{v^2} \frac{\partial^2 y}{\partial t^2} = 2A = \frac{\partial^2 y}{\partial x^2}
$$

### c) $y(x,t) = A \log(x+vt)$

This has the form

$$
y(x,t) = f(x+vt)
$$

with

$$
f(\xi) = A \log \xi
$$

Therefore it also satisfies the wave equation on the domain where the logarithm is defined, namely

$$
x + vt > 0
$$

A direct check gives

$$
\frac{\partial^2 y}{\partial x^2} = -\frac{A}{(x+vt)^2}
$$

and

$$
\frac{\partial^2 y}{\partial t^2} = -\frac{Av^2}{(x+vt)^2}
$$

thus

$$
\frac{1}{v^2} \frac{\partial^2 y}{\partial t^2} = -\frac{A}{(x+vt)^2}
$$

which matches the spatial second derivative.

## Final Result

The functions that satisfy the wave equation are

$$
\text{(b)} \quad y(x,t) = A(x-vt)^2
$$

and

$$
\text{(c)} \quad y(x,t) = A \log(x+vt)
$$

The function

$$
\text{(a)} \quad y(x,t) = A \cos(kx^2 - \omega t)
$$

does not satisfy the wave equation.

## Interpretation

A traveling-wave solution must depend on space and time through the combinations $x-vt$ or $x+vt$. This guarantees that the shape translates without distortion.

---

## Task 9 – Damped Oscillator

## Problem Statement

For the damped harmonic oscillator

$$
m \frac{d^2 x}{dt^2} + b \frac{dx}{dt} + k x = 0
$$

state the general solution, classify the damping regimes, formulate the numerical RK4 method, and describe how the parameter $b$ affects the graphs of $x(t)$ and the phase portrait.

## Theory

The equation can be written as

$$
m \ddot{x} + b \dot{x} + kx = 0
$$

The characteristic equation is

$$
mr^2 + br + k = 0
$$

with roots

$$
r = \frac{-b \pm \sqrt{b^2 - 4mk}}{2m}
$$

The discriminant

$$
\Delta = b^2 - 4mk
$$

determines the qualitative behavior.

## Step-by-Step Solution

### 1. General Solution

#### Underdamped Case

If

$$
b^2 < 4mk
$$

define

$$
\gamma = \frac{b}{2m}
$$

and

$$
\omega_d = \sqrt{\frac{k}{m} - \gamma^2}
$$

Then the solution is

$$
x(t) = e^{-\gamma t} \left( C_1 \cos(\omega_d t) + C_2 \sin(\omega_d t) \right)
$$

#### Critically Damped Case

If

$$
b^2 = 4mk
$$

the repeated root is

$$
r = -\frac{b}{2m}
$$

and the solution is

$$
x(t) = (C_1 + C_2 t)e^{-bt/(2m)}
$$

#### Overdamped Case

If

$$
b^2 > 4mk
$$

the two roots are real:

$$
r_{1,2} = \frac{-b \pm \sqrt{b^2 - 4mk}}{2m}
$$

and the solution is

$$
x(t) = C_1 e^{r_1 t} + C_2 e^{r_2 t}
$$

### 2. Classification of Cases

The critical damping value is

$$
b_c = 2\sqrt{mk}
$$

Thus:

Underdamped:

$$
b < b_c
$$

Critically damped:

$$
b = b_c
$$

Overdamped:

$$
b > b_c
$$

### 3. Numerical Formulation with RK4

Introduce the velocity

$$
v = \dot{x}
$$

Then the second-order equation becomes the first-order system

$$
\dot{x} = v
$$

$$
\dot{v} = -\frac{b}{m}v - \frac{k}{m}x
$$

Let the state vector be

$$
\mathbf{y} =
\begin{pmatrix}
x \\
v \\
\end{pmatrix}
$$

Then

$$
\frac{d\mathbf{y}}{dt} =
\begin{pmatrix}
v \\
-\frac{b}{m}v - \frac{k}{m}x \\
\end{pmatrix}
$$

For time step $h$, the RK4 update is

$$
\begin{align}
\mathbf{k}_1 &= \mathbf{F}(t_n,\mathbf{y}_n) \\
\mathbf{k}_2 &= \mathbf{F}\left(t_n + \frac{h}{2}, \mathbf{y}_n + \frac{h}{2}\mathbf{k}_1\right) \\
\mathbf{k}_3 &= \mathbf{F}\left(t_n + \frac{h}{2}, \mathbf{y}_n + \frac{h}{2}\mathbf{k}_2\right) \\
\mathbf{k}_4 &= \mathbf{F}(t_n + h, \mathbf{y}_n + h\mathbf{k}_3)
\end{align}
$$

and

$$
\mathbf{y}_{n+1} = \mathbf{y}_n + \frac{h}{6}\left(\mathbf{k}_1 + 2\mathbf{k}_2 + 2\mathbf{k}_3 + \mathbf{k}_4\right)
$$

### 4. Effect of the Parameter $b$

For small $b$, the motion remains oscillatory and the amplitude decays slowly.

As $b$ increases toward the critical value, the oscillations disappear and the return to equilibrium becomes faster.

For $b > b_c$, the motion is non-oscillatory but slower than the critically damped case.

### 5. Graph of $x(t)$

The displacement graph has the following qualitative forms:

- underdamped: oscillatory decay,
- critically damped: fastest monotonic return to equilibrium,
- overdamped: slow monotonic return.

### 6. Phase Portrait

In the $(x,v)$ plane:

- underdamped motion spirals toward the origin,
- critically damped motion approaches the origin without spiraling,
- overdamped motion also approaches without spiraling, but along a slower trajectory.

## Final Result

The damped oscillator is classified by the comparison of $b$ with

$$
b_c = 2\sqrt{mk}
$$

The analytical and numerical descriptions agree:

- $b < b_c$: oscillatory decay,
- $b = b_c$: fastest non-oscillatory decay,
- $b > b_c$: slower non-oscillatory decay.

## Interpretation

The damping coefficient governs energy loss. The larger the value of $b$, the more rapidly energy is dissipated. However, the fastest return to equilibrium without oscillation occurs not for very large damping, but exactly at critical damping.

---

## Task 10 – Superposition of Waves from Multiple Sources

## Problem Statement

Consider point sources that generate waves of the form

$$
u(\vec{r},t) = \frac{A}{|\vec{r}-\vec{r_0}|^\alpha} \sin(k |\vec{r} - \vec{r_0}| - \omega t)
$$

where $\vec{r_0}$ is the source position and $\alpha \in [0,2]$. Formulate the total wave field and describe how the parameter $\alpha$ influences the observed pattern.

## Theory

If several sources are present, the total displacement is the sum of all partial waves:

$$
u_{\text{tot}}(\vec{r},t) = \sum_{i=1}^{N} \frac{A}{|\vec{r}-\vec{r_i}|^\alpha} \sin(k |\vec{r} - \vec{r_i}| - \omega t)
$$

The wave number and wavelength are related by

$$
k = \frac{2\pi}{\lambda}
$$

The factor

$$
\frac{1}{|\vec{r}-\vec{r_i}|^\alpha}
$$

describes how the amplitude decreases with distance from each source.

## Step-by-Step Solution

### 1. Field of a Single Source

For one source located at $\vec{r_0}$, the field depends on the distance

$$
r = |\vec{r} - \vec{r_0}|
$$

and is given by

$$
u(\vec{r},t) = \frac{A}{r^\alpha} \sin(kr - \omega t)
$$

### 2. Superposition of Many Sources

If the source positions are $\vec{r_1}, \vec{r_2}, \dots, \vec{r_N}$, then the total field is

$$
u_{\text{tot}}(\vec{r},t) = \sum_{i=1}^{N} \frac{A}{|\vec{r}-\vec{r_i}|^\alpha} \sin(k |\vec{r} - \vec{r_i}| - \omega t)
$$

### 3. Role of the Parameter $\alpha$

If

$$
\alpha = 0
$$

then the amplitude does not decay with distance.

If

$$
\alpha = 1
$$

the amplitude decreases inversely with distance.

If

$$
\alpha = 2
$$

the amplitude decreases more strongly, so distant sources contribute much less.

### 4. Numerical Consideration

At points very close to a source, the factor $1/r^\alpha$ becomes very large. In numerical work, one usually introduces a small cutoff

$$
r_{\text{eff}} = \max(r,\varepsilon)
$$

to avoid singular behavior.

## Final Result

The total displacement field produced by all sources is

$$
u_{\text{tot}}(\vec{r},t) = \sum_{i=1}^{N} \frac{A}{|\vec{r}-\vec{r_i}|^\alpha} \sin(k |\vec{r} - \vec{r_i}| - \omega t)
$$

with

$$
k = \frac{2\pi}{\lambda}
$$

The exponent $\alpha$ controls the spatial decay of the source amplitude.

## Interpretation

This model illustrates interference in a system of many emitters. Small values of $\alpha$ allow long-range influence from each source, whereas larger values emphasize local effects near each source.

---

## Task 11 – Two-Slit Interference

## Problem Statement

In Young's experiment, two slits act as coherent point sources. The resultant wave is

$$
u(\vec{r},t) = \frac{A}{|\vec{r}-\vec{r_1}|} \sin(k |\vec{r} - \vec{r_1}| - \omega t) + \frac{A}{|\vec{r}-\vec{r_2}|} \sin(k |\vec{r} - \vec{r_2}| - \omega t)
$$

Describe the interference pattern and determine how it depends on slit separation $d = |\vec{r_1} - \vec{r_2}|$ and wavelength $\lambda$.

## Theory

Let

$$
r_1 = |\vec{r} - \vec{r_1}|
$$

and

$$
r_2 = |\vec{r} - \vec{r_2}|
$$

Then the total field is

$$
u(\vec{r},t) = \frac{A}{r_1} \sin(k r_1 - \omega t) + \frac{A}{r_2} \sin(k r_2 - \omega t)
$$

where

$$
k = \frac{2\pi}{\lambda}
$$

Interference depends on the path difference

$$
\Delta r = r_2 - r_1
$$

### Conditions for Interference

Constructive interference occurs when

$$
\Delta r = m\lambda
$$

where $m$ is an integer.

Destructive interference occurs when

$$
\Delta r = \left(m + \frac{1}{2}\right)\lambda
$$

## Step-by-Step Solution

### 1. Geometry of the Two Sources

If the slit separation is $d$, the source positions may be written as

$$
\vec{r_1} = (x_0, y_0 - d/2)
$$

and

$$
\vec{r_2} = (x_0, y_0 + d/2)
$$

### 2. Field at an Observation Point

At point $\vec{r}$, the total displacement is

$$
u(\vec{r},t) = \frac{A}{r_1} \sin(k r_1 - \omega t) + \frac{A}{r_2} \sin(k r_2 - \omega t)
$$

The local amplitude depends on the phase difference produced by the different path lengths.

### 3. Effect of Slit Separation

If $d$ increases, the path difference changes more rapidly across space. Therefore the fringes become more closely spaced.

### 4. Effect of Wavelength

If $\lambda$ increases, the constructive and destructive conditions are satisfied at larger spatial intervals. Therefore the fringes become more widely spaced.

## Final Result

The interference pattern is determined by the path difference

$$
\Delta r = r_2 - r_1
$$

with maxima at

$$
\Delta r = m\lambda
$$

and minima at

$$
\Delta r = \left(m + \frac{1}{2}\right)\lambda
$$

A larger slit separation produces narrower fringe spacing, while a larger wavelength produces wider fringe spacing.

## Interpretation

Young's experiment demonstrates the wave nature of light or any coherent wave. The alternating bright and dark bands are a direct consequence of superposition and phase difference between the two coherent sources.