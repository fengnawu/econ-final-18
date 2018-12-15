
## Consumer Choice (Chapter 2)

#### Intermediate Microeconomics (Econ 100 A)

#### Natalia Lazzati

#### UCSC - Winter 2019

---------------------------------
## Consumer Choice
* This section presents some standard economic models of consumer behavior.

---------------------------------
## 2.1 Rational Choice
The basic model of consumer choice studies the decision of a single person regarding what goods to acquire, and how much to buy of each of them, taking as given the prices of the goods and the income level of the consumer. Our simple model assumes that each consumer chooses the “best” combination of goods ---or bundle---  that “he can afford”. The idea of “best” builds on the notions of preferences and utility; our model captures “affordability” via budget sets. 


1. **Preferences**: The preferences on an individual consist of his personal ranking over all possible alternatives. We often capture these preferences by the so called utility function. 


2. **Budget Set**: The budget set of an individual is the collection of all alternatives that he can afford given his resources (income or wealth) and the prices of the goods he faces in the market.


Together, **(1)** and **(2)** induce choices. That is, they determine what consumption bundles are selected by the consumer. As prices and/or income change, so does the budget set and (often) the combination of goods that the consumer selects. The demand function describes the consumption decisions for all different combinations of prices and income levels. 

To simplify the exposition, we will focus on a simple version of the consumer problem. The components of our model are as follows:

1. We assume there are only two goods: good 1 and good 2.
2. We represent the quantities of these goods as $x_{1} and x_{2}$ , respectively. The ordered pair ($x_{1},x_{2}$) denotes a bundle of goods.
3. The prices of the goods are represented by p₁ and p₂, respectively.
4. The income level of the consumer is denoted by *m*.

--------
**Example**: Suppose good 1 is orange juice and good 2 is salad. Then $x_{1},x_{2}$ is the quantity of salads (say in pounds). In this context, the combination ($\frac{1}{2}$ , 1) represents the bundle of half liter of orange juice and one pound of salad. Suppose also that a liter of orange juice costs 5 dollars, a pound of salad costs 10 dollars, and the income level of the consumer is 500 dollars. In our notation, this information is concisely written as $p_{1} = 5, p_{2} = 10$ , and m = 500.

This simple two-goods model can be easily extended to more goods (e.g., it can be extended to the set of all goods you can get in the supermarket). We use the two-goods case because it helps us to illustrate the main concepts and tools in a simple way, often invoking a graphical representations of the model.

---------------------------------
## Utility Function

Consumer preferences represent a ranking over consumption bundles or combinations of different goods. For instance, if the consumer strictly prefers bundle $(x_{1}, x_{2}) = (1 pizza, 2 burritos)$ over bundle $(x_{1}',x_{2}') = (2 pizzas, 1 burritos)$ , then the first combination of goods is ranked before than the second one in the preferences of this consumer.

We will always assume consumer preferences are transitive. Transitivity means that if a consumer prefers bundle a over bundle b, and he also prefers bundle <em>b</em> over bundle <em>c</em>, then it must be the case that the consumer prefers bundle <em>a</em> over bundle <em>c</em>

Transitivity is a very important property as it allows us to talk of the most preferred bundle! When it holds, we can often conveniently represent the preferences of a given consumer by what we call a utility function.

* To do so, we also require the preferences to be continuous. Roughly speaking, “preferences are continuous” if whenever an alternative A is preferred to an alternative B, any option A’ that is sufficiently similar to option A is also preferred to option B.

Formally, a utility function is a function that assigns a number to each bundle in such a way that these numbers respect the underlying preference ranking of the consumer (i.e., the utility function assigns higher numbers to more preferred combinations of goods).

----------------------------
**Example**: : Let good 1 be pizza and good 2 be burrito. In addition, assume the preferences of a given consumer over slices of pizza and burritos are captured by the next utility function:

<p align="center"> $u(x_{1},x_{2})=(x_{1})^{1/4}(x_{2})^{3/4}$ </p>

Suppose that a first bundle contains 16 slices of pizza and 1 burrito, so that <em>u</em>(16,1)=2. If a second bundle has 3 slices of pizzas and 3 burritos, then <em>u</em>(3,3)=3. It follows that this consumer prefers the second over the first combination of goods (i.e., he likes to have 3 slices of pizzas and 3 burritos more than having 16 slices of pizza and 1 burrito.)

Though there are many types of utility functions, in this course we will mainly focus on three of them: Cobb-Douglas, Perfect Complements (i.e., Leontieff), and Perfect Substitutes (i.e., linear). We will sometimes also use the CES utility function. (CES stands for constant elasticity of substitution. We will clarify this term later.) The specific mathematical (functional) form of each of these utilities is given in the next table.
-  To do so, we also require the preferences to be continuous. Roughly speaking, “preferences are continuous” if whenever an alternative A is preferred to an alternative B, any option A’ that is sufficiently similar to option A is also preferred to option B.

| Utility Function| Mathematical Form|
| ------------- |:-------------:| 
| Perfect Substitutes  | $u(x_{1},x_{2})=ax_{1},ax_{2}$  | 
| Perfect Complements  | ![](https://i.imgur.com/Ela3pj3.png) |
| Cobb-Douglas | $u(x_{1},x_{2})={(x_{1}^{a}), (x_{2}}^{b})$  | 
| CES |$u(x_{1},x_{2})=(a{x_{1}}^{r}+b{x_{2}}^{r})^{1/r}$ | 

In the first three cases we typically assume <em>$a,b\geq 0$ </em>. In the last one, we let <em>$r\leq 1$ </em>. As we shall see, these parameters play very different roles in each specification.

As we explained earlier, the important aspect of a utility function is that it captures the underlying preferences of a specific consumer. According to the ordinal utility theory, it is meaningful to ask whether a bundle is better than a second one, but not how much better it is. In other words, the actual numbers that a utility function assigns to the specific bundles are not important as far as they preserve (respect) the ranking of the individual over the combination of goods. It follows that when the preferences of an individual can be represented by a utility function, then an infinite number of them can capture the same preferences!

---------
**Example**: Suppose that our previous consumer strictly prefers 16 slices of pizza and 1 burrito to 3 slices of pizzas and 3 burritos. In addition, he is indifferent between having 3 slices of pizzas and 3 burritos and 2 slices of pizzas and 4 burritos. Moreover, he strictly prefers 2 slices of pizzas and 4 burritos to having 2 slices of pizzas and 2 burritos. In summary, this consumer ranks the different combinations of goods as follows:

<p align="center"> $1^{st} (16,1) ;  2^{nd} (3,3) and (2,4) ; 3^{rd} (2,2)$ </p>

It follows that a utility function represents his preferences if and only if it assigns numbers to each combination of goods in the following way:

<p align="center"> <em> $u(16,1) > u(3,3) = (2,4) > u (2,2)$ </em> </p>

Let us now consider the three possible utility functions shown in the next table. Which of these three utilities represent the preferences we just described? 

| **Bundle** | **Utility 1** | **Utility 2** | **Utility 3** |
|--------|-----------|-----------|-----------|
|(16,1)|8|12|4|
|(3,3)|7|9|2|
|(2,4)|6|9|2|
|(2,2)|3|2|-1|

It is clear that Utility 1 does not do so. The reason is that it assigns to bundle 3,3 a higher number than to bundle 2,4, contradicting the fact that the consumer is indifferent between these two combinations of goods. On the other hand, even when Utility 2 and Utility 3 assign different numbers to the bundles, both of them are consistent with the preference ranking of the consumer. Therefore, Utility 2 and Utility 3 both represent this consumer’s preferences.

There are two concepts associated to the utility function, which play a key role in explaining consumer behavior, namely, indifference curves and marginal rate of substitution. We next elaborate on each of them.

An indifference curve is the set of all bundles that a consumer regards as equally desirable. In other words, it is the set of all combination of goods that give the consumer the same utility level. 

We often assume that preferences satisfy a property that says more is always better. Under this monotonicity assumption, the indifference curves cannot be “thick” and they must be downward slopping. 

Weakly preferred sets also provide a convenient characterization of preferences. In terms of the utility function, a weakly preferred set is the sets of all bundles ($x_{1},x_{2}$) such that u($x_{1},x_{2}$) is at least as large as a specific value <em>k</em>.

---------
**Example**: Let $u(x_{1},x_{2})=(x_{1})^{1/4}(x_{2})^{3/4}$. Then, 

<p align="center">$u(x_{1},x_{2})=(x_{1})^{1/4}(x_{2})^{3/4} = k$ </p>

implicitly describes the set of all combinations of goods 1 and 2 that give the consumer a level <em>k</em> of utility. For each k, this set ---which can be also written as $x_{2}=k^{2}/x_{1}$ --- denotes a specific indifferent curve. We can get all the indifference curves by changing k

In addition, for each k, the associated weakly preferred set is $x_{2}\geq k^{4/3}/(x_{1})^{1/3}$ . 

--------
The next figure shows the typical shape of the indifference curves for the case of Perfect Substitutes (top, left), Perfect Complements (top, right), Cobb-Douglas (bottom, left) and CES (bottom, right). You can find an interactive version of this figure here:
 <https://www.desmos.com/calculator/sh2hmdkie9>

![](https://i.imgur.com/CWlfW0G.png) 

As we will explain, the marginal rate of substitution (MRS) is intimately related with the concept of marginal utility (MU). Thus, we start describing the latter. 

The marginal utility of good 1 captures the extra utility the consumer gets if he slightly increases the consumption of good 1, while keeping fixed the consumption of the second one. We can similarly define the marginal utility of good 2. When the utility function $u(x_{1},x_{2})$ is differentiable, then the marginal utilities of goods 1 and 2 (denoted by <em>MU1</em> and <em>MU2</em> ) are simply the partial derivatives of $u(x_{1},x_{2})$ with respect to goods 1 and 2, respectively. That is, 

<p align="center"> $MU_{1}=\partial u(x_{1},x_{2})/\partial x_{1}$  and   $MU_{2}=\partial u(x_{1},x_{2})/\partial x_{2}$  </p>

---------
**Example**: Let \[u(x_{1},x_{2})=(x_{1})^{1/4}(x_{2})^{3/4}\]. Then, 

<p align="center"> $MU_{1}(x_{1},x_{2})=\frac{1}{4}(x_{1})^{-3/4}(x_{2})^{3/4}$   and    $MU_{2}(x_{1},x_{2})=\frac{3}{4}(x_{1})^{1/4}(x_{2})^{-1/4}$ </p>

We showed before that two different utility functions might induce the same ranking over consumption bundles. These two utility functions represent the same preferences. As the next example illustrates, an issue with the concept of marginal utility is that it is sensitive to the way in which we represent consumer preferences. 

-----------
**Example**: Let us work with the same utility as in the previous example, $u(x_{1},x_{2})=(x_{1})^{1/4}(x_{2})^{3/4}$, except that now we multiply it by 4. That is, $u(x_{1},x_{2})=4(x_{1})^{1/4}(x_{2})^{3/4}$. Then, 

<p align="center"> $MU_{1}(x_{1},x_{2})=(x_{1})^{-3/4}(x_{2})^{3/4}$   and    $MU_{2}(x_{1},x_{2})=3(x_{1})^{1/4}(x_{2})^{-1/4}$ </p>

Since this utility is just $u(x_{1},x_{2})=(x_{1})^{1/4}(x_{2})^{3/4}$  multiplied by 4, it represents the same ranking over consumption bundles as the utility of the previous example. Nevertheless, the two MUs are four times as large with $u(x_{1},x_{2})=4(x_{1})^{1/4}(x_{2})^{3/4}$  as compared to $u(x_{1},x_{2})=(x_{1})^{1/4}(x_{2})^{3/4}$ .

Notice that the assumption of monotonicity implies that MUs are always positive.

As we mentioned above, a second concept related to the utility function that is very important in economics is the marginal rate of substitution (MRS). The MRS is a measure of the relative value of good 1 in terms of good 2. In particular, it measures (approximately) of how much the consumer is willing to give up of good 2 in order to obtain an additional unit of good1.

Mathematically, the MRS is given by the slope of an indifference curve (IC) at a given bundle. Therefore, it can be obtained as follows: Assuming that preferences are monotonic and can be represented by the utility function $u(x_{1},x_{2})$, we can think of an IC as a function $x_{2}(x_{1})$. Along this IC, we have:

<p align="center"> $u(x_{1},x_{2}(x_{1})) = k $</p>

If we differentiate this function with respect to x1 (using the [Chain Rule](https://en.wikipedia.org/wiki/Differentiation_rules)), we get

<p align="center"> $\frac{\partial u}{\partial x_{1}}(x_{1},x_{2})+[\frac{\partial u}{\partial x_{2}}(x_{1},x_{2})]\frac{\partial x_{2}}{x{1}}(x_{1}) =0$  </p>

Since the MRS is the slope of the IC, we get that

<p align="center"> $MRS = \frac{\partial x_{2}}{\partial x_{1}}(x_{1}) = - MU_{1}/MU_{2}$  </p>

A very important property of the MRS is that (unlike the marginal utilities MUs) it is not affected by the way in which we measure preferences! 

----------
**Example**: Let the utility function be either $u(x_{1},x_{2})=(x_{1})^{1/4}(x_{2})^{3/4}$ or $u(x_{1},x_{2})=4(x_{1})^{1/4}(x_{2})^{3/4}$. In both cases, we have that

<p align="center"> $MRS(x_{1},x_{2})=-MU_{1}(x_{1},x_{2})/MU_{2}(x_{1},x_{2})=-x_{2}/3x_{1} $ </p>

In other words, the MRS remains the same for both utilities.

When the utility function increases in the consumption of each good, then the MRS is negative. This means that if the consumer sacrifices a bit of one good, then he must be compensated with a bit more of the other good to be as well as before.

In addition, we often assume that the MRS is decreasing (in absolute value). This captures the idea that the consumer prefers some sort of diversification across goods ---he prefers to have some of each good rather than having a lot of one good and nothing of the other. A decreasing MRS means that the more the consumer sacrifices of one good, the more he needs to be compensated with the other one to be as well as before. When this happens, we we say that consumer preferences are convex.

-----------
##### Budget Set
The budget set is the set of all bundles or combinations of goods that are affordable by the consumer. That is, the set of all ($x_{1},x_{2}$) that satisfy:

<p align="center"> $p_{1}x_{1}+p_{2}x_{2}\leq m$  </p>

where $p_{1}, p_{2}$ and <em>m</em> represent the price of good 1, the price of good 2, and the income level, respectively. 

The set of bundles that exhaust the income of the consumer is called the budget line:

<p align="center"> $p_{1}x_{1}+p_{2}x_{2} = m$  </p>

In both cases, we also assume $x_{1}\geq 10$ and $x_{2}\geq 0$ 

In a graph where $x_{1}$ is represented along the horizontal axis, and $x_{2}$ along the vertical axis, the slope of the budget line is given by $-p_{1}/p_{2}.$ Notice that the maximum amount of good 1 that the consumer can purchase is given by the intercept of the budget line with the horizontal axis, and its magnitude is $m/p_{1}$. Similarly, for good 2, this magnitude is $m/p_{2}$.

The next picture shows the budget set and line for the case of $p_{1}$ = 2, $p_{2}$ = 2 and m = 40. 

![](https://i.imgur.com/n0FbVMF.png)

---------
**Example**: Suppose the government imposes a per unit tax of <em>t</em> dollars on good 2. Then, the new budget line is

<p align="center"> $p_{1}x_{1}+(p_{2}+t)x_{2}=m.$ </p>

Notice that the tax reduces the number of units the consumer can afford of <em>both</em> goods 1 and 2. This happens even while the tax only affects the price of good 2. 

-----------
##### Optimal Choice
We have discussed both consumer’s preferences (captured by his utility function) and consumption restrictions (captured by his budget set). To characterize consumer behavior ---that is, to explain the bundle that he will acquire in the market for each combination of prices and income level--- we assume the consumer behaves in an optimal way. In words, we postulate that the consumer selects the most desirable bundle out of the ones that he can actually afford. 

Mathematically, this implies that the consumer solves the following problem:

<p align="center"> $max_{x_{1}, x_{2}}\left \{ u(x_{1},x_{2}): p_{1}x_{1}+p_{1}x_{2} = m \right \}$  </p>

We start with a graphical explanation for the solution of the consumer problem. 

The next figure shows the case of  a consumer with income level <em>m=40</em>, who faces prices $p_{1}=2$ and  $p_{2}=2$. Thus, his budget set is  $2x_{1}+2x_{2}\leq 40$ , which is illustrated in the shaded triangular area. Suppose that the utility function of this consumer has a Cobb-Douglas specification $u(x_{1},x_{2})=(x_{1})^{3/4}(x_{2})^{1/4}$. The left panel of the figure also shows four ICs corresponding to the following different utility levels: <em> $k_{1}=6, k_{2}=9, k_{3}=11.39$ and $k_{4}=15$ </em>. As it is readily verified, the further away from the origin, the higher the utility level of the consumer. Recall that we assume the consumer acquires the most desirable combination of goods among the ones that he can afford. This consumer can definitely get a utility level of 6 ---since there are some affordable bundles (under the shaded area) that provide this level of satisfaction. The same applies to a utility of level of 9. Notice that this is not true for a utility of level 15 ---since there is no affordable bundle that provides the consumer this level of satisfaction. It turns out that, in this example, the highest achievable utility level is $k_{3}=5^{1/4}15^{3/4}\simeq 11.39$ , with the optimal consumption bundle being (5,15). 

- notice that we have chosen to draw only four out of an infinite number of possible indifference curves

It follows from our simple example that the best affordable combination of goods is the one that belongs to the highest IC that just touches ---usually in only one point--- the budget constraint.

![](https://i.imgur.com/rkrlrwu.png)

--------

We now present the mathematical solution of the consumer problem for three of the most commonly used utility functions. 

- **Optimal Choice with Cobb-Douglas Preferences**

The consumer problem with Cobb-Douglas preferences is given by 

<p align="center"> $max_{x_{1},x_{2}} \left \{ x_{1}^{a} x_{2}^{b} : p_{1}x_{1}+p_{2}x_{2} = m\right \}$  </p> 

To find the optimal bundle when preferences are Cobb-Douglas (C-D), we use the Lagrangian method. The associated Lagrangian function is

<p align="center"> $L(x_{1},x_{2},\lambda )={x_{1}^{a}x_{2}^{b}-\lambda (p_{1}x_{1}+p_{2}x_{2}-m)}$ </p>

Recall that we can get the solution of our initial problem by finding the maximizers of the Lagrangian function. The first order conditions of our problem (FOCs) are:

- $\frac{\partial L}{\partial x_{1}}=ax_{1}^{a-1}x_{2}^{b}-\lambda p_{1} = 0$ 	 (FOC1)

- $\frac{\partial L}{\partial x_{2}}=bx_{1}^{a}x_{2}^{b-1}-\lambda p_{2} = 0$ 	 (FOC2)

- $\frac{\partial L}{\partial \lambda }=-p_{1}x_{1}-p_{2}x_{2}+m = 0$ 	 (FOC3)

To find the optimal consumption bundle, we need to find the $x_{1}, x_{2}$, and $\lambda$  that solve this system of three equations and three unknowns (as a function of $p_{1}, p_{2}$ and <em>m</em>). 

We can solve this system of equations by first obtaining an expression for $\lambda$ from both FOC1 and FOC2, and then make these two terms equal to each other. Doing so we get:

<p align="center"> $\frac{ax_{1}^{a-1}x_{2}^{b}}{p_{1}} =\frac{bx_{2}^{b-1}x_{1}^{a}}{p_{2}}$  </p>

This expression simplifies to:

<p align="center"> $\frac{ax_{2}}{bx_{1}}= \frac{p_{1}}{p_{2}}$ </p>

Combining this last result with FOC3, we finally get:

<p align="center"> $x_{1}* = \frac{a}{a+b}\frac{m}{p_{1}}$  | $x_{2}* = \frac{b}{a+b}\frac{m}{p_{2}}$ </p>

To find $\lambda$ *  , we can simply plug $x_{1}$ * and $x_{2}$ *  into either FOC1 or FOC2. 

It follows from our previous results, that the optimal solution satisfies

<p align="center"> $MRS = \frac{p_{1}}{p_{2}}$ and $m = p_{1}x_{1}+p_{2}x_{2}$  </p>

The first condition states that the relative value of the goods from the perspective of the consumer has to equal their relative value from the perspective of the market. The second condition simply states that the optimal bundle must be on the budget line.

--------
**Example**: Let us assume that $u(x_{1},x_{2})=x_{1}^{a} x_{2}^{b}$  with a = ¼, b = ¾, m = 40, $p_{1} = 2$ and $p_{2} = 2$. Thus, the Lagrangian of the problem is:

<p align="center"> $L (x_{1},x_{2},\lambda ) = x_{1}^{1/4}x_{2}^{3/4}-\lambda (2x_{1}+2x_{2}-40)$  </p>

Taking the partial derivatives wrt $x_{1} x_{2}$ and $\lambda$, we get:

- $\frac{\partial L}{\partial x_{1}}=(1/4)x_{1}^{1/4-1}x_{2}^{3/4}-\lambda 2 = 0$ 	 (FOC1)

- $\frac{\partial L}{\partial x_{2}}=(3/4)x_{2}^{3/4-1}x_{1}^{1/4}-\lambda 2 = 0$ 	 (FOC2)

- $\frac{\partial L}{\partial \lambda }= 40 - 2x_{1}-2x_{2} = 0$ 	 (FOC3)

To find the optimal $x_{1} and x_{2}$, we first get $\lambda$ from FOC1 and FOC2 and then make these two terms equal to each other:

<p align="center"> $\frac{1/4x_{1}^{-3/4}x_{2}^{3/4}}{2} = \frac{3/4x_{2}^{-1/4}x_{1}^{1/4}}{2}$  </p>

This expression simplifies to:

<p align="center"> $\frac{x_{2}}{3x_{1}}=\frac{p_{1}}{p_{2}}$  </p>

Combining the latter with FOC3, we solve for $x_{1} and x_{2}$ and obtain

<p align="center"> $x_{1}* =( \frac{1}{4}) (\frac{40}{2}) = 5$ and $x_{2}* =( \frac{3}{4}) (\frac{40}{2}) = 15$  </p>

-------
- **Optimal Choice with Perfect Substitutes Preferences**

When the goods are perfect substitutes from the perspective of the consumer, then we cannot use the Lagrangian method to obtain the optimal bundle. The reason is that, in this case, the solution is usually non-interior. We next explain how to approach the consumer problem in this case. 

The consumer problem with perfect substitute preferences is given by:

<p align="center"> $max_{x_{1},x_{2}}\left \{ ax_{1}+bx_{2}: p_{1}x_{1} + p_{2}x_{2} = m \right \}$  </p>

In this case, the MRS between the goods is given by:

<p align="center"> $MRS = \frac{\partial u/ \partial x_{1}}{\partial u/ \partial x_{2}} = \frac{a}{b}$  </p>

Recall that the MRS defines the relative value of good 1 in terms of good 2 from the perspective of the consumer. With perfect substitute preferences, the MRS is just a constant.

On the other hand, the ratio $\frac{p_{1}}{p_{2}}$  describes the relative market valuation of good 1 in terms of good 2. 

In the case of perfect substitutes, the optimal choice relies on the comparison between the MRS and the ratio of prices.  

- Case 1: If $MRS = \frac{a}{b} > \frac{p_{1}}{p_{2}}$ then $x_{1}$ * = $\frac{m}{p_{1}}$ and $x_{2}$ * = 0
- Case 2: If $MRS = \frac{a}{b} < \frac{p_{1}}{p_{2}}$ then $x_{1}$ * = 0 and $x_{2}$ * = $\frac{m}{p_{2}}$ 
- Case 3: If $MRS = \frac{a}{b} = \frac{p_{1}}{p_{2}}$ then $x_{1}$ * $\in [0, \frac{m}{p_{1}}]$ and $x_{2}$ * $\in [0, \frac{m}{p_{2}}]$ such that $x_{1}$ * + $x_{2}$ * = m

To understand the first case, notice that $\frac{a}{b} > \frac{p_{1}}{p_{2}}$   means that the extra value of the first good as compared to the second one from the perspective of the consumer is higher than the extra cost of getting the first good as compared to getting the second one. Thus, it is convenient for this person to spend all his income in the first good. Case 2 has a similar explanation. Case 3 corresponds to a situation in which the MRS equals the relative prices; in this last case, the consumer is indifferent between spending all, some, or no money in good 1 as far as he spends the rest of his income in the other good 

----------
**Example**: Suppose <em> a</em>=1.5 and <em>b</em>=1. Then, <em>MRS</em> =1.5. This means that this consumer is willing to give up to 1.5 units of good 2 for an additional unit of good 1. On the other hand, let us assume that $p_{1}$=2, $p_{2}$=2 and m=40. Thus, the relative market value of good 1 in terms of good 2 is just 1, i.e., $\frac{p_{1}}{p_{2}} = 1$. Given that 

- $MRS = 1.5 > 1 = \frac{p_{1}}{p_{2}}$ 

regardless the bundle selected, we are in Case 1 above. Thus, it is optimal for the consumer to spend all his income in good 1. That is,

<p align="center"> $x_{1}$ * = $\frac{m}{p_{1}}=\frac{40}{2} = 20$ and  $x_{2}$ * = 0 </p>  

The next figure illustrates this solution:

![](https://i.imgur.com/ZLe3apa.png)

-------

- **Optimal Choice with Perfect Complement Preferences**

Remember that the utility function for perfect complement preferences is given by 

<p align="center"> $u(x_{1}x_{2})=min\left \{ \frac{x_{1}}{a},\frac{x_{2}}{b} \right \}$  </p>

As with the case of perfect substitutes, when the goods are perfect complements from the perspective of the consumer, then we cannot use the Lagrangian method to obtain the optimal bundle. In this case, the reason is that the corresponding utility function is not differentiable. 

The consumer problem with perfect complements utility function is given by 

<p align="center"> $max_{x_{1},x_{2}}\left \{ min\left \{ \frac{x_{1}}{a}, \frac{x_{2}}{b} \right \} : p_{1}x_{1} + p_{2}x_{2} = m \right \}$  </p>

Notice that, in this case, as long as $p_{1}, p_{2}$, <em>a</em> and <em>b</em> are all strictly positive, the optimal bundle will always satisfy:

<p align="center"> $\frac{x_{1}}{a} =\frac{x_{2}}{b}$ </p>

The reason is quite simple.  Suppose that instead we have $\frac{x_{2}}{b} > \frac{x_{1}}{a}$  . Then, 

<p align="center"> $x_{2}/b>x_{1}/a=u(x_{1},x_{2})=min\left \{ \frac{x_{1}}{a}, \frac{x_{2}}{b} \right \}$  </p>

It follows that this consumer could be strictly better off by spending a bit less in the second good and using that money to get a bit more of the first good! This process repeats till  $x_{1}/a = x_{2}/b$ . (A similar idea applies when $x_{1}/a > x_{2}/b$ .)

In addition, we know that the optimal bundle must satisfy the budget constraint. That is, 

<p align="center"> $p_{1}x_{1} + p_{2}x_{2} = m$ </p>

Combining our two observations, we get:

<p align="center"> $p_{1}x_{1} + p_{2}\frac{bx_1}{a} = m$ </p>

So that $x_{1}$ * = $\frac{ma}{(ap_{1}+bp_{2})}$ . In a similar way, we get that $x_{2}$ * = $\frac{mb}{(ap_{1}+bp_{2})}$

Example: Let us assume $u(x_{1}, x_{2}) = min( \frac{x_{1}}{a}, \frac{x_{2}}{b} )$    with a=1, b=1, $p_{1}$=2, $p_{2}$=2, and m=40. In this case, we know that the optimal consumption of good 1 and 2 must satisfy:

<p align="center"> $x_{1} = x_{2}$ </p>

We also know that: 

<p align="center"> $2x_{1} + 2x_{2} = 40$ </p>

Using these two equations, we get that:

<p align="center"> $x_{1}$ * = $\frac{ma}{(ap_{1}+bp_{2})} = \frac{40}{2+2} = 10$ and $x_{2} * = \frac{mb}{(ap_{1}+bp_{2})} = \frac{40}{2+2} = 10$  </p>


The next figure illustrates this solution. 

![](https://i.imgur.com/DMPgsL5.png)

<p align="center"> Solution for the perfect complements. </p>

**Note 1: Income Tax vs Sale Tax.** We study choices and welfare implications under two tax specifications that provide the same income level for the government.

------------

## 2.2 Demand Function

##### Individual Demand Function

We explained earlier that the consumer problem consists of selecting the most preferred bundle among the ones that the consumer can afford. Mathematically, the problem was described as follows

<p align="center"> $max_{x_{1},x_{2}}\left \{ u(x_{1},x_{2}) : p_{1}x_{1} + p_{2}x_{2} = m \right \}$  </p>

The solution of this problem consists of a pair x1* and x2*.  We typically write this choice as:

<p align="center"> $x_{1}$ * = $x_{1}(p_{1},p_{2},m)$ and $x_{2}$ * = $x_{2}(p_{1},p_{2},m)$ </p>

to highlight the fact that the optimal amounts of good 1 and good 2 depend on the prices of the goods and the income level of the consumer. In other words, optimal choices are function of $p_{1}, p_{2}$ and m . We refer to them as the individual demand functions.

The demand function of good <em>i</em> (with <em>i</em>=1,2) receives different names according to the way in which it responds to changes in each of its arguments. (In economics, we often call this exercise comparative statics.) We next describe the main relationships.

Changes with respect to income:

- If $x_{i}(p_{1}•p_{2},m)$ increases with m, we say the good is normal.
- If $x_{i}(p_{1}•p_{2},m)$ decreases with m, we say the good is inferior.

Changes with respect to own price:

- If $x_{i}(p_{1}•p_{2},m)$ decreases with $p_{i}$, we say the good is ordinary.
- If $x_{i}(p_{1}•p_{2},m)$ increases with $p_{i}$, we say the good is Giffen.

Changes with respect to the price of the other good:

- If $x_{i}(p_{1}•p_{2},m)$ increases with $p_{j}$, we say the goods are substitute.
- If $x_{i}(p_{1}•p_{2},m)$ decreases with $p_{j}$,  we say the goods are complement.

Out of all these possibilities, Giffen goods are probably the less frequently observed. Jensen and Miller (AER, 2008) provided the first real-world evidence of Giffen behavior, i.e., a good with upward-sloping demand. The authors found this behavior when studying rice subsidies for poor households in Hunan and Gansu, China. 

----------
**Example**: Let the utility be $u(x_{1},x_{2})=(x_{1})^{1/4}(x_{2})^{3/4}$ . We showed before that, in this case,

<p align="center"> $x_{1}$ * = $x_{1}(p_{1}p_{2},m)=\frac{1}{4}\frac{m}{p_{1}}$ and $x_{2}$ * = $x_{2}(p_{1}p_{2},m)=\frac{3}{4}\frac{m}{p_{2}}$  </p>

Thus, according to our previous definitions, both goods are normal and ordinary. Since the quantity demanded of one of them does not depend on the price of the other one, we also say that they are independent. 

The next figures provide a graphical representation of the our comparative statics results.


Own price changes:

![](https://i.imgur.com/l7beOvN.png)

Income Changes:

![](https://i.imgur.com/nyKQ4zB.png)

Our previous classifications of the goods seem to suggest that about any change in consumption is possible as prices and income levels change. Thus, one immediately wonders: 

**Does our theory generate any testable implication?**

We will show that the answer is yes. This is important as, otherwise, our theory of consumer choice could never be proven false! 

The testable implication of our theory receives the name of **Weak Axiom of Revealed Preferences (WARP)**. This basic result is quite simple. If a bundle is acquired, then it must be the case that the consumer prefers this combination of goods to all other affordable ones. In other words, via choices, the consumer is providing us some information regarding his preferences. By testing WARP we make sure that consumer’s choices don’t provide contradicting information. The next example illustrates this possibility.

-----------
**Example**: Imagine that we observe the next choices

| Price of good 1 | Price of good 2 | Income | Choice of good 1 | Choice of good 2 |
|-----------------|-----------------|--------|-----------------|-----------------|
| $p_{1} = 2$ | $p_{2} = 1$ | m = 10 | $x_{1}$ * = 4 | $x_{2}$ * = 2 |
| p1 = 1 | p2 = 1 | m = 8 | $x_{1}$ * = 1 | $x_{2}$ * = 7 |

We are interested in the next question: 

<p align="center"> Could these choices have been made by a utility maximizer? </p>

The answer is no. The reason is as follows. 

When the prices and income level were given by $p_{1}=2, p_{2}=1$, and m=10, the consumer selected 4 units of good 1 and 2 units of good 2. Notice that, since 2 x 1 + 1 x 7 < 10, he could have selected to consume 1 unit of good 1 and 7 units of good 2. This is telling us that this consumer strictly prefers bundle (4, 2) to bundle (1, 7). 

Alternatively, when the prices and income level of the consumer were given by $p_{1}=1, p_{2}=1$, and m=8, he selected 1 unit of good 1 and 7 units of good 2. Notice that, since 1 x 4 + 1 x 2 < 8, he could have selected to consume 4 units of good 1 and 2 units of good 2. Thus, this consumer strictly prefers bundle (1, 7) to bundle (4, 2) which contradicts our previous claim. 

The WARP simply formalizes our observations in the last example.

**Weak Axiom of Revealed Preference (WARP)**: Suppose that $(x_{1},x_{2})$ is selected when the prices are $(p_{1},p_{2})$, and $(x_{1}',x_{2}')$ is chosen when the prices are $(p{1}',p{2}')$. 

If $p_{1}x_{1}' + p_{2}x_{2}' \leq  p_{1}x_{1} + p_{2}x_{2}$, then it must be that $p_{1}'x_{1} + p_{2}'x_{2} > p_{1}'x_{1}'+p_{2}'x_{2}'.$


In words, WARP is telling us that if $(x_{1},x_{2})$ was selected when $(x_{1}',x_{2}')$ was affordable, then it cannot be the case that $(x_{1},x_{2})$ was affordable when the consumer selected $(x_{1}',x_{2}').$

The next figure displays the three key cases to check whether WARP is satisfied or not. Using our previous definition, it is easy to see that the only violation happens in panel (a).

![](https://i.imgur.com/c4NmddD.png)

**Redo Note 1** without assuming any particular functional form for the utility function.

Echenique et. al (2010) uses US data for purchasing decisions in the supermarket to check whether people behave according to our model. While they find some violations, they prove that they are not that severe. They also relate the strength of the violations with people characteristics. Among other results, they find that older people behave closer to the model.

##### Market Demand Function

We just learned that the individual demand function of good <em>i</em>, with <em>i</em>=1,2, represents the choice of good i in the bundle that maximizes the utility of the consumer for each pair of prices and income level. If we refer to an arbitrary consumer as consumer j, then

<p align="center"> $x_{1}^{j} (p_{1}, p_{2}, m^{j})$ and $x_{2}^{j} (p_{1}, p_{2}, m^{j})$ </p>

indicate consumer <em>j</em>'s demands for goods 1 and 2, respectively.

The market demands for these goods are given by

- $Q_{1}^{d}(p_{1}, p_{2}, m^{1}, m_{2}, ...., m^{J}) = \sum_{j=1}^{J}x_{1}^{j}(p_{1}, p_{2}, m^{j})$ 
- $Q_{2}^{d}(p_{1}, p_{2}, m^{1}, m_{2}, ...., m^{J}) = \sum_{j=1}^{J}x_{2}^{j}(p_{1}, p_{2}, m^{j})$

where J indicates the number of consumers in the economy. That is, for each fixed vector of prices and income levels, the market demand of each good is simply the sum of the individual market demands of all consumers in the economy for that specific good.
	
Notice that the market demand of each good depends on the prices of the two goods as well as the income distribution.

We just derived the quantity demanded for each good as a function of the market prices. It is sometimes convenient to express market prices as functions of quantities. We refer to P(x) as the inverse demand function of a certain good.

---------
**Example**: Suppose that the economy consists of two individuals with demand functions given by

<p align="center"> $x^{1}(p, m^{1}) = 20 - p$ and $x^{2} (p,m^{2}) = 30-3p$ </p>

The aggregate demand function is thereby given by

- $Q^{d}(p, m^{1}, m^{2}) = x^{1}(p,m^{1})+x^{2}(p,m^{1}) = 50 - 4p$ if $p\leq 10$ 
- $Q^{d}(p, m^{1}, m^{2}) = x^{1}(p,m^{1})+x^{2}(p,m^{1}) = 20 - p$ if $p > 10$ 

Note that we add quantities for the same price! The next picture illustrates this result.

![](https://i.imgur.com/bWONg2U.png)

When demands are linear, then there is usually a kink in the market demand. 

In this example, the inverse demand function is given by

- $p(Q, m^{1}, m^{2}) = 12.5 - \frac{1}{4}Q$ if $Q \geq 10$ 
- $p(Q, m^{1}, m^{2}) = 20- Q$ if $Q < 10$ 

Let $Q^{d}(p)$ be the demand function. The elasticity of demand is given by

- $\varepsilon = (\partial Q^{d}(p)/\partial p)(p/Q^{d}(p))$ 

Since, generally, $\partial Q^{d} (p)/\partial p \leq 0$ , we often express $\varepsilon $ in absolute values. The elasticity of demand measures how sensitive is the demand function to price changes. 

When $|\varepsilon |$>1, we say the demand is elastic. This means that the quantity demanded is very responsive to price changes. It usually happens when the good we are considering has close substitutes. For example, A4 paper from Office World and A4 paper from Boise.

When $|\varepsilon |$<1, we say the demand is inelastic. This means that the quantity demanded does not respond very much to changes in prices. It usually happens when the good does not have close substitutes. For example, some medications, like Triluma.

---------
Example:  Let $Q^{d}(p) = a-bp$ . The elasticity of demand is 

- $|\varepsilon| = bp/(a-bp)$

The next picture shows the way in which $|\varepsilon |$ varies with x.

![](https://i.imgur.com/iBdnng8.png)

Notice that the good is elastic or inelastic according to the amount that the consumer gets.

----------
## 2.3 Intertemporal Choice

The model we studied in the last section assumes that either there is a single period of time or that the consumer spends all his income every period, without saving or borrowing. This section shows that a similar approach can be used to model consumer behavior across different periods of time. 

This extension will allow us to understand the relationship between saving (or borrowing) and the interest rate. It is also important as it shows that, with small modifications, our initial model can accommodate many situations of interest.

In our simple intertemporal choice model, consumers decide how to allocate their income between consumption today and tomorrow. The main components of the model are as follows.

1. Two goods: current consumption $(c_{1})$ and future consumption $(c_{2})$

2. Prices of current and future consumption is 1 (i.e., we assume no inflation)

3. Income levels: current income $(m_{1})$ and future income $(m_{1})$

4. Interest rate: <em>r</em>

As you can see, we make a few simplifying assumptions. First, we assume that there is no inflation. Second, we assume there is a  bank that allows the consumer to either save his current income $(m_{1})$ or to borrow up from his future income $(m_{2})$. Moreover, we suppose that the interest rate r is the same for saving and borrowing money. (These restrictions can be easily relaxed with small, though probably tedious, modifications of our main results.)

In the intertemporal model, consumers’ preferences are captured by a utility function over current and future consumption

<p align="center"> $u(c_{1},c_{2})$ </p>

Because we are allowing the consumer to either save or borrow money, the consumer faces a single budget constraint for the “whole life” ---or two periods. Expressed in future value, the lifetime income of this person is 1+rm1+m2. To understand better this equation, notice that 1+r represents the extra income the consumer can experience in the second period per dollar that he saves in the first period of time. If in period of time 1 the consumer puts 1 dollar of his income in the bank, then in the second period the bank gives the consumer the dollar he invested plus the interest rate r. Similarly, her lifetime consumption is 1+rc1+c2. His budget constraint simply reflects that these two amounts must be the same. That is, 

<p align="center"> $(1+r)c_{1} + c_{2} = (1+r)m_{1} + m_{2}$ </p>

Notice that, in a graph where $c_{1}$ is in the horizontal axis and $c_{2}$ is in the vertical axis, the slope of the budget line is -(1+r). 

We can also write the budget line in present value terms

<p align="center"> $c_{1}+c_{2}/(1+r) = m_{1}+m_{2}/(1+r)$ </p>

In this representation, 1/(1+r) indicates how much more the consumer can buy in period of time 1 if he sacrifices 1 unit of consumption in period 2. To achieve this goal, the consumer borrows 1/(1+r) dollars from the bank in the first period of time with the promise of paying [1/(1+r)] x (1+r) =1 to the bank in period of time 2.

The (intertemporal) problem of the consumer is as follows:

<p align="center"> $max_{c{1},c{2}}\left \{ u(c_{1},c_{2}) : (1+r) c_{1}+c_{2}=(1+r)m_{1}+m_{2}\right \}$  </p>

Notice that, from a mathematical perspective, this problem is very similar to our initial consumer choice model! Moreover, it is indeed identical if we let

- $x_{1}=c_{1}$ and $x_{2}=c_{2}$ 
- $p_{1}=1+r$ and $p_{2}=1$ 
- $m = (1+r)m_{1}+m_{2}$

------
Example: As we just described, we assume no inflation and indicate by $m_{1}, m_{2}$, and <em>r</em> the corresponding income levels and interest rate. In this example, we will also suppose the consumer has the following utility specification for consumption in periods 1 and 2 

<p align="center"> $u(c_{1},c_{2}) = (c_{1})^{1/4}(c_{2})^{3/4}$ </p>

The problem of the consumer is 

<p align="center"> $max_{c{1},c{2}}\left \{ (c_{1})^{1/4}(c_{2})^{3/4} : (1+r) c_{1} + c_{2} = (1+r) m_{1} + m_{2}\right \}$ </p>

Given the connection we just established between this model and the initial consumer problem, we can use our previous results to state that 

<p align="center"> $c_{1}$ * = $\frac{1}{4} [(1+r)m_{1}+m_{2}][1/(1+r)]$ and $c_{2}$ *= $\frac{3}{4} [(1+r)m_{1}+m_{2}]$ </p>


**Note 2: Revealed Preferences and the Interest Rate.((  In this note we study the effect of increasing the interest rate for a "saver" and a "borrower" consumer.

We just studied the optimal allocation of consumption levels between today and tomorrow. Let us next assume that our intertemporal consumer faces the possibility of investing some amount of money today with the promise of receiving some specific return tomorrow. Should the consumer make such an investment? We now develop a criterion which the consumer should use in deciding whether or not to do so.

To be more clear, let us consider an investment which has a negative cash flow of - dollar A today ---the investment--- and a positive cashflow of dollar B in 1 year ---the return. The question we want to address is 

<p align="center"> Should the person invest in this project? </p>

The answer to this question is indeed very simple.

The person should invest if (and only if) 

<p align="center"> $-A + B/(1+r) \geq 0$ </p>

(Positive Net Present Value in Finance.) The reason is that if $-A + B/(1+r) \geq 0$ ,  then the budget line of the consumer shifts up.

Notice that the previous rule does not depend on the preferences of the consumer!

**Note 3: Investment on Schooling.** We study investment on schooling with and without borrowing constraints

**Note 4: Choosing a Retirement Plan.** We study the selection of two different retirement plans.

--------
##2.4 Choice Under Risk

In this section, we study individual behavior with respect to choices involving risk. We face risks in almost every single decision we make since, in most cases, it is hard to anticipate the exact consequences of each alternative. 

Let’s start with an example. As an economics professor at UC Berkeley, Gary Becker had to give an exam at 8:00 AM. He arrived at the university at 7:55 AM, so he did not have enough time to go to the parking lot and be on time for the test. He faced two options:

1. go to the parking lot, so to avoid the parking ticket, but be late for the exam with certainty; or

2. park in front of the Economics Department, so to be be on time for the exam, but face the risk of getting a parking ticket.

As you can see, each option has pros and cons. The question is how to compare them! To do so we need a model that would allow us to compare options in which we are not sure about the final outcomes. We next present the most commonly used method.

In economics, we typically use the framework of Expected Utility (EU). In this approach, every possible outcome has a utility level associated to it. In this example, <em>u(late, no penalty)</em> would denote the utility that Gary Becker gets from option (1). Under option (2), there are two possibilities, he either gets caught or he doesn't. Let <em>u(on time, penalty)</em>  and <em>u(on time, no penalty)</em> indicate the utility levels under these two possible outcomes of option (2). Also, suppose that he estimates that if he parks in front of the Economics Department, then the probability of getting caught is <em>p</em>. According to the expected utility approach, Gary Becker values the risky alternative as a weighted combination of the utilities he could experience in that course of action. Following that logic he should decide to be late if and only if:

<p align="center"> <em> u(late, no penalty)>p u(on time, penalty)+(1-p)u(on time,no penalty)</em> </p>

Otherwise, he should choose to “break the law”, and park in front of the Econ Department.

- This example is given by Gary Becker as the starting point of his economic analysis of criminal decisions.

More generally, the expected utility model assumes that the utility a person gets from each risky choice depends on (i) the utility of the different outcomes the individual might face; and (ii) the probability of each of these possible outcomes. In particular, the valuation of a risky choice in the expected utility model is as follows:

<p align="center"> $EU=p_{1}u(c_{1})+p_{2}u(c_{2})$ </p>

where $c_{1}$ and $c_{2}$ are two possible outcomes usually measured in monetary terms (for example $1 and $10), and $p_{1}$ and $p_{2}$ are their corresponding probabilities (for example ⅓ and ⅔, respectively). Under this specification, the overall utility is just the weighted average of the utility that the person gets under each possible circumstance, where the weights are the probabilities that the person assigns to the different events. 

As we mentioned earlier, though the expected utility approach is probably the most widely utilized method, it is not the only model that has been used to study choice under risk. The field of behavioral economics studies other conceptual approaches, among which the prospect theory by Tversky and Kahneman (1979) is probably the most prominent one.  

In what follows, we will only consider situations where the different outcomes of the risky choice are simply different amounts of money. In that sense, we will restrict attention to situations that are similar to the ones that consumers face when they buy lottery tickets or go to the casino.

--------
**Example**: (Lottery) An individual has 100 dollars in his wallet and is evaluating whether to buy a lottery ticket. The ticket costs 20 dollars and he knows that with 50% chance he can get 40 dollars, and with 50% chance he gets 0 dollars. In our notation, $c_{1}=100-20+40=120$, $c_{2}=100-20=80$,  $p_{1}=0.5$ and $p_{2}=0.5$. Let us also  assume, the utility function of this person is given by:

<p align="center"> $u(c_{i})=c_{i}^{1/2}$ </p>

where c_{i} is the money that the consumer gets in each outcome <em>i</em>. Under this specification, if the person buys the ticket, his expected utility (denoted by <em>EU</em>) is given by:

| Expected Utility of the Lottery Ticket (EU) | = $\frac{1}{2}u(100-20+40) + \frac{1}{2}u(100-20)$|
|---------------------------------------------|---------------------------------| 
| | = $\frac{1}{2}(120)^{1/2}+ \frac{1}{2}(80)^{1/2}$ |
| | $\approx$  9.95 |


On the other hand, if the individual does not get the ticket, his utility is $u(100)=(100)^{1/2}=10$, with certainty. Since 10 > 9.95, this consumer will rather prefer not to buy the ticket for the lottery. ■ 

It is important to notice that the expected value of buying the ticket in the previous example is

<p align="center"> $\frac{1}{2} (100-20+40) + \frac{1}{2}(100-20) = 100$ </p>
 
That is, it the same as not buying the ticket. Yet, this consumer preferred to avoid taking the risk involved in the lottery. The next example shows the key role that the shape of the utility function has in determining whether a person takes or not a specific risk.

----------
**Example**: (Investment) An individual is contemplating the possibility of either investing his money in a risky project that pays 36 dollars if he wins and 0 dollars otherwise or in a safe project that always pays 18 dollars. He estimates that the probability of winning in the risky project is ½. That is, $c_{1}=36, c_{2}=0,  p_{1}=0.5$ and $p_{2}=0.5.$

We are interested in a simple question: Should a rational person invest in the risky project? 

We next show that the answer of this question depends on the preferences of the individual, which are captured by the shape of the utility function u.

If the person gets involved in the risky project, then his expected utility is 

<p align="center"> EU[<em>risky project</em>]=$\frac{1}{2}u(36)+\frac{1}{2}u(0)$ </p>

Since the safe option always pays $18, he should invest in the risky project whenever

<p align="center"> EU[<em>risky project</em>]=$\frac{1}{2}u(36)+\frac{1}{2}u(0)\geq u(18)$</p>

Otherwise, this person would be better off putting his money in the safe option. 

Without any other information regarding the shape of <em>u</em>, we cannot answer our initial question. We next contemplate three different possibilities. 

Let us assume first that $u(c_{i})=(c_{i})^{1/2}$. In this case, the expected utility of the risky project is

<p align="center"> EU[<em>risky project</em>]=$\frac{1}{2}u(36)+\frac{1}{2}u(0) = \frac{1}{2}(36)^{1/2}+\frac{1}{2}(0)^{1/2} = 3$ </p>

In addition, the utility he gets from the safe project is $(18)^{1/2} \approx 4.24$. Since 

<p align="center"> EU[<em>risky project</em>]= $\frac{1}{2}(36)^{1/2}+\frac{1}{2}(0)^{1/2} = 3 < 4.24$ </p>

we conclude that this person should select the safe option. The following picture illustrates this first situation. 


![](https://i.imgur.com/mZLrDFP.png)

Note: You can access an interactive version of this graph [here](https://www.desmos.com/calculator/zhqanv1cib).

Let us now suppose that $u(c_{i}=c){i}$. In this case, we have that

<p align="center"> EU[<em>risky project</em>]= $\frac{1}{2}u(36)+\frac{1}{2}u(0) = \frac{1}{2}(36)+ \frac{1}{2}(0)$</p>

In addition, the utility from the safe project is (18)=18. Thus, this person is just indifferent between the safe and the risky option.

![](https://i.imgur.com/bCh80fs.png)

Finally, let us set $u(c_{i}=(c_{i})^{2}$. In this case, we have that 

<p align="center"> EU[<em>risky project</em>]= $ \frac{1}{2}u(36)+ \frac{1}{2}u(0) = \frac{1}{2}(36)^{2}+ \frac{1}{2}(0)^{2}=648$ </p>

In addition, the utility from the safe project is u(18)=(18)^{2}=324. Thus, this person clearly prefers the risky investment.

![](https://i.imgur.com/80EmAAe.png)

We often classify individuals according to their attitudes toward risk. As we shall see, the standard classification is intimately related to our last example. It involves the comparison between the expected utility of the risky project

<p align="center"> $p_{1}u(c_{1})+p_{2}u(c_{2})$ </p>

and the utility of the person evaluated at the expected value of the risky project

<p align="center"> $u(p_{1}c_{1}+p_{2}c_{2})$ </p>

The expected value of the risky project ---$p_{1}c_{1}+p_{2}c_{2}$---- can be thought as the amount of money that a person who invests in the risky project many times would get on average. 

The next table classifies people according to attitudes toward risk and establishes a connection between these attitudes and the curvature of the utility function.

| Attitude/Behavior | Shape of utility function | Property of utility function |
|-------------------|---------------------------|------------------------------|
| Risk Averse| Concave Utility|$p_{1}u(c_{1})+p_{2}u(c_{2})\leq u(p_{1}c_{1}+p_{2}c_{2})$ |
| Risk Neutral|Linear Utility|$p_{1}u(c_{1})+p_{2}u(c_{2})= u(p_{1}c_{1}+p_{2}c_{2})$|
|Risk Loving| Convex Utility| $p_{1}u(c_{1})+p_{2}u(c_{2})> u(p_{1}c_{1}+p_{2}c_{2})$ |

---------
**Example**: Suppose that, as in the last example, an individual is contemplating the possibility of either investing his money in a risky project that pays 36 dollars if he wins and 0 dollars otherwise or in a safe project that always pays 18 dollars. The probability of winning in the risky project is again 1/2. 

In the previous example we studied the investment decision of three individuals that differed regarding the shape of the utility function: ![](https://i.imgur.com/i5F9O3X.png) We found that the first individual would not invest, the second one was indifferent, and the third one would always invest in the risky project. Given our last table, we could have made the prediction without any calculation!

The reason is that the expected value of the risky project was given by

<p align="center"> $\frac{1}{2}36+\frac{1}{2}0=18$</p>

This is the same as the money the individual makes with the safe investment. In addition, $u(c_{i})=(c_{i})^{1/2}$ is a concave function, $u(c_{i})=c_{i}$ is a linear function, and $u(c_{i})=(c_{i})^{2}$ is a convex function.



<!--

// This piece of code below creates the reveal presentation and pushes to GitHub and then deploys to GitHub pages. Modify the commit message and paste it into terminal.

cd docs && \
pandoc  \
-t revealjs -V revealjs-url=reveal.js \
--css=reveal.js/css/theme/simple.css \
-H reveal.js/js/revealMathJax.js \
-s S5_Choice_Ch5.md -o S5_Choice_Ch5.html && \
cd .. && \
git add docs/S5_Choice_Ch5.html && \
git commit -am " add content to S5_Choice_Ch5.md " && \
git push origin master && \
mkdocs gh-deploy 

-->






