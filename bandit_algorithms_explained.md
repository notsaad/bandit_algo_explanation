# Bandit Algorithms Explained

I recently published a research paper on abstract bandit algorithms, specifically stochastic and adversarial bandit algorithms. When I told people this, the natural reaction is often to wonder what bandit algorithms are.

Bandit Algorithms are a subset of optimization algorithms / reinforcement learning. That is to say, bandit algorithms are used when we want to find the best option out of a set of choices, often with limited data. There is two main branches of bandit algorithms, stochastic and adversarial. Where the difference lies in the probability distributions of the arms when they are pulled.

Firstly, stochastic bandits are used where the choices have unknown but fixed reward distributions, meaning the reward distributions do not change over time. Secondly, adversarial bandits are when the rewards from pulling the arms have a dynamic reward distribution.

Examples of applications of stochastic bandits are for financial portfolio optimization or for online advertising. Financial portfolio optimization is a key example of adversarial bandits because of the constantly changing reward distributions of stocks, if we were to use a stochastic algorithm the algorithm would fixate on a previously well performing stock, disregarding modern performance. As for online advertising, bandit algorithms are used to determine which sets of ads to show to optimized click through rates by learning user preferences over time.
