The predictive posterior distribution of the frequency of success in coin flip is estimated by sampling given apriori knowledge and a sample of previous outcomes of flipping the same coin. The algorithm NUTS (implemented in the library <code>pymc</code>) is used for sampling. The histogram of the predictive posterior distribution is plotted after generation.

<b>Selected model.</b>

The Beta prior is used and the effect of strength of the prior is tested. 5 different strengths of prior (numbers of pseudo-trials) are tested.

<b>Results.</b>

As expected, the mean of the posterior distribution converges to the apriori probability of success when the number of pseudo-trials increases. The Standard Deviation of the posterior predictive distribution decreases. On the other hand, its decrease is quite slow. 

<b>Feedback and additional questions.</b>

All questions about the source code should be adressed to its author Alexandre Aksenov:
* GitHub: Alexandre-aksenov
* Email: alexander1aksenov@gmail.com
