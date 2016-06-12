# QM 4
## The Quantum description of the Hydrogen Atom 

In general, we can't say *exactly* where an electron is, we have to consider it as a probability distribution that's a function of the radius 

$$ \Psi(r) = \frac{ e^{-\frac{r}{r_0}} }{ \sqrt{ \pi r_{0}^{3} }  } $$

Where $r_0$ is a constant. 

Potential energy for the hyrdogen atom 

$$ U(r) = - \frac{1}{4 \pi \epsilon_0 } \frac{e^2}{r^2} $$

The *time independent* schrodinger equation is then 

$$ - \frac{\hbar}{2m} = \nabla^2 \Psi   - \frac{1}{4 \pi \epsilon_0 } \frac{e^2}{r^2} \Psi = E \Psi $$

## One electron Atoms 

Imagine the following system, in a normal Hydrogen Atom ($_1^2H$), there is a single electron of mass $m_e$ orbiting around a much more massive proton of mass $m_p$. 

In reality, the center of mass is to the right of the proton, and so bpth particles orbit the center of mass. It's much more convenient for us to treat the proton itself as the center of mass and give the electron the *reduced mass* $\mu$. 

$$ \mu = \frac{Mm}{m+M}$$ 

Where $M$ is the true mass of the nucleus, and $m$ is the true mass of the elctron. We can apply this model to any single electron atoms. The electron of reduced mass $\mu$ under the influence of the coloumb potential, is represented as follows. 

$$ V(x,y,z) = \frac{-Ze^2}{ 4 \pi \epsilon_0 \sqrt{x^2 + y^2 + z^2 }  } $$

Where $x$,$y$,ad $z$ are rectangular coordinates of an electron relative to the nucleus centered at the origin.  The square root in the denominator is just the electron-nucleus separation distance $r$. The nuclear charge is $+Ze$ ($Z = 1$ for neutral hydrogen, $Z = 2$ for singly ionized helium, etc.)

Let's develop the Schrodinger equation by first finding the total energy for the system. 

$$ E = \frac{1}{2\mu}(p_x^2 + p_y^2, + p_z^2) + V(x,y,z) $$

The quantities $p_x$, $p_y$, $p_z$ are the $x$, $y$, $z$ components of the linear momentum of the electron. Thus the first term on the left is the kinetic energy of the system, while the second term is its potential energy. Now we replace the dynamical quantities $p_x^2$ + $p_y^2$, and $p_z^2$ and $E$ by their associated *differential* operators, using an obvious three-dimensional scheme. This gives us the *operator equation*. 

$$ - \frac{\hbar}{2 \mu} \cdot \big( \frac{\partial^2}{\partial x^2} + \frac{\partial^2}{\partial y^2} + \frac{\partial^2}{\partial z^2} \Big) + V(x,y,z) = i \hbar \frac{\partial}{\partial t} $$

With some simplifying this becomes 

$$ - \frac{\hbar}{2 \mu} = \nabla^2 \Psi + V\Psi = E \Psi $$

###### note: $\nabla^2 = \frac{\partial^2}{\partial x^2} + \frac{\partial^2}{\partial y^2} + \frac{\partial^2}{\partial z^2}$. Often called the $Laplacian$ operator. 

There are time independent solutions for this function, due to the fact that $V$ does not depend on time! However this function seems difficult to manage. We could solve it using separation of variables to split the partial differential equation into a set of three ordinary differential equations, each involving only one coordinate and solve them independently. However the trouble comes when dealing with $V$. We get around this by switching to *spherical polar coordinates*. These are $r$, $\theta$ and $\varphi$. 

![](http://i.imgur.com/phlkPo8.png)

Our new solution to the Schrodinger equation is the following form. 

$$ \Psi(r,\theta, \varphi) = R(r) \Theta( \theta ) \Phi(\varphi) $$


Solutions in multiple dimensions. 

$$ \Phi(\varphi) = e^{i m_l \varphi}   $$

$$ e^{i m_l 2 \pi} = e^{i m_l 0}   $$

This can only be true if the values of $m_l$ are the following. 

$$|m_l| = 0,1,2,3,...$$

In other words, m1can be only a positive or negative integer. Thus the set of functions which are *acceptable* solutions to are defined below. The *quantum number* $m_l$ is used as a subscript to identify the specific form of an acceptable solution.

$$ \Phi_{m_l}(\varphi) = e^{i m_l \varphi} $$

In solving (7-16) for the functions $\Theta(\theta)$, the procedure is similar to that used in Appendix I to obtain analytical solutions of the time independent Schroedinger equation for the simple harmonic oscillator potential. Here we shall only quote the results. It is found that solutions to which are acceptable (remain finite) are obtained only if the constant 1 is equal to one of the integers.$$ l  = | m_l |, | m_l | + 1, | m_l | + 2, | m_l | + 3, . . .  $$

$$ \Theta _{lm_l} (\theta) = \sin^{|m_l|}(\theta) F_{l|m_l|}(\cos(\theta)) $$

and eventually, 

$$ R_{nl}(r) = e^{\frac{-Zr}{na_0}} \Big( \frac{Zr}{a_0} \Big)^l G_{nl} \Big( \frac{Zr}{a_0} \Big)^l  $$ 

$$ a_0 = \frac{4 \pi \epsilon_0 \hbar^2}{ \mu e^2} $$

Because of its role in specifying the total energy of the atom, $n$ is sometimes called the *principal* quantum number. 
Because the azimuthal, or orbital, angular momentum of the atom depends on $l$, its called the *azimuthal* quantum number. 
If the atom is in an external magnetic field there is a dependence of its energy on $m_l$. Consequently, $m_l$ sometimes called the *magnetic* quantum number.

$$m_l =0,1,2,3,...$$ $$ l = |m_l|, |m_l| +1,|m_l|+ 2,|m_l|+ 3 ,... $$ $$n=1+1,1+2,1+3,...$$

rather, $n = 1,2,3...$ and $l = n-1$ and $m_l$ can range from $l$ to $-l$. 

These conditions show that for a given value of $n$ there are several different possible values of $l$ and $m_l$. Since the form of the eigen-functions depends on all three quantum numbers, there are situations in which two or more completely different eigenfunctions correspond to exactly the same eigenvalue $E$. 

Since the energy eigenfunctions describe the behavior of the atom, it has states with **different** behavior that nevertheless have the same *total* energy. In physics the word used to characterize this phenomenon is *degeneracy*, and eigenfunctions corresponding to the same eigenvalue are said to be *degenerate*.

Inspection of these properties shows that:
	
- For each value of $n$, there are n possible values of $l$.
- For each value of $l$, there are ($2l + 1$) possible values of $m_l$.- For each value of $n$, there are a total of $n^2$ degenerate eigenfunctions.

### Eigenfunctions of a one electron atom

So the question becomes the following. We've done a lot of work to develop a means of making predictions that we already had before in the form of the Bohr model of the atom. So the question becomes, is this *worth* the extra work? **YES**

Eigenfunctions give us so much more information then the Bohr model. They are formed by taking the following product.$$ \Psi = R_{nl}(r)\Theta_{l m_l}(\theta) \Phi_{m_l}(\varphi) $$

We also know the forms of each of these functions. 

$$ \Theta _{lm_l} (\theta) = \sin^{|m_l|}(\theta) (polynomial \space  in \space \cos(\theta) ) $$

$$ \Phi(\varphi) = e^{i m_l \varphi }$$

$$ R(r) = e^{- r/n} r^l $$
**Example 7-2:** Verify that the eigenfunction $\psi_{211}$, and the associated eigenvalue $E_2$, satisfy the time-independent Schroedinger equation for the one-electron atom with $Z=1$.

**Answer:** Since the differential equation is linear in $\psi$, for the purposes of this verification we can ignore completely the multiplicative constant $1/8 \pi^{1/2} a_0^{5/2}$, and write the eigenfunction as $\psi = re^{-r/2a_0} \sin{(\theta)} e^{i \varphi}$

$$ \psi = g(\theta, \varphi)re^{-r / 2a_0} $$

We go back to our original schrodinger equation, 
$$ E \psi =  - \frac{\hbar^2}{2 \mu} \Big[ \frac{1}{r^2} \frac{\partial }{\partial r }  \Big( r^2 \frac{\partial \psi}{\partial r} \Big) + \frac{1}{r^2 \sin{\theta}} \frac{\partial }{\partial \theta } \Big( \sin{\theta} \frac{\partial \psi}{\partial \theta } \Big) + \frac{1}{r^2 \sin^2{(\theta)}} \Big( \sin^2{\theta} \frac{\partial \psi}{\partial \varphi } \Big) \Big]  + V\psi $$

Refer to the table on the last page for better information / pattern matching.


### Probability Densities
We begin to extract information from the one-electron atom eigenfunctions by studying the forms of the corresponding probability density functions.

$$ \Psi^* \Psi = \psi^*_{nl m_l } e^{ i E_n t / \hbar}  \psi_{nl m_l }e^{ -i E_n t / \hbar} = \psi^*_{nl m_l } \psi_{nl m_l }$$

We definte the *radial probability* density $P(r)$, defined so that $P(r) dr$ is the lity of finding the electron at any location with radial coordinate between $r$ and $r + dr$. By integrating the probability density $F^*h$ which is a probability unit volume, over the volume enclosed between spheres of radii $r$ andeasy to show $t$. 
<br>



## Sources
http://www.nat.vu.nl/~wimu/EDUC/MNW-lect-2.pdf

https://www.physics.rutgers.edu/ugrad/323/QM4.html


