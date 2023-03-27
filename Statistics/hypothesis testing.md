[[p-value]]

two hypothesis, test, decision

$H_{0}$: No relationship between $X$ and $Y$ --> $\hat{\beta}_{1}=0$

$H_{a}$: Some relationship between $X$ and $Y$ --> $\hat{\beta}_{1}\neq0$

Test:
Determine how far $\hat{\beta}_{1}$ is from 0 compared to $SE(\hat{\beta}_{1})$ $(|\hat{\beta}_{1}-0|\gt SE(\hat{\beta}_{1}))$

compute the t-statistic given by: $t=\frac{\hat{\beta}_{1}-0}{SE(\hat{\beta}_{1})}$ which measures the number of std dev that $\hat{\beta}_{1}$ is away from 0.

 Note that for $n \gtrapprox 30$ the t-distr converges to a gaussian distr.
 
 Process for making a decision:
 1. sample to compute $\hat{\beta}_{1}$ and $SE(\hat{\beta}_{1})$
 2. compute $t=\frac{\hat{\beta}_{1}-0}{SE(\hat{\beta}_{1})}$
 3. compute $P(X\geq t)=p$ where $X$ has a t-distr (see [[p-value]])

Interpret $P(X\geq t)=p$:
This is the probability of sampling in the critical region (which would lead to accept the alternative hypothesis) given the null hypothesis to be true. We want the p-value to be small which would indicates that it is unlikely to observe a relationship between $X$ and $Y$ due to chance if in true there is no assocation between the predictor and the response.