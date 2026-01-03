# Kassenbuch-Vorlage

Dieses Repository enthält eine Excel-Vorlage (`kassenbuch_vorlage.xlsx`) und eine begleitende Anleitung zur Verwendung der Datei als digitales Kassenbuch.
Die Anleitung ist in dieser README.md beschrieben und mit beispielhaften Darstellungen illustriert.

## Inhalt der Vorlage

Die Vorlage besteht aus dreizehn Tabellenblättern:
- einer **Jahresübersicht**
- zwölf identisch aufgebauten **Monatsblättern** (Januar–Dezember)

## Jahresübersicht

Das Jahresübersichtsblatt fasst alle monatlichen Kassenbewegungen zusammen.
Es zeigt oben die Gesamt‑Einnahmen, Gesamt‑Ausgaben und den daraus abgeleiteten Jahres‑Saldo.

Darunter werden alle Monate tabellarisch aufgeführt mit folgenden Spalten:

| Spalte | Bedeutung |
|------|----------|
| Anfangsbestand | Übertrag aus Vorjahr bzw. Vormonat |
| Einnahmen | Summe der monatlichen Einnahmen |
| Ausgaben | Summe der monatlichen Ausgaben |
| Saldo | Einnahmen − Ausgaben |
| Endbestand | Anfangsbestand + Einnahmen − Ausgaben |
| Ø Ausgaben (Tag) | Durchschnittliche Tagesausgaben |
| Hinweis | z.B. `#DIV/0!` bei Division durch 0 |

## Monatsblätter

Jedes Monatsblatt dient zur Erfassung der täglichen Einnahmen und Ausgaben.
Der Aufbau ist für alle Monate identisch.

### Berechnung des Bestands

- Anfangsbestand in **C5**
- Laufender Bestand ab Zeile 6:

```
=C5 + A6 - B6
```

## Verwendung

1. Excel-Datei öffnen
2. Anfangsbestand eintragen
3. Einnahmen und Ausgaben erfassen
4. Summen prüfen
5. Jahresübersicht auswerten
