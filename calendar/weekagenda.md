# Weekagenda

Los deze workflow op via `prompts.json` in de root en laad vóór uitvoering alle vereiste gedeelde contracten.

## Doel

Toon de kalenderafspraken van de huidige week in een compact en chronologisch overzicht.

## Workflow

1. Bepaal de lokale grenzen van de huidige week.
2. Haal Google Calendar-afspraken voor de week op.
3. Groepeer per dag en sorteer chronologisch.
4. Markeer overlap, ongewoon drukke dagen en relevante voorbereidingsbehoeften wanneer ondersteund door de gegevens.
5. Maak informatieve afspraken voor de hele dag visueel ondergeschikt aan afspraken met een tijd, tenzij ze actie beïnvloeden.

## Uitvoer

Gebruik één compacte sectie per dag met relevante afspraken. Sluit indien nuttig af met een korte observatie over de weekplanning.

## Regels

- Calendar is leidend voor afspraaktijden.
- Maak, verplaats of verwijder afspraken niet automatisch.
- Zet kalenderdrukte niet automatisch gelijk aan productiviteit.
