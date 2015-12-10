## Deriving the Work Energy Theorem

### David Awad


This is a small synopsis on the derivation of the work energy theorem! 


The key step is to convert the calculus definition for acceleration into an expression that is a derivative of x.

$$ a = \frac{dv}{dt} = \frac{dv}{ds} \frac{ds}{dt} = v\frac{dv}{ds} $$


We start with Newton's second law of motion, which states that the sum of all forces acting on a object are equal to a resultant force that is the object's mass times the objects acceleration. 


$$ \sum \vec{F} = ma $$

$$ \sum \vec{F} = mv\frac{dv}{ds} $$



The integral of the force irrespective of position, is the definition of work 

$$ W = \int_{s_i}^{s_f} \sum \vec{F} \thinspace ds $$

$$ W = \int_{s_i}^{s_f} ma \thinspace ds $$

Now we can substitute using our identity for acceleration. 

$$ a = v\frac{dv}{ds} $$


$$ W = \int_{s_i}^{s_f} m a \thinspace ds $$


$$ W = \int_{s_i}^{s_f} m v\frac{dv}{ds} \thinspace ds $$


$$ W = \int_{v_i}^{v_f} m v \thinspace dv $$

$$ W = \tfrac{1}{2} s^2 \Big|_{v_i}^{v_f} $$

And so we end up with a function for work that's completely irrespective of position! 

$$ W = \frac{1}{2} m v_f^2 - \frac{1}{2} m v_i^2 $$


<!-- -> ![](http://faculty.wwu.edu/vawter/physicsnet/topics/Work/gifs/Work12.gif) <- --> 