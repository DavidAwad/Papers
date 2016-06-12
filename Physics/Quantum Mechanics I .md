# QM 1 

## Thermal Radiation

All objects emit electromagnetic radiation. It is because all objects absorb thermal energy that forces charged particles to vibrate and emit radiation like an antennae. 

This is called *thermal radiation*.

One of the ways to understand this is to consider how ti depends on the wavelength and the temperature. 

One of the ways we explain it is the *spectral radiancy* (R) and can be written as a function of frequerncy or wavelength. 

It's units are watts per square meter per meter.  $ R(\lambda) = \frac{W/m^2}{m} $

The spectral radiation (the power being emitted) increases as temperature goes up. Each curve has a well defined peak for each wavelength which will give the maximum radiation. This is described by Wein's law. 


***Wien's displacement law*** states that the black body radiation curve for different temperatures peaks at a wavelength inversely proportional to the temperature.

$$ \lambda_{max} = \frac{b}{T} $$ 

where $ b $ is *Wein's displacement constant*, $ b = 2.897 \times 10^{-3} m K$

Using Wein's law, for the human body, (310K) working out Wein's law we find that $\lambda_{max} = 9 \mu m$ which is in the infrared spectrum. 


$$ R = \frac{c}{4} \rho_t $$ 
where $R$ is the spectral radiancy and $ \rho_t$ is the energy density. 


*Rayleigh–Jeans law* attempts to describe the spectral radiance of electromagnetic radiation at all wavelengths from a black body at a given temperature through classical arguments. This actually fails horribly for small values of $ \lambda $. This was referred to as the **ultraviolet catastrophe**. 

$$ \rho_t(\lambda) = \frac{8\pi k T}{\lambda^4} $$ 


$$	B_{\lambda} (T) = \frac{2ck_{\mathrm{B}} T}{\lambda^4} $$

$$	B_{\nu}(T) = \frac{2 \nu^2 k_{\mathrm{B}} T}{c^2} $$

Plank made the assertion that the energy must be a multiple of some certain quantity. 

$$ E = n h \nu $$

The energy must be some integer multiple n times some universal constant h times the frequency $ \nu $. This was the first notion of some discrete energy, which was the first accurate description of thermal radiation/

$$ \rho_t (\lambda) = \frac{8 \pi h c}{\lambda^5} \times \frac{1}{ e^{ hc / \lambda k t} - 1 } $$


Where $c$ is the speed of light, $k_{B}$ is the Boltzmann constant and $T$ is the temperature in kelvins. Also expressed where $\nu$ is the frequency. 


## photoelectric effect 

1905 Einstien 

Intensity is a measure of how much energy there is. Power per unit area. ($w/m^2$). 

Set up a potential difference between two plates to determine at what potential we overcome the kinetic energy of the electron being emitted by the two plates. 

This will be the stopping potential $V_s$. 

$ eV_s = K_e $

but for some reason when increasing the frequency of the light, $ \nu$, there was found to be a linear proportionality  with the stopping potential. 

There was also found to be a minimum frequency in which the photoelectric effect still took place. 

You could have thought of it as a one to one process. 

So what happens to energy in the photoelectric effect? 

Energy is given to be h times the frequency of the light. $ E = h\nu $, that energy will go into releasing one photon and one electron 

You can also represent it in terms of phi, or the work function, $\phi$. Which is the minimum energy required to displace 1 eletron from a metal. $h\nu = \phi + eV_s $

once you reach the required energy required for the work function, all that remains would be kinetic energy of the electron, or the electron times the stopping potential. 

The work function can be thought of as the binding energy of the electron. 

## bohr model of the hydrogen atom
around the year 1913 

we knew that all objects emitted electromagnetic radiation as well as a line spectrum. Which is a unique set of wavelengths for each element or compound. 

The set of wavelengths $\lambda$ are given by $ \frac{1}{\lambda} = R_H(1/n_f^2 - 1/n_i^2)$ where $R_H = 0.01097 m^{-1}$ is the Rhydberg constant for hydrogen. 

Where $n_f$ is any positive number, and $n_i$ begins at $n_f +1$. 

Any electron orbiting in a circle must experience centripidal acceleration, therefore in the bohr model of the atom there would only be the couloumb force acting upon the electron orbiting the proton. 
 
$$ k\frac{q_1q_2}{r^2} = \frac{mv^2}{r}$$ 
solving for r yields
$$ r = k\frac{q^2}{mv^2} $$
But how would we know how fast the electron is moving? 
Bohr suggests the following, since $ l = mvr $ The angular momentum of the particle is an integer $n \times \hbar$
$$v = \frac{n \hbar}{mr} $$

When combining the two equations we find that the radius is actually discrete and quantized, as is the speed for any values of the quantum number n, referring to particular orbitals. 

$$ r = 4\pi \epsilon_0 \frac{n^2 \hbar^2}{mZe^2} $$ 

$$ v = \frac{1}{4 \pi \epsilon_0} \frac{Ze^2}{n \hbar} $$

This makes it easy to find what the energy of an electron is. We'll start with the usual. 

$$ E = K + U  = 1/2mv^2 - \frac{1}{4\pi \epsilon_0} \frac{Ze^2}{r} $$ 

An electron could spontaneously jump from one orbital to lower one and in doing so, couild emit an electron, conserving energy. 

We can actually receive some information from the emitted photon, because we can observe that the energy will change. 

$$ \frac{hc}{\lambda} = E_i - E_f $$

This model correctly predicted the Rhydberg constant, giving us an experimentally verified and accurate picture of the atom. 


That happens simply by using the following equation for the $n$th energy level. 
$$ E_n = - \frac{Z^2 m e^4}{3 \pi^2 \epsilon_0^2 \hbar^2 n^2}$$

