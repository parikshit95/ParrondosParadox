# ParrondosParadox

As counter intuitive as it may seem, in certain games, a combination of losing strategies can yield
a winning strategy. This fascinating phenomenon was discovered by physicist Juan Parrondo
in his study of Brownian Rachets, a thought experiment involving a perpetual motion machine;
wherein the simple machine, consisting of a tiny paddle wheel and a ratchet, is able to extract
useful work from random fluctuations (heat) in a system at thermal equilibrium in violation of the
second law of thermodynamics.

I along with [Ernesto Garcia](https://github.com/egarcia55), [Konstantine Mushegian](https://github.com/kmushegi) and [Marcus Christiansen](https://github.com/MarcusEFC/Parrondos-Paradox)  take a different approach to investigate and mathematically describe this phenomenon
by using three simple games. The first game, Game A involves tossing an biased coin. The second,
Game B tosses a biased coin with a distinct probability if the player has a multiple of 3 in his
pocket; else, a biased coin with different probability is tossed when the player does not have a
multiple of 3 in his pocket.While, Game C simply involves alternating between Game A and Game
B with equal chance. For each trial, we flip a coin 10,000 times and keep track of aggregate
winnings under the setup of each game. This is then repeated for 1000 trials, the results
averaged and finally plotted to gain some insight into the trend over the 1000 repetitions and
under different magnitudes of the bias (e). 

Interestingly, we demonstrate that the random transition from each of these states under the
games can be modeled using matrices known as Markov matrices. The transform defined by such
a Markov matrix on these probability vectors represents transitioning from the probability vector
at the n-th to the n+1-th game; thus, enabling us to look at these games as dynamical systems
in discrete time.Interestingly, using a theorem, called the Perron-Frobenius Theorem we show
how this discrete dynamical system would always approach a steady state.

The rest of the paper is organized as follows, section II. introduces the games more formally and
describes the results of the simulations.Section III. and IV. model the game by elaborating on the
theory behind MarkovChains, Discrete Dynamical Systems and the Perron 􀀀 Frobenius Theorem
and evaluates whether theory explains the results from the simulations respectively.Section V.
concludes. Finally, Section VI. ponders on the applications of the model and their scope in fields
such as Finance.
