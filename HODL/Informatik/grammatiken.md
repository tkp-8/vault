---
title: Grammatiken
date: 2025-05-09 07:23
tags: 
---

----

### Definition
Eine Grammatik $G$ ist ein 4er-Tupel $G = (V,\Sigma,P,S)$ wobai gilt:

> - $V$ ist eine endliche Menge von Variablen
> - $\Sigma$ ist eine endliche Menge von Terminalsymbolen. Dabei gilt $V\cap \Sigma\neq \empty$
> - $P\subseteq \{(L,R)\mid L,R\in (V\cup \Sigma)^{*}\}$ ist eine endliche Menge von Produktionsregeln 
> - $S\in V$ ist das Startsymbol

---

### Konzept
- Beschreibung des Aufbaus von [Sprachen](sprachen) durch Produktionsregeln
- Auch fuer komplexe Strukturen
- Gaengig fuer die Beschreibung von Programmiersprachen

---

### Klassifizierung
##### Chomsky-Hierarchie
 
- allgemein (Typ 0)
- kontextsensitiv (Typ 1)
- [kontextfrei](kontextfreie_grammatiken) (Typ 2)
- regulaer (Typ 3)




----

----
**Backlinks:**
- [📂Formale Sprachen Grammatiken Automaten](/📁Formale_Sprachen%linkAutomaten)
