---
title: 1.1 Grundsätze beim UI - Design 
description : "Grundsätze"
tags: ["UI", "Grundsätze"]
---

Die Gestaltung der Benutzeroberfläche ist ein zentrales Thema für die Benutzbarkeit eines Softwareprodukts, weshalb viele Grundprinzipien zum UI-Design entwickelt worden sind. Dabei werden Aufbau und Benutzbarkeit, sowie auch Aussehen und Funktionen einer Benutzeroberfläche betrachtet. Wie bereits in der Einleitung erwähnt, wird im Folgenden auf elementare Anforderungen und Normen eingegangen. Dabei werden hauptsächlich die *10 Heuristiken nach Nielsen* aufgegriffen, wobei teilweise auch auf ähnliche Regeln von Shneiderman verwiesen wird. Die mehrfache Vertretung an gleichen Grundsätzen unterstreicht nochmals ihre Bedeutsamkeit. 

1. Sichtbarkeit des Systemstatus

Wichtig für die Orientierung im System, spielt das angemessene Feedback eine wesentliche Rolle. Denn das Design sollte den Nutzer immer innerhalb einer angemessenen Zeitspanne über den aktuellen Stand der Dinge informieren, so Nielsen in seiner ersten Heuristik. Auch Shneiderman sagt in Regel 3 über informatives Feedback aus, dass die Rückmeldung bei häufigen und geringfügigen Aktionen bescheidener ausfallen kann, während sie bei seltenen und größeren Aktionen umfangreicher sein sollte. Durch angemessenes Feedback erkennen Nutzer immer den aktuellen Systemstatus und können zukünftige Interaktionsmöglichkeiten vorhersehen.

2. Übereinstimmung von System und Wirklichkeit

Das System sollte die Sprache des Nutzers sprechen. Die Art und Weise des UI-Designs hängt immer sehr stark von ihren spezifischen Benutzern ab. Begriffe, Konzepte, Symbole und Bilder, die beispielsweise einer jungen Benutzergruppe völlig klar erscheinen, können für ältere Anwender ungewohnt oder verwirrend sein. Wenn die Steuerelemente eines Designs realen Konventionen folgen und den gewünschten Ergebnissen entsprechen, so vereinfacht es die Lernbarkeit einer Schnittstelle. Dies schafft ein intuitives und positives Nutzererlebnis.

3. Benutzerkontrolle und Freiheit

Anwender führen oft versehentlich Aktionen aus. Sie brauchen deswegen häufig einen deutlich gekennzeichneten "Notausgang", um die unerwünschte Aktion zu verlassen, ohne einen längeren und anstrengenden Prozess durchlaufen zu müssen. Ausgänge ermöglichen es den Benutzern, die Kontrolle über das System beizubehalten und ihnen gleichzeitig ein Gefühl der Freiheit in ihren Interaktionen zu ermöglichen. Das Beherrschen der Benutzerschnittstelle unterbindet das Frustrationsempfinden durch Vermeiden von Überraschungen oder Änderungen im gewohnten Verhalten oder Schwierigkeiten bei der Beschaffung notwendiger Informationen, die mit langwierigen Dateninputabläufen verbunden sind, so Shneiderman unter seiner Regel 7. Für die Oberflächengestaltung bedeutet es “Rückgängig” und “Wiederholung”-Optionen, beispielsweise in Form von Buttons, einzubauen. Das Abbrechen einer Aktion sollte stets klar gekennzeichnet und auffindbar sein, wobei auch “Zurück”-Buttons gut geeignet sind.

![](/webhandbook/ui_ux/images/11.png)

4. Beständigkeit und Standards

Nutzer sollten sich nicht fragen, ob verschiedene Wörter, Situationen oder Handlungen dasselbe bedeuten. Somit weist Nielsen auf das Befolgen von Konventionen und Standards hin. Er rät zur Gestaltung einer Konsistenz innerhalb desselben Systems. Die Oberfläche sollte stets einheitlich gestaltet werden, um dem Nutzer eine einfache Bedienung durch das wiederholte Anwenden von bereits erlerntem Wissen zu gewährleisten. Der Nutzer gewöhnt sich an die Bedienbarkeit und muss keine neuen Konzepte erlernen. Aussehen, Inhalt und Verhalten sollten dafür ebenfalls konsistent bleiben, um eine angenehmere Nutzung zu ermöglichen. Mit der Gestaltung ähnlicher Layouts, Farben oder Schriftarten gewöhnt sich der Nutzer an die Bedienbarkeit und muss keine neuen Konzepte erlernen, so auch Shneiderman in seiner ersten Regel.

![](/webhandbook/ui_ux/images/12.png)

5. Fehlervermeidung

Gute Fehlermeldungen sind wichtig, aber auch die besten UI-Designs verhindern nur, dass Probleme überhaupt erst auftreten. Zwar sollte der Nutzer, wie bereits in Punkt 3 genannt, möglichst die gesamte Kontrolle besitzen, jedoch sollte das Interface auch so konzipiert sein, dass bei der freien Verwendung keine Fehler auftauchen. Entweder werden fehleranfällige Bedingungen eliminiert oder es wird dem Nutzer vor einer entsprechenden Aktion eine Bestätigungsoption angeboten. Beim Interface-Entwurf kann beispielsweise bereits darauf geachtet werden, Menüpunkte auszugrauen auf die nicht mehr zugegriffen werden soll. In numerische Datenfelder (z.B. Postleitzahlangabe) sollte beim Design bereits beachtet werden Buchstaben zu unterbinden oder darauf hinzuweisen. Allgemein sollte bei fehlerhaften Aktionen der Zustand der Schnittstelle unverändert bleiben oder die Schnittstelle sollte Anweisungen zur Wiederherstellung des Zustands angeboten werden.

![](/webhandbook/ui_ux/images/13.png)

6. Wiedererkennung statt Erinnerung

Ein gutes UI-Design sollte klar und deutlich erkennbare Aktionsmöglichkeiten und Elemente anzeigen, sodass sich der Nutzer nicht alle Informationen merken muss. Nutzer sollen Informationen wiedererkennen, anstatt sich alles zu merken. Informationen oder Anleitungen, die für die Verwendung des Designs erforderlich sind (z. B. Feldbeschriftungen oder Menüpunkte) sollten sichtbar oder bei Bedarf leicht abrufbar sein. Nielsen rät dazu stets Hilfe im Kontext anzubieten, anstatt den Benutzern eine lange Anleitung zum Auswendiglernen zu geben. Shneiderman weist auf die Faustregel (Millers Law) hin, dass sich Menschen durchschnittlich nur 7 plus/minus 2 Objekte merken können. Aufgrund dessen sollte beim UI-Design immer das Kurzzeitgedächtnis des Menschen berücksichtigt werden, denn das System sollte sich alles merken, nicht der Benutzer.

7. Flexibilität und Effizienz

Ein gutes System sollte für jede Benutzergruppe geeignet und angepasst werden können. Beispielsweise können durch Abkürzungen Interaktionen für erfahrene Nutzer beschleunigt werden, ohne das Benutzererlebnis für unerfahrene Nutzer zu beeinträchtigen. Funktionen und Aktionen sollten individuell anpassbar sein, um einen flexiblen Prozess für jeden zu ermöglichen. Ein Beispiel hierfür ist das Einbringen einer “Überspringen”-Option für bestimmte Anleitungen eines Systems.

8. Ästhetisches und minimalistisches Design

Schnittstellen sollten keine irrelevanten Informationen enthalten, die gar nicht oder selten benötigt werden. Jedes einzelne Element einer Anwendung dient der Kommunikation mit dem Nutzer, so zum Beispiel auch schon Text, Farben oder Symbole. Alles davon ist eine Informationseinheit. Jede zusätzliche Informationseinheit im UI konkurriert mit relevanten Informationseinheiten und verringert deren relative Sichtbarkeit. Es sollte somit jederzeit sichergestellt werden, dass die visuelle Gestaltung und auch der Inhalt auf das Wesentlichste konzentriert ist. Einfachheit und Klarheit sind die Grundbausteine im UI-Design. Ein überladenes Interface lenkt den Nutzer nur ab und könnte sogar dafür sorgen, dass elementare Funktionen übersehen werden. Nielsen plädiert darauf zu achten, dass jedes visuelle Element eines UI auch die primären Ziele der Nutzer unterstützt.

![](/webhandbook/ui_ux/images/14.png)

9. Hilfestellung beim Erkennen, Bewerten und Beheben von Fehlern

Nielsen sagt aus, dass Fehlermeldungen visuell immer so aufbereitet werden müssen, dass sie von den Benutzern auch wahrgenommen und erkannt werden können. Dabei kann beim UI-Design integriert werden, Fehlermeldungen in roter Farbe oder fettgedruckten Text ausgeben zu lassen. Dies ist der verbreitetste Standard (Heuristik 4) und wird von den meisten Nutzern direkt wiedererkannt (Heuristik 6). Auch sollten solche Meldungen stets klar und in einfacher Sprache formuliert sein, genau das Problem benennen und eine konstruktive Lösung vorschlagen.

![](/webhandbook/ui_ux/images/15.png)

10. Hilfe und Dokumentation

Im Idealfall sollte das System komplett intuitiv sein und keine zusätzlichen Erklärungen benötigen. Doch dies ist in den meisten Fällen nicht möglich, weshalb es von Vorteil ist, eine Dokumentation zur Verfügung zu stellen. Bedienungshilfen und Dokumentationen sollten im UI leicht auffindbar sein. Diese sollten die wichtigsten Schritte kurz und konkret beschreiben.