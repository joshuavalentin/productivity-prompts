# Inbox-overzicht

Los deze workflow op via `prompts.json` in de root en laad vóór uitvoering alle vereiste gedeelde contracten.

## Doel

Vat de e-mailinbox samen op basis van actiegerichtheid in plaats van het aantal ongelezen berichten.

## Workflow

1. Haal recente of relevante Gmail-threads op voor de gevraagde periode.
2. Identificeer berichten die een antwoord, beslissing, taak of bewustzijn op korte termijn vereisen.
3. Scheid berichten waarop de gebruiker kan handelen van threads die op een andere partij wachten.
4. Groepeer informatieve mail met lage waarde alleen apart wanneer dat nuttig is.
5. Vat iedere actiegerichte thread samen in één beknopte regel met afzender/context en volgende actie.

## Standaarduitvoer

- `Antwoord/actie nodig`
- `Wachten`
- `Ter info` — optioneel en compact
- `Eerste actie` — één aanbeveling

## Regels

- Ongelezen betekent niet automatisch belangrijk.
- Geef voorkeur aan samenvattingen per thread boven lijsten per bericht.
- Reproduceer geen privéberichtinhoud wanneer een samenvatting volstaat.
- Verstuur, archiveer, label of verwijder geen e-mail zonder expliciete instructie van de gebruiker.
