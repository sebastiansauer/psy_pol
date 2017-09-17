---
title: "Wie populistisch tweeten unsere Politiker? Teil 3"
subtitle: "Emotionswerte der Tweets"
author: "Sebastian Sauer"
tags: [Populismus, textmining]
layout: post
categories: blog
---




In diesem dritten Teil der Serie geht es um den Grad der Emotionalität der Tweets der Politiker bzw. der Parteien. Dieser Wert ist vielleicht deswegen am interessantesten, da der theoretische Bezug zum Populismus am stärksten ist. Einige Theorien - wie die *Elaboration Likelihood* Theorie von Petty und Cacioppo^[Petty, R. E. & Cacioppo, J. T.
The elaboration likelihood model of persuasion 
Advances in experimental social psychology, 1986, 19, 123-205]  oder die *Dual Processing* Theorie^[Evans, J. S. B., Dual-processing accounts of reasoning, judgment, and social cognition, Annu. Rev. Psychol., 2008, 59, 255-278] gehen davon aus, dass Emotion verwendet wird, um ohne Fakten, ohne rationale Argumente zu überzeugen. In diesem Sinne kann Emotionalität in der Sprache, gerade bei Politikern, als ein nicht-rationaler, nicht vernunftorienterter Versuch der Überzeugung verstanden werden - Populismus insofern.

Man kann dagegen halten, dass man auch rationale Argumente mit Emotionalität "schmücken" könne, gar müsse als Politiker. Das ist richtig, aber trotzdem bleibt das Argument richtig, dass - unter sonst gleichen Umständen - ein hoher Emotionswert im Sinne oben genannter Theorien als Indikator für Populismus gelten kann.



# Emotionswert der Tweets nach Parteien
Betrachten wir einige Ergebnisse:

<img src="https://sebastiansauer.github.io/psy_pol/images/2017-09-15/p_emo_per_party.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" width="80%" style="display: block; margin: auto;" />

Die Abbildung zeigt, dass der (mediane) Emotionsgehalt in den Tweets der AfD am stärksten ausgeprägt ist. Die CSU hingegen markiert das untere Ende der Emotionalität; ihr Wert ist im Vergleich am geringsten ausgeprägt. Zu beachten ist, dass hier z-Werte dargestellt sind. z-Werte zeigen, wie weit eine Partei vom mittleren Wert über alle Parteien bzw. über alle Politiker entfernt ist. Große positive Werte bedeuten also weit überdurchschnittliche Werte etc. Natürlich ist zu beachten, dass hier nur eine Stichprobe (wenn auch eine recht große) aller Tweets betrachtet wurde. Außerdem sind Tweets sicher nicht mehr als ein Teil (eine Stichprobe) der gesamten Kommunikation oder dem gesamten öffentlichen Auftreten einer Partei; und ein nicht unbedingt repräsentativer. Allerdings ein nicht unwesentlicher.

Eine wichtige Frage ist, wie die Emotionalität der Wörter beurteilt wurde, da dies natürlich über die Ergebnisse maßgeblich entscheidet. Die Emotionswerte wurden aus dem "SentiWS-Wörterbuch" ohne Änderung übernommen; die Quelle ist [hier]().


# Die häufigsten emotionalen Wörter, die unique für die AfD sind

Eine interessante, sich anschließende Frage ist: Wenn die AfD die Partei mit den emotionalsten Tweets sind, welche *uniquen* Wörter verwendet sie? Also welche Wörter erscheinen in den häufigsten Emo-Wörtern der AfD, die *nicht* bei den anderen Parteien in der Top-Liste erscheinen?

Es sind diese:


```
#>  [1] "ablehnung"        "vorwurf"          "unrecht"         
#>  [4] "belasten"         "trennung"         "toll"            
#>  [7] "leid"             "hölle"            "verletzung"      
#> [10] "zerstört"         "katastrophe"      "unklar"          
#> [13] "ruhe"             "hass"             "super"           
#> [16] "gefährden"        "lüge"             "genießen"        
#> [19] "zwingen"          "unsinn"           "beklagen"        
#> [22] "negativ"          "stehlen"          "feiern"          
#> [25] "fremd"            "katastrophal"     "betrug"          
#> [28] "vernichten"       "übel"             "propaganda"      
#> [31] "unverantwortlich" "angenehm"         "unangemessen"
```

Ein kurzer Blick zeigt, dass die Wörter vor allem negativ konnotiert sind. Insgesamt lässt sich ein Narrativ eines Bedrohungsszenarios ausmachen: "Unrecht", "katastrophal", "vernichten", "übel", "zerstört", "zwingen" oder "zerstört". Das Narrativ der Lüge zeigt sich deutlich: "unsinn", "lüge" "propaganda", "betrug", "unsinn", "vorwurf" oder "unklar".

Als Gegenprobe erscheint interessant zu schauen, welche emotionalen Wörter sich in der Hitliste der AfD *und auch gleichzeitig* bei den übrigen untersuchten Parteien findet:



```
#>  [1] "gefahr"          "schuld"          "unnötig"        
#>  [4] "schädlich"       "schwach"         "schämen"        
#>  [7] "unfair"          "verdacht"        "feind"          
#> [10] "brechen"         "schuldig"        "ungerecht"      
#> [13] "schlecht"        "bedenklich"      "verurteilen"    
#> [16] "falsch"          "betrügen"        "unwürdig"       
#> [19] "perfekt"         "lob"             "gemein"         
#> [22] "spannend"        "wunderschön"     "risiko"         
#> [25] "fehler"          "streit"          "gering"         
#> [28] "freude"          "kritiker"        "schlimmer"      
#> [31] "lächerlich"      "ungeeignet"      "gefährlich"     
#> [34] "unverständlich"  "unzufriedenheit" "sturz"          
#> [37] "verbieten"       "unsicher"        "vorurteil"      
#> [40] "ausgrenzung"     "schlicht"        "täuschen"       
#> [43] "unbedeutend"     "faulheit"        "mut"            
#> [46] "verdammen"       "freundlich"      "dumm"           
#> [49] "hervorragend"    "kreativ"         "abstoßend"      
#> [52] "prima"           "besonders"       "kampf"          
#> [55] "fehlen"          "krieg"           "gewalt"         
#> [58] "kritik"          "schaden"         "vermeiden"      
#> [61] "töten"           "verletzt"        "stolz"          
#> [64] "überflüssig"     "angst"           "zerstören"      
#> [67] "übersehen"
```


Das Bild bleibt stark negativ gefärbt, wird aber deutlich vielfältiger, bunter und nuancierter.


# Die emotionalsten Wörter nach Parteien

Schauen wir uns als nächstes an, was die emotionalsten Wörter *pro Partei* sind. Diese Wörter können sich nach Partei unterscheiden. Dafür wurde die Tabelle mit den Tweets und deren Emotionalität nach sieben untersuchten Parteien aufgeteilt. Dann wurde jede der resultierenden Teiltabellen nach Emotionalität der Tweets (absteigend) sortiert. Die oberen (emotionalsten) 1% der Wörter pro Partei sind im Folgende dargestellt.


<img src="https://sebastiansauer.github.io/psy_pol/images/2017-09-15/p_most_emo_words_facets.png" title="plot of chunk unnamed-chunk-4" alt="plot of chunk unnamed-chunk-4" width="100%" style="display: block; margin: auto;" />


Wie man sieht, finden sich einige Gemeinsamkeiten: "Gefahr" und "Schuld" sind offenbar die Wörter, die im SentiWS-Wörterbuch als die emotionalsten Wörter aufgeführt waren und die zugleich in den Tweets vorkamen. Es ist also möglich, dass es noch emotionalere Wörter in den Tweets gibt, die aber im Emotionslexikon (SentiWS) nicht enthalten sind. Dies ist u.U. schwer nachzuprüfen und wurde hier nicht weiter untersucht. 

Da die Stichprobe an Tweets in z.B. der SPD viel größer ist als z.B. die der AfD sind die einzelnen Datenmengen - also die Menge der Top-1%-Tweets - auch unterschiedlich groß.

# Fazit

Die AfD ist die Partei, die recht deutlich mit dem stärksten Emotionswert unterm Strich aufwartet. Sicher sind hier noch viele Aspekte nicht untersucht und das Ergebnis vorläufig und mit Vorbehalten zu betrachten. Nichtsdestoweniger zeigen die vorliegenden Daten in eine deutliche Richtung. Die Aufschlüsselung der uniquen Top-Emo-Wörter der AfD passen in die erwartete Richtung, unterstreichen das Bild der AfD als "wütend"; es finden sich in diesen Wörter zum Narrativ der "Bedrohung".
