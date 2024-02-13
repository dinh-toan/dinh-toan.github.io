---
layout: post
title: Semigroup in \(L^p\), ultra-contractivity, and \(L^p\) convergence
date: 2024-02-11 00:20:00
categories: sample-posts
featured: true
---

Let $$\mathcal{L}$$ be an essentially self-adjoint operator with respect to the $$\sigma$$-finite measure $\mu$ of the measurable space $$(E, \mathcal{F})$$.  By spectral theory, $$\mathcal{L}$$ is uniquely associated with a self-adjoint strongly continuous contraction semigroup $$(P_t)_{t \in \mathbb{R}_+}$$ on $$L^2(E,\mu)$$.
asdasd

In this note, our goal is to explain the extension this semigroup beyond $$L^2$$ space, focusing on constructing corresponding semigroups $$(P_t)$$ for $$L^p$$ spaces using the interpolation theorem. Additionally, we will examine the exponential convergence rate of $$(P_t)$$ across all $$L^p$$ spaces (for $$p \in [1, \infty]$$ ) under ultracontractivity and the Poincaré inequality. These results are stated as follows:

**Proposition** Let $$(P_t)$$ be a self-adjoint contraction semigroup on $$L^2( \mu)$$ that satisfies the submarkov property i.e. $$0 \le P_tf \le 1$$ if $$0 \le f \le 1$$ and $$f \in L^2,t>0$$. Then, there is a unique family of contraction semigroup $$P_t^{(p)}: L^p \rightarrow L^p$$ such that $$P_t^{(p)} \equiv P_t$$ on $$L^1 \cap L^{\infty}$$. i.e.
+ $P_t^{(p)} f = P_tf$ for all $$f \in L^1 \cap L^{\infty}.$$
+ $\| P_tf \|_p \le \|f\|_p$  for all $$p \in [1, \infty[$$, $$f \in L^p$$.
+ $$\| P_tf \|_\infty \le \|f\|_\infty$$  for all $$f \in L^\infty\cap L^1$$.

*Remark*:  The main technical issue for $$p= \infty$$ is that $$L^1\cap L^\infty$$ is ,in general, not dense in $$L^\infty$$. Hence, the image of $$L_1\cap L^\infty$$  into $$L^\infty$$ by $$P_t$$ does not uniquely define the mapping $$P_t$$ on $$L^\infty$$.  Nonetheless, when $$\mu$$ is finite, $$L_1\cap L^\infty= L^\infty$$.

**Proposition**  Consider a strongly continuous contraction operator $$(P_t)$$ on $$L^2(\mu)$$ that satisfies the submarkov property, where $$\mu$$ is assumed to be a probability measure. If $$(P_t)$$ satisfies the Poincaré's inequality for some constant $$\lambda>0$$ ,i.e. 

$$\| P_tf \|_2 \le e^{-\lambda t} \| f\|_2  \qquad \text{ for all }t>0 \text{, } f \in L^2_0(\mu)$$

with $$L^2_0(\mu):=\{f \in L^2 \text{ such that } \int f \mathrm{d} \mu =0 \},$$

and the ultracontractivity at some instant $$t>0$$, i.e. there exists a constant $$c>0$$ and $$t>0$$ such that:

$$\| P_t f\|_{\infty} \le c \|f\|_1 \qquad \text{ for all }f.$$

Then there is a constant $$c_0 \ge 1$$ independent of $$p \in [1, \infty]$$ such that for all $$f$$ such that $$\int f \mathrm{d} \mu =0$$

$$\|P_t f \|_p \le c_0 e^{-\lambda t} \|f\|_p.$$

In short,

$$\text{Poincaré's ineq.} +\text{Ultraconctivity}+\text{Finite measure} \Rightarrow \text{Exponential decay}$$

# Some premilinaries
## Contraction semigroup


