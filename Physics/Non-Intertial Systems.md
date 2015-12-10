## Non Inertial Systems
### David Awad

Inertial systems that are frames of reference with no acceleration. Systems where there are no fictions forces. 

Imagine a system moving at acceleration $$$ \textbf{A}$$$, where $$$a$$$ is the acceleration of the observer. 

The observed force from outside the system $$$F'$$$, is adjusted based on the difference of acceleration. 

$$ F' = ma' $$

$$ a' = a - \textbf{A} $$

$$ F' = ma - m\textbf{A} $$

$$ F' = F + F_{fict} $$




A small weight of mass m hangs from a string in an automobile that accelerates at rate A. What is the static angle of the string from the vertical, and what is the tension in the string?We shall analyze the problem both in an inertial frame and in a non- inertial frame accelerating with the car.

-> ![](http://i.imgur.com/LbODVj3.png)  <-



![](http://i.imgur.com/jnRObLs.png) <!-- Accelerating -->
![](http://i.imgur.com/ZjVRyfg.png) <!-- Laboratory -->

Let's look at the laboratory system in order to get an intuitive idea of 

##### Laboratory System

Using the sum of the forces in both directions, we derive. 

$$ \sum{F}_y = T cos(\theta) − W = 0 $$$$ \sum{F}_x = T sin(\theta) = mA    $$######Dividing one equation by the other, and substituting $$$W$$$ with mg, we end up with: 
$$ \frac{T sin(\theta)}{T cos(\theta)} = \frac{mA}{W} $$$$ tan(\theta) = \frac{mA}{mg} = \frac{A}{g} $$


$$ T = m \sqrt{g^2 + \textbf{A}^2}$$ 


##### Accelerating System

Looking at the accelerating system, our sum of the forces is a bit different. 

$$ \sum{F}_y = T cos(\theta) − W = 0$$###### here, $$$ F_{f} $$$ is the fictitious force that appears to be acting in the $$ \sum{F}_x = T sin(\theta) - F_f = 0 $$######Dividing one equation by the other, and substituting $$$W$$$ with mg, we end up with: 
$$ \frac{T sin(\theta)}{T cos(\theta)} = \frac{mA}{F_f} $$

$$ tan(\theta) = \frac{mA}{mg} = \frac{A}{g} $$


###  Physics in a rotating coordinate system

We'll see that by adding two *fictitious* forces, the *centrifugal force* and the *Coriolis force*, we can treat motion in a rotating coordinate system as if we were in an inertial system. Which is cray cray. 

Let's consider a rotating coordinate system, $$$x', y', z'$$$, whose origin coincides with the origin of the inertial system $$$x, y, z$$$, suppose for the sake of argument, that the system is rotating such that the z axes coincide. 

Thus the angular velocity of the system, $$$\Omega$$$, lies along the $$$z$$$ axis. In addition, at time $$$t$$$.

-> ![](http://i.imgur.com/oNNsrn8.png) <-

A particle has position $$$\textbf{r}(t)$$$ at time $$$t$$$, in the $$$xz$$$ and $$$x'z'$$$ planes at time $$$t$$$. at time $$$ t + \Delta t $$$, the particle is at position $$$\textbf{r}(t + \Delta t)$$$

-> ![](http://i.imgur.com/LdptIul.png) <-

This situation isn't the same for someone who's in a rotating coordinate system. While he still sees the same final position vector The displacement he measures relative to his coordinates is $$$ \Delta \textbf{r}'(t) = \textbf{r}(t + \Delta t) - \textbf{r}'(t)$$$ 

$$$ \Delta \textbf{r}(t) = \Delta \textbf{r}'(t) + \textbf{r}'(t) - \textbf{r}(t)$$$ 


$$$ \textbf{r}'(t) - \textbf{r}(t) = (\Omega \times \textbf{r}) \Delta t $$$ 

![](http://i.imgur.com/QGLpx6p.png ) $$  \big( \frac{d \textbf{B} }{dt} \big)_{in} = \big( \frac{d\textbf{B}}{dt} \big) + ( \Omega \times \textbf{r} ) $$


###### here the first term on the right side, $$$\frac{d\textbf{B}}{dt} $$$ is the measured change in the rotating frame. 

### Apparent force in a rotating coordinate system. 

The force observed in the rotating system is this. 
$$ \sum \textbf{F}_{rot} = ma_r = ma - m  [ 2 \Omega \times \textbf{v} - \Omega \times (\Omega \times \textbf{r}) ] $$

###### where a is the acceleration of the inertial system. 

Where the fictitious force, is the following: 

$$ \sum \textbf{F} = - 2m \Omega \times \textbf{v} - m\Omega \times (\Omega \times \textbf{r}) $$

The first term $$$ - 2m \Omega \times \textbf{v} $$$ is called the *Coriolis force*, which is a fictitious force that appears due to the rotation. 

The second term $$$ m\Omega \times (\Omega \times \textbf{r}) $$$, is called the *centrifugal force* and always points outward from the axis of rotation.


Imagine a car turning around a curve, it skids outwards... *as if* being pushed by the centrifugal force. If you're watching this happen in an inertial frame, what's actually happening is that the force of the road on the tires isn't enough to keep the car turning with the road. 

It's a lot more intuitive to describe rotational motion with a *rotating* system. Imagine whirling a rock on a string, it's intuitive to say the centrifugal force is pulling the rock outward, this balances the tension in the string. 

However, in an inertial system there is no centrifugal force. There is only the force of the string forcing the rock radially outward. 

##### Surface of a rotating liquid

A bucket of water spins with angular speed $$$\omega$$$. What shape does the water's surface assume? 

-> ![](http://i.imgur.com/ILOhatj.png) <-

Imagine a coordinate system rotating with the bucket, the problem is static. 

The forces on a small volume of water of mass $$$m$$$ on the surface of the liquid, at equilibrium would be as follows. 

The forces are the contact force $$$\textbf{F}$$$, the weight,$$$W$$$, and the fictitious force, $$$F_{fict}$$$. 

###### sum of forces in y direction
$$ \textbf{F} cos(\phi) - W  = 0 $$

###### sum of forces in x direction
$$ -\textbf{F}sin(\phi) + F_{fict}  = 0 $$

###### note: here $$$F_{fict}$$$ is equal to $$$m\Omega^2r$$$, and $$$\Omega$$$ = $$$\omega$$$ for a rotating coordinate system. We also move the fictitious force to the other side to remove the negative. 

Solving these equations for $$$\phi$$$ we end up at the following. 

$$ tan(\phi) = \frac{\omega^2 r }{g} $$ 

$$ \phi = arctan(\frac{\omega^2 r }{g})$$


The slope of the surface of water at any point is modeled by $$$\frac{dz}{dr} = tan(\phi) = \frac{\omega^2 r }{g} $$$

###### note: the reason it's simply $$$\frac{dz}{dr}$$$ is due to the way that force is applied perpendicularly to the surface.

So we now have a function of the surface of the water, let's simply integrate. 

$$\int dz = \frac{\omega^2}{g} \int r dr $$

$$ z = \frac{\omega^2r^2}{2g} $$ 

You might notice that this is a variant of the formula for a paraboloid of revolution!

