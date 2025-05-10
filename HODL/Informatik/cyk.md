---
title: CYK-Algorithmus
date: 2025-05-10 02:28
tags: 
---

----

### Zweck

- Wortproblem fuer [kontextfreie Sprachen](kontextfreie_sprachen) loesen
- Entscheidet ob [Wort](woerter) $w\in L(G)$
- Nur fuer [kontextfreie Grammatiken](kontextfreie_grammatiken) in [CNF](cnf)

---

### Eingabe
- Wort $w=w_{1},w_{2},\ldots ,w_n$
- Grammatik $G=(V,\Sigma,P,S)$

---

### Initialisierung
- Sei $w[j,j]$ das Teilwort von $w$, welches mit dem $i$-ten Zeichen beginnt und 
  mit dem $j$-ten Zeichen endet.
$$
  W_{i,j}\coloneqq \{X\in V\mid X\Rightarrow ^{*} w[i,j]\}  
$$



----

----
**Backlinks:**
- [Kontextfreie Sprachen](/kontextfreie_sprachen)
