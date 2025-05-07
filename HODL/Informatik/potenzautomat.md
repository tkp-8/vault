---
title: Potenzautomat
date: 2025-05-07 07:44
tags: 
---

----

### Definition 
Sei $N=(Q,\Sigma,\delta,q_{0},F)$ ein [NEA](nea), dann ist der Potenzautomat
zu $N$ ein [DEA](dea) $M=(Q_P,\Sigma_P,\delta_P,q_p,F_P)$ mit   
> - $Q_P\coloneqq \mathcal{P}(Q)$
> - $\delta_P$ gegeben durch $\delta_P(P,x)\coloneqq 
E(\bigcup\nolimits_{p \in  P}\delta(p,x))$
> - $q_P\coloneqq E(q_{0})$
> - $F_P = \{P\subseteq Q \mid \exists p \in P:p \in F\}$






----

----
**Backlinks:**
- [📂Formale Sprachen Potenzautomat Automaten](/📁Formale_Sprachen%linkAutomaten)
