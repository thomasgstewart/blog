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
