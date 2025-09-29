Probability Equation
$$
P(D|H_1,X)
$$
- $D$ is an observed data
- $H_1$ is a hypothesis
- $X$ is a prior experience

This reads as probability of an observation $D$ based on hypothesis $H_1$ with prior experience $X$. 
- $P(D)$ : Probability of observation D. 
- $P(D|X)$ : Probability of observation D given prior experience X.
- P(H_1|X) : Probability of your hypothesis based on prior experience

Usually a hypothesis can better help explain the data you observe
$$ P(D|H_1,X) >> P(D|X)$$
With new observations your hypothesis may change for example $D_{updated}$ you will have new hypothesis $H_2$. You can say:
$$P(D_{updated}|H_2,X) >> P(D_{updated}|H_1,X)$$
Since the new data supports your new hypothesis and not your original hypothesis. The ratio
$$\frac{P(D_{updated}|H_2,X) }{P(D_{updated}|H_1,X)}$$ can help show how much better your new hypothesis helps support the data.

# Exercises

1. Rewrite statements using notation from this chapters
	- The probability of rain is low
		- $P(rain) = low$
	- The probability of rain given that it is cloudy is high
		- $P(rain | cloudy) = high$
	- The probability of you having an umbrella given it is raining is much greater than the probability of you have an umbrella in general
		- $P(umbrella | raining) >> P(umbrella)$
2. Organize the data in mathematical notation and come up with hypothesis
	- You come home from work and notice that your front door is open and the side window is broken. As you walk inside, you immediately notice that your laptop is missing
		- $D$ = front door is open, window is broken, laptop is missing 
		- $H_1$ = someone broke in and stole the laptop
		- $P(D | H_1)$
3. The following scenario adds data to the previous one. Come up with new hypothesis for this
	- A neighborhood child runs up to you and apologizes profusely for accidentally throwing a rock through your window. They claim that they saw the laptop and didn't want it stolen so they opened the front door to grab it, and your laptop is safe at their house.
		- $D_{updated}$ = front door is open, window is broken, laptop is missing, child apologizes
		- $H_2$ = child broken the window and took laptop for safe keeping
		- $P(D_{updated} | H_2) >> P(D_{updated} | H_1)$