---
layout: post
title: "A compact way to write general cases of damped harmonic system"
---

(Last Updated: 2023-04-27)

The typical derivation for the analytic solution of a mass-spring-damper system (and any other systems with the same mathematical form) always irked me somewhat whenever it reached the step of splitting into the under/over/critically-damped cases. Particularly the reasoning for [where the $t$ term came from in the critical case.](https://math.stackexchange.com/questions/2187946/where-does-the-t-come-from-in-the-solution-to-a-critically-damped-differential) 

The stackexchange post listed above pointed out how you can put the characteristic value $\lambda$ in the denominator of the odd exponentials, for which taking the limits resolves it into the three distinct cases. This makes sense because there isn't really an abrupt "first-order phase change" when you tune a system shifting from being underdamped to overdamped, it just smoothly approaches and deviates from the critical case.



<iframe src="https://www.desmos.com/calculator/bblul7k8fl?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>