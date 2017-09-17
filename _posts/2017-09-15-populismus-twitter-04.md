---
title: "Wie populistisch tweeten unsere Politiker? Teil 4"
subtitle: "Wer tweetet am meisten über 'deutsch*'"
author: "Sebastian Sauer"
tags: [Populismus, textmining]
layout: post
categories: blog
---




In diesem vierten Teil der Analyse von Tweets deutscher Parteien geht es um die Frage, welche Bedeutung Wörter mit dem Stamm 'deutsch' in den Tweets der Politiker haben, also Wörter wie "Deutsch", "Deutschland", "Deutsche". Kurz: wer spricht am meisten über "Deutsches"?


Zu diesem Zweck wurde die Liste aller Tweets bzw. (genauer) die Liste der Wörter der Tweets ausgelesen nach dem Wortstamm 'deutsch*'. Damit wurden alle Wörter berücksichtigt, die mit 'deutsch' beginnen. Dann wurde schlicht gezählt, wie häufig (absolut und relativ zu der Anzahl der Wörter) ein Politiker oder eine Partei diesen Wortstamm verwendet.

Das Ergebnis ist recht eindeutig:


<img src="https://sebastiansauer.github.io/psy_pol/images/2017-09-15/p_horde_03_boxplot.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" width="80%" style="display: block; margin: auto;" />


Die AfD verwendet "Deutsch-Begriffe" deutlich am häufigsten. Der zweite Platz geht an eine Politikerin, die der Union angehörte, aber die Partei verlassen hat und jetzt fraktionslos im Bundestag sitzt. Da es sich hier nur um eine Person handelt, sollte diesem Wert nur wenig Bedeutung zugemessen werden. Der dritte Platz geht an die Union, wobei sich die Schwesterparteien CDU und CSU sich kaum unterscheiden. Die FDP markiert das untere Ende der Häufigkeitsliste.

# Emotional tweeten = 'deutsch*' tweeten?

Eine interessante sich anknüpfende Frag ist, ob diejenigen Politiker die viel 'deutsch*' tweeten, auch emotional tweeten? Diese Frage -bzw. eine Antwort darauf- ist in folgenden zwei Abbildungen dargestellt:

<img src="https://sebastiansauer.github.io/psy_pol/images/2017-09-15/p_emo_deutsch.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" width="70%" style="display: block; margin: auto;" /><img src="https://sebastiansauer.github.io/psy_pol/images/2017-09-15/p_emo_deutsch_afd_only.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" width="70%" style="display: block; margin: auto;" />

Die erste Abbildung zeigt, dass es generell keinen Zusammenhang (in den Daten) gibt zwischen dem Emotionswert eines Politikers und seinem Deutsch-Wert. Nicht vergessen: Diese Werte beziehen sich auf die "typische" Sprache in seinen oder ihre Tweets. Die zweite Abbildung untersucht diesen Zusammenhang nur für AfD-Politiker. Hier findet sich ein negativer Zusammmenhang: Je emotionaler, desto weniger 'deutsch*' und umgekehrt. Wie ist das zu verstehen bzw. zu interpretieren? Die vielleicht wichtigste Aussage dazu ist, dass aufgrund der kleinen Stichprobengröße große Zurückhaltung bei der Interpretation geboten ist. 

# Fazit

Für Die AfD spielen Deutsch-Begriffe also die größte Rolle, wenn man die Daten nach "Häufigkeit ist gleich Relevanz" interpretiert. Sicherlich ist diese Interpretation nicht immer und nicht in vollem Umfang richtig. Andererseits erscheint es plausibel, dass die AfD, die "Deutschland" in ihrem Namen trägt, sich dieser Begriffe häufig bedient.

Nach dem Modell der vorliegenden Studie wird hohen Werten des Deutsch-Begriffes ein hoher Populismuswert zugeordnet. Die AfD ist demnach die populistischste Partei.

Dabei muss einschränkend gesagt werden, dass es sich bei diesem Indikator nur um einen von mehreren Indikatoren von Populismus handelt. Nichtsdestotrotz sind die Ergebnisse für diesen Indikator eindeutig.
