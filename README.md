# DWDS-Wortschatz „Fußball“

## Publikation

https://www.dwds.de/fussball

## Datenmodell

In diesem Repositorium finden Sie das mit weiteren Informationen angereicherte DWDS-Themenglossar „Fußball“.

Das Glossar teilt sich auf in:

### Kategorien und Aspekte

**Kategorien** sind thematische Cluster, in die Einträge zuordnet werden können.

**Aspekte** sind Schlagworte zu konkrete Situationen, Abstrakta und Konkreta und ermöglichen eine genauere Zuordnung von Einträgen innerhalb der Fußballsprache.

Beide Formen bieten jeweils einen Zugang zu und eine nähere Bestimmung der einzelnen Begriffe.

Datenstruktur:

|Datenelement|Beschreibung|
|------------|------------|
|`/glossar/cluster/item`|Kategorie bzw. Aspekt|
|`item/@type`|Typ: `aspect` oder `category`
|`item/@xml:id`|ID zur Verknüpfung der Einträge|
|`item/title`|Titel|
|`item/desc`|Beschreibung|
|`item/figure[@ref]`|illustratives Bild (optional)|
|`item/item`|Unterelement (optional)|

### Die einzelnen Worteinträge

Die einzelnen Worteinträge enthalten Informationen, die nicht direkt aus dem DWDS-Wörterbuch extrahiert werden können. Das bedeutet: Informationen zur Wortart, Definitionen, diasystematische Markierungen (z. B. Sprachareale) etc. werden hier nicht kodiert, da diese jeweils in den einzelnen Wörterbucheinträgen im DWDS stehen.

|Datenelement|Beschreibung|
|------------|------------|
|`/glossar/entries/entry`|Worteintrag|
|`entry/@aspect`|Zuordnung zu Aspekten|
|`entry/@category`|Zuordnung zu Kategorien|
|`entry/form`|Schreibung|
|`entry/form/@hom`|Homografenindex (bei mehreren Wörtern gleicher Schreibung im DWDS)|
|`entry/ref[@type="kicktionary"]`|Verweis auf Eintrag im [Kicktionary](http://www.kicktionary.de/)|
|`entry/map`|Verweis auf Regionalkarte im DWDS|
|`entry/map/@corpus`|Korpus im DWDS: `regional` (Default) oder `webmonitor`|
|`entry/map/@query`|Korpusabfrage (falls abweichend von der Schreibung)|

## Abbildungen

Alle Abbildungen im Verzeichnis `img` wurden mit DALL·E 3 erstellt.

## Autor

DWDS, Digitales Wörterbuch der deutschen Sprache, www.dwds.de
