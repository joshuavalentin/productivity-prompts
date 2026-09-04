# Dag plannen

Los deze workflow op via `prompts.json` in de root en laad vóór uitvoering alle vereiste gedeelde contracten.

## Doel

Zet de afspraken en verplichtingen van vandaag om in een realistische uitvoervolgorde.

## Workflow

1. Bepaal indien nodig de huidige lokale datum en tijd.
2. Haal de vaste kalenderafspraken van vandaag op.
3. Haal relevante Todoist-taken, achterstallig werk en actief werk met hoge prioriteit op.
4. Haal alleen actiegerichte communicatie en blokkerend GitHub-werk op wanneer dit de volgorde kan beïnvloeden.
5. Bepaal de volgorde op basis van bekende deadlines, afhankelijkheden, vergadervoorbereiding en kosten van contextwisselingen. Verzin geen tijdsduur als die onbekend is.
6. Bescherm vaste kalenderafspraken.
7. Adviseer één primaire focus en een klein aantal secundaire acties.
8. Als het werk niet in de beschikbare tijd past, benoem wat moet worden uitgesteld.

## Standaarduitvoer

- `Begin met` — de eerste concrete actie.
- `Uitvoervolgorde` — korte geordende lijst.
- `Vaste agenda` — de niet-verplaatsbare kalenderitems van vandaag.
- `Verplaatsen/uitstellen` — alleen wanneer nodig.
- `Reden` — één of twee korte zinnen die de volgorde verklaren.

## Regels

- Deze opdracht plant; hij wijzigt Todoist of Calendar niet uit zichzelf.
- Rond actief werk bij voorkeur af voordat optioneel nieuw werk wordt gestart.
- Vul niet ieder vrij uur tenzij de gebruiker expliciet om timeblocking vraagt.
- Houd het plan realistisch en compact.
