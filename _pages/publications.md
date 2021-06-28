---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Submitted

* Sharrock, L., Kantas, N., Pavliotis, G., and Panos, P. (2021). “Parameter Estimation for the Stochastic McKean-Vlasov Equation.”  arXiv preprint: [2106.13751](https://arxiv.org/abs/2106.13751)

*In this paper, we revisit the problem of parameter estimation for a fully observed McKean-Vlasov stochastic differential equation (McKean-Vlasov SDE), and the associated weakly interacting particle system (IPS). We first establish consistency and asymptotic normality of the offline maximum likelihood estimator (MLE) of the IPS, in the limit as N → ∞. We then propose a recursive MLE, which evolves according to a continuous-time stochastic gradient descent algorithm on the asymptotic log-likelihood of the IPS. We prove that this estimator converges in L1 to the stationary points of the asymptotic log-likelihood of the McKean-Vlasov SDE in the joint limit as N → ∞ and t → ∞, under suitable assumptions which guarantee ergodicity and uniform-in-time propagation of chaos of the McKean-Vlasov SDE. Under the additional assumption of global strong concavity, we also demonstrate that our estimator converges in L2 to the unique maximiser of the asymptotic log-likelihood, and establish an L2 convergence rate. Our results are demonstrated via two numerical examples, namely, a linear mean field model and a stochastic opinion dynamics model.*


* Sharrock, L. and Kantas, N. (2020). "Two Timescale Stochastic Gradient Descent in Continuous Time with Applications to Joint Online Parameter Estimation and Optimal Sensor Placement." arXiv preprint: [2007.15998](https://arxiv.org/abs/2007.15998).  

*In this paper, we establish the almost sure convergence of two-timescale stochastic gradient descent algorithms in continuous time under general noise and stability conditions, extending well known results in discrete time. We analyse algorithms with additive noise and those with non-additive noise. In the non-additive case, our analysis is carried out under the assumption that the noise is a continuous-time Markov process, controlled by the algorithm states. The algorithms we consider can be applied to a broad class of bilevel optimisation problems. We study one such problem in detail, namely, the problem of joint online parameter estimation and optimal sensor placement for a partially observed diffusion process. We demonstrate how this can be formulated as a bilevel optimisation problem, and propose a solution in the form of a continuous-time, two-timescale, stochastic gradient descent algorithm. Furthermore, under suitable conditions on the latent signal, the filter, and the filter derivatives, we establish almost sure convergence of the online parameter estimates and optimal sensor placements to the stationary points of the asymptotic log-likelihood and asymptotic filter covariance, respectively. We also provide numerical examples, illustrating the application of the proposed methodology to a partially observed Beneš equation, and a partially observed stochastic advection-diffusion equation.*  


* Sharrock, L. and Kantas, N. (2020). "Joint Online Parameter Estimation and Optimal Sensor Placement for the Partially Observed Stochastic Advection-Diffusion Equation." arXiv preprint: [2009.08693](https://arxiv.org/abs/2009.08693).  

*In this paper, we consider the problem of jointly performing online parameter estimation and optimal sensor placement for a partially observed infinite dimensional linear diffusion process. We present a novel solution to this problem in the form of a continuous-time, two-timescale stochastic gradient descent algorithm, which recursively seeks to maximise the log-likelihood with respect to the unknown model parameters, and to minimise the expected mean squared error of the hidden state estimate with respect to the sensor locations. We also provide extensive numerical results illustrating the performance of the proposed approach in the case that the hidden signal is governed by the two-dimensional stochastic advection-diffusion equation.*    
