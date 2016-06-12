# T2
## Thermodynamics II

### The second law of thermodynamics
The second law of thermodynamics states that for a thermodynamically defined process to actually occur, the sum of the entropies of the participating bodies must increase. In an idealized limiting case, that of a reversible process, this sum remains unchanged.

**Entropy:** a thermodynamic quantity representing the unavailability of a system's thermal energy for conversion into mechanical work, often interpreted as the degree of disorder or randomness in the system.


For mathematical analysis of processes, entropy is introduced as follows. In a fictive reversible process, an infinitesimal increment in the entropy ($dS$) of a system results from an infinitesimal transfer of heat ($\delta Q$) to a closed system divided by the common temperature ($T$) of the system and the surroundings which supply the heat:

$$ \mathrm dS = \frac{\Delta Q}{T} \text {(closed system, idealized fictive reversible process)}. $$

For an actually possible infinitesimal process without exchange of matter with the surroundings, the second law requires that the increment in system entropy be greater than that:

$$ \mathrm dS > \frac{\Delta Q}{T} \text {(closed system, actually possible, irreversible process).} $$

This is because a general process for this case may include work being done on the system by its surroundings, which must have frictional or viscous effects inside the system, and because heat transfer actually occurs only irreversibly, driven by a finite temperature difference.

"you can't have perfect energy usage there has to be a net increase of disorder in the universe"

### The Carnot Cycle

A Carnot heat engine is an engine that operates on the reversible Carnot cycle. The basic model for this engine was developed by Nicolas Léonard Sadi Carnot in 1824.

The conceptual value of the Carnot cycle is that it establishes the maximum possible efficiency for an engine cycle operating between $T_H$ and $T_C$. It is not a practical engine cycle because the heat transfer into the engine in the isothermal process is too slow to be of practical value. As Schroeder puts it "So don't bother installing a Carnot engine in your car; while it would increase your gas mileage, you would be passed on the highway by pedestrians."

![](https://upload.wikimedia.org/wikipedia/commons/thumb/2/22/Carnot_heat_engine_2.svg/300px-Carnot_heat_engine_2.svg.png)

The efficiency of a heat engine cycle is given by the following: 

$$ \eta = \frac{W}{Q_H} = \frac{Q_H - Q_C}{Q_H} $$

![](http://hyperphysics.phy-astr.gsu.edu/hbase/thermo/imgheat/carnot2.gif)

The Carnot cycle when acting as a heat engine consists of the following steps:

1. Reversible isothermal expansion of the gas at the "hot" temperature, TH (isothermal heat addition or absorption). During this step the gas is allowed to expand and it does work on the surroundings. The temperature of the gas does not change during the process, and thus the expansion is isothermic. The gas expansion is propelled by absorption of heat energy Q1 and of entropy $\Delta S_\text{H}=Q_\text{H}/T_\text{H}$ from the high temperature reservoir.

2. Isentropic (reversible adiabatic) expansion of the gas (isentropic work output). For this step (2 to 3 on Figure 1, B to C in Figure 2) the piston and cylinder are assumed to be thermally insulated, thus they neither gain nor lose heat. The gas continues to expand, doing work on the surroundings, and losing an equivalent amount of internal energy. The gas expansion causes it to cool to the "cold" temperature, TC. The entropy remains unchanged.

3. Reversible isothermal compression of the gas at the "cold" temperature, TC. (isothermal heat rejection) (3 to 4 on Figure 1, C to D on Figure 2) Now the surroundings do work on the gas, causing an amount of heat energy Q2 and of entropy $\Delta S_\text{C}=Q_\text{C}/T_\text{C}$ to flow out of the gas to the low temperature reservoir. (This is the same amount of entropy absorbed in step 1.)

4. Isentropic compression of the gas (isentropic work input). (4 to 1 on Figure 1, D to A on Figure 2) Once again the piston and cylinder are assumed to be thermally insulated. During this step, the surroundings do work on the gas, increasing its internal energy and compressing it, causing the temperature to rise to TH. The entropy remains unchanged. At this point the gas is in the same state as at the start of step 1.


**Explanation:**
This maximum efficiency $\eta$ is defined as above:

 $W$ is the work done by the system (energy exiting the system as work),
 $Q_\text{H}$  is the heat put into the system (heat energy entering the system),
 $T_\text{C}$  is the absolute temperature of the cold reservoir, and
 $T_\text{H}$  is the absolute temperature of the hot reservoir.
A corollary to Carnot's theorem states that: All reversible engines operating between the same heat reservoirs are equally efficient.

It is easily shown that the efficiency $\eta$ is maximum when the entire cyclic process is a reversible process. This means the total entropy of the total system consisting of the three parts: the entropy of the hot furnace, the entropy of the "working fluid" of the Heat engine, and the entropy of the cold sink. The total entropy of the system remains constant when the "working fluid" completes one cycle and returns to its original state.


### Enthalpy

**Enthalpy:** a measure of energy in a thermodynamic system. It includes the internal energy, which is the energy required to create a system, and the amount of energy required to make room for it by displacing its environment and establishing its volume and pressure.

The enthalpy of a homogeneous system is defined as the following:

$H = U + p V$

$H$ is the enthalpy of the system,
$U$ is the internal energy of the system,
$p$ is the pressure of the system,
$V$ is the volume of the system.

**Internal Energy:** The internal energy $U$ of a given state of the system is determined relative to that of a standard state of the system, by adding up the macroscopic transfers of energy that accompany a change of state from the reference state to the given state: $ \Delta U = \sum_i  E_i\ $

where $ΔU$ denotes the difference between the internal energy of the given state and that of the reference state, and the $E_i$ are the various energies transferred to the system in the steps from the reference state to the given state. It is the energy needed to create the given state of the system from the reference state.


![](http://chemwiki.ucdavis.edu/@api/deki/files/10057/=Screen_shot_2010-10-30_at_8.56.51_PM.png?revision=1)


### Thermodynamic identity 


$$ dU = TdS - PdV $$

The Increase in Entropy Principle states that for any process the total change in entropy of a system together with its enclosing adiabatic surroundings is always greater than or equal to zero. This total change of entropy is denoted the Entropy Generated during the process (Sgen [kJ/K] or sgen [kJ/kg.K])

for an **adiabatic** process, $dU = -PdV$


### Maxwells Relations

The structure of Maxwell relations is a statement of equality among the second derivatives for continuous functions. It follows directly from the fact that the order of differentiation of an analytic function of two variables is irrelevant (Schwarz theorem). In the case of Maxwell relations the function considered is a thermodynamic potential and xi and xj are two different natural variables for that potential:

$$ \frac{\partial }{\partial x_j}\left(\frac{\partial \Phi}{\partial x_i}\right)= \frac{\partial }{\partial x_i}\left(\frac{\partial \Phi}{\partial x_j}\right) $$

where the partial derivatives are taken with all other natural variables held constant. It is seen that for every thermodynamic potential there are n(n − 1)/2 possible Maxwell relations where n is the number of natural variables for that potential.



### The four common maxwells relation

The four most common Maxwell relations are the equalities of the second derivatives of each of the four thermodynamic potentials, with respect to their thermal natural variable (temperature T; or entropy S) and their mechanical natural variable (pressure P; or volume V):

$$ \left(\frac{\partial T}{\partial V}\right)_S  = -\left(\frac{\partial P}{\partial S}\right)_V = \frac{\partial^2 U }{\partial S \partial V} $$

$$ \left(\frac{\partial T}{\partial P}\right)_S = \left(\frac{\partial V}
{\partial S}\right)_P = \frac{\partial^2 H }{\partial S \partial P} $$

$$ \left(\frac{\partial S}{\partial V}\right)_T = \left(\frac{\partial P}{\partial T}\right)_V = -\frac{\partial^2 F }{\partial T \partial V} $$ 

$$ -\left(\frac{\partial S}{\partial P}\right)_T = \left(\frac{\partial V}{\partial T}\right)_P = \frac{\partial^2 G }{\partial T \partial P} $$

![](https://upload.wikimedia.org/wikipedia/commons/thumb/0/09/Thermodynamic_map.svg/400px-Thermodynamic_map.svg.png)

