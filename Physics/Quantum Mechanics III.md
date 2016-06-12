# QM 3

## Quantum Mechanical Operators

both light and matter have two different types of charaacteristics. 

We'll begin getting into the heart of quantum mechanics. 

Generally speaking, we can't tell what the trajectory of a particle is going to be at some arbitrary time $t$. Even if we know all the forces acting on that particle. 

We then define a concept of a *wave function*. $\Psi(x, t)$

A wave function is a function that satisfies a wave equation and describes the properties of a wave.

## The wave function

We start off with a standard equation for a wave.

$$ A(x,t) = A_0 e^{ i (kx - \omega t)}$$

$ A(x,t)$ means that means that what this wave looks like depends on position ($x$) and time ($t$). The description is set out in complex number form and can be displayed with an Argand diagram (For more info see here). 

This wave is a solution of the Wave Equation, and what we want to see is if the wave equation can be used to describe matter waves. The wave equation is

$$ \frac{\partial^2 A}{\partial x^2} = \frac{\partial^2 A}{c^2 \partial t^2}  $$

What this equation is saying is that, if you partially differentiate your wave, A, with respect to x twice, it will equal the partial differential of your wave with respect to t twice, multiplied by a constant, which in this case is 1/c^2.

So now we need to see if it will work, so first we take our wave and differentiate it twice with respect to $x$ So differentiating twice gives 


$$ \frac{\partial^{2} A}{\partial x^2} = -k^{2}A_{0}e^{ikx}e^{i\omega t}=-k^2A $$

You may be wondering why I’ve changed the original equation whilst doing the differentiations. Originally we had $A_0e^{i(kx-\omega t)}$ and now we have $ A_0e^{ikx}e^{-i\omega t}$. This is just a maths trick you can do to exponential powers and I personally think it makes the differentiation easier. We now differentiate the wave twice with respect to time to get

$$ \frac{\partial^{2} A}{\partial t^2} = -\omega^{2}A_{0}e^{ikx}e^{i\omega t}=-\omega^2A $$

We can now substitute these two results into the equation to give

$$ -k^{2}A = \frac{-\omega^2A}{c^2} $$

Conveniently the minus signs, the A‘s and the squares cancel to give us

$$ \omega = ck $$
Now, if we take the 2 base quantum formulas from the first section

$$ E=\hbar\omega $$

$$ p = \hbar k $$ 
 
 
and try and substitute into them we get a problem

$$\frac{E}{\hbar} = c \frac{p}{\hbar} $$

$$E = pc$$

However $E \neq pc$ for matter. For non-relativistic matter the relationship between energy and momentum obeys the following law. 

 $$ E = \frac{p^2}{2m} $$

So it looks like we have a problem. The Wave Equation doesn’t work for matter. One way to try and get it to work is to say that instead of $\omega^2\propto k^2$, what if we tried to get it so it was $\omega \propto k^2$? To do this we would need a wave equation that was differentiated twice with $x$ and only once with $t$. Also if we replace the constant we can make life easier for ourselves. So lets try

$$ \frac{\partial^2 \psi}{\partial x^2} = \alpha\frac{\partial \psi}{\partial t} $$ 

as our new wave equation. We have now changed $A$ to $\psi$ as this will be the equation that works and $\psi$ is the common symbol used for quantum mechanical waves, the equation for $\psi$ is the same as for $A$. So if we now do the differentiation

$$ \frac{\partial^{2} \psi}{\partial x^2} = -k^{2}\psi_{0}e^{ikx}e^{i\omega t}=-k^2\psi $$

$$ \frac{\partial^{2} \psi}{\partial t} = -i\omega^{2}\psi $$

Which when we put back in our new wave equation gives us 

$$ -k^2 = -i\alpha\omega $$

Which is the relationship between $\omega$ and $k$ we were after. So now we can rearrange for $\omega$ and substitute into equations to get



Which is the relationship between $\omega$ and $k$ we were after. So now we can rearrange for $\omega$ and substitute into equations (4) to get

$$ \omega=\frac{k^2}{i\alpha}$$

$$ E=\hbar\frac{k^2}{i\alpha}$$

We can now chose our constant $\alpha$ as

$$ \alpha=\frac{-2mi}{\hbar}$$ 

so we get

$$ E=\frac{\hbar^2k^2}{2m}=\frac{p^2}{2m} $$

Which is correct!! So far so good, our new wave equation for matter gives us the correct energy. So let’s put the constant back in

$$ \frac{\partial^2 \psi}{\partial x^2} = \frac{-2mi}{\hbar}\frac{\partial \psi}{\partial t} $$

And now once again rearrange to get it in a nicer looking form,

$$ i\hbar\frac{\partial \psi}{\partial t} = \frac{\hbar}{2m}\frac{\partial^2 \psi}{\partial x^2} $$

We’re nearly there now. The equation is almost complete. However when we solve it for the energy of a particle we get

$$ E\psi=\left(\frac{p^2}{2m}\right) \psi $$

but sometimes a particle can get energy from its surroundings, for example if it was in a potential, so we have to make one slight adjustment to account for all of the particles possible energies

$$ E \psi=\left(\frac{p^2}{2m} + V\right)\psi $$

Which means our wave equation becomes

$$ i\hbar\frac{\partial \psi}{\partial t} = \left(\frac{\hbar}{2m}\frac{\partial^2}{\partial x^2}+V\right)\psi $$

This is called the One Dimensional Time Dependent Schrödinger Equation. 


## The Schrödinger Equation

The wave function allows us to find the *probability* of a particle being in a certain position $x$ at a time $t$. 

The probability is given by the complex conjugate of the wave function, times the wave function times dx. 

$$P = \Psi^* \cdot \Psi dx$$  

This is the probability that the particle is located in some infinitessimally small distance $dx$. 

So we can do this by solving the schrodinger equation. 

#### The Schrödinger equation is the fundamental equation of physics for describing quantum mechanical behavior. It is also often called the Schrödinger wave equation, and is a partial differential equation that describes how the wavefunction of a physical system evolves over time.


Time Independent Version: 
$$ E \Psi(x) = -\frac{\hbar^2}{2m} \frac{d^2 \psi(x)}{d x^2} + V(x) \Psi(x) $$

Time dependent version: 
$$ i \hbar \frac{d\Psi}{d t} = -\dfrac{\hslash^2}{2m} \frac{d^2 \psi}{d x^2} + V(x,t) \Psi(x,t) $$



Where $V(x)$ is the potential energy. 


### Looking into the infinite square well
There's a particle who's potential energy is shown on a graph, to be $\infty$ at length $x > l$ and at $x < 0$. The potential is 0 inside this well. Essentially the particle is trapped. 

The solution for this wave function can be written as a set of functions characterized by a set of integer functions.

$$ \Psi_n(x,t) = \sqrt{\frac{2}{L}} \cdot \sin \Big( \frac{n\pi x}{L} \Big) e^{-i \omega_n t} $$

where $\omega_n = \frac{n^2 \pi^2 \hbar}{2mL^2}$

We have stationary state functions in terms of a quantum number $n$.

An *operator*, is something corresponding to any observable, such as energy. Which can be described by an *operator*. An operator is really just an operation.

In quantum mechanics we learn that applying the energy operator is the equivalent of taking a measurement of that observable. 

$$E_{op} = i \hbar \frac{\partial}{\partial t}$$

$$P_{xop} = -i \hbar \frac{\partial}{\partial x}$$

$$x_{op} = x$$


## Measuring Expectation

How do these concepts become useful? 

Let's say we make a measurement of position or energy of a particle described by some potential. 

One of the useful things we might need to calculate is the average value that we measure. The operators give us a convenient way to figure out the expectation value.

For some event Q, the average value is equal to the integral of the complex conjugate of the wave function times $\Psi$

$$ <Q> = \int \Psi^* Q_{op} \Psi dx $$ 

sometimes we find that given some function $\Psi$, when we apply an operator to the $\Psi$, we get a constant $\lambda$ times the original wave function. 

e.g. $ A \Psi = \lambda \Psi$ Where $A$ is a matrix and $\lambda$ is a scalar, or an *eigenvalue*. If such an equation exists, then We can say that $\Psi$ is an eigenstate of $A$ with *eigenvalue* $\lambda$. 

That corresponding eigenvalue would be the only possible value that we could observe. 

So if we apply the position vector, and find that there is an eigen state, the expectation of that operator is that eigenvalue. 

## Measuring Energy of the infinite square well

Let's look at the infinite square well again, 

is the infinite well an **eigenvalue of energy**? 

Let's apply the energy operator to the wave function, 

$$ E_{op} = i \hbar \frac{\partial}{\partial t}$$

$$ E_{op} \Psi = i \hbar \frac{\partial \Psi}{\partial t} = i \hbar \Psi (-i \omega_n) = \hbar \omega_n \Psi_n $$

In this case, $\hbar$ and $\omega_n$ are just constants. 

So the wave function of an infinite square well is an eigenstate of the energy operator. 

This tells us that if we make a measurement of energy, we will always observe a value of $\hbar \omega_n$ if the wave function is $\Psi_n$. 

This means the expectation of energy, is that eigenvalue as well. 

$$<E> = \hbar \omega_n $$

We now know that the infinite square well is an eigenstate of energy. 

Is the infinite square well an eigenstate of momentum? 

$$ P_{op} \Psi_n = -i \hbar \frac{\partial \Psi_n}{\partial x}$$

$$ \Psi_n(x,t) = \sqrt{\frac{2}{L}} \cdot \sin \Big( \frac{n\pi x}{L} \Big) e^{-i \omega_n t } $$

The wave function of the infinite square well has a sinusoidal dependence on $x$, and the rest of it remains the same with respect to $x$.

Our derivative becomes $ n \pi \cdot \cos{\Big( \frac{ n\pi x}{L} \Big)} $ 

This means that the wave function cannot be represented as an eigenstate of momentum, because of the cosinuoidal dependence on $x$, which is not constant.

How could it be that we don't have a fixed value of momentum, when we have a fixed value of energy? the reason that momentum is treated differently is because it's a vector. 

let's then calculate the expectation of the momentum of the infinite square well. 


$$ < P_{op} > = \int_0^L \Psi^* \cdot (-i \hbar) \frac{\partial \Psi}{\partial x} = 0 $$

This isn't a huge suprise, what this means is that the perticle in this well would be constantly going back and forth over and over again, and the expectation value of it's momentum would be $0$.

Let's then turn to the position operator. 

The infinite square well is not an eigenstate of momentum, but it is an eigenstate of energy. 

Is the wave function an eigenstate of position? 

Well... no, the only thing the operator is defined as is multiplying by x. Which of course is not constant. 

Let's then take the expectation of the position. 

$$ <x> = \int \Psi^* x \Psi dx = \int_0^L \sqrt{ \frac{2}{L} }  \sin \Big( \frac{n\pi x}{L} \Big) e^{i \omega_n t }  \cdot x  \cdot \sqrt{ \frac{2}{L} }  \sin \Big( \frac{n\pi x}{L} \Big) e^{i \omega_n t }  dx $$

##### note that here, $e$ is raised to $i \omega_n t$, because we have taken the complex conjugate.

This actually simplifies quite a bit! (thank the lord)

$$ \int_0^L \frac{2}{L} x \sin^2(\frac{n \pi x}{L} ) dx  =$$

When we present solutions for the schrodinger equation, any linear combination of solutions, will also be a solution.

## Eigenstate Superpositions 

suppose a particle in an infinite square well is given to be  in a super position of $\Psi_1$ and $\Psi_2$. 

Since the infinite square well is an eigenstate of energy for any of these wave functions, if we're given a wave function, $\Psi$, that is a superposition of states, is $\Psi$ an eigenstate of energy for this wave function? 

$$ E_{OP} \Psi = aE_{OP} \Psi_1 + bE_{OP} \Psi_1$$

We actually already know that energy is. Since $\Psi$ is an eigenstate of energy, and we know what the constant is, we can substitute in the eigenvalue of energy, $\hbar \omega$. 

now each $\Psi$ has constant coefficient, but those coefficients are not necessarily equal to each other. ($\omega$). 

So we have learned that a superposition is not an eigenstate of energy. This means that if we make an observation of energy, we would get different values. 

We can always work out the *expectation* value fortunately. So we'll find out more about the meaning of these coefficients. 

$$ <E> = \int_0^L \Psi^* i \hbar \frac{\partial \Psi}{\partial t} dx $$

$$ <E> = i \hbar \int_0^L  ( a^* \Psi_1^* + b^* \Psi_2^*) (-i \omega a \Psi_1 - i \omega_2b \Psi_2) $$

Foiling it out, it becomes, 

$$ <E> = a^* a \hbar \omega_1  + b^*b \hbar \omega_2 $$

Which means for each energy state, the average evergy is just based on the coefficient. $a^*a$ is just the probability that we will measure the state $\hbar \omega_1$. 


When you add the two terms you of course get the average value.


## Dealing with a potential step.

![](http://i.imgur.com/rB1UXRL.png)

Imagine a particle in a space with a potential step, where at x = 0 there is a potential that exists. 

This is the time independent schrodinger equation,

$$ E \psi(x) = - \frac{\hbar^2}{2m} \frac{\partial^2 \psi(x)}{\partial x^2} + V(x) \psi(x) $$

There are three possible scenarios. 

- The particle is in a potition in which there is no potential. 
	$V = 0$
	the Schrodinger equation becomes $$ E \psi(x) = - \frac{\hbar^2}{2m} \frac{\partial^2 \psi(x)}{\partial x^2} $$


- The particle's energy is greater than the potential step.
	$E > V_0$
 
 for $x > 0$ 
 	the schrodinger equation is rearranged to be the following. 
 	
 	$$  \frac{2m \big( E - V_0 \big) }{ \hbar^2 } + \frac{\partial^2 \psi(x)}{\partial x^2} = 0 $$

The graph of the particle is basically an oscillator, but with a lower amplitude due to the constant potential step. 


- The particle is in a position where the potential is greater than it's energy.
	$E > V_0$
	
when the particle enters the potential step in this case I forget what happens. Feel free to message me about this lmao.


$$	h = 6.626\ 070\ 040(81)\times 10^{-34}\text{ J⋅s} = 4.135\ 667\ 662(25)\times 10^{-15}\text{ eV⋅s} $$

$$ \hbar = {{h}\over{2\pi}} = 1.054\ 571\ 800(13)\times 10^{-34}\text{ J⋅s} = 6.582\ 119\ 514(40)\times 10^{-16}\text{ eV⋅s} $$

<!-- useful resources http://physicsforidiots.com/physics/quantum-mechanics/ -->