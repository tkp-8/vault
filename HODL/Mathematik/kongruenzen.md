---
title: Kongruenzen
date: 2025-05-17 12:22
tags: 
---

----

### Definition 
Seien $a$ und $b$ ganze Zahlen, und sei $m\in N$.
Wir sagen, dass $a$ **kongruent** zu $b$ **modulo** $m$ ist, wenn $m$ ein Teiler von 
$a-b$ ist. 

---

### Notation
**$a$ kongruent zu $b$ modulo $m$** \
$a\equiv b \mod{m}$

**Wenn nicht**\
$a\not\equiv b \mod{m}$

---

### Bemerkung
Seien $a,b\in \mathbb{Z}$, und sei $m\in \mathbb{N}, \ m>1$.
$$
  a\equiv b\mod{m}\Leftrightarrow \exists k\in Z: a=b+km
$$
**Beweis**\
$\Rightarrow$: Es gilt $m\mid (a-b)$, also gibt es ein $k\in \mathbb{Z}$ mit $a-b=km$.
Somit gilt $a=b+km$ fuer ein $k\in \mathbb{Z}$\
$\Leftarrow$: Es folgt $a-b=km$, also $m\mid (a-b)$. Somi gilt $a\equiv b \mod{m}$.

---

### Eigenschaften
**Proposition 1:** Seien $a,b\in Z$ und sei $m\in N, \ m>1$. 
$$
  a\equiv b \mod{m} \Leftrightarrow a \text{ und } b \text{ haben bei der Division durch } m
  \text{ mit Rest denselben Rest}
$$
**Beweis:** Sei $a\equiv b \mod{m}$. Wir teilen $a$ und $b$ durch $m$ mit Rest und erhalten
$$
  a=q_{1}m+r_{1} \text{ und } b=q_{2}m+r_{2} \text{ mit } 0\le r_{1},r_{2}<m.
$$
$\Rightarrow$: Es gilt $a-b=(q_{1}-q_{2})m +r_{1}-r_{2}$. Da $m$ ein Teiler von $a-b$ und $(q_{1}-q_{2})m$
ist, muss $m$ auch $r_{1}-r_{2}$ teilen. Da $0\le r_{1},r_{2}<m$ gilt, folgt $|r_{1}-r_{2}|<m$.
Daher ist $m\mid (r_{1}-r_{2})$ nur dann moeglich, wenn $r_{1}-r_{2}=0$ gilt. Es folgt $r_{1}=r_{2}.$\
$\Leftarrow$: Seien umgekehrt $a=q_{1}m+r$ und $b=q_{2}m+r$ mit $0\le r\le m$. Dann gilt 
$a-b=(q_{1}-q_{2})m$, also $m\mid (a-b)$, und es gilt $a\equiv b \mod{m}$.

**Korollar zu Proposition 1**:
$$
  a\equiv b \mod{m} \Leftrightarrow a\text{ mod }{m}=b\text{ mod }{m}
$$

----

----
**Backlinks:**
- [📂Elementare_Zahlentheorie](/📁Elementare_Zahlentheorie)
