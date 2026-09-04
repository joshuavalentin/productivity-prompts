# Vandaag

Los deze workflow op via `prompts.json` in de root en laad vóór uitvoering alle vereiste gedeelde contracten.

## Doel

Maak één beknopt en uitvoerbaar overzicht van wat vandaag belangrijk is uit alle relevante gekoppelde productiviteitsbronnen.

## Bronnen

Gebruik de relevante beschikbare bronnen, normaal gesproken:

- Todoist voor taken en deadlines;
- Google Calendar voor afspraken van vandaag en tijdsbeperkingen;
- Gmail voor communicatie die daadwerkelijk actie vereist of tijdkritisch is;
- GitHub voor actief ontwikkelwerk, toegewezen/openstaande issues en recent actief werk wanneer relevant;
- relevante ChatGPT-context voor afspraken of werk dat expliciet in het huidige gesprek is vastgesteld.

Vraag een bron niet op om alleen een sectie te vullen. Gebruik een bron alleen wanneer die de prioriteiten van vandaag materieel kan veranderen.

## Workflow

1. Bepaal indien nodig de lokale datum en huidige tijd van de gebruiker.
2. Haal de kalenderafspraken van vandaag op en identificeer vaste tijdsblokken.
3. Haal taken op die vandaag aflopen, achterstallige taken en actieve taken met hoge prioriteit.
4. Identificeer e-mailthreads die vandaag actie vereisen of een andere afspraak blokkeren. Behandel ongelezen niet automatisch als belangrijk.
5. Identificeer actief GitHub-werk dat in uitvoering, deadlinegebonden, blokkerend of direct relevant is voor het werk van vandaag.
6. Voeg duplicaten tussen bronnen samen.
7. Classificeer items als uitvoerbaar werk, wachten, vaste afspraken of optioneel/backlogwerk.
8. Prioriteer met `contracts/PRIORITIZATION.md`.
9. Geef één compact overzicht terug, niet één rapport per bron.

## Standaarduitvoer

- `Moet` — normaal maximaal drie items;
- `Daarna` — nuttig werk na Moet;
- `Agenda` — vaste afspraken en relevante voorbereidingsblokken;
- `Wachten` — alleen als iets belangrijks afhankelijk is van een andere persoon of systeem;
- `Aandacht` — conflicten, achterstallige risico's, deadlines of belangrijke onbeantwoorde opvolging;
- `Focus` — één beknopte aanbeveling voor wat als eerste te doen.

Laat lege secties weg.

## Regels

- Maak onderscheid tussen feiten en aanbevelingen.
- Verzin nooit taakprioriteit, deadlines, vergaderdetails of e-mailurgentie.
- Houd optionele ideeën en verre backlog buiten `Moet`, tenzij de gebruiker ze expliciet naar voren haalt.
- Als de dag te vol is, benoem wat moet verschuiven in plaats van te doen alsof alles past.
- Als een relevante bron niet beschikbaar is, ga door met de beschikbare gegevens en vermeld de ontbrekende bron kort.
