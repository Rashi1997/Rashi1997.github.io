---
title: "[Re] Goal-conditioned Imitation Learning"
excerpt: " Reproduced the GoalGAIL results from Figure 3<a href='https://openreview.net/forum?id=HJlCUp5M6H'>Open Review</a><br/><img src='/images/results.png'>"
collection: portfolio
---

Examined the code and modified how often the trajectories were being modified by HER and expert relabeling and significantly
improved the poor results, but still did not achieve the same results for the baselines. GAIL appeared to have great difficulty
improving its initial results, while HER was able to achieve a greater value fairly early on. Initially expected GAIL to outperform
HER and for HER to slowly catch up, however this might have appeared farther on in training. Overall though, goalGAIL
did perform more strongly than either of the baselines.