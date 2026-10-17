---
title: Eukarya
toc: false
pager: false
---

# Eukarya (c) Susanne Hövelmann

```js
// load shared diagram source from file
dot2svg( await FileAttachment("eukarya.dot").text() )
```

## Legende

Jeder Pfeil zeigt von der Ursache zur Wirkung. Die vier Kantenarten, jeweils mit einem Beispiel aus dem Diagramm oben:

**Grüner Pfeil**: Wirkung

${digraph`tragfaehige_beziehung [label="Tragfähige Beziehung"] gemeinsame_entwicklung [label="Differenz als Quelle gemeinsamer Entwicklung"] tragfaehige_beziehung -> gemeinsame_entwicklung`}

> Die Ursache trägt zur Wirkung bei und fördert sie. Eine tragfähige Beziehung macht es möglich, dass Differenz zur Quelle gemeinsamer Entwicklung wird.

**Roter Pfeil**: schädliche Wirkung

${digraph`tragfaehige_beziehung [label="Tragfähige Beziehung"] dominanz [label="Dominanz"] dominanz -> tragfaehige_beziehung [color=red]`}

> Die Ursache hat eine unerwünschte Wirkung. Dominanz untergräbt die Tragfähigkeit der Beziehung.

**Grüner Pfeil mit ⊖**: reduzierende Wirkung

${digraph`nicht_dominanz [label="Nicht-Dominanz"] dominanz [label="Dominanz"] nicht_dominanz -> dominanz [label="⊖"]`}

> Die Ursache reduziert die Wirkung. Nicht-Dominanz schwächt Dominanz ab und begrenzt sie. Sie verhindert sie nicht. Der Einfluss selbst ist erwünscht (grün), aber das Ziel des Pfeils wird kleiner.

**Grauer, gepunkteter Pfeil**: Inferenz

${digraph`Kooperationsabsicht -> Kooperation [color=grey style=dotted]`}

> Die Kante zeigt eine Folge, die sich bereits aus anderen Kanten im Diagramm ergibt. Sie behauptet keine eigene, unabhängige Wirkbeziehung, sondern macht nur sichtbar, was sich sonst erst über den ganzen Pfad erschließen ließe. Logisch ist sie überflüssig; gezeichnet wird sie nur der Lesbarkeit wegen.
>
> Zugleich lässt sich die Kante als Lebenslinie lesen: Kooperationsabsicht und Kooperation sind zwei Zeitstufen derselben Sache, hier im selben Schnitt gezeigt.

```js
import{ digraph, digraph2svg, dot2svg, visco } from "@kxfm/browser"
```
<div id="ktsConsole"></div>
