$\neg$ means not or negation $P(X) + \neg P(X) = 1$. We can find the negations of $P(X)$ by subtracting it from 1.

$\Omega$ is used to indicate the set of all of events. For example the set of all event of flipping a coin is $\Omega = {heads,tails}$. You can calculate the probability of $X$ occurring by 

If you have the odds that $X$ happens is $m$ and the odds it does not happen is $n$. The probability of it happening can be calculated as
$$\frac{P(X)}{\neg P(X)} = \frac{m}{n}$$
$$n * P(X) = m * \neg P(X)$$
$$n*P(X) = m(1-P(X))$$
$$n*P(X) = m-m*P(X)$$
$$(n+m)*P(X) = m$$
$$P(X) = \frac{m}{n+m}$$

# Exercises
1. What is the probability of rolling two six-sided dice and getting a value greater than 7?
	 - The total amount of combination of rolling 2 six-sided dice is 36. Greater than 7 would be {8,9,10,11,12}. There are 5 combinations that make 8, 4 combinations that make 9, 3 combinations that make 10, 2 combinations that make 11, and 1 combinations that makes 12. Adding those together we get 15 combinations that make >7 so the odds are
	   $$\frac{15}{36} \approx 0.416 $$
2. What is the probability of rolling a 3 six-sided dice and getting a value greater than 7?
	- This time there are $6^3 = 216$ combinations. To solve this we will instead write a python program to quickly find the sets that are greater than 7. 

	  ```python
res = 0

for i in range(1,7):
	for j in range(1,7):
		for k in range(1,7):
			if i + j + k > 7:
				res += 1

print(res)
```
	 -  The result of this code is 181 therefore the probability of the 3 dice rolling greater than 7 is 
	   $$\frac{181}{216} \approx 0.837$$
3. You put 30 to 5 odds on the Red Sox winning. What is the probability that you have assigned to the red sox winning.
	- $P(X) = \frac{30}{5 + 30} = \frac{30}{35} \approx 0.857$ - so about 86% chance the Red Sox win.

