$f(x|y)=\frac{f(x,y)}{f_{1}(x)}$, where $f(x,y)$ is the joint distribution of X, Y and $f_{1}(x)=\int_{-\infty}^{\infty}f(x,y)dy$ is the marginal pdf of X.

Note : $f_{1}(x)$ is the pdf of the r.v. X and $f_{2}(y)$ is the r.v. of Y.

If the random variables are independent : $f(y|x)=\frac{f(x,y)}{f_{1}(x)}=\frac{f_{1}(x)f_{2}(y)}{f_{1}(x)}=f_{2}(y)$

The above shows that $f(y|x)$ for dependent random variables X and Y that the conditional pdf is the joint pdf restricted in its sample space to outcomes with $X=x$ divided by the value of the pdf of X at X=x.

$f(x_{1},x_{2})=f(x_{2}|x_{1})f_{1}(x_{1})=f(x_{1}|x_{2})f_{2}(x_{2})$

Thus, $f(x_{2}|x_{1})=\frac{f_{2}(x_{2})f(x_{1}|x_{2})}{f_{1}(x_{1})}$

$f(y|x)$ is the pdf of y restricted in its sample space such that the outcomes in its sample space are restricted to $y$'s belonging to ordered pairs with 

---

"Mathematically, computing a conditional probability amounts to shrinking our sample space to a particular event."

For discrete pdf, $P(A|B)=\frac{P(A,B)}{P(B)}$ where $A,B\in S$, $S$ being the sample space. This is the probability of getting an outcome of $A$ in the $B$ considered as the new sample space.

