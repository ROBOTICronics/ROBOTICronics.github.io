---
layout: post
title: not yet ready
date: 2017-09-12 00:00:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: Work-in-progress-1024x603.png # Add image post (optional)
tags: [Productivity, Software] # add tag
---
<script src="//yihui.org/js/math-code.js" defer></script>
<script defer   src="//mathjax.rstudio.com/latest/MathJax.js?config=TeX-MML-AM_CHTML"> </script>

![not yet ready]({{site.baseurl}}/assets/img/Work-in-progress-1024x603.png)
# La costante di Planck rilevata sperimentalmente
Il lettore potrà apprezzare quanto sia fondamentale la formula di Einstein scoperta nel 1905, che gli valse il premio Nobel nel 1921.

$$E = h \cdot \nu$$

La costante $$h$$, fondamentale per la teoria quantistica (a livello atomico), è la **costante di Planck**, che la propose nel 1900.

Le sue dimensioni sono Joule * secondi, se l'energia viene misurata in Joule e la frequ4nza in oscillazioni al secondo.

Il suo valore è $$h = 6,626068 10^{–34} J\cdot s$$.

Il lettore noti che la "fisica classica", quella delle leggi di Newton e di Maxwell, vale piuttosto bene fintanto che il prodotto dell'energia per il tempo dà un risultato sensibilmente maggiore di h.

**Motivazioni.**

Planck era interessato a spiegare lo spettro continuo emesso dai corpi solidi caldi, ovvero lo "spettro di corpo nero", chiamato così poiché si considera emesso da un oggetto caldo ideale (appunto, il "corpo nero").<br >
L'esperienza quotidiana (un prato è verde, i mattoni sono rossi) insegna che un oggetto solido riscaldato emette luce avente una frequenza dominante, che si sposta gradualmente verso la zona blu dello spettro al crescere della temperatura; esempi come un ferro rovente lavorato da un fabbro, il colore del quale ferro ulteriormente riscaldato sposta la luce emessa dal rosso cupo all'arancione, oppure la luce infrarossa emessa da una mano umana calda, o ancora una lampadina che normalmente brilla di luce bianco-gialla, spostandosi verso l'arancione se la batteria che la alimenta si sta scaricando, e, infine, l'arco voltaico che si produce tra du elettrodi di ccarbone attraversati da una forte corrente, si colora di luce blu-ultravioletta, la cui frequenza è nociva per l'occhio umano.

## Il metodo di misura
Si sfrutta l’emissione luminosa da parte dei dispositivi a semiconduttore noti come LED.

Attraverso la giunzione p-n del diodo LED verrà fatta scorrere una corrente diretta; gli elettroni, ricombinandosi con le lacune in prossimità della giunzione, produrranno fotoni di energia $$E\cdot f$$ prossima al valore dell'**energy gap** (l'intervallo dellle energie proibite situate tra la banda di valenza e quella di conduzione). L'energia di questi fotoni emessi è data dal dal lavoro fatto dal campo elettrico $$V_{LED}\cdot e$$ applicato alla giunzione polarizzata direttamente (quadrante I).

$$ E = V_{LED} \cdot e = h \cdot \nu$$

![Schema elettrico di principio]({{site.baseurl}}/assets/img/2021-12-08_170407.png)

## Scopo dell’esperimento
Calcolare la tensione di innesco del led, ovvero la differenza di potenziale che causa l’accensione del diodo LED, necessaria, quindi, a calcolare e a verificare la costante di Planck. 

## Materiale utilizzato
- Geogebra, per elaborare i grafici
- Arduino
- Basetta sperimentale
- Potenziometro
- Cavi e resistore
- 3 led (verde, giallo, rosso)


### Descrizione delle varie fasi dell’esperimento:
- Fase 1: Preparazione dell’H/w (inserire anche una foto del progetto reale)
Si utilizzao 3 led (verde, giallo, rosso), una breadboard, una resistore, vari cavi e un potenziometro e Arduino.
- La tensione di attivazione del diodo LED:
  - Metodo 1. All'interno di una camera oscurata si miusra la tensione ai capi dei terminali anodo e catodo con un voltmetro, rilevando questa tensione elettrica nel momento in cui il diodo LED emette luce.
  - Determinazione della caratteristica I-V del diodo LED, estrapolando la tensione al _ginocchio_ di detta curva.
- 

## Dati ottenuti dalle misurazioni##
---
Tipo LED | Lunghezza d’onda (nm)  | Frequenza $$10^_{14}$$ Hz | Tensione di Attivazione (V)|
Infrarosso |  930 | 3.22581 | 1.0!
---
