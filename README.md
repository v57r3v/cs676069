java c
Homework set 1- non-assessed
Convolutions
Further Topics in Probability, 2nd teaching block, 2025
Problems with •’s are to be handed in. These are due in Blackboard before noon on Thursday 30 January. Please show your work leading to the result, not only the result. Each problem worth the number of •’s you see right next to it. Hence, for example, Problem 1.1 worth three marks. Random variables are defined on a common probability space unless otherwise stated.
1.1 ••• Determine the mass function of the sum of the numbers shown by two fair four-sided (tetrahedron) dice after rolling them.
1.2 ••• Let X be a discrete uniform. random variable on the set {0, 1, . . . , n − 1} (that is, it takes on any of these values with probability 1/n). Argue that if n is not a prime number then the distribution of X can be written as the convolution of two integer-valued distributions.
1.3 Show analytically that ∗rGeom(p) = NegBinom(r, p). HINT: Can use induction on the sum of binomial coefficients that emerges.
1.4 ••• Let X ∼ Poisson(λ) and Y ∼ Uniform(0, 1) be independent random variables. Find the distribution function of the random variable Z : = X + Y .
1.5 •••• A man takes the train and then transfers to the bus when commuting to work each day. It takes two minutes for him to walk from the train to the bus at the transfer station. In principle the train arrives at 7:30am, and the bus leaves at 7:37am. The fact is that the train arrives at a normally distributed random time, having mean 7:30am and standard deviation 4 minutes. Independently, the bus leaves at a normally distributed random time with mean 7:37am and standard deviation 3 minutes. What is the probability that our man misses his bus at most once on the five working days of the week? HINT: Use what you know about the sum of independent normal variables.
1.6 (This is not convolution, just a bit of outlook.) Let X and Y be iid. Uniform. random variables on the interval (0, 1). Find the density of their product XY .
1.7 •••• Let X and Y be iid. random variables, each with density f(x) = 3x2· 1{x ∈ [0, 1]} (1 stands for the indicator function here). Determine the density of the random variables
a) U : = X + Y ;
b) V : = X − Y .
1.8 Let X1, X2, . . . , Xn, . . . be iid. random variables, each of Uniform(0, 1) distribution. Denote by fn(x) the density of the random variable Sn := Pnk=1Xk. Prove

Plot, using a computer,

for n = 1, 2, . . . , 10. What do you see?
1.9 Let X1, X2, . . . , Xn, . . . be iid. random variables, each of distribution P{Xi = 0} = P{Xi = 1} = 2/1. Let Y : = P∞n=1 2−nXn. Argue that Y is uniformly distributed on the real interval [0, 1]. HINT: It is enough to show that probabilities of Y falling in intervals agree with those of the uniform. distribution. The two ends of an interval can be approximated by numbers in the base 12number system.
1.10 Let X1, X2, . . . , Xn, . . . be iid. random variables, each of distribution P{Xi = 0} = p = P{Xi = 1} = 1 − p. Let Y : = P∞n=1 2−nXn. Argue that Y is singular w.r.t. the uniform. distribution on the interval [0, 1], that is,
∀ε > 0 ∃A ⊂ R : P{Y ∈ A} ≥ 1 − ε, P{U ∈ A} ≤ ε,
where U is uniformly distributed over (0, 1). (In fact, A has to be Borel measurable, but don’t worry about this.) HINT: Again, think in the base 12number system. The Weak Law of Large Numbers says that the probability that the average of the first n Xi’s is off from p by more than δ converges to zero as n → ∞.
Homework set 2- first assessed homework
Gamma distribution


Problems with •’s are to be handed in. These are due in Blackboard before noon on Thursday 6 February. Please show your work leading to the result, not only the result. Each problem worth the number of •’s you see right next to it. Random variables are defined on a common probability space unless otherwise stated.
2.1 Prove that if ξ is a Cauchy random variable with density f(x) = π11+1x2, then X : = 1/ξ, Y : = 2ξ/(1 − ξ2), and Z : = (3ξ − ξ3)/(1 − 3ξ2) are also Cauchy distributed. HINT: use the trigonometric identities: if ξ = tan(α), then 1/ξ = tan( π2 −α), 2ξ/(1−ξ2) = tan(2α), and (3ξ − ξ3)/(1 − 3ξ2) = tan(3α).
2.2 Let X be a Cauchy random variable with density f(x) = π11+1x2. We know that E|X| = ∞, but E(|X|1−ε) < ∞ for any ε > 0. Determine the limit lim ε↘0 εE(|X|1−ε). HINT: Split the integral at a well chosen point.
2.3 Let X and Y be iid. standard Normal random variables. Determine the joint density of the pair U = X, V = X/Y . Then use it to show that X/Y has the standard Cauchy distribution.
2.4 We are given a biased coin that shows Heads with probability p and Tails with probability 1−p. The coin initially shows Heads, and at time moments given by a Poisson(λ) process we flip the coin again and again. What is the probability that the coin shows Heads at time t?
2.5 •••• (With a good understanding of stuff, you can solve this problem without any compu-tation.) Let X1, X2, . . . be iid. random variables each with density 12x2e−xfor x > 0 and 0 otherwise. Let S0 = 0 and Sn : = X1 + · · · + Xn, and N(t) : = max{n : Sn < t}.
a) Determine the density of the random variable S2.
b) Find the mass function of the random variable N(t).
2.6 Show, using the convolution formula, that Gamma(α, λ) and Gamma(β, λ) convolve to Gamma(α + β, λ) for any positive reals α, β, λ. Along the way there will be a tricky integral, which doesn’t have to be explicitly calculated as long as you can scale out its dependence on the important variable. You can then use the fact that Gamma densities are normalized (thus proving a representation of Beta functions this way).
2.7 ••• Find the density of the sum of an Exponential(λ) and an independent Exponential(µ) random variable (λ = µ). What happens when µ → λ?
2.8 •••• Are the following functions generating functions of non-negative integer probability distrib代 写Further Topics in Probability, 2nd teaching block, 2025R
代做程序编程语言utions?




2.9 ••• Let X be a non-negative integer-valued random variable with generating function P(s). Find the generating function for the distribution of Y : = X + 2 and the one for Z : = 3X.
2.10 ••• Let X1, X2, X3, . . . be iid. random variables with common distribution function F. Let ν ≥ 1 an independent, integer-valued variable with generating function P, and define Y : = max{X1, X2, X3, . . . , Xν}. Show that Y has distribution function P   
Homework set 3- non assessed
Generating functions




Problems with •’s are to be handed in. These are due in Blackboard before noon on Thursday 20 February. Please show your work leading to the result, not only the result. Each problem worth the number of •’s you see right next to it. Random variables are defined on a common probability space unless otherwise stated.
3.1 Let X1, X2, . . . be iid. Optimistic Geometric(p1) random variables, and Z an independent Optimistic Geometric(p2) random variable. Prove, using generating functions, that





Give a probabilistic interpretation of this fact.
3.2 •••• The distribution of a random variable X is called infinitely divisible, if for every n ≥ 1 integer there exist Y1(n), . . . , Yn(n)iid. random variables such that





a) Is the Poisson distribution infinitely divisible? Why or why not?
b) Is the Binomial distribution infinitely divisible? Why or why not?
c) Prove that for every 0 < p < 1 there exists a probability mass function p1, p2, . . . and λ > 0 with which P Zi=1 Xi ∼ Pessimistic Geometric(p), where X1, X2, . . . are iid., for k ≥ 1 P{Xi = k} = pk, and Z is an independent Poisson(λ) random variable.
d) Show, with the help of c), that the Pessimistic Geometric distribution is infinitely divisible.
3.3 a) In a branching process
P(s) = as2 + bs + c
where a > 0, b > 0, c > 0, P(1) = 1. Compute π. Give a condition for sure extinction.
b) Little Johnny is salesman in a store where servicing a customer takes exactly 1 minute. Under this time, with probability 0.6 two new customers arrive in the queue, with probability 0.2 one new customer arrives, with probability 0.2 no new customers appear. Little Johnny can have his coffee if the queue empties out. What is the probability that this ever happens after the first customer steps in the store? Explain.
3.4 ••• In a branching process let X =P∞n=0 Zn be the number of individuals that ever existed. You can use, as we saw in class, that its generating function Q satisfies
Q(s) = sP(Q(s)).




a) Find Q(s) when the distribution of the number of children of an individual is Bernoulli(p).




b) Find Q(s) when the distribution of the number of children of an individual is Pes-simistic Geometric(p).
c) Find EX in both cases.
3.5 •••• Car traffic of a street is modeled by
a) dividing the time into unit seconds;
b) assuming that with probability 0 < p < 1 a car passes in a given second;
c) events (of cars passing or not) in different seconds are independent of each other.
A pedestrian wants to cross this street, and she can do so if no cars come in two consecutive seconds. (We assume that the pedestrian sees enough of that street to decide if she can cross safely.) Find the generating function and expectation of the time the pedestrian spends on waiting for the street to clear enough so that she can cross.
3.6 A monkey repeatedly types in any of the 26 letters of the English alphabet independently with equal chance. Let T be the number of letters typed in when the word “DAD” first appears. Find the generating function and the expected value of T.
3.7 ••• Little Johnny regularly speeds with his car, and police regularly stop him. Every such instance he pays ↔ 100 or ↔ 500 with probability 1/2-1/2, independently of everything else. Moreover, Johnny handles such situations in a very bad manner, and the blustering fellow he is, every such occasion also results in his driving licence being revoked with probability p. Find the generating function, expectation and standard deviation of the total amount of fines paid by Johnny.
3.8 A Skip Free Negative Random Walk. Suppose {Xn, n ≥ 1} is independent, identi-cally distributed. Define S0 = X0 = 1 and for n ≥ 1
Sn = X0 + X1 + · · · + Xn.
For n ≥ 1 the distribution of Xn is specified by
P{Xn = j − 1} = pj, j = 0, 1, . . .




where





(The random walk starts at 1; when it moves in the negative direction, it does so only by jumps of −1. The walk cannot jump over states when moving in the negative direction.)
Let
N = inf{n : Sn = 0}.
If P(s) = EsN , show P(s) = sf(P(s)). (Note what happens at the first step: Either the random walk goes from 1 to 0 with probability p0 or from 1 to j with probability pj.) If f(s) = p/(1 − qs) corresponding to a geometric distribution, find the smallest solution.
3.9 Consider the simple random walk that starts from the root of a rooted tree of degree d ≥ 3. That is, in each step the walker picks independently any of the d neighbors of a vertex to step on with equal chance. Compute the generating function of
a) the hitting time of a given neighbor of the root;




b) the generating function of the first return time to the origin;
c) the generating function of the last return time to the origin.
3.10 ••• For a simple random walk {Sn} let u0 = 1 and for n ≥ 1, let
un = P{Sn = 0}.
Compute by combinatorics the value of un. Find the generating function





in closed form. To get this in closed form. you need the identity





The binomial coefficient for general α ∈ R and positive integer k is defined as





With this definition and assuming |x| < |y|, the Binomial Theorem holds:





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
