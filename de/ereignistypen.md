# Ereignistypen

Jedes Ereignis ist typisiert. Der Typ gibt bspw. an, ob ein Mitarbeiter bei diesem Ereignis abwesend ist oder es wird
geregelt, dass automatisch bei Anlage eines konkreten Ereignisses auch ein PDF-Dokument erzeugt wird.

![Ereignistypen][img-types-thumb]

## Systemvorgaben

Für die meisten Anwendungsfälle gibt es bereits vom System vorgegebene Ereignistypen. Diese sind:

 * Urlaub (vacation)
 * Überstunden (overtime)
 * Krankheit (disease)
 * Schulung (training)
 * Sonderurlaub (special_leave)
 * Home Office (home_office)

Tipp: Verwenden Sie die englische Bezeichung in Klammern. Diese Werte werden automatisch in alle unterstützten Sprachen übersetzt.

## Farbgebung

Für die Darstellung eines Ereignisses im [Kalender][3] wird die Farbgebung des Typs benutzt. Systemvorgaben können Sie
nicht verändern. Eigene Ereignistypen sollten sich farblich an artverwandten Systemvorgaben orientieren. Das vereinfacht
die Erfassung von vielen Ereignisse im [Kalender][3].


## Eigenschaften eines Ereignistyps

Folgende Eigenschaften kann für jeden Typ gewählt werden:

 * Bedeutet das Ereignis eine Abwesenheit
 * Bedeutet das Ereignis reduziert die Jahresurlaubstage eines Mitarbeiters
 * Kann ein Mitarbeiter diesen Ereignistyp selber wählen oder kann nur ein Personalverantwortlicher diesen Typ für Mitarbeiter vergeben
 * Benötigt dieses Ereignis eine Freigabe durch einen Personalverantwortlichen
 * Wird ein PDF Dokument als Beleg für diese Abwesenheit benötigt
 * Soll ein Personalverantwortlicher informiert werden, wenn ein Ereignis diesen Typs von einem Mitarbeiter erstellt wird


## Ereignistyp erstellen

Für eigene Bedürfnisse können Sie eigene Ereignistypen erstellen.

![Ereignistyp erstellen][img-types-create-thumb]

Unter [Ereignistypen][1] können Sie eine Liste der vorhandenen Ereignistypen sehen.

### Step-by-Step
1. Aktion [Ereignistyp erstellen][2] klicken
2. Farbe wählen, wenn der Vorschlag nicht zusagt
3. Namen des Typs eingeben
4. Eigenschaften des Typs auswählen
5. Ereignistyp anlegen
6. Fertig


## Ereignistyp bearbeiten

In der Liste der [Ereignistypen][1] gibt es zu jedem Ereignistyp einen Button zum *Bearbeiten*. Dort erhalten Sie
 die gleichen Möglichkeiten wie beim Anlegen eines Ereignistyps.

![Ereignistyp bearbeiten][img-types-edit-thumb]

## Ereignistyp löschen

Es können nur Ereignistypen gelöscht werden, die nicht verwendet werden.

Zum Löschen gehen Sie zunächst zum Bearbeiten eines Ereignistyps und wählen innerhalb des dargestellten
 Formulars den Button zum *Löschen*. Nach erfolgter Löschbestätigung sehen Sie wieder die Liste der
 [Ereignistypen][1].


----
#### Quicklinks
> <i class="fa fa-flag-o fa-fw"></i> [Ereignistypen][1]

> <i class="fa fa-calendar fa-fw"></i> [Kalender][3]

> <i class="fa fa-plus fa-fw"></i> [Ereignistyp erstellen][2]

> <i class="fa fa-picture-o fa-fw"></i> [Ereignistypen][img-types]

> <i class="fa fa-picture-o fa-fw"></i> [Ereignistyp erstellen][img-types-create]

> <i class="fa fa-picture-o fa-fw"></i> [Ereignistyp bearbeiten][img-types-edit]

[1]: /event-types
[2]: /event-types/create
[3]: /calendar
[img-types-thumb]: /images/screenshots/mb_types_manager_1024x565.png "Ereignistypen"
[img-types]: /images/screenshots/mb_types_manager_1024x702.png "Ereignistypen"
[img-types-create-thumb]: /images/screenshots/mb_types_create_manager_1024x565.png "Ereignistyp erstellen"
[img-types-create]: /images/screenshots/mb_types_create_manager_1024x702.png "Ereignistyp erstellen"
[img-types-edit-thumb]: /images/screenshots/mb_types_edit_manager_1024x565.png "Ereignistyp bearbeiten"
[img-types-edit]: /images/screenshots/mb_types_edit_manager_1024x702.png "Ereignistyp bearbeiten"