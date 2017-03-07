# Mitarbeiter

## Anlegen eines Mitarbeiters

Beim [Anlegen eines Mitarbeiters][1] werden diverse Werte zur Person abgefragt. Neben dem Namen wird
die Personalnummer, seine organisatorische Rolle im Unternehmen und seine Arbeitsvertragsdaten abgefragt.

![Mitarbeiter anlegen][img-employee-create]

Für den Zugang zu mitarbeiterbereich können Sie auch Zugangsdaten anlegen.


### Arbeitsvertragsdaten

#### Personalnummer

Die Personalnummer wird für verschiedene Zwecke verwendet. Sie wird bspw. auf den Urlaubsantrag
geschrieben für die Akten.


#### Organisatorische Rolle im Unternehmen

Die Rolle *Personalverwalter* hat auch entsprechende Berechtigungen in mitarbeiterbereich zur Folge.
Es werden alle Informationen von anderen Mitarbeitern sichtbar. Wollen Sie dies vermeiden, vergeben
Sie lediglich die Rolle *Mitarbeiter*.


#### Arbeitsbeginn und -ende

Mit diesen Werten legen Sie fest, ob der Mitarbeiter schon, bzw. noch aktuell in der Firma tätig ist.
Dies hat bspw. Auswirkungen auf die Tagsübersicht im [Dashboard][2] oder beim Anlegen einer Abwesenheit.


#### Organisationseinheiten

Ein großer Vorteil bietet die freie Vergabe von Organisationseinheiten. Sie ermöglichen eine Einordnung
eines Mitarbeiters in Abteilungen, Projekte, Standorte oder ähnliche Kategorien.

Bei den [Kalenderexporten][3] kann gezielt auf Organisationseinheiten gefiltert werden. Dadurch werden
Standortkalender oder Projektkalender möglich, die nicht mit dem Wechsel von Mitarbeitern aktualisiert
werden müssen, da sie [dynamisch][4] sind.


#### Urlaubstage

Abhängig der Firmenzugehörigkeit (Arbeitsbeginn und -ende) werden hier für jedes Jahr die Urlaubstage
angegeben. Bei der Änderung der Firmenzugehörigkeit müssen Sie einmal zwischenspeichern damit die
verfügbaren Jahre für die Urlaubstage angezeigt werden.

Bei der Anlage einer Abwesenheit, die *Urlaubstage reduziert*, werden die Urlaubstage passend zu den
Jahresurlaubstagen abgezogen.


#### Arbeitstage

Die Wochenarbeitstage werden hier festgelegt. Sie werden für die Darstellung der anwesenden Mitarbeiter
auf dem [Dashboard][5] genutzt.


### Zugangsdaten

#### E-Mail

Soll der Mitarbeiter Zugriff auf sein Profil und seine Daten in mitarbeiterbereich erhalten, geben Sie
hier bitte seine E-Mail-Adresse ein. Daraufhin wird der Mitarbeiter per E-Mail von mitarbeiterbereich
aufgefordert sich bei mitarbeiterbereich einzuloggen.


#### Berechtigung

Sie können dem eingeladenen Mitarbeiter auch die Berechtigung eines Firmenverwalters geben. Es muss
mindestens einen Firmenverwalter geben, deshalb lässt sich der letzte Firmenverwalter nicht wieder
löschen. Dazu muss zuvor ein anderer Mitarbeiter mit Zugang diese Berechtigung erhalten.

Mehr dazu finden Sie im Thema [Rollen im System][6].


----
#### Quicklinks
> <i class="fa fa-plus fa-fw"></i> [Mitarbeiter anlegen][1]

> <i class="fa fa-dashboard fa-fw"></i> [Dashboard][2]

> <i class="fa fa-calendar fa-fw"></i> [Kalenderexporte][3]

> <i class="fa fa-book fa-fw"></i> [Kalenderexporte][4]

> <i class="fa fa-book fa-fw"></i> [Dashboard][5]

> <i class="fa fa-question fa-fw"></i> [Rollen im System][6]

[1]: https://www.mitarbeiterbereich.de/employee/create
[2]: https://www.mitarbeiterbereich.de/dashboard
[3]: https://www.mitarbeiterbereich.de/exports
[4]: ./kalenderexporte.md
[5]: ./dashboard.md
[6]: /docs/faq/rollen-im-system
[img-employee-create]: ./images/mb_employee_create_1024x732.png "Mitarbeiter anlegen"