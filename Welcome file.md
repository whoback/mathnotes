# Essense of Calculus Notes

## Chapter 1

Calc is related to the study of circles.
$$\text{Recap: }Area = \pi R^2$$
A circle can be broken up into rings of a specific width we will call $$dr$$.
The height or length of each segment of dr = 2piR
These rings, notated as dr, can be used to approximate the Area of a circle
$$\text{Area} = 2 \pi R(dr)$$

These segments of dr can be graphed and will form the area under the line
$$y=2 \pi R$$

This area is just a triangle with an $$\text{Area} = 1/2bh \text{ where b = R and h = 2} \pi R$$

dr is both a factor in our equations and the space between our different values of R i.e. our rings

d stands for "a little bit of..." so above dr is a little bit of radius. In distance/velocity problems you might see dt which is a little bit of time.

for any dx the smaller the value of x gets us to a better approximation of the area under the graph

integrals are just functions
derivatives are measures of how sensitive a function is to small changes in its input

fundamental theorem of calculus is about the idea that derivatives and integrals are opposite operations of each other (not true inverses...)

## Chapter 2
Derivatives
Derivatives can be confusing due to their relationship with time. Typically, derivatives are described as measuring an instantaneous rate of change. 

Realize:
1. Change happens between discrete points in time and requires multiple points
2. Instantaneous refers to a single point in time

This is somewhat paradoxical!

Important names in Calc:
 1. Barrow
 2. Newton
 3. Liebniz
 4. Cauchy
 5. Weierstrass


To the point...

If we graph distance a car travels as a function of time then the height tells us how far we travel after that amount of time. Let this function be s(t)
If we graph the velocity of the car over this trip we get a function v(t)

s(t) and v(t) are related. 
how does v(t) depend on s(t)?

Remember:
$$
Velocity = \frac {\Delta distance} {\Delta time}
$$
Since we're dealing with changes we need multiple points. v(t) will give us velocity at discrete points in time. How does it do this?
$$\text{Let d = "a little bit of..." in this case it can be 0.01}$$
$$\text {Let dt = the difference in times of two points (x-values) very close on our graph such as 3.0 and 3.01 seconds}$$
$$\text{Let ds = the difference in distance traveled at two points (y-values) on our graph such as 20.0 and 20.21 meters}$$

this gives us:
$$
ds = (20.21 - 20.0) meters \over dt = (3.01 - 3.0) seconds
$$

We can think of $$ ds\over dt $$ as $$ rise\over run $$ on our graph of s(t). This allows us to find the graph of v(t) mentioned above which is just computed velocity over tiny changes in time. The resulting formula looks like:
$$
\frac {ds}{dt} (t) = \frac {s(t+dt)-s(t)}{dt}
$$
Read this as: 
the difference between the distance at time t + dt (the time 0.01 seconds after t) and time t (the given time) divided by dt (the change in time or 0.01)
 
 This is almost what a derivative is... what needs to change is our concept of dt. We don't really want to look at a specific value but at what happens when $$dt \rarr 0$$

As dt approaches 0, 2 things happen:
1. our two points move closer together ie approach each other
2. the slope of our line between ds and dt approaches the slope of the line that is tangent to the graph at point t!

So we can say that a derivative is equal to the slope of the line tangent to the given point t on our graph. Another way to think of a derivative is the best constant approximation for rate of change around  a given point.

Points to remember:
1. dt is not "infinitely small"
2. dt is not 0

## Chapter 3
Computing derivatives - how and why
Derivatives are fundamentally about tiny changes over time. Many real life applications are modeled using pure functions like polynomial, trigonometric, exponentials etc... We want to be able to have a shared language to discuss the rates of change for any of these real life situations. 

Rule of thumb: you can ignore any amount of dx raised to a power greater than 1


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTM5ODQ1MTU4MiwxMTc1NTE2Mjk2XX0=
-->