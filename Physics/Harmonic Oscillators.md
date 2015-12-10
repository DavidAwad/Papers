## A Small Intro to Harmonic Oscillators 
### David Awad




$$\sum{ \vec{F} } = m \frac{\mathrm{d} \vec{\mathbf{v}}} {\mathrm{d}t}  $$



There are multiple formulas that can be used to describe the motion of a harmonic oscillator. The most important to be aware of is that usually, a harmonic oscillator follows some given motion. 


start with newton's second law. 

$$\sum{ \vec{F} } = m\vec{a} $$


Adjust for spring force.

######(and other forces if they apply, doesn't matter in this example but you get my point)



$$\ -kx = m\ddot{x} $$

$$\ 0 = m\ddot{x} + kx$$

Now we have it in a form where we can do some really useful things to find the oscillations. 

###### divide by m, note that we've put k over m for the convenience of a particular formula

$$\ 0 = \ddot{x} + \frac{k}{m} x$$

$$ \omega_0 = \sqrt{ \frac{k}{m}} $$

Where $$$\omega_0$$$ is the natural frequency of a simple harmonic oscillator, with a spring constant $$$k$$$ and mass $$$m$$$.

This leaves us with an interesting differential equation. 

$$\ 0 = \ddot{x} + \omega_0^2 x$$

###### note: this equation represents the position as a function of time. If this isn't clear, remember that $$$\ddot{x}$$$ is simply the acceleration, which is also a function of time. 

So how can we solve this? One way is to use the convenient $$$e^{i\omega t}$$$ who's derivative is very similar. 


$$\frac{d^2}{dt^2} e^{i\omega t} = -\omega^2e^{i\omega t} $$ 

Leaving us with an equation to properly model the motion in terms of natural frequency! 

###### note: don't confuse natural frequency $$$\omega_0$$$ with the actual oscillating frequency $$$\omega$$$ which is the frequency that the system is actually oscillating at. 

So let's look at our new equation. 

$$ 0 = \ddot{x} + \omega_0^2 x$$

$$f(x) = e^{i\omega t}$$


$$ 0 = -\omega^2e^{i\omega t} + \omega_0^2 e^{i\omega t}$$


$$ 0 = e^{i\omega t} (-\omega^2 + \omega_0^2) $$

In order for this equality to hold it must be the case that 
