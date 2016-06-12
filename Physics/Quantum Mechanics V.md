# QM 5 
## Atomic Structure

###  Multielectron Atoms

The wavefunctions corresponding to particles that are the same are *indistinguishable*. Since the two identical particles are indistinguishable, we should be able to exchange their labels without changing a measurable quantity such as the probability density.


### Exchange Symmetry

It is possible to construct an eigenfunction which satisfies the time- independent Schroedinger equation, and has its probability density function not changed by a relabeling of the particles. In fact, there are two ways of doing this. Consider the following two equations: 

$$ \psi_S = \frac{1}{\sqrt{2}} [ \psi_{\alpha}(1)\psi_{\beta}(2)   +  \psi_{\beta}(1) \psi_{\alpha}(2) ]$$

$$ \psi_A = \frac{1}{\sqrt{2}} [ \psi_{\alpha}(1)\psi_{\beta}(2)   -  \psi_{\beta}(1) \psi_{\alpha}(2) ]$$


The first is called the *symmetric* total eigenfunction, and the second the *antisymmetric* total eigenfunction. Now the **total** energy of a system containing a particle in a quantum state $\alpha$ and another particle in a quantum state $\beta$ will not depend on which particle is in which state, if the particles are identical. Thus both $ \psi_T = \psi_{\alpha}(1)\psi_{\beta}(2)$ and $ \psi_T = \psi_{\beta}(1)\psi_{\alpha}(2)$ are solutions corresponding to the same total energy. 

Because that equation is linear, it follows that the linear combinations $\Psi_S$ and $\Psi_A$, of the two forms of $\Psi_T$ are also solutions since they correspond to the same value of $E_T$, they are *degenerate solutions*, *different eigenfunctions* corresponding to precisely the *same eigenvalue*. The phenomenon is called *exchange degeneracy* since the difference between the *degenerate eigenfunctions* has to do with exchange of the particle labels.

### The exclusion Principle

As a result of an analysis of data concerning the energy levels of atoms, which we shall study soon, in 1925 Pauli was led to his famous exclusion principle.

*In a multielectron atom there can never be more than one electron in the same quantum state.*

Now consider the antisymmetric total eigenfunction, for a case in which both particles are in the same space and spin quantum state $\alpha$.

$$ \psi_A = \frac{1}{\sqrt{2}} [ \psi_{\alpha}(1)\psi_{\alpha}(2)   -  \psi_{\alpha}(1) \psi_{\alpha}(2) ]  = 0 $$

The eigenfunction is identically equal to zero. Hence, if two particles are described by the antisymmetric total eigenfunction, they cannot both be in a state with the same space and spin quantum numbers.


In other words, all antisymmetric total eigenfunctions have properties which conform to the require- ments of the exclusion principle. So we conclude there is an alternative expression of the exclusion principle:*"A system containing several electrons must be described by an antisymmetric total eigenfunction"*

![](http://i.imgur.com/QDbPKHL.png)

Table (9-1) lists several kinds of particles, their symmetry character, and also the value of the quantum number s that specifies the magnitude of their spin angular momentum. Also indicated are the two names, fermion and boson, sometimes used to distinguish the two classes of particles according to their symmetry character. 

It is very interesting to note that there must be some connection between the symmetry character of a particle and its spin. The point is that all the antisymmetric particles have half-integral spin just as the electron has, while all the symmetric particles have zero or integral spin.

he symmetry of a well-bound composite particle, like a helium atom, can be predicted immediately from the symmetries of its constituents. (If the composite particle has an even number of antisymmetric constituents, it is symmetric.)

### Exchange forces and the helium atom
We turn now to a property of indistinguishable particles which is, to say the least, very strange. Consider a pair of electrons in a system in which we can ignore any explicit interactions (like the Coulomb interaction) between the two particles. The total eigenfunction for the system can be written as the following. 

$$ \psi_A = \frac{1}{\sqrt{2}}[  \psi_{\alpha}(1) \psi_{\beta}(2) - \psi_{\beta}(1) \psi_{\alpha}(2)  ] $$

Total Eigenfunction = space eigenfunction X spin eigenfunction

The only possible antisymmetric spin eigenfunction for two noninteracting elec-trons is an assymetric spin eigenfunction

$ \frac{1}{\sqrt{2}} [(+ 1/2, -1/2) - (-1/2, +1/2)] $ (singlet)


There are three possible symmetric spin eigenfunctions

$$(1/2 , 1/2)$$$$ \frac{1}{\sqrt{2}} [(+ 1/2, -1/2) - (-1/2, +1/2)] $$$$(-1/2 , -1/2)$$

Their symmetry is obvious since for each an exchange of labels results in no change in the eigenfunction. These three describe the so-called triplet states, and the anti- symmetric eigenfunction describes the so-called singlet state. All four of these spin eigenfunctions are normalized.

A physical interpretation of the singlet and triplet states can be obtained by eval- uating, for each state, the magnitude $S'$ and $z$ component $S_z$ of the total *spin angular momentum* $S'$

$$ S' = S_1 + S_2$$ 

The sum of the spin angular momenta of the two electrons. As is true for all angular momenta in quantum mechanics, $S'$ and $Sz$ are quantized according to the relations.

$$ S' = \sqrt{s' (s' + 1 ) \hbar} $$

$$ S'_z = m'_s \hbar $$

![](http://i.imgur.com/bYzPJ5h.png)
Vector diagrams representing the rules for how to add quantum numbers
$s_1 = 1/2$ and $s_2 = 1/2$ to obtain the possible values for the quantum numbers $s'$ and $m_s'$. Left: The maximum possible value of $s'$ is obtained when a vector of magnitude $s_1$ is added to a parallel vector of magnitude $s_2$ , yielding $s' = s_1 + s_2 = 1/2 + 1/2 = 1$. The maximum possible $z$ component of this vector gives the maximum possible value of the quantum number $m_s$, and the minimum possible $z$ component gives the minimum possible value of $m_s$. 

The intermediate values of $m_s$ (only one in this case) differ by integers. Thus the possible values are $m_s' = +1, 0, —1$. 

Right: A vector of magnitude $s_1 = 1/2$ is added to an antiparallel vector of magnitude $s_2 = 1/2$ to yield a vector of magnitude $s' = s_1 — s_2 = 1/2 — 1/2 = O$. A vector whose length is zero must have $z$ component zero as well, so the only possible value for $m_s$ is **zero**. 

The term **triplet** refers to the state $s' = 1$ where **three** possible values of $m_s$ arise; the term **singlet** refers to the state $s' = 0$ where only one possible value of $m_s'$ arises.


![](http://i.imgur.com/dBU9UgV.png)

Triplet state: Two spin angular momentum vectors of magnitudes $S_1 = S_2 = (1/2)(1/2 + 1) \hbar$. Either can be found with equal likelyhood anywhere on a cone symmetrical about the vertical $z$ axis. But their orientations are correlated so that if one is found to be pointing in a particular direction the other will be found to be pointing in the same general direction.

The requirement that a description of the system must use a total eigenfunction which is antisymmetric where an exchange of their labels leads to a coupling between their spin and space variables. 

They act as if they move under the influence of a force whose sign depends on the orientation of their spins. This is called an **exchange force**. It is a purely quantum mechanical effect and has no classical analogy.



### Conclusions of the Hartree theory

1. In multielectron atoms the inner shells of small n are of very small radii because for these shells there is little shielding, and the electrons feel the full Coulomb attrac- tion of the highly charged nucleus
2. The electrons in the inner shells are in a region of large negative potential energy, so their total energies are correspondingly large and negative. The results of the Hartree theory predict that the magnitude of the total energy of an electron in the $n = 1$ shell is more negative than that of an electron in the $n = 1$ shell of hydrogen by approximately a factor of $(Z — 2)^2$
3. Electrons in the outer shells of large n are almost completely shielded from the nucleus, and so they feel an attraction to it not so different from that felt by an elec- tron to the singly charged nucleus of a hydrogen atom. The radius of the outermost shell can be obtained from our crude description by setting $Z = Z_n \propto n$ in the one electron atom radial expectation value equation, yielding $\bar{r} = \frac{n^2 a_0}{Z_n} = n a_0 $ 
4. We can also see, from our crude description of the Hartree theory results, that the theory predicts that the total energy of an electron in the outermost populated shell of any atom is *comparable to that of an electron in the ground state of hydrogen*. If we set $Z = Z_n$ in the one-electron atom energy equation to obtain:
$$ E_n = \frac{ \mu Z_n^2 e^4 }{ (4 \pi \epsilon_0)^2 2 \hbar^2 n^2 }  $$
5. Finally, we can use that to describe the dependence of the total energy of an electron on its quantum number $n$. Due both to the $Z_n$ in the numerator and the $n^2$ in the denominator, $E$ becomes less negative with increasing $n$ in going through the shells of a given atom. The total energy of an electron in a given multielectron atom becomes less negative very rapidly with increasing n for small $n$, but much less rapidly for large $n$. The behavior for large $n$ reflects the fact that the energy cannot become positive since the electron is bound. 



### Why the most stable nuclei have about the same number of neutrons and protons





## Questions:

**What approximation is involved when we describe atoms in terms of one-electron wave functions?**

In the first approximation used in treating a multielectron atom of atomic number $Z$, we must consider the Coulomb interaction between each of its $Z$ electrons of charge $-e$ and its nucleus of charge $+Ze$.

*the atomic electrons must be treated as moving independently*

**How we can make some corrections to this approximation**

Due to the magnitude of the nuclear charge, this is the strongest single interaction felt by each electron. But even in the first approximation we must also consider the Coulomb interactions between each electron and all the other electrons in the atom. These interactions are individually weaker than the interaction between each electron and the nucleus, but, as we saw for the case of the helium atom, they are certainly not negligible.


The requirements of the last two paragraphs are in conflict, the Coulomb interactions between the electrons must be considered, but the electrons must be treated as moving independently. A compromise between the requirements is obtained by assuming each electron to move independently in a spherically symmetrical net po- tential $V(r)$, where $r$ is the radial coordinate of the electron with respect to the nucleus.

**The structure of the periodic table of the elements** 



**The possible interactions of a photon with an atom?**

**How a population inversion is produced?**

**Why you need a population inversion for a laser to operate?**


