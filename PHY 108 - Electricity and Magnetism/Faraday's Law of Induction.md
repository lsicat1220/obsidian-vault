Faraday's Law of Induction states that an [emf](Electromotive%20Force.md) in a [circuit](Circuits.md) may be induced by a changing [Magnetic Flux](magnetic%20flux.md). 

$$
\xi = - \frac{d\Phi_B}{dt}
$$

To find the magnetic flux through a coil of N turns, we simply multiply this equation by N.

However, there doesn't need to be a circuit to induce an emf. Since charges will move due to this changing magnetic field, we may say that a current will produce an electric field at any loop around it, which will do work on a charge at every point in the closed loop. Mathematically, this relationship looks like this:

$$
\xi = \oint \vec{E} \cdot d\vec{s} = -\frac{d\Phi_B}{dt}
$$

Essentially, what this law states is that if a magnetic field in an area changes, the charges in that area will try to oppose the change in electric flux by creating its own change in magnetic flux. However, as soon as the magnetic flux stops changing, there is no more reaction from the charges. 

This law also means that circuits, especially those with an [inductor](inductors.md), will resist a change in the current, since a current will inevitably [create a magnetic field around it](Biot-Savart%20Law.md), creating a change in magnetic flux that the charges will want to oppose. As a result, there is an opposing emf that will only diminish once the current stabilizes. This is known as self-induction.

$$
\xi_L = -\frac{d(N\Phi)}{dt} \Rightarrow -L \frac{di}{dt}
$$