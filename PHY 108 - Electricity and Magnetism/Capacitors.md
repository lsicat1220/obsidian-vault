A capacitor is a device in a circuit that stores electric energy by storing opposite [electric charges](electric%20charge.md) on two closely spaced surfaces. The charge it can store is determined by its [Capacitance](capacitance.md) and the [voltage](electric%20potential.md) of the battery it's connected to:

$$
q=CV
$$

When a capacitor is connected to a battery in a [circuit](Circuits.md), the battery will bring electrons from one plate to the other against equilibrium until the voltage held by the capacitor matches that of the battery, increasing the potential energy of the capacitor by the amount of work the battery does. The work the battery has to do to bring a charge to the other side increases for each charge already brought over, so we must integrate it over each charge to find the total work:

$$
W_{battery} = \int_0^q V dq = \int_0^q \frac{q}{C}dq = \frac{q^2}{2C}
$$

When it is charged and placed in a circuit where electrons can flow freely, the electrons that have been pushed to the negative plate will rush back to the other side to re-achieve equilibrium, releasing the stored up potential energy. 