<head><script type="text/javascript" id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script></head>

# This if the first doc

This is a test of test 3

$$
\begin{aligned}
\text{trt} &= \begin{cases}
1 & \text{active intervention}\\
0 & \text{placebo}
\end{cases}\\
\ \\
E[y|\text{trt}] &= \beta_0 + \beta_1 \text{trt}\\
V[y|\text{trt}] &= \sigma^2\\
\ \\
\beta_0 &\sim N(0,\theta_{\beta_0})\\
\beta_1 &\sim N(0,\theta_{\beta_1})\\
\sigma &\sim \text{exponential}(\theta_{\sigma}).
\end{aligned}
$$

Each replicate consists of a pseudo-dataset which mimics the data to be
collected in the trial. Because type I error is of interest, the
pseudo-dataset is generated so that the outcome distributions are the
same for active and placebo groups. That is, the data are generated with
a treatment effect of zero, (*β*<sub>1</sub> = 0). Then, the dataset is
analyzed with the specific value of *θ*<sub>*β*<sub>1</sub></sub> and
the treatment effect is estimated and the decision-making quantity is
calculated. The type I error rate is the proportion of datasets which
resulted in a conclusive difference, contrary to the true underlying
equality of active and placebo groups.
