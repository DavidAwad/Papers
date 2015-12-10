## Electromagnetism II Notes
### David Awad


Proportionality of potential and charge on a conductor leads to $$$Q = C V$$$, defining the capacitance $$$C$$$.

<!-- SECTION 1 -->

#### Energy per unit volume in an electric field

$$\frac{E^2}{2 ε_0}$$


#### Fields of conductors
Because the surface of a conductor is necessarily a surface of constant potential, the electric field, which is $$$\nabla \varphi$$$ must be *perpendicular* to the surface on at every point.
 
At any point just outside the conductor $$$\textbf{E}$$$ is perpendicular to the surface, and $$$\textbf{E} = 4\pi\sigma $$$ where $$$\sigma$$$ is the local density of surface charge. 

$$ Q_k = \int_{S_k} \sigma da = \frac{1}{4\pi} \int \textbf{E} \cdot d\textbf{a} $$

#### Simple Conductors

Let's examine two simple spherical conductors, with sphere of charge $$$Q_1$$$ encapsulating the smaller sphere of charge $$$Q_2$$$. 

This shouldn't be too different from what you may have seen before, outside the sphere the potential $$$\varphi$$$ is the following.  

$$ \frac{Q_1 + Q_2}{R_1}$$

The inner sphere is a bit trickier. 

$$ \varphi = \frac{Q_1 + Q_2}{R_1} + \int_{R_1}^{R_2} -\frac{Q^2}{r^2} dr = \frac{Q_1}{R_1} + \frac{Q_2}{R_2} $$


#### Potential of a conducting disk

$$ \phi = \frac{(\pi/2) Q}{a} $$

Where $$$\phi$$$ is the electric potential, $$$Q$$$ is the charge on the disk, and $$$a$$$ is the radius. 

**Capacitance** - the ability of a body to store an electrical charge. Any object that can be electrically charged exhibits capacitance. 

#### Energy stored in a generic capacitor

 $$ U = \frac{QV}{2} = \frac{CV^2}{2}=   \frac{Q^2}{2C} $$

#### Parallel Plate Capacitors:

-> ![](http://i.imgur.com/BYxKajS.png) <-

The capacitance of two conducting plates separated a distance $$$s$$$ apart from each other. 

$$ C = \frac{A(in \space cm^2)}{4\pi s} $$

The charge is simply a function of the difference in the potentials of the two plates. 

$$ Q = C (\varphi_1 - \varphi_2) $$

-> ![](http://i.imgur.com/KJD3OCG.png) <-

#### Enclosed capacitors

If a capacitor of charge $$$Q_1$$$ is enclosed inside of another capacitor of charge $$$Q_2$$$, then the capacitance is defined as the following. 


<!--
#### Laplace's equation

Laplace's equation and Poisson's equation are the simplest examples of elliptic partial differential equations. The general theory of solutions to Laplace's equation is known as potential theory. Note that here, $$$\varphi$$$ is the potential function. 

$$ \nabla^2 \varphi = 0 $$ 

In three dimensions, the problem is to find twice-differentiable real-valued functions f, of real variables x, y, and z, such that


$$	\nabla^2 \varphi = {\partial^2\varphi\over \partial x^2 } +
	{\partial^2\varphi \over \partial y^2 } +
	{\partial^2\varphi\over \partial z^2 } = 0 $$

--> 

#### Energy stored in a capacitor

Suppose we moved a charge from the negative plate to the positive one. Performing some work and increasing the charge from $$$Q$$$ to $$$Q + dQ$$$. 

$$ W = \frac{1}{C} \int_{Q=0}^{Q_f} Q dQ = \frac{Q_f^2}{2C}  $$ 

This is the energy $$$U$$$ which is stored in the capacitor. It can also be expressed by

$$ U = 1/2 C \varphi^2$$

For the capacitor with area $$$A$$$ and separation $$$s$$$ we found that 

$$C = \frac{A}{4\pi s} \space \space E = \frac{\varphi}{s} \space \therefore $$ 



$$ U = \frac{E^2}{8\pi} \cdot As = \frac{E^2}{8\pi} \cdot volume $$

#### Force between conducting plates
$$ F = \frac{Q^2}{2} \frac{d}{dx} \frac{1}{C} $$

This properly models the force experienced by two conducting plates holding them together.


<!-- SECTION 2 -->


## Currents

#### The relation between current and the density and velocity of the charged particles .

$$ I = \frac{coulombs}{sec}  = \frac{esu}{sec} = \int_s \textbf{J} d\textbf{a} $$ 

#### Charge conservation

$$ \int_s \textbf{J} \cdot d\textbf{a} = - \frac{d}{dt} \int_V \rho dv $$


The instantaneous rate at which charge is leaving the enclosed volume, or *current*.


$$  J = - \frac{\partial \rho}{\partial t}  $$


##### current density is proportional to the strength of the electric field the causes it. 

$$ \textbf{J} = \sigma \textbf{E} $$

where $$$\sigma$$$ is the *conductivity* of the material. Large for good conductors, small for insulators, etc. 

Let's imagine a more applied scenario; we are interested in the total current $$$I$$$ flowing through a wire or conductor with well defined ends. And the difference in potential for those ends, we'll denote as $$$V$$$ rather than $$$\varphi_1 - \varphi_2$$$. If $$$\textbf{J}$$$ is proportional to $$$\textbf{E}$$$ everywhere inside the conductor then $$$I$$$ must be proportional to $$$V$$$. 

After all, $$$I$$$ is the integral of $$$\textbf{J}$$$ over a cross section of the conductor. And $$$V$$$ is the line integral of $$$\textbf{E}$$$ on a path through the conductor from one end to the other. 

That leaves us finding that $$$V = R I$$$. Where $$$R$$$ is the *resistance* of the conductor between the two terminals. 

-> ![](http://i.imgur.com/fi8TtZS.png) <-

#### Resistors in parallel

$$ R = \frac{R_1R_2}{R_1 + R_2} $$

Capacitors are added this was when in series.

When examining power, which is measured in joules per second. 

$$ P = I^2R $$ 


#### The difference between conductors, semi-conductors, and insulators.

**Conductors** are materials that permit electrons to flow freely from particle to particle. 

**Semiconductors** are materials that act as conductors or insulators based on factors like temperature. 

**Insulators** are materials that impede the free flow of electrons from atom to atom


#### Energy dissipation and electromotive force.

**Electromotive force**, also called **emf** (denoted $$$\mathcal{E}$$$ and measured in volts), is the voltage developed by any source of electrical energy such as a battery or dynamo.


#### Problems: 

Purcell 4.16,4.17,4.18,4.26

<!--  SECTION 3  -->

## Dielectrics


This section introduces the microscopic picture of material in an electric field for the case of dielectrics where the electrons are bound to the atoms, but an electric field can induce a relative displacement of the positive and negative charges (ions and electrons) producing microscopic electric dipoles which result in an additional contribution to the electric field in the material.


Displacements of positive and negative charges in the dielectric.


Dipole density.


Susceptibility of a material and the displacement of charges.


Free and polarization charges.




In section 10.5 the induced dipole moment vector p is assumed to be proportional to the perturbing field E. To recapitulate, let a neutral atom be represented by a positive (nuclear) charge +q anchored at the center of a uniform spherical cloud of negative charge -q of radius a. In an external electric field E the negative cloud is displaced a distance dz in the direction opposite to E . Assume the cloud remains spherical after the displacement and that the positive nuclear charge is fixed. The displacement dz is determined by requiring cancellation between the external field and the opposing electrical attraction between the displaced cloud and the nuclear charge. One can show that the magnitude of this opposing electric field is given by Eopp = (dz)3 q/(a3 (dz)2)) , so that E=Eopp requires dz = a3 E /q and thus that the dipole moment p = q dz = a3 E is indeed proportional to the applied electric field.
If all charges are alike, what is the difference between free and polarization charges?


#### Read

Chapt. 10 - Electric Fields in Matter, Sec. 10.1-10.2, 10.4-10.5,10.7-10.8, 10.11


#### Problems: 

Purcell 10.13 (Omit the comparison with magnetic energy!), 10.14, 10.16