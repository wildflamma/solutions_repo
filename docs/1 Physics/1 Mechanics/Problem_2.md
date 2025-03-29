# Problem 2
# Investigating the Dynamics of a Forced Damped Pendulum

## Motivation
The forced damped pendulum is a captivating example of a physical system with intricate behavior resulting from the interplay of damping, restoring forces, and external driving forces. These phenomena serve as a foundation for understanding complex real-world systems, such as driven oscillators, climate systems, and mechanical structures under periodic stress.

## Theoretical Foundation
The equation governing a forced damped pendulum is:

$$ \ddot{\theta} + b \dot{\theta} + \frac{g}{L} \sin(\theta) = A \cos(\omega t) $$

For small angles, $$ \sin(\theta) \approx \theta $$, leading to a linearized equation that can be solved analytically. However, for large angles, numerical solutions are needed.

## Analysis of Dynamics
- Low damping leads to oscillations close to simple harmonic motion.
- At resonance, the system absorbs maximum energy.
- With high forcing, chaotic behavior can emerge.

## Practical Applications
- Energy harvesting
- Suspension bridges (Tacoma Narrows collapse)
- Oscillating circuits (RLC circuits)

## Implementation
We solve the equation numerically using the Runge-Kutta method.
![alt text](image-5.png)


### Phase Space Analysis
We also plot the phase portrait.

![alt text](image-6.png)
```

 Deliverables
- Theoretical derivations of projectile motion and forced damped pendulum dynamics.
- Python implementations for simulations and visualizations.
- Discussions on real-world applications and model limitations.

These analyses provide insights into classical mechanics while connecting them to modern engineering.


