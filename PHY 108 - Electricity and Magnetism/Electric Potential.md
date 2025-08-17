---
aliases:
  - voltage
---
For any given [Electric Field](electric%20field.md), there is energy. To place a [charge](Electric%20Charge.md) anywhere next to another charge, you must do some work to bring it there, since charges will always exert forces on each other, except at an infinite distance. 

The work that the electric puts on the charge as we bring a charge from infinity to some distance R away from another particle is represented by the following function:

$$
W_{you}=\int_{\infty}^R k\cdot \frac{q_1q_2}{r^2}dr \Rightarrow k\cdot \frac{q_1q_2}{R}
$$

The work that the charge does on our charge is stored as potential energy between the two charges and is equal to the work you do but negative, just as gravity does negative work on an object and puts it in gravitational potential energy when you lift it. 

Potential energy can be generalized, similar to electric fields, by dividing it by a test charge. This new quality, the joules per coulomb in an electric field, is called *electric potential*, and is represented in volts (V).

$$
V=k\cdot \frac{q}{r}
$$


The voltage, or potential difference of two points in an electric field may be obtained using the following line integral. 

$$
\Delta V = -\int_{r_1}^{r_2} \vec{E} \cdot dr
$$

The integral is negative because if a test charge (positive) went in the direction of the electric field, its potential would decrease (the electric field is helping it move).

Using the previous equation, it is also possible to find the amount of work to bring a given charge from one voltage to another by multiplying both sides of the equation.

$$
q\Delta V = q\int_{r_1}^{r_2} \vec{E} \cdot dr = \int_{r_1}^{r_2} \vec{F_e} \cdot dr = w_{you}
$$