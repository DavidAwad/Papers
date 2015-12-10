## A series of notes on Rotational Mechanics and Angular Momentum
#### David Awad


## Rotational Kinetic Energy

The majority of information on this section of physics stems from the conservation of energy that you already know. 

$$  \vec{E} = \vec{E}_i $$

$$	\vec{E} = U + KE $$

$$	\vec{E} = mgh + \frac{1}{2}m v^2 $$

Now much like there are two types of potential energy (through things like the spring force) there are also different types of kinetic energy. 

There is a translational portion, and a *rotational* portion. 

So this is represented by a new quantity that we account for in our formula for kinetic energy. 

$$ KE = \frac{1}{2}m v^2 + \frac{1}{2}I \omega^2 $$

This $$$I$$$ quantity is called the *moment of intertia*. So why do we have it? Well, it certainly follows that the way in which we evaluate the rotational energy would have something to do with the *speed* of rotation itself, $$$\omega$$$, but what then does $$$I$$$ mean? It's a quantity evaluated based on the properties of the object that's rotating. 

######note: $$$\omega$$$ is measured in terms of $$$\frac{rad}{sec}$$$

Its affected by things like the mass distribution of an object. Like for example a sphere will rotate very differently than a disc.   

Here are some of different geometric figures that can exhibit rotational kinetic energy and they're corresponding moments of inertia. 

->![](http://hyperphysics.phy-astr.gsu.edu/hbase/imgmec/mic.gif)<-



Let's look at a sample problem that can apply some of this new information we have.

Suppose we have a hoop of mass $$$M$$$ and Radius $$$R$$$ sitting at the top of an inclined plane that's inclined with some angle $$$\theta$$$, assuming there is no slipping, what is the change in potential energy after the hoop has descended some distance $$$x$$$ from the top of the incline? 
###### the picture doesn't have the $$$\theta$$$ in it, my bad.

->![](http://img.sparknotes.com/content/testprep/bookimgs/sat2/physics/0008/incline.gif)<-


The hoop starts at the top of the incline, bearing this in mind there's a change in potential energy due to the change in height. It descends some distance $$$\Delta{x}$$$ along the incline due to the vertical component of gravity. 

So our change in potential energy looks something like this. 

$$ \Delta{U} = mg\Delta{x} \times Sin(\theta) $$ 

So out change in potential energy has to be equal to our change in kinetic energy. 

$$ \Delta{U} = mg\Delta{x} \times Sin(\theta) = \frac{1}{2} m \dot{x}^2 + \frac{1}{2}I\omega^2 $$

So how do we proceed? We want velocity as a function of position $$$x$$$. Well, let's deal with $$$\omega$$$ first. We know there's a one to one relationship between the speed and the rotation. 

Imagining that the initial point of contact wraps around the circumference of the hoop multiple times as it descends the hill. You can express this as an angle $$$\Delta \phi $$$

Because it rolls without slipping, you can assert $$$x = R\Delta\phi$$$. Essentially asserting that the radius times the angle is a length that the hoop has traveled along the incline. 

$$x = R\Delta\phi$$ 
	
$$ therefore, $$ 

$$\dot{x} = R  \dot{\phi}$$

$$ \dot{\phi} = \omega $$

###oh snap.

So for motion in which there is no slipping, $$$\dot{x} = R\omega$$$

And remember, since we're looking at a hoop, we have $$ I = MR^2 $$ 


So let's look back at our conservation of energy theorem

$$ \Delta{U} = Mg\Delta{x} \times Sin(\alpha) = \Delta KE = \frac{1}{2} M \dot{x} + \frac{1}{2}I\omega^2 $$

$$ Mg\Delta{x} Sin(\alpha) = \frac{1}{2} M \dot{x}^2 + \frac{1}{2}(MR^2)(\frac{ \dot{x} }{R})^2 $$


$$ Mg\Delta{x} Sin(\alpha) = \frac{1}{2} M \dot{x}^2 + \frac{1}{2}(MR^2)(\frac{ \dot{x} }{R})^2 $$


$$ \dot{x}^2 = gx \sin(\alpha) $$

We end up with a function of the $$$\alpha$$$ that models the motion down an incline that's simply a function of the forces being applied in the direction of motion. (at least for a hoop, anyway.)

###This is an important fact that we've just found as it means that physically its rotation is independent of the radius and the mass.


## Angular momentum 

Angular momentum is analagous to linear momentum. However it's a little different than linear momentum in the cases of rotation. It's a conservative force!  

It's usually defined relative to some origin. Imagine a particle traveling with some velocity $$$v$$$ traveling above the origin. With it's position defined by some radius $$$r$$$

<!-- ![](Desktop/particle momentum2.png) --> 


We'd say that particle has angular momentum $$$\vec{L} = r \times p = \vec{r} \times m\vec{v}$$$
######note: we always define angular momentum with respect to some origin in some coordinate system. 

$$$\vec{L}$$$ in this case is a vector coming out of the page.

$$ \vec{r} = (vt)\hat{x} + b\hat{y} $$

Where $$$b$$$ is defined as the vertical height of the particle from the $$$y=0$$$. 
######note: this 'b' quantity is sometimes called the impact distance. Why? No clue. 


So if we were looking for the angular momentum $$$\vec{L} = r \times p = m \vec{v} b \hat{z} $$$

####This means that angular momentum is a constant force!

What if we wanted the rate of change in this force? 

$$ \frac{d\vec{L}}{dt} = \frac{d \vec{r} }{dt} \times \vec{P} + \vec{r} \times \frac{d \vec{p} }{dt} $$
This looks a bit more like something newtonian! 

$$ \frac{d\vec{L}}{dt} = \vec{r} \times \vec{F} = \vec{\tau} $$


#### Here's an example problem 

Imagine a small mass orbiting a much larger mass in system. Such that the smaller mass' force is negligible.

![](http://hyperphysics.phy-astr.gsu.edu/hbase/imgmec/amp1.gif) 

$$ \vec{\tau} = \vec{r} \times \vec{F} = 0 $$

-> Therefore $$$\vec{L}$$$ is constant. <-

<!-- The angular momentum of a particle of mass m with respect to a chosen origin is given by $$ \vec{L} = mvr\sin{\theta}$$ -->

$$ \frac{dA}{dt} = \frac{1}{2} r^2 \frac{d\theta}{dt} $$


$$ \frac{dA}{dt} = \frac{1}{2} r^2 \omega = \frac{\vec{L}}{2m} $$

<!-- 

## rotation of a rod 

$$ \Delta E = mgx $$

$$ mgx = T $$

$$ T = mgx = \frac{1}{2}m \dot{x}^2 - \frac{1}{2}I\omega^2 $$

$$ x = \frac{l}{2} (1 - \cos{\theta} )$$

$$ \dot{x} = \frac{l\omega}{2} \sin{\theta}    $$

-->


## Useful formulas

$$ a(t) = r\alpha $$

$$	\alpha(t) = \frac{d\omega}{dt} = \frac{d^2\theta}{dt^2} $$

$$ \omega(t) = \frac{\Delta \theta}{\Delta t} = \frac{\theta_2 - \theta_1}{t_2 - t_1} $$

$$	\omega=\frac{d\theta}{dt} =  \frac{v}{r} $$ 

For the torque of a rigid body it's proportional to the moment of inertia times the angular acceleration

$$	T = I\alpha $$

$$ \omega = 2 \mathrm{\pi} f (\frac{rad}{sec}) $$ 

######section of a circle $$$ s = r\theta $$$


