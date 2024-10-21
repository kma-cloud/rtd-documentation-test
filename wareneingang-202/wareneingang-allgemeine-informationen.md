---
description: Allgemeine Informationen zum Wareneingang
---

# Wareneingang - Allgemeine Informationen

Beim Wareneingang werden die angelieferten Waren in PROLAG Word erfasst (vereinnahmt) und nach zuvor getroffenen Vorgaben eingelagert. Der Einlagerungsprozess besteht grundsätzlich aus: Warenerfassung (I-Punkt/automatisierte Vereinnahmung): hier wird pro erfasster Ware automatisch eine Bestelleingangsposition angelegt (sowohl geplante als auch ungeplante Einlagerung, s. u.) Buchung der Bewegung (am mobilen Gerät, am Browser oder automatisch über die geplante Aktion und Transport der Waren zum Zielort

Es wird zwischen einer geplanten und einer ungeplanten Einlagerung unterschieden:&#x20;

**a) geplant**&#x20;

{% hint style="info" %}
Es liegt eine Bestellung in PROLAG World vor. Die zu vereinnahmende Ware wird über die in der Bestellung vorhandenen Bestellpositionen vorgegeben. Eine Bestellposition kann in Wareneingangspositionen (z. B. haben die Waren einer Bestellposition unterschiedliche Warenmerkmale wie Chargen oder MHD) unterteilt werden. Eine Bestellung kann entweder in PROLAG World manuell über die Maske WE-Büro (Wareneingangsbüro) angelegt oder durch ein Hostsystem übermittelt werden. Weitere Informationen s. Allgemeines zur Avis-Verwaltung.&#x20;
{% endhint %}

**b) ungeplant**

{% hint style="info" %}
Es liegt keine Bestellung in PROLAG World vor. Die zu vereinnahmende Ware wird über den Artikelstamm (z. B. Auswählen oder Scannen der Artikelnummern oder GTIN) durch den Mitarbeitenden am Wareneingang gewählt.
{% endhint %}

## Verwendung

Die Warenerfassung kann am I-Punkt (Identifikations-Punkt) oder über automatisierte Vereinnahmung erfolgen.

1. I -Punkt - geplant oder ungeplant
    + Die Einlagerung über PROLAG World findet am am I-Punkt (Identifikations-Punkt) statt, entweder am
      browserbasierten (geplant oder ungeplant) oder am PROLAG Go I-Punkt (geplant oder ungeplant).
    + Die Einlagerung am I-Punkt besteht aus folgenden Aktionen:
    + Warenerfassung
    + Zielort im Lager bestimmen: Ortsvorschlag durch PROLAG World oder manuelle Ortsauswahl
    + Bestätigung des Zielortes
    + Buchung und Transport der Ware zum Zielort im Lager**
2. Automatisierte Vereinnahmung
    + Die automatisierte Vereinnahmung steht nur für geplante Einlagerungen zur Verfügung. Eine Bestellung kann in
      PROLAG World automatisiert vereinnahmt werden, sofern alle benötigten Informationen vorliegen. (s. u.
      Konfiguration - Artikelstamm). Die automatisierte Vereinnahmung besteht aus folgenden Aktionen:
      Warenerfassung in der jeweiligen Maske "...automatisiert vereinnahmen": Bestellung, Bestellposition,
      Wareneingangsposition am Browser (nicht am mobilen Gerät verfügbar korrekt?)
    + Buchung und Transport der Ware zum Zielort im Lager

### **Beispiel**:

> Ein Artikel 20001 (Standardmenge 50 Stück im Artikelstamm gepflegt) wird geplant angeliefert. Die Bestellmenge beträgt
> 150 Stück.
>> 1. Eine Bestellposition: 150 Stück
>>2. Zwei Wareneingangspositionen:
>>+ 50 Stück (Warenmerkmal MHD 30.05.XXXX)
>>+ 100 Stück (Warenmerkmal MHD 30.10.XXXX)
>>
>>Die Bestellung wird am geplanten I-Punkt vereinnahmt. Es soll die im Artikelstamm festgelegte Standardmenge von 50
> > Stück pro Transport-Lagerhilfsmittel eingelagert werden.
> > Bei der Vereinnahmung entstehen drei Bestelleingangspositionen:
> > 3a 50 Stück (Warenmerkmal MHD 30.05.XXXX)
> > 3b 50 Stück (Warenmerkmal MHD 30.10.XXXX)
> > 3c 50 Stück (Warenmerkmal MHD 30.10.XXXX)
> > Die Ware wird zum Zielort gebracht. Die Einlagerung ist abgeschlossen. Die Bestelleingangspositionen in PROLAG World
> > werden automatisch gelöscht.