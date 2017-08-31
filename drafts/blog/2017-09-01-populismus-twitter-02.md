---
title: "Wie populistisch tweeten unsere Politiker? Teil 2"
subtitle: "Details zum Populismus-Profil"
author: "Sebastian Sauer"
tags: [Populismus, textmining]
layout: post
categories: blog
---



Im ersten Teil dieser Serie haben wir uns einen Überblick verschafft über den "Populismuswert" einiger deutscher Parteien, s. [hier](https://sebastiansauer.github.io/psy_pol/blog/populismus-tweets/).

# Datenmaterial
Dieser Populismuswert basiert auf der Analyse von ca. 400.000 Tweets von ca. 200 deutschen Politikern. Etwa 6 Millionen Wörter gingen in die Analyse ein. Auf diesem Datensatz wurden 8 Kriterien für Populismus extrahiert, die auf Karl Poppers Idee der Stammesgesellschaft als Ursprung populistischen Denkens beruhen.

# Analyse
Als Referenzpunkt wurde Donald Trump in die Analyse einbezogen; wie zu erwarten, führte Donald Trump mit großem Vorsprung die Populismus-Rangliste an. Allerdings ist hinzuzufügen, dass alle übrigen Politiker auf Deutsch twittern, nur Trump auf Englisch. Der Sprachenunterschied kann die Vergleichbarkeit der Ergebnisse beeinflussen. Allerdings scheint plausibel, dass z.B. die Häufigkeit von Großbuchstaben in englischer und deutscher Sprache in ähnlicher Häufigkeit auftreten kann.

# Populismus nach Parteien

Wie man sieht, erreicht die AfD den höchsten Populismuswert deutscher Parteien, kurz gefolgt von der Linken. Grüne und FDP liegen im Mittelfeld. Die beiden großen Volksparteien (Union und SPD) weisen die geringsten Populismuswerte auf. Dabei ist zu beachten, dass pro Partei der Median über alle Politiker (sofern im Datensatz enthalten) gebildet wurde. Aus dieser Sicht kommt also nicht raus, ob der populistischste Politiker in Deutschland aus der AfD, CSU oder einer sonstigen Partei stammt.

![](https://sebastiansauer.github.io/psy_pol/images/2017-08-28/p_party_pop_scores_2.png)


# Detailliertes Populismusprofil nach Parteien

Wie in [diesem Post](https://sebastiansauer.github.io/psy_pol/blog/populismus-tweets/) dargestellt, gingen diese 8 Indikatoren in die Berechnung des Populismuswerts ein:


- "Wortkürze"
- "Verhältnis negativer/positiver Wörter",
- "Anteil negativer Wörter",
- "Anteil emotionaler Wörter",
- "Wert an negativer Emotion",
- "Wert an Emotionalität",
- "Anteil GROSSBUCHSTABEN",
- "Verhältnis von Adjektiven zu Adverben"


Daher stellt sich die Frage, wie diese acht Populismus-Indikatoren pro Partei ausgeprägt sind. Die folgende Abbildung stellt die Populismus-Indikatoren dar. Alle Werte sind als z-Werte dargestellt. z-Werte sind, kurz gesagt, ein Maß dafür, wie über- oder unterdurchschnittlich ein Wert im Vergleich zu allen untersuchten Politikern ist. z-Werte größer als Null stellen überdurchschnittliche hohe Werte dar; z-Werte kleiner als Null entsprechend unterdurchschnittliche Werte. Dabei können z-Werte von -1 bis +1 als "mittel" gelten; z-Werte im Bereich von -2 bis -1 bzw. +1 bis +2 als "stark ausgeprägt"; darüber (>2) als "sehr stark" oder "extrem" ausgeprägt.

Man sieht leicht, dass Trumps Werte am extremsten sind. Allerdings ist insofern Vorsicht geboten, als *Wortkürze* nur sehr eingeschränkt zu werten ist, da die Sprachunterschiede (Deutsch vs. Englisch) hier stark zum Tragen kommen. Aus dem gleichen Grund wurde verzichtet, einen Emotionswert an die Wörter von Trump anzulegen; dieser Wert wäre mit dem für deutsche Wörter kaum zu vergleichen.


![](https://sebastiansauer.github.io/psy_pol/images/2017-08-28/p_party_pop_scores_details.png)


Vor dem Hintergrund der Vergleichsprobleme von englischem und deutschem Textmaterial bei dieser Sprachanalyse ist es aufschlussreich, nur die deutschen Politiker zu betrachten.


![](https://sebastiansauer.github.io/psy_pol/images/2017-08-28/p_party_pop_scores_details.png)

Das Diagramm stellt den Median pro Populismus-Indikator dar; und das für jede der 7 untersuchten Parteien. Einfach gesagt: Je länger ein Balken nach rechts zeigt, desto stärker ausgeprägt ist der von diesem Indikator geschätzte Populismusaspekt. Mit dieser Lesehilfe im Hinterkopf sind einige zentrale Aspekte des Diagramms schnell erfasst: Bei der AfD und bei der Linken ragen die Balken häufig weit nach rechts. Allerdings zeichnet sich die Linke durch sehr lange Wörter in ihren Tweets auf (d.h. sehr geringe Wortkürze im Vergleich zu den anderen Parteien); ähnliches gilt für die Grünen. In dieser Hinsicht (Wortlänge) gleichen sich die Linke und die Grünen.

Die Profilkurve von CSU und CDU ist dabei auffällig ähnlich; offenbar zeigt sich das Geschwistertum auch in der formalen Struktur der Tweets. Allerdings ist die CSU sehr wenig emotional, zumindest im Vergleich zu den übrigen Parteien (d.h. deren Mediane über alle untersuchten Politiker). Die Partei, die am meisten emotionale Inhalte anrührt, ist die Afd; kurz darauf folgt die Linke. Eine weitere starke Differenz lässt sich besonders zwischen AfD und CSU festmachen: Die AfD verwendet sehr viele negative Wörter; die CSU ist sehr viel positiver (wenn sie denn man emotionale Wörter verwendet). Zugespitzt formuliert: In Bayern ist die Welt in Ordnung (zumindest in den Tweets aus Bayern); im übrigen sind die Bayern sehr nüchtern (wenig emotional). Das Gegenteil zu Bayern ist die Afd, sozusagen...

Warum ist der Quotient von Adjektiven zu Adverben eingegangen? Mit Adjektiven werden Zustände, also Seinsweisen, festgezurrt. So wird in dem Satz "Er ist verwirrt" ein Adjektiv verwendet. Dem Träger dieser Eigenschaft wird also Verwirrtheit zugeschrieben, offenbar als Charaktermerkmal. Ein Gegensatz dazu ist der Satz "Er spricht wirr". In diesem Satz wird nicht der Person ein Merkmal zugeschrieben, sondern - und das ist spezifischer - ein Verhalten spezifiziert. Damit wird weniger pauschalisiert. Mit Adverben lassen sich Lösungen finden, denn Verhalten lässt sich ändern. Menschen zu ändern ist hingegen schwierig.

# Fazit
Das Profil der Populismus-Indikatoren detailliert den aggregierten Populismuswert wie oben dargestellt. Die Ergebnisse entsprechend damit (notgedrungen) dem aggregierten Ergebnis. Allerdings finden sich auch einige interessante Details, wie der Gegensatz von CSU und AfD. Dieser Gegensatz überrascht, da sich beide Parteien gerne als sehr konservativ präsentieren. Trotz dieser Gemeinsamkeit, der konserativen Ausrichtung, stehen die Parteien aber im starken Kontrast, was ihre Sprachweise betrifft.

# Cave
Bei allen diesen Aussagen wie "Sprachweise" etc. ist immer zu beachten, dass stets nur die Ergebnisse dieser Analyse gemeint sind. So ist kein direkter Schluss auf *alle* Kommunikationsweisen *aller* Politiker Deutschlands zu *allen* Zeiten etc. gemeint. Die Repräsentativität von Tweets für alle Aussagen einer Partei ist auch diskussionswürdig. Allerdings spielen Nachrichten in den sozialen Medien wie Twitter eine große Rolle in der Darstellung von Parteien. Daher kommt Tweets und deren Analyse eine substanzielle Bedeutung zu - man denke an das Twitter-Gewitter von Donald Trump.
