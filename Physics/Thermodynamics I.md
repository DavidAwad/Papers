# T1
## Thermodynamics

### Heat and temperature

Heat is not a property of a system. Heat is a process function. Temperature is a property of a system because is a state function. For instance, the state of a simple gas is given by temperature, pressure, and composition $(T,p,N)$.

Temperature is defined as the inverse ratio of variation of entropy $S$ to changes in internal energy $U$

$$T≡(∂S \cdot ∂U)−1$$

This is the thermodynamic concept of temperature, which is more general than the kinetic concept that you are considering. Regarding your question, part of the energy given as heat is used to break the bonds and when are broken if you continue supplying energy this will increase the kinetic energy of the molecules.

Moreover, kinetic temperature is not the average of the kinetic energies of all the molecules of the object. This average of kinetic energies is the average kinetic energy. The kinetic temperature is defined as $2/3$ the average internal energy per number density.

At the other hand, heat $Q$ is defined for a given process as the internal energy interchanged which is neither work nor due to flow of matter

$$Q ≡ \Delta U−W−U_{matter}$$

Notice that internal energy is a state function and $ΔU$ denotes the difference between the initial and final energies, but heat is not a state function and this is why we write $Q$ instead of an incorrect $ΔQ$.

The concept of process function is most easily understood with the example of a lake. A lake has some amount of water, and this can change by evaporation and raining. You can count the amount of water added to the lake by some raining process, but the lake itself does not have any amount of "raining" or evaporation" only some amount of water. Similarly a thermodynamic system has internal energy but has not heat or work.


### Temperature Scales 

#### Farenheit

On the Fahrenheit scale, the freezing point of water is 32 degrees Fahrenheit (°F) and the boiling point is 212 °F (at standard atmospheric pressure). This puts the boiling and freezing points of water exactly 180 degrees apart. Therefore, a degree on the Fahrenheit scale is 1⁄180 of the interval between the freezing point and the boiling point. On the Celsius scale, the freezing and boiling points of water are 100 degrees apart. A temperature interval of 1 °F is equal to an interval of 5⁄9 degrees Celsius. The Fahrenheit and Celsius scales intersect at −40° (−40 °F and −40 °C represent the same temperature).



#### Celsius
$$ C = \frac{5}{9} (F - 32)$$

Celsius, historically known as centigrade, is a scale and unit of measurement for temperature. As an SI derived unit, it is used by most countries in the world. It is named after the Swedish astronomer Anders Celsius (1701–1744), who developed a similar temperature scale. The degree Celsius (°C) can refer to a specific temperature on the Celsius scale as well as a unit to indicate a temperature interval, a difference between two temperatures or an uncertainty. Before being renamed to honour Anders Celsius in 1948, the unit was called centigrade, from the Latin centum, which means 100, and gradus, which means steps.

From 1744 until 1954, 0 °C was defined as the freezing point of water and 100 °C was defined as the boiling point of water, both at a pressure of one standard atmosphere with mercury being the working material. Although these defining correlations are commonly taught in schools today, by international agreement the unit "degree Celsius" and the Celsius scale are currently defined by two different temperatures: absolute zero, and the triple point of VSMOW (specially purified water). This definition also precisely relates the Celsius scale to the Kelvin scale, which defines the SI base unit of thermodynamic temperature with symbol $K$. Absolute zero, the lowest temperature possible, is defined as being precisely 0 K and −273.15 °C. The temperature of the triple point of water is defined as precisely 273.16 K and 0.01 °C.



#### Kelvin

$$ K = C + 273.15 $$

The kelvin is a unit of measure for temperature based upon an absolute scale. It is one of the seven base units in the International System of Units (SI) and is assigned the unit symbol K. The Kelvin scale is an absolute, thermodynamic temperature scale using as its null point absolute zero, the temperature at which all thermal motion ceases in the classical description of thermodynamics.

#### isothermal:
An **isothermal process** is a change of a system, in which the temperature remains constant: $ΔT = 0$.

#### isobaric:
An **isobaric process** is a thermodynamic process in which the pressure stays constant: $ΔP = 0$.

#### adiabatic:
An **adiabatic process** is one that occurs without transfer of heat or matter between a thermodynamic system and its surroundings. In an adiabatic process, energy is transferred only as work.

#### heat capacity 
In the International System of Units, heat capacity has the unit joules per kelvin. An object's heat capacity (symbol C) is defined as the ratio of the amount of heat energy transferred to an object and the resulting increase in temperature of the object. 

$$ C = \frac{Q}{\Delta T} $$


The above is true assuming that the temperature range is sufficiently small so that the heat capacity is constant. More generally, because heat capacity does depend upon temperature, it should be written as

$$ C (T) \equiv \frac{\Delta Q}{d T}$$

### Ideal Gas Law

- An ideal gas consists of a large number of identical molecules.

- The volume occupied by the molecules themselves is negligible compared to the volume occupied by the gas.

- The molecules obey Newton's laws of motion, and they move in random motion.

$n$ = number of moles

$R$ = universal gas constant = $8.3145 J/mol K$

$N$ = number of molecules

$k$ = Boltzmann constant = $1.38066 x 10-23 J/K = 8.617385 x 10^{5} eV/K $


$k$ = $R/NA$

#### Properties of a Van der Waals Gas
These properties are meant to correct for "real" gases. 

$$ \big[ P + \frac{an^2}{v^2}  \big] (V + nb) = nRT $$

##### $a$: Constant to correct for intermolecular attractive forces
##### $b$: Constant to correct for volume of individual gas molecules

| Compound  | $a$  | $b$  |
|---|---|---|
| $He$   |   0.03412 |0.02370   |
| $Ne$   |  0.2107 | 0.01709 |   
| $H_2$  |   0.2444 | 0.02661 |  
| $Ar$   |   1.345 | 0.03219   |
| $O_2$  |   1.360 |0.03803 |

Intermolecular attractive forces (IMF) of gas molecules are greater.
Mass (and subsequently volume) of gas molecules is greater.


Conditions are more real at low temperature and high pressure

More "ideal" at High temperature and low pressure

##### why? 

- At High T, the gas molecules have a higher average kinetic energy (KEavg) which overcomes the IMF.
- At Low P, the gas molecules are spread further apart and can therefore avoid IMF.
- P of a real gas < P of an ideal gas because the actual paths of gas molecules are curved (not straight) due to the IMF.
- V of a real gas > V of an ideal gas because V of gas molecules is significant when P is high.  Ideal Gas Equation assumes that the individual gas molecules have no volume.


### The first law of thermodynamics:

The first law of thermodynamics is a version of the law of conservation of energy, adapted for thermodynamic systems. The law of conservation of energy states that the total energy of an isolated system is constant; energy can be transformed from one form to another, but cannot be created or destroyed.

$$ \Delta U = Q + W $$


### Specific Heat of gases

$$ Q = n C_{V}  \Delta T $$
$$ Q = n C_{P}  \Delta T $$

Two specific heats are defined for gases, one for constant volume, $C_{V}$ and one for constant pressure, $C_P$. 


<hr>

**Problem #1:** A 610. g piece of copper tubing is heated to 95.3 °C and placed in an insulated vessel containing 45.0 g of water at 36.5 °C. Assuming no loss of water and heat capacity for the vessel of 10.0 J/K, what is the final temperature of the system (Cp of copper = 0.387 J/g-K)?

$$ q_{lost by copper} = q_{gained by water} + qgained by calorimeter $$

$ (610. g) (95.3 °C - x) (0.387 J g-1 K-1) = $
$ (45.0 g) (x - 36.5 °C) (4.184 J g-1 °C-1) + [(10.0 J/K) (x - 36.5 °C)] $

###### Comment: The K and the °C cancel because the °C in this problem is a temperature difference (not one single specific value) and the "size" of one K = one °C.

$ 22497.471 - 236.07x = 198.28x - 7237.22 $

$ 424.35x = 29734.691 $

$ x = 70.1 °C $


**Problem #4:** A 5.00 g sample of aluminum (specific heat capacity = 0.89 J °C-1 g-1) and a 10.00 g sample of iron (specific heat capacity = 0.45 J °C-1 g-1) are heated to 100.0 °C. The mixture of hot iron and aluminum is then dropped into 91.9 g of water at 23.7 °C. Calculate the final temperature of the metal and water mixture, assuming no heat loss to the surroundings.

$$ q_{Al} + q_{Fe} = q_{water} $$
$$ (5.00 g) (100 °C - x) (0.89 J °C-1 g-1) + (10.00 g) (100 °C - x) (0.45 J °C-1 g-1) = $$

$$ (91.9 g) (x - 23.7 °C) (4.184 J °C-1 g-1) $$

$ (445 - 4.45x) + (450 - 4.5x) = 384.5096x - 9112.87752 $
$ 393.4596x = 10007.87752 $
$ x = 25.4 °C $

**Problem #10:** $50.0 g$ of copper at $200.0 °C$ is placed in ice at $0.0 °C$. How many grams of ice will melt?

1) The copper will go down in temperature to zero Celsius, liberating a certain amount of heat:

$$ (50.0 g) (200.0 °C) (0.385 J / g °C) = 3850 J $$
2) All of the heat from the copper melts ice:

$ (334.16 J/g) (x) = 3850 J $ 
$ x = 11.5 g $