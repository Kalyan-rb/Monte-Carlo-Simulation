# Monte-Carlo-Simulation

# Problem Statement:

### If we throw a dart randomly inside the Square of sides of length 2, what is the probability that the dart is inside the Circle of radius 1?

#### Answer:

##### The Probaility of throwing a dart inside the circle is just proportional to the Area of the Circle to the Area of the Rectangle

##### i.e
$$ A_{\text{circle}} = \pi r^2 $$  $$ A_{\text{rectangle}} = \text{length} \times \text{width} $$

###### Final Answer: 
$$ \pi/4 = 0.785 $$

Using Monte Carlo, We can Sample the number of points from the square and find the proportion of Points falling 
inside the Circle, Which Ultimately gives the probability of dart falling inside the circle
