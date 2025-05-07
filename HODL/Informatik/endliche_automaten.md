---
title: Endliche Automaten
date: 2025-05-06 08:36
tags: 
---

----

### Definition 
##### Endlicher Automat
Modell zur Darstellung eines Zustandsueberganssystems mit begrenztem Speicher


##### Sprache des Automaten
$L(M)$: Menge aller Woerter, die der Automat $M$ akzeptiert

**Regulaere Sprachen:** [Sprachen](sprachen) von endlichen Automaten

---

### Unterscheidungen
[DEA](dea)
NEA

### Der Deterministische Endliche Automat (DEA)
- Loesen des **Wortproblems** von bestimmten formalen Sprachen
- Eingabe: [Wort](woerter), Ausgabe: Wahrheitswert, ob Eingabe Element der zugehoerigen Sprache
- DEA **akzeptiert**/**verwirft** das Eingabewort
- Lesen des Wortes erfolgt nur **zeichenweise**
- DEA kann waehrend der Verarbeitung endlich viele **Zustaende** annehmen
- **Zustandsuebergang** haengt vom aktuellen Zeichen der Eingabe ab
 
##### Definition
Ein DEA $M$ wird durch eine Tupel $(Q,\Sigma, \delta, q_{0}, F)$ dargestellt

- $Q$ eine endliche nich-leere Menge, genannt **Zusatsmenge**
- $\Sigma$ ein (endliches) [Alphabet](alphabet)
- $\delta$ eine Funktion $\delta:Q\times \Sigma \to Q$, genannt **Uebergangsfunktion**
- $q_{0}$ ein Element aus $Q$, genannt **Startzustand**
- $F$ eine Teilmenge von $Q$, genannt Menge der **akzeptierten Zustaende**




----

----
**Backlinks:**
- [📂Formale_Sprachen&Automaten](📁Formale_Sprachen&Automaten)
