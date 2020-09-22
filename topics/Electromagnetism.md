---
title: Electromagnetism
layout: default
description: OwO
use_math: true
---

### Magnetic Field

| Symbol    | Description                                      |
| --------- | ------------------------------------------------ |
| $$\mu$$     | Magnetic Permeability. $$\mu_0=4\pi\times10^{-7}$$ |
| $$\vec{B}$$ | Magnetic Field (Vector field)                    |

#### 1. Long Straight Wires

$$
\lvert\vec{B}\rvert=\frac{\mu_0\cdot I}{2 \pi r}
$$

**Note:** Use right hand rule to find out the direction of the magnetic field

#### 2. Flat Circular Loop

$$
\lvert\vec{B}\rvert=\frac{\mu_0\cdot I}{2r}
$$

**If** $$N$$ loops are to be stacked (and the current's direction is the same)
$$
\lvert\vec{B}\rvert=N\times\frac{\mu_0\cdot I}{2r}
$$

**Note:** This is only valid at the center of the loop

#### 3. Solenoid

$$
\lvert\vec{B}\rvert=\mu_0 nI
$$

- $$n$$ is number of loops per unit length of the solenoid, $$n=N\div l$$

- $$N$$ is number of loops
- $$l$$ is the length of the solenoid

**Note:** The field inside of a solenoid is nearly uniform in direction and magnitude, only near the ends does it begin to weaken and change direction.

#### 4. Permeability

$$
\mu=\mu_r\mu_0
$$

**e.g.** $$\mu_r$$ of iron is about 5000, this means that the magnetic field of a solenoid with an iron core would be about 5000 times stronger
**Note:** $$\mu_r$$ is not constant and will depend on the 'magnetisation history' of the material.

### Magnetic Force

![FBI mnemonics - Wikipedia](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/ManoLaplace.svg/220px-ManoLaplace.svg.png)

#### 1. Force of magnetic field on a wire

$$
\vec{F}=\vec{I}L\times\vec{B}\quad\text{and/or}\quad|\vec{F}|=ILB\sin{\alpha}
$$
**Note:** $$\vec{I}$$ is **conventional current**
**Note:** Use Fleming's **left** hand rule to find the direction of the force
**Note:** $$\alpha$$ is the angle between the magnetic field's direction and the wire's direction

#### 2. Force of magnetic field on a moving charge

$$
\vec{F}=q\vec{v}\times\vec{B}\quad\text{and/or}\quad|\vec{F}|=qvB\sin{\alpha}
$$

**Note:** If the charge is not moving, there is no force
**Note:** $$\alpha$$ is the angle between the magnetic field's direction and the charge's velocity's direction

### Circular motion of particle in a magnetic field

Since $$a=\frac{v^2}{R}$$ and $$F=ma$$, $$F=qvB=m\frac{v^2}{R}\ \Rightarrow\ R=\frac{mv}{qB}$$



| Electric Field (E) | Electric Potential (V) | Magnetic Field (B) |
|---|---|---|
| ![E-field Charge+Charge](https://www.expunctis.com/images/2018-06-10/E_1_1.png) | ![V-Field Charge+Charge](https://www.expunctis.com/images/2018-06-10/V_1_1.png) | ![B-field Wire Same Direction](https://www.expunctis.com/images/2018-06-10/B_1_1.png) |
| ![E-field different charge](https://www.expunctis.com/images/2018-06-10/E_-03_1.png) | ![V-field different charge](https://www.expunctis.com/images/2018-06-10/V_-03_1.png) | ![B-field Opposite direction](https://www.expunctis.com/images/2018-06-10/B_-03_1.png) |
