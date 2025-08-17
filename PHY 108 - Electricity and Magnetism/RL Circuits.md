An RL circuit is a [circuit](Circuits.md) that includes a resistor and an [inductor](Inductors.md). Generally, when a circuit with a battery and resistor is completed, the current very rapidly increases to the maximum current dictated by Ohm's law. However, with the presence of an inductor, a greater magnetic field is induced within the inductor, meaning that there is a greater resistance to rapid changes in current, determined by the inductor's [Inductance](inductance.md).

When the RL circuit is completed, the current will initially start to increase rapidly but will slow down as it approaches the maximum current. Mathematically, this works out to be:

$$
i=\frac{\xi}{R} (1-e^{-t/\tau})
$$

Where tau, the time constant, is $L/R$. 