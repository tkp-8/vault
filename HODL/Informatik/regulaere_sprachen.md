---
title: Regulaere Sprachen
date: 2025-05-07 05:42
tags: 
---

----

### Definition
[Sprache](sprachen) zu der es einen sie definierenden [regulaerer_ausdruck](regulaerer_ausdruck) gibt

Jede der folgenden Bedingungen ist aequivalent zur Regularitaed einer Sprache 
$L$
 
- Es gibt einen [endlichen Automaten](endliche_automaten), der die Sprache akzeptiert 
- $L$ wird von einer regulaeren Grammatik erzeugt


### Satz
##### Jede endliche Sprache ist regulaer
**Beweis.** Sei $L\subseteq \Sigma ^{*}$ eine endliche Sprache. $l$: laengstes
Wort, $\Sigma=\{\texttt{a},\texttt{b}\}$ \
Wir muessen zeigen, dass es einen [DEA](dea) $M$ fuer $L$ existiert.\

- Grundstruktur des Zustandsdiagramms entspricht einem [binearen Baum](binaerer_baum)
    - Tiefe $l$ 
    - von einem inneren Knoten gibt es zweit Kanten: $\texttt{a}$ und $\texttt{b}$
    - Wurzel: Startzustand 
- fuer jeden Knoten existiert genau einen Pfad von der Wurzel
- Zustand $q_w$, wenn $w$ das [Wort](woerter), das man lesen muss, um ihn zu erreichen
- $F=\{q_w\mid w\in L\}$
- **Muellzustand** $q_-$ fuer $|w|>l$
- **Allgemein:** $k$-aerer Baum mit $k=|\Sigma|$





----

----
**Backlinks:**
- [Endliche Automaten](endliche_automaten)
