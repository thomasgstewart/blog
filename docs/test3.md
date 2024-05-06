<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script> 

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
