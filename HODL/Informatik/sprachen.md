---
title: Sprachen
date: 2025-05-06 05:01
tags: 
---

----

### Definition 
##### Sprache
Eine Menge von [Woertern](woerter)

##### Komplement
Komplement der Sprache $L$: \
Die Sprache $\Sigma ^{*}\setminus L$

### Notation
**Konkatenation** $\circ$\
Seien $L_{1},L_{2}$ Sprachen aus dem selben [Alphabet](alphabet)
$L_{1}\circ L_{2}\coloneqq \{uv\mid u\in L_{1} \ \text{und} \ v\in L_{2}\}$

$$
  L^{k}\coloneqq \{w_{1}\cdots w_k\mid \forall i\le k:w_i \in L\}   
$$

$$
  L^{1}\coloneqq L,\quad L^{0}\coloneqq \{\varepsilon\}, \quad L^{*}\coloneqq 
  \bigcup_{k =  0}^{\infty}L^{k}, \quad L^{+} \coloneqq \bigcup_{k=1}^{\infty}L^{k}       
$$
 
**Komplement**\
$\overline{L}$

**Spiegelung**\
$\overleftarrow{L}\coloneqq \{\overleftarrow{w}\mid w\in L\}$

### Beispiel
**Entscheidungsproblem:** "Ist die Zahl $x$ eine Primzahl?"
$$
  L_{prim} = \{\text{bin}(x)\in \{\texttt{0},\texttt{1}\}^{*}\mid x \ \text{ist Primzahl}   \}  
$$
Das Problem reduziert sich darauf, zu entscheiden, ob ein Wort($\text{bin}(x)$) aus einer 
gegebenen Sprache($L_{prim})$
ist $\to$ **Wortproblem**  


----

----
**Backlinks:**
- [📂Grundlagen_Theoretische_Informatik](/📁Grundlagen_Theoretische_Informatik)
