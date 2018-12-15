
## Producer (Chapter 3) 

#### Intermediate Microeconomics (Econ 100A)

#### Natalia Lazzati

#### UCSC - Winter 2019


---------

## 3.1 Profit Maximization

We will study profit maximization in competitive markets. These are markets where each firm takes as given both the price of the good that it produces and the prices of the inputs that it uses to produce that good (e.g., labor and capital). 

There are two key concepts in our model of the competitive firm:

1. **Technology**: It tells us how much the firm can produce for each combination of inputs.
2. **Prices of the output** ---or the good that it produces--- and inputs.

Together, **1** and **2** determine both how much a competitive firm will optimally produce and how is going to produce it.

To simplify the exposition, we will focus on a simple version of the problem of the firm ---as we did with consumer problem. The components of our model are as follows:

1. We assume there are only two inputs: input 1 and input 2.
2. We represent the quantities of these inputs as $x_{1} and x_{2}$, respectively.
3. The production function is given by $f(x_{1},x_{2})$.
4. The prices of the inputs are represented by w₁ and w₂, respectively.
5. The price of the output is represented <em>p</em>.

-------
The purpose of the firm is to select the combination of inputs that maximizes its profits. More formally, we can express its problem as follows

<p align="center"> $max_{x_1,x_2}\left \{ pf(x_{1},{x_2})-w_{1}x_{1}-w_{2}x_{2} \right \}$  </p>

where $pf(x_{1},x_{2})$ is the revenue of the firm and $w_{1}x_{1} + w_{2}x_{2}$

To solve this problem, we will assume that the production function of the firm, $f(x_{1},x_{2})$,  is differentiable and the solution of the problem is interior. When these conditions are satisfied, then the First Order Conditions (FOCs) are as follows

- $p\partial f(x_{1},x_{2})/\partial x_{1}-w_{1} = 0$      **(FOC1)**

- $p\partial f(x_{1},x_{2})/\partial x_{2}-w_{2} = 0$      **(FOC2)**

The solution of this problem is given by the pair 

<p align="center"> $x_{1}(p,w_{1},w_{2})$   and   $x_{2}(p,w_{1},w_{2})$ </p>

that simultaneously solves the system of two equations FOC1 and FOC2. These functions are called the unconditional input demands of the firm.

The output function is given by

<p align="center"> $y(p,w_{1},w_{2})=f(x_{1}(p,w_{1},w_{2}),x_{2}(p,w_{1},w_{2})).$ </p>

This function tells us how much the firm will optimally produce for each combination of the prices of the output and inputs that it might face. 

The optimal solution of the firm problem has an interesting economic interpretation. To show it, let

<p align="center"> $MP_{i}(x_{1},x_{2})=\partial f(x_{1},x_{2})/\partial x_{i}$    for i=1,2 </p>

be defined as the marginal product of input i. It represents the extra amount of the good that the firm gets by increasing input i in one unit. Using this concept, the optimal solution satisfies

<p align="center"> $MP_{i}(x_{1},x_{2})/w_{1}=MP_{2}(x_{1},x_{2})/w_{2}$  </p>

That is, the marginal product per dollar spent in each input is the same for the two of them. To see why this should be the case, let us assume that the firm is producing at a point in which

<p align="center"> $MP_{i}(x_{1},x_{2})/w_{i}>MP_{2}(x_{1},x_{2})/w_{2}$  </p>

This means that the extra product per dollar spent in input 1 is strictly higher than the extra product the firm gets per dollar spent in input 2. In this case, the firm could be better off by increasing the amount of the first input and decreasing the amount of the second one. Doing so, the firm could produce the same in a cheaper way! This process stops when both terms are the same. (A similar idea applies to the case in which $MP_{i}(x_{1},x_{2})/w_{i}<MP_{2}(x_{1},x_{2})/w_{2})$

--------

**Example**:  Let us assume the production function of the firm has a Cobb-Douglas specification. In particular, let

<p align="center"> $f(x_{1},x_{2})=(x_{1})^{1/4}(x_{2})^{1/4}$ </p>

Under this specification, the problem of the firm is 

<p align="center"> $max_{x_{1}, x_{2}} \left \{ px_{1}^{1/4}x_{2}^{1/4} -w_{1}x_{1}-w_{2}x_{2}\right \}$  </p>

Differentiating with respect to the two input variables we get

- $p(1/4)x_{1}^{-3/4}x_{2}^{1/4}-w_{1} = 0$ 	 **(FOC1)**

- $p(1/4)x_{1}^{1/4}x_{2}^{-3/4}-w_{2} = 0$ 	 **(FOC2)**

Together, these two equations imply that 

<p align="center"> $ x_{2}w_{2} = x_{1}w_{1}$ </p> 

Substituting this expression in FOC1 we get 

<p align="center"> $x_{1}$* =$(1/16) p_{2} w_{1}^{-3/2}w_{2}^{1/2}$   and   $x_{2}$* =$(1/16) p_{2} w_{1}^{1/2}w_{2}^{-3/2}.$ </p>

Thus, the optimal level of production of the firm is

<p align="center"> y*= $f(x_{1}^{*},x_{2}^{*})=[(1/16)p^{2}w_{1}^{-3/2}w_{2}^{1/2}]^{1/4}[(1/16)p^{2}w_{1}^{1/2}w_{2}^{-3/2}]^{1/4}=p/[4(w_{1}w_{2})^{1/2}]$ </p>

-------
When we studied the problem of the consumer we illustrated the ideas by using three different specifications of the utility function:

- Cobb-Douglas
- Perfect Substitutes
- Perfect Complements

While the same three specifications can be used for the production function of the firm, some of them lead to unreasonable conclusions for the competitive environment. 

--------
**Example**: Let us assume the production function of the firm has a perfect substitutes specification. In particular, let

<p align="center"> $f(x_{1},x_{2})=x_{1} + x_{2}$ </p>

Under this specification, the problem of the firm is

<p align="center"> $max_{x_{1},x_{2}} \left \{ p(x_{1}+x_{2}) - w_{1}x_{1}-w_{2}x_{2} \right \}$ </p>

Suppose that, for some $x_{1}=x_{1}' and x_{2}=x_{2}'$, 

<p align="center"> $p(x_{1}'+x_{2}')-w_{1}x_{1}'-w_{2}x_{2}'=10>0$ </p>

That is, with this combination of inputs the firm is making 10$. Let us next consider using twice as much input as before. Then,

<p align="center"> $p(2x_{1}'+2x_{2}')-w_{1}(2x_{1}')-w_{2}(2x_{2}') = 2[p(x_{1}'+x_{2}')-w_{1}x_{1}'-w_{2}x_{2}'] = 20 > 0$ </p>

This means that, by doubling the amount of the inputs, then the firm gets twice as much profits as before. By repeating this process a few times, you will realize that the optimal level of inputs are just infinite! Since we do not observe firms behaving in this way, we conclude that this specification of the production function is probably not adequately when we model competitive markets.

One can show that a similar problem appears for the perfect complement specification of the production function and with the Cobb-Douglas one when $a + b > 1$

----------------------
## 3.2 Profit Maximization and Cost Minimization
The problem of the firm can be studied in a different way

<p align="center">$max_{y} \left \{py - C(y) \right \}$  </p>

where $C(y)$ is the minimum cost of producing y. The FOC of this problem is captured by

<p align="center"> $p=C'(y)$ </p>

where $C'(y) = \partial C(y)/\partial y$  is the marginal cost function. 

The solution of this problem, $y*=y(p)$, is the supply function (or supply curve) of the firm.

To show that this problem is indeed equivalent to the one of maximizing profits we just studied, we need to find an expression for the minimum cost function C(y).

The problem of cost minimization can be postulated as follows: The firm wants to produce a specific amount of good, y, in the cheapest possible way. Formally, its problem is given by

<p align="center"> $min_{x_{1}x_{2}}\left \{ {w_{1}x_{1}+w_{2}x_{2} : f(x_{1},x_{2})=y} \right \}$  </p>

Note that this problem is relevant for any profit maximizing firm ---even those with market power! 

The problem of cost minimization is a constrained optimization problem. Thus, assuming f is differentiable, and the solution is interior, we can use the Lagrangian method to solve it.

The Lagrangian for this minimization problem is given by

<p align="center"> $L(x_{1},x_{2},\lambda)= w_{1}x_{1} + w_{2}x_{2} -\lambda[f(x_{1},x_{2})-y]$ </p>

Differentiating this function with respect to the two input variables  and  λ we get

 - $w_{1}-\lambda\partial f(x_{1},x_{2})/ \partial x_{1} =0$  **(FOC1)**

 - $w_{2}-\lambda\partial f(x_{1},x_{2})/ \partial x_{2} =0$ 	 **(FOC2)**

 - $[f(x_{1},x_{2}-y] =0$		 **(FOC3)**

The solution of this problem is given by a pair

<p align="center"> $x_{1}'=x_{1}(w_{1},w_{2},y)$   and   $x_{2}'=x_{2}(w_{1},w_{2},y)$ </p>

These functions are called the conditional input demands of the firm. The reason for the name is that we are conditioning them to get a specific level of output.

The (minimum) cost function is obtained as follows

<p align="center"> $C(y)=w_{1}x_{1}(w_{1},w_{2},y) + w_{2}x_{2}(w_{1},w_{2},y)$ </p>

--------
**Example**: Let us assume the production function of the firm has the Cobb-Douglas specification

<p align="center"> $f(x_{1},x_{2})=(x_{1})^{1/4}(x_{2})^{1/4}$ </p>

Under this specification, the problem of the cost minimizing firm is 

<p align="center"> $min_{x_{1},x_{2}} \left \{ w_{1}x_{1}+w_{2}x_{2}:x_{1}^{1/4} x_{2}^{1/4}=y \right \}$  </p>

The Lagrangian function for this problem is given by

<p align="center"> $L(x_{1},x_{2},\lambda )=w_{1}x_{1}+w_{2}x_{2}- \lambda (x_{1}^{1/4}x_{2}^{1/4}-y)$ </p>

Differentiating this function with respect to the two input variables  and  $\lambda$ we get

 - $w_{1}-\lambda(1/4)x_{1}^{-3/4}x_{2}^{1/4} =0$	 (FOC1)

- $w_{2}-\lambda(1/4)x_{1}^{1/4}x_{2}^{-3/4} =0$  (FOC2)

- $- x_{1}^{1/4}x_{2}^{1/4} +y =0$ 	  	(FOC3)

Using FOC1 and FOC2, we get

<p align="center"> $x_{1}=x_{2}w_{2}/w_{1}$ </p>

Substituting the latter in FOC3, we get

<p align="center"> $-(x_{2}w_{2}/w_{1})x_{2}^{1/4} +y =0$ </p>

Thus, $x_{2}' =y_{2}(w_{1}/w_{2})^{1/2}$ . Proceeding in a similar way, we get $x_{1}' =y_{2}(w_{2}/w_{1})^{1/2}$ 

It follows that the cost function of the firm is given by

<p align="center"> $C(y)=w_{1} y^{2}(w_{2}/w_{1})^{1/2} + w_{2} y^{2} (w_{1}/w_{2})^{1/2} = 2y^{2}(w_{1}w_{2})^{1/2}$ </p>

Given this result, the problem of the profit maximizing firm can be expressed as follows

<p align="center"> $max_y\left \{ py-2y^{2}(w_{1}w_{2})^{1/2} \right \}$ </p> 

Differentiating the objective function with respect to y, we get 

<p align="center"> $p-4y(w_{1}w_{2})^{1/2} = 0$ </p>

Thus, the optimal level of production is 

<p align="center"> $y'=p/[4(w_{1}w_{2})^{1/2}]$  </p>

This is exactly the same expression we obtained in the previous section.


----------------------
## 3.3 Supply Function

We have seen that the supply function of the firm is a function that indicates the amount of the good that the firm produces ---to maximize profits--- for each pair of prices of the good and inputs. We are often interested in the relation between the level of production and the market price of the good. In these cases, we assume that the prices of the inputs remain the same and express the supply of the firm as a sole function of the price of the good

<p align="center"> y*=y(p) </p>

The supply function of the market combines the supply curve of each firm. It state the aggregate level of production that the firms would optimally choose for each possible price of the good under consideration. In the time horizon where the number of firms is fixed (typically called the “short run”), the market supply curve is the horizontal sum of each firm supply curve:

<p align="center"> $Q^{s}(p)=\sum_{h=1}^{h=H}y^h(p)$ </p>

where $y^{h}(p)=y^{h*} is the supply function of firm <em>j</em>, and H is the total number of firms currently in the market.

------
Example: In the previous example, the supply curve of a firm with Cobb Douglas technology $f(x_{1},x_{2})=x_{1}^{1/4}x_{2}^{1/4}$ was $y*=p/[4(w_{1}w_{2}^{1/2}]$. Let us assume that the prices of the production factors are both equal to one; that is, $w_{1}=w_{2}=1$. This implies that $y^{h}(p)=p/4$. If there are 100 identical firms in the market, then the supply curve of the market is

<p align="center"> $Q^{s}(p)=\sum_{h=1}^{h=100}y^h(p) = \sum_{h=1}^{h=100} \frac{p}{4} = 100\frac{p}{4} = 25p$ </p>

That is, the market supply is $Q^{s} = 25p$.

----------------------
## 3.4 Stay in the Market?

We can define the profit function of the firm as the amount of money that the firm makes for each combination of prices of the good and inputs, assuming that the firm selects the combination of inputs that maximizes its profits. That is, 

<p align="center"> $\pi (p,w_{1},w_{2})=max_{x_{1},x_{2}}\left \{ pf(x_{1},x_{2})-w_{1}x_{1}-w_{2}x_{2} \right \} = max_{y}\left \{ py-C(y) \right \}$  </p>

This function represents the maximum profits the firm can make in the market.

A competitive firm decides to stay in the market if and only if 

<p align="center"> $ \pi (p,w_{1},w_{2}) \geq  0$ </p>


This is the same as to say

<p align="center"> $p\geq C(y^{*})/y^{*}$ </p>

where C(y)/y represents the average cost function of the firm.

There are two important concepts in economics that the firm should consider while taking the stay/exit decision. These ideas are also important in many daily decisions we make. 

The first concept is the **opportunity cost**. It captures the loss of potential gain from other courses of action when one specific alternative is chosen. When the firm decides whether to stay in the market, it should consider the opportunity cost of all inputs! For instance, it should take into account the value of the working time of the owner of the firm.

The second concept is the **sunk cost**. It captures a cost that has already been incurred and cannot be recovered. When the firm decides whether to stay in the market, it should not consider the sunk costs! For instance, its decision should not be affected by the cost of evaluating the feasibility of an investment project.

In the long run, we might expect

<p align="center"> $p=C(y^{*})/y^{*}$ </p>

The reason is that, whenever p>C(y*)/y* , many firms find it attractive to enter the market. The entrance of new firms usually increases the overall level of production, pushing the price down. This process repeats till the initial condition ** p = C(y^*)/y* ** is reached.





<!--

// This piece of code below creates the reveal presentation and pushes to GitHub and then deploys to GitHub pages. Modify the commit message and paste it into terminal.

cd docs && \
pandoc  \
-t revealjs -V revealjs-url=reveal.js \
--css=reveal.js/css/theme/simple.css \
-H reveal.js/js/revealMathJax.js \
-s S13_Monopoly_Ch25.md -o S13_Monopoly_Ch25.html && \
cd .. && \
git add docs/* && \
git commit -am " add content to S13_Monopoly_Ch25.md " && \
git push origin master && \
mkdocs gh-deploy 

-->