# Chapter 15: Kinetics, reaction orders

pages 453 - 482

## Week 29

- Monday - Read pages 453 - 457 stop before Collision Theory
- Tuesday - Read pages 457 - 461 stop before It lasts only for an instant
- Wednesday - Read pages 461 - 467 stop before Activation Energy, Temp, and The Rate Constant
- Thursday - Class - Lab 15.1 and Review Reading

## Notes

- The rate of a reaction is really important. How fast the reaction occurs tells us how much it will impact its surroundings.
- Kinetics - the study of chemical rates
- Simple rate formula - Rate = &#916;[C]/&#916;t where &#916;[C] is the change in concentration of the product C usually denoted in molarity (M) and &#916;t is the change in time usually denoted in seconds (s). If you measure the concentration of a reactant instead of a product you have to negate everything to keep the result positive.
- the reaction rate is usually proportional to the concentration of reactants. 
- the reaction rate is usually proportional to the surface area over which the reaction can occur.
- the reaction rate is usually proportional to the temperature.
- In general, the more contact the molecules/atoms of the reactants have, the faster they will react to form the products.
- Not all collisions between reactants are the same. In some cases the reactants have to collide in just the right way to react.
- Effective collisions are those collisions that lead to a reaction.
- rate equation - Rate = k[A]<sup>x</sup>[B]<sup>y</sup> where k is a rate constant that is particular to the reaction of A and B (so you need a table) and A and B are reactants and x and y are the "order" of the reaction. The word order here is similar to the word power or exponent, it refers to the fact that we are raising the concentration of A or B to a power. This may be 1 which doesn't change the number. (Remember that any number raised to the power of 1 is itself).
- The overall reaction order is given by adding x and y from the rate equation.
- So, what are the units for k? Well, it depends. We want the units in k to cancel out the other units leaving us with just M/s for rate. But [A] and [B] are both in M which will give us M<sup>2</sup>. And if the "order" of [A] or [B] is more than 1 then we have even more M's since [A]<sup>3</sup> => [A] * [A] * [A] => which makes the units M * M * M => M<sup>3</sup>. So, the units for k change depending on the overall order of the reaction.
- As soon as the reaction starts the concentrations of all the reactants and products are changing. So the rate we calculate at the beginning of a reaction isn't really the rate of the reaction in the middle or at the end.
- So the rate equation is really just giving us the instaneous rate of the reaction at a moment in time that we choose.
- So how do we determine these reaction orders that seem so important? the answer is you can't get them easily from anything in the equation. The simplest way is to measure the rate of the reaction 3 times varying the concentrations carefully so you can determine the x and y values.


## Examples

CC1. From 1.15 M at t = 0.0 s to 0.98 M at t = 15.0 s. Is it a product or reactant? What was the rate of change?
- The concetration went down, so this was a reactant.
- Rate = - &#916;[C]/&#916;t = - (0.98 M - 1.15 M)/(15.0 s - 0.0 s) = (0.17 M)/(15.0 s) = **0.011 M/s** 

CC2. Which has a lower reaction rate?
- large chunks or powdered - large chunks will have less surface area and reduce the number of collisions. So large chunks have a lower reaction rate.
- 15 degrees or 50 degrees - 15 degrees would slow down the molecules and reduce the number of collisions. So 15 degrees has a lower reaction rate.
- 5.0 M or 1.0 M - 1.0 M is less concentrated and therefore has less molecules per liter which will reduce the number of collisions. So, 1.0 M has a lower reaction rate.

CC3. 2 reactants; overall order = 1; order with respect to the first reactant is 1
- what is the order of the second reactant? x + y = 1; x = 1; therefore **y = 0**
- what are the units on the rate constant? the overall order is 1 so there is just one M. so **1/(M * s)**

CC4. Reaction: NO (g) + O<sub>3</sub> (g) --> NO<sub>2</sub> (g) + O<sub>2</sub> (g); What's the rate equation?
| Trial | [NO] | [O<sub>3</sub>] | instaneous rate |
|---|---|---|---|
| 1 | 0.0010 M | 0.0010 M | 22.0 M/s |
| 2 | 0.0010 M | 0.0020 M | 44.0 M/s |
| 3 | 0.0020 M | 0.0010 M | 44.0 M/s |
- First, you should notice that no matter which reactant was doubled, the rate also doubled, so x should equal y, but let's work it out
- Remember the equation: Rate = k[A]<sup>x</sup>[B]<sup>y</sup>
- We can create 3 different equations from our table:
  - equation 1: 22.0 M/s = k(0.0010 M)<sup>x</sup>(0.0010 M)<sup>y</sup>
  - equation 2: 44.0 M/s = k(0.0010 M)<sup>x</sup>(0.0020 M)<sup>y</sup>
  - equation 3: 44.0 M/s = k(0.0020 M)<sup>x</sup>(0.0010 M)<sup>y</sup>
- If you remember in Algebra 2, when you have 3 equations and 3 variables, you can solve for each variable usually by combining the equations. Let's start with equation 2. As long as I add/subtract/multiply or divide both sides by the same amount, the equation is still valid. Equation 1 tells us that 22.0 M/s is the same amount as k(0.0010 M)<sup>x</sup>(0.0010 M)<sup>y</sup> (they just look really different). Since those are the same amounts, I can divide both sides of equation 2 with these amounts.
- So, (44.0 M/s) / (22.0 M/s) = (k(0.0010 M)<sup>x</sup>(0.0020 M)<sup>y</sup>) / (k(0.0010 M)<sup>x</sup>(0.0010 M)<sup>y</sup>)
- Hopefully, that makes sense. Now we can cancel some things out on both sides and really simplify this new equation.
- So, 2.00 = (0.0020 M)<sup>y</sup> / (0.0010 M)<sup>y</sup>
- So, 2.00 = (0.0020 M / 0.0010 M)<sup>y</sup>
- So, 2.00 = (2.0)<sup>y</sup> ... so y must be 1
- You can do the same thing for x by dividing both sides of equation 3 with equation 1 like we did here, but you will get the same answer. 
- **x = 1 and y = 1**
- But we still need to know k. But that's pretty easy now that we have x and y. We just need to solve for k. Let's use equation 1.
- 22.0 M/s = k(0.0010 M)<sup>1</sup>(0.0010 M)<sup>1</sup>
- 22.0 M/s = k(0.0010 M)(0.0010 M)
- 22.0 M/s = k(0.0000010 M<sup>2</sup>)
- k = (22.0 M/s) / (0.0000010 M<sup>2</sup>) = (22.0/0.0000010) M/s = **22,000,000 M/s**
- So, rate = (2.2 * 10<sub>7</sub> M/s)[NO]<sup>1</sup>[O<sub>3</sub>]<sup>1</sup>

CC5. 

## Optional Videos

## Class Videos
