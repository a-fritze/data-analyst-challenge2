# Anmerkungen und Ergebnisse

Anemerkungen:
Im ersten Schritt wäre in einer reelen Situation natürlich die Rücksprache mit der Redaktion notwenig um eine nützliche Datenanalyse durchzuführen. Es müssten vorab einige Fragen geklärt werden. Wichtig wäre es z.B. zu erfahren mit welchen KPIs die Redaktion arbeiten, was für sie spezifische interessant ist und welche Kennzahlen eher für andere Abteilungen interessant sind.
Es wäre für meine Arbeit wichtig zu erfahren welchen Aufschluss die unterschiedlichen Kennzahlen geben können. Meine Überlegungen zu den Kennzahlen sind, dass zusätzlich Kennzahlen wie die Verweildauer überprüft werden sollten, da diese mehr Auskunft darüber geben, ob die Inhalte von den Leser:innen wirklich gelesen wurden. Pageviews sind nicht nur vom Inhalt und Headline abhängig sondern auch stark abhängug von der Platzierung, des Datums, Wochentags, SEO und Platzierung in Social Media und Newsletter und anderen Verlinkungen. SubscriberPageViews sind wiederrum wichtig um zu erfahren was die bestehenden Abodementen interessiert und deshalb eine bede


Im Notebook, dass sich in diesem Repository befindet, sind die Schritte der Analyse nachzuvollziegen, vo der Datenbereinigung, der Datensichtung, Plotting und Analyse. Die Analyse ist nicht vollumfänglich, um zu einem Ergbniss zukommen, mit dem die Redaktion arbeiten kann, müssten vorab einige Fragen geklärt werden. 

Um eine relevante Analyse machen zu können müsste zu dem das Daten der Veröffentlichung eine Rolle spielen, da Artikel, die seid längerem zur Verfügung stehen, mehr Klicks und Conversionsgenerieren können, als Artikel, die erste vor kurzem veröffentlicht werden. Es wäre vielleicht eine Lösung nur die Kennzahlen von Artikeln zu bergleichen, die sie in den erstem zwei Wochen der Veröffentlichung geneieren konnten. 

In meiner ersten Analyse habe ich das Datum der Veröffentlichung erstmal ignoriert, Dinge die auf Grundlage des Datums noch geprüft werden könnten:

  - Spielt die Uhrzeit oder der Wochentag der Veröffentlichung eine Rolle bei der Generation von Klickzahlen?
  - Werden die unterschiedlichen Ressorts an manchen Wochentagen oder Uhrzeiten verrmehrt gelesen? Lohnt es sich zum Beispiel Artikel des Ressorts Gesellschaft eher am Abend zu veröffentlichen und Artikel des Ressorts eher am Morgen? 
  
Was natürlich wichtig bei der Auswertung ist, sind Informationen darüber wo der Artikel plaziert und verlinkt wurde. 

Zu den ersten analyste Ergebnissen:
## „Welche Ressorts laufen besonders gut? Gibt es signifikante Unterschiede zwischen Ressort hinsichtlich der Zahlen?“ 

Zu beantworten welche Ressorts gut laufen ist anhand der vorhanden Zahlen nur sehr eingeschrankt möglich. Da Kennzahlen fehlen, bzw. die Laufzeiten der Artikel sehr unterschiedlich lang ist. 
Eine Zusammenfassung aus dem Notebook: 
- Da die meisten Ressorts extreme Outliner verzeichnen in den unterschiedlichen Kennzahlen, wurde der Median der unterschiedlichen Kennzahlen errechnet, mit dem Ergbniss, dass Politik das Ressort mit den beste Werten bei allen vorhandenen Kennzahlen ist, gefolgt von Gesellschaft und Gesundheit.
Hier sehen wir die Kennwerte als Median, Mean und als Summer im Vergleich: 


![output](https://github.com/a-fritze/data-analyst-challenge/assets/118194705/f583fd73-6bd9-4afa-a2b5-bbe9846701a8)

Es gibt Signifikante Unterschiede hinsichtlich der Zahlen unterhalb der Ressorts aber besonders auch unterhalb der Artikel unabhängig vom Ressort. 


## „Welche Maßnahmen sollten wir ergreifen noch besser zu werden?“ 

 Fragen und Anmerkungen: 
 
 - Das die Ressorts extreme Outliner verzeichnen und die Erfolge der Artikel innerhalb der Ressorts stark variieren ist die Betrachtung der einzelnen Artikel relevant, unabhängig vom Ressor. Ein Vorschlag wäre sich die 10-20 erfolgsreichsten Artikel rauszusuchen und deren Kennzahlen zu betrachten und eingehend analysieren, warum sind diese Artikel besser gelaufen als andere Artikel
 - Macht es Sinn Artikel neben dem Resort einer Unterruprik zuzuordnen? Wenn, dann sollte es stringend gemacht werden
 - Tags: Es wurden fast keine Tags gesetzt und wenn, erscheinen sie recht unspezifisch. Entweder lassen und Tagstrategie ausarbeiten oder automatisiertes Tagsystem etablieren? Tags könnten helfen Artikel besser nach Themen gruppieren und analysieren zu können
 - Qualität der Daten: Manche Artikel wurden gar kein Ressort zugeorndet oder haben kein Veröffentlichungsdatum, für eine gute  Analyse ist auf die Qualität der Daten zu achten 
 - Es gibt sechs Duplikate, wie ist das zustande gekommen und wie kann der Fehler in Zukunft verhindert werden?
 
