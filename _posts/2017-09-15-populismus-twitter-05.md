---
title: "Wie populistisch tweeten unsere Politiker? Teil 5"
subtitle: "Der 'Horden-Score'"
author: "Sebastian Sauer"
tags: [Populismus, textmining]
layout: post
categories: blog
---




Dieser fünfte Teil der Analyse von Tweets deutscher Parteien fragt, wessen Text sich wie stark aus Wörtern der Stammesgesellschaft oder 'geschlossener' Gesellschaft speist. Je näher ein Text (die Tweets eines Politikers) zu dieser 'Stammessprache', desto höher der Populismus, so die Hypothese. Dabei ist zu bedenken, dass Populismus - wie in allen Teilen der Studie - definiert ist, als Manifestation einer Denk- oder Seinsweise der 'geschlossenen Gesellschaft', wie es Popper definiert hat. Ein einfacher (vielleicht populistischer) Begriff, um die Nähe der Sprachproben zum Populismus zu fasen, ist der 'Horden-Score' (oder Hordenscore). Dieser ist im Folgenden dargestellt, zuerst in dieser Abbildung:



<img src="https://sebastiansauer.github.io/psy_pol/images/2017-09-15/p_horde_04_boxplot.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" width="80%" style="display: block; margin: auto;" />


Man sieht einfach, dass der 'Horden-Score' (ein krasses Wort) für fraktionslose Politiker am größten ist. Allerdings steht nur eine Person dahinter, so dass beim Vergleich von Parteien dieser Wert sicher besser zu ignorieren ist. Donald Trump ist von dieser Analyse ausgeschlossen, da die deutsche und die englische Sprache sich hier nicht (einfach) vergleichen lassen.

Die Partei mit dem ausgeprägtesten Horden-Score ist die CSU, gefolgt von der AfD. Die Linke ist am wenigsten 'hordenorientiert'. Die übrigen Parteien bilden das Mittelfeld. CSU und AfD erscheinen recht ähnlich, wenn man nicht nur den Median, sondern die Verteilung, d.h. den Interquartilsabstand betrachtet, wie durch die Erstreckung der Box im Boxplot dargestellt. Mit anderen Worten: CSU und AfD gleichen sich in ihrem (relativ) am stärksten Verwendung von Wörtern der 'Horden-Sprache'.

Wenn auch die Definition von Horden-Denken nach Popper relativ klar ist (und in früheren Posts dieser Reihe beschrieben) wurde, so stellt sich doch die Frage, welche Wörter *konkret* dem Horden-Score zugeordnet wurden. Es sind diese hier:


```
#>  [1] "Stamm"             "Bund"              "Deutsch"          
#>  [4] "deutsch"           "Deutschland"       "Volk"             
#>  [7] "Gemeinschaft"      "Schöpfung"         "Ehre"             
#> [10] "Respekt"           "Held"              "Heroe"            
#> [13] "heroisch"          "heldenhaft"        "ehrenvoll"        
#> [16] "völkisch"          "Volksgemeinschaft" "Kampf"            
#> [19] "Sieg"              "Vernichtung"       "Blut"             
#> [22] "Boden"             "ausländisch"       "Ausländer"        
#> [25] "Krieger"           "Krieg"             "Tradition"        
#> [28] "Überlieferung"     "heilig"            "heilige"          
#> [31] "Gnade"             "ewig"              "Ahnung"           
#> [34] "Erlösung"          "erlöst"            "erlösen"          
#> [37] "Verdammung"        "Fluch"             "verdammt"         
#> [40] "verflucht"         "verdammen"         "verfluchen"       
#> [43] "Verheißung"        "Anmaßung"          "anmaßend"         
#> [46] "anmaßen"           "Böse"              "Verachtung"       
#> [49] "Verlangen"         "Heimat"
```

Natürlich wurde dieses 'Horden-Lexikon', um im Duktus zu bleiben, vorab, vor der Analyse der Daten, zusammengestellt. Bei der Betrachtung der Wörter fällt auf, dass viele mythisches Denken aufgreifen: Geschichten von Kampf, Helden, Ehre, Sieg und Niederlage klingen an. Dieses mythische - explizit nicht rationale - Denken ist ein wesentlicher Aspekt des Denkens der geschlossenen Gesellschaft. Ein zweiter Aspekt ist der Bezug auf das "so war es schon immer, daher machen wir es weiter so"; ebenfalls ein nicht (unbedingt) rationaler Gedanke. Zu diesem Argument: Natürlich kann es geschickt oder sinnvoll sein, bei Bewährtem zu bleiben. Aber das ist nicht Argument. Das Argument ist, dass die Idee "Verwahren ist per se" zu verwerfen ist bzw. nicht rational ist.

Die Wörter des Horden-Lexikons sind nicht (komplett) spezifisch; aber sie sind typischer für das Denken der geschlossenen Gesellschaft als für das Denken der offenen Gesellschaft. So ist der Horden-Score nicht zu verstehen: Dass ein einzelnes Wort zwischen Populismus und Rationalismus unterscheidet. Aber ein deutlicher Unterschied, der auf viele einzelne Beispiele beruht, gilt - im Lichte der Popper'schen Ideen - als Indikator; zumindest als Hypothese mit einigem Beleg, die weiterer Prüfung bedarf.

