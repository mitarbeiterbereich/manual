# Kalenderexporte

Kalenderexporte dienen der Nutzung der Abwesenheitsdaten in anderen Kalender-Applikationen. Dies sind bspw.
 Google Kalender, Microsoft Exchange, Microsoft Outlook oder Thunderbird mit Sunbird Erweiterung.
> <i class="fa fa-exclamation-triangle fa-fw text-warning"></i> Die Einbindung eines externen Kalenders entnehmen
 Sie bitte der Dokumentation der verwendeten Software.

Es wird ein Kalender im [iCal Format][3] (.ics) erstellt.

![Exportkalender][img-export-list]

### Kalender anlegen / bearbeiten

Für einen Exportkalender wird ein Name und die Informationstiefe angegeben. Die Informationstiefe wurde aus
 datenschutzrelevanten Gründen eingeführt.

Daneben können alle oder einzelne Mitarbeiter gewählt werden. Daraufhin werden alle Abwesenheiten der gewählten
 Mitarbeiter angezeigt.

Im dritten Bereich können ergänzend Organisationseinheiten gewählt werden. Alle Mitarbeiter, die diesen
 Einheiten zugeordnet sind werden für den Kalenderexport abgefragt, dynamisch. Dies ermöglicht dynamische Kalender
 für Projekte, Standorte oder Abteilungen.


#### Informationsgrade

1. Alle Details

	Mitarbeitername und Abwesenheitstyp wird angezeigt

2. keine Abwesenheitstypen

	Nur der Mitarbeitername wird angezeigt und als abwesend deklariert

3. nur Statusinformationen

	Es wird lediglich angezeigt, wie viele Mitarbeiter abwesend sind, keine Namen oder Abwesenheitstypen


### Kalender verwenden

In der [Liste aller Exportkalender][1] können Sie die URL des Kalenders kopieren. Falls Sie den [Google
 Kalender][4] verwenden, so klicken Sie den entsprechenden *Button* in der Liste. Daraufhin öffnet sich Google
 Kalender mit dem Kalender importieren Dialog.


#### Aktualisierung des Kalenders

Der Kalender liefert bei jedem Zugriff den aktuellen Stand aller freigegebenen Abwesenheiten zum Zeitpunkt
 des Abrufes.

#### Besonderheit Google Kalender

Beachten Sie, dass wir keinen Einfluss auf den Abruf durch den Google Kalender haben. Erfahrungsgemäß fragt
 Google mindestens 4mal täglich nach Aktualisierungen. Lediglich neu importierte Kalender werden umgehend
 abgerufen. Neu bestätigte Abwesenheiten sind nicht sofort im Google Kalender ersichtlich. Bitte prüfen
 Sie es später erneut.


----
#### Quicklinks
> <i class="fa fa-calendar fa-fw"></i> [Kalenderexporte][1]

> <i class="fa fa-plus fa-fw"></i> [Kalenderexport anlegen][2]

> <i class="fa fa-globe fa-fw"></i> Wikipedia [iCal Format][3]

> <i class="fa fa-globe fa-fw"></i> [Google Kalender][4]

[1]: https://www.mitarbeiterbereich.de/exports
[2]: https://www.mitarbeiterbereich.de/exports/create
[3]: http://de.wikipedia.org/wiki/ICalendar
[4]: https://www.google.com/calendar
[img-export-list]: ./images/mb_export_list_manager_1024x702.png "Exportkalender"