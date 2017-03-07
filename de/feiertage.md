# Feiertage

Bei der Anlage von Abwesenheitsereignissen wird Rücksicht auf die Wochenarbeitstage des Mitarbeiters und die
 [Feiertage][1] der Firma genommen. Diese Ereignisse werden nur an Arbeitstagen angelegt, die keine Feiertage
 sind. Dies hat insbesondere Auswirkung auf den Verbrauch der Jahresurlaubstage eines Mitarbeiters.

![Feiertage][img-holiday-list]

## Feiertage anlegen

Es ist möglich Feiertage manuell anzulegen. Für die Anlage von Feiertagen wählen Sie den Link
 [Feiertag anlegen][6] . Im Formular geben Sie den Tag und eine Bezeichnung für den Feiertag ein.

Sie können für ein Datum nur einen Feiertag anlegen.

## Feiertage importieren

Feiertage lassen sich von einer Datei im [iCal Format][2] (.ics) oder von einer URL importieren.

> Beispielhaft für einen URL-Import sei hier der Webdienst [ifeiertage.de][3] genannt. Von dort können Sie
 beispielsweise eine Feiertags-URL für Ihr Bundesland erhalten. Diese tragen Sie bei mitarbeiterbereich ein.

![Feiertage importieren][img-holiday-import-file]

Beim Import müssen Sie die Zeitspanne des Importes angeben. Das verwendete iCal Format bietet die Möglichkeit
 Wiederholungstermine abzubilden. Diese Wiederholungen werden beim Import in mitarbeiterbereich zu konkreten
 Einzelterminen innerhalb der angegebenen Zeitspanne aufgelöst.

Ein Import kann jederzeit wiederholt werden. Bei jedem Import werden bestehende Einträge nicht verändert,
 sondern nur neue ergänzt. Falls Sie händisch bestimmte Einträge gelöscht haben, werden diese nach dem nächsten
 Import von der gleichen Quelle wieder vorhanden sein.

Diese Funktion ist nur Premium-Kunden zugänglich.

## Feiertage löschen

Feiertage können einzeln gelöscht werden. Dafür befindet sich neben jedem Feiertag ein Button zum *Löschen*.

![Feiertage löschen][img-holiday-delete]

----
#### Quicklinks
> <i class="fa fa-book fa-fw"></i> [Feiertage][1]

> <i class="fa fa-book fa-fw"></i> [Feiertag anlegen][6]

> <i class="fa fa-globe fa-fw"></i> Wikipedia [iCal Format][2]

> <i class="fa fa-globe fa-fw"></i> [ifeiertage.de][3] <small>mitarbeiterbereich hat keinerlei Einfluss auf oder Abhängigkeit zu ifeiertage.de</small>

> <i class="fa fa-book fa-fw"></i> [Ereignis anlegen][4]

> <i class="fa fa-book fa-fw"></i> [Premiumfunktionen][5]

> <i class="fa fa-picture-o fa-fw"></i> [Feiertage][img-holiday-list]

> <i class="fa fa-picture-o fa-fw"></i> [Feiertage importieren][img-holiday-import-file]

> <i class="fa fa-picture-o fa-fw"></i> [Feiertage löschen][img-holiday-delete]

[1]: https://www.mitarbeiterbereich.de/holidays
[2]: http://de.wikipedia.org/wiki/ICalendar
[3]: http://www.ifeiertage.de/
[4]: ./ereignisse.md
[5]: ./premium.md
[6]: https://www.mitarbeiterbereich.de/holidays/create
[img-holiday-list]: ./images/mb_holiday_list_manager_1024x3643.png "Feiertage"
[img-holiday-import-file]: ./images/mb_import_file_manager_1024x702.png "Feiertage importieren"
[img-holiday-delete]: ./images/mb_holiday_delete_confirm_1024x702.png "Feiertage löschen"