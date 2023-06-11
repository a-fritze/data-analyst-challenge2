# Anmerkungen und Ergebnisse

Anmerkungen:
In einer realen Situation wäre der erste Schritt natürlich die Rücksprache mit dem Redaktionsteam. Einige Fragen müssten im Vorfeld geklärt werden. Zum Beispiel wäre es wichtig herauszufinden, mit welchen KPIs die Redaktion arbeitet, was speziell für sie interessant ist und welche KPIs eher für andere Abteilungen interessant sind.
Für meine Arbeit wäre es wichtig, herauszufinden, welche Informationen die verschiedenen KPIs liefern können. Meine Gedanken zu den KPIs sind, dass zusätzlich KPIs wie die Verweildauer überprüft werden sollten, weil sie mehr Informationen darüber geben, ob der Inhalt von den Abonnenten wirklich gelesen wurde. Pageviews und SubscriberPageViews sind nicht nur vom Inhalt und der Überschrift abhängig, sondern auch stark von der Platzierung, dem Datum der Veröffentlichung, dem Wochentag, SEO und der Platzierung auf Social Media und Newslettern und die Verlinkungen auf der eigenen Seite sowie externen Seiten. Conversions ist eine besonders interessante Kennzahl, wenn es darum geht, zu überprüfen, welches Thema und welche Schlagzeile die Leute zum Abonnieren veranlasst hat, und ist besonders wichtig für den langfristigen wirtschaftlichen Erfolg der Zeitung.

Um eine aussagekräftige Analyse zu erstellen, müsste das Veröffentlichungsdatum eine Rolle spielen, da Artikel, die schon lange verfügbar sind, mehr Klicks und Conversions generieren können als Artikel, die erst kürzlich veröffentlicht wurden. Es könnte eine Lösung sein, nur die Kennzahlen für Artikel zu vergleichen, die sie in den ersten zwei Wochen nach ihrer Veröffentlichung generieren konnten. 

In meiner ersten Analyse habe ich das Datum der Veröffentlichung vorerst ignoriert, was anhand des Datums noch überprüft werden könnte:

  - Spielt die Tageszeit oder der Wochentag der Veröffentlichung eine Rolle bei der Generierung von Klickzahlen?
- Werden die verschiedenen Rubriken an bestimmten Wochentagen oder zu bestimmten Uhrzeiten bevorzugt gelesen? Lohnt es sich beispielsweise, Artikel aus dem Ressort Gesellschaft mehr am Abend und Artikel aus dem Ressort Politik mehr am Morgen zu veröffentlichen? 
 
 Wichtig bei der Auswertung ist natürlich die Information, wo der Artikel platziert und verlinkt wurde. 
 
Im Notizbuch, das sich in diesem Repository befindet, können die Schritte der Analyse von der Datenbereinigung über das Plotten bis hin zur Analyse nachvollzogen werden. 


Zu den ersten Ergebnissen der Datenanalyse:

## „Welche Ressorts laufen besonders gut? Gibt es signifikante Unterschiede zwischen Ressort hinsichtlich der Zahlen?“ 

Welche Ressorts gut laufen, lässt sich anhand der vorliegenden Zahlen nur sehr bedingt beantworten. Es fehlen wichtige Kennzahlen, und die Laufzeiten der Artikel sind sehr unterschiedlich. 

Eine Zusammenfassung aus dem Notebook: 
- Da die meisten Ressorts extreme Outliner bei den verschiedenen Kennzahlen aufweisen, wurde der Median der verschiedenen Kennzahlen berechnet, mit dem Ergebnis, dass Politik das Ressort mit den besten Werten bei allen verfügbaren Kennzahlen ist, gefolgt von Gesellschaft und Gesundheit.
Hier sehen wir die Kennzahlen als Median, Mittelwert und in Summe im Vergleich: 


![output](https://github.com/a-fritze/data-analyst-challenge/assets/118194705/f583fd73-6bd9-4afa-a2b5-bbe9846701a8)

Es gibt signifikante Unterschiede hinsichtlich der Zahlen unterhalb der Ressorts, aber besonders auch unterhalb der Artikel unabhängig vom Ressort. 


## „Welche Maßnahmen sollten wir ergreifen noch besser zu werden?“ 

 Fragen und Anmerkungen: 
- Da es in den Ressorts extreme Outliner gibt und der Erfolg der Artikel innerhalb der Ressorts stark variiert, ist die Betrachtung einzelner Artikel unabhängig vom Ressort relevant. Ein Vorschlag wäre, die 10-20 erfolgreichsten Artikel auszuwählen, ihre Kennzahlen zu betrachten und im Detail zu analysieren, warum diese Artikel besser abschneiden als andere Artikel.
- Ist für die Analyse sinnvoll, die Artikel neben einem Ressort auch einer Rubrik zuzuordnen? Wenn ja, dann sollte dies stringent geschehen
- Tags: Es wurden fast keine Tags gesetzt, und wenn doch, dann scheinen sie recht unspezifisch zu sein. Entweder sollte auf die Vergabe von Tags ganz verzichtet werden, oder es sollte eine Tagging-Strategie ausgearbeitet werden, oder vielleicht sollte ein automatisches Tagging-System eingerichtet werden? 
 - Tags könnten helfen, Artikel besser nach Themen zu gruppieren und zu analysieren
 - Qualität der Daten: Einige Artikel wurden keinem Ressort zugeordnet oder haben kein Veröffentlichungsdatum; für eine gute Analyse muss die Qualität der Daten gewährleistet sein. 
- Es gibt sechs Duplikate. Wie ist das zustande gekommen und wie kann der Fehler in Zukunft vermieden werden? 
