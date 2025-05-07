---
title: NEA
date: 2025-05-07 06:16
tags: 
---

----

### Definition 
##### Nichtdeterministischer Endlicher Automat $M$
$M\coloneqq (Q,\Sigma, \delta, q_{0}, F)$\
$\mathcal{P}(X)\coloneqq \{Y\mid Y\subseteq X\}$

> - $Q$ eine endliche nich-leere Menge, genannt **Zusatsmenge**
> - $\Sigma$ ein (endliches) [Alphabet](alphabet)
> - $\delta$ eine Funktion $\delta:Q\times (\Sigma \cup \{\varepsilon\}) \to \mathcal{P}(Q)$, genannt **Uebergangsfunktion**
> - $q_{0}$ ein Element aus $Q$, genannt **Startzustand**
> - $F$ eine Teilmenge von $Q$, genannt Menge der **akzeptierten Zustaende**

##### $\varepsilon$-Uebergaenge
Zustandsuebergang, **ohne** ein Zeichen der Eingabe zu lesen

Sei $E(p)$ die Menge aller Zustaende, die wir von $p$ aus erreichen koennen, ohne
ein Zeichen zu lesen
$$
  E(p)\coloneqq \{q\mid q \text{ ist von } p \text{ durch eine Sequenz von }\ge 0 \ \varepsilon\text{-
Uebergaengen erreichbar}\}  
$$
Fuer Mengen $P\subseteq Q$ definieren wir
$$
  E(P)\coloneqq \bigcup_{p \in  P}E(p) 
$$

---

### Iterierte Uebergangsfunktion 









----

----
**Backlinks:**
- [Endliche Automaten](/endliche_automaten)
