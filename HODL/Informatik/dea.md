---
title: DEA
date: 2025-05-07 01:13
tags: 
---

----

### Definition  
##### Deterministischer Endlicher Automat $M$
$M=(Q,\Sigma, \delta, q_{0}, F)$

- $Q$ eine endliche nich-leere Menge, genannt **Zusatsmenge**
- $\Sigma$ ein (endliches) [Alphabet](alphabet)
- $\delta$ eine Funktion $\delta:Q\times \Sigma \to Q$, genannt **Uebergangsfunktion**
- $q_{0}$ ein Element aus $Q$, genannt **Startzustand**
- $F$ eine Teilmenge von $Q$, genannt Menge der **akzeptierten Zustaende**

---

### Besonderheiten
- Loesen des **Wortproblems** von bestimmten formalen Sprachen
- **Eingabe:** [Wort](woerter), **Ausgabe:** Wahrheitswert, ob Eingabe Element der zugehoerigen Sprache
- DEA **akzeptiert**/**verwirft** das Eingabewort
- Lesen des Wortes erfolgt nur **zeichenweise**
- DEA kann waehrend der Verarbeitung endlich viele **Zustaende** annehmen
- **Zustandsuebergang** haengt vom aktuellen Zeichen der Eingabe ab
- Nur **ein Folgezustand** moeglich 
 
---

### Beispiel 
$M_{1}=(Q,\Sigma,\delta,q_{0},F)$ mit $Q=\{q_{0},q_{1}\}, \Sigma=\{\texttt{a},\texttt{b}\}, F=\{q_{0}\}$

|$q\in Q$|$x\in \Sigma$|$\delta(q,x)$|
|----- |--- |--- |
|$q_{0}$|$\texttt{a}$|$q_{1}$|
| $q_{0}$ |  $\texttt{b}$ | $q_{0}$  |
|  $q_{1}$ |$\texttt{a}$   |  $q_{0}$ |
| $q_{1}$  | $\texttt{b}$  |  $q_{1}$ |

![fff](img/dea_1.png)








----

----
**Backlinks:**
- [Endliche Automaten](/endliche_automaten)
