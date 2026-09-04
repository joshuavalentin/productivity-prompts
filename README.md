# Productivity Prompts

Een persoonlijk productiviteitspromptsysteem voor ChatGPT dat taken, agenda, e-mail, GitHub en gesprekscontext combineert tot compacte, uitvoerbare overzichten.

## Versie

`0.1.1`

## Auteur

Joshua Valentin

## Licentie

Proprietary / geen openbare licentie. Alle rechten voorbehouden.

## Kernprincipe

**Eén overzicht, niet één rapport per app.**

De bronapplicaties blijven de bron van waarheid. Deze prompts orkestreren, interpreteren, prioriteren en vatten informatie uit gekoppelde diensten samen.

## Primaire commando's

| Commando | Doel |
| --- | --- |
| `vandaag` | Toon wat vandaag belangrijk is uit alle beschikbare bronnen. |
| `deze-week` | Toon relevante verplichtingen, deadlines en focus voor de huidige week. |
| `dag-plannen` | Zet de verplichtingen van vandaag om in een realistische uitvoervolgorde. |
| `openstaande-zaken` | Vind onafgeronde verplichtingen, openstaande reacties en onopgelost werk. |
| `inbox` | Triage van actiegerichte items uit taken, e-mail en werkinboxen. |
| `weekevaluatie` | Evalueer de afgelopen week en bereid de volgende voor. |

De eerdere Engelse commando's blijven als aliases beschikbaar voor achterwaartse compatibiliteit.

## Bronnen

- Todoist — taken en taakdeadlines
- Google Calendar — afspraken en tijdsverplichtingen
- Gmail — communicatie en opvolging
- GitHub — ontwikkelwerk en issuestatus
- ChatGPT-context — relevante context uit het huidige gesprek wanneer beschikbaar

Todoist wordt uitsluitend als databron gebruikt. Taken worden als gewone tekst/Markdown weergegeven, niet als inline Todoist-venster of embedded interface.

## Structuur

- `contracts/` — gedeelde gedrags-, prioriterings-, bron- en veiligheidsregels
- `daily/` — dagelijkse overzichten en planningsworkflows
- `weekly/` — weekoverzichten en evaluatieworkflows
- `tasks/` — taaktriage en prioriteringsworkflows
- `calendar/` — agenda- en vergaderworkflows
- `communication/` — inbox- en opvolgingsworkflows
- `work/` — GitHub- en ontwikkelfocusworkflows
- `prompts.json` — canoniek commandoregister en resolver

## Gebruik

Vraag ChatGPT direct om een commando, bijvoorbeeld:

```text
vandaag
```

of:

```text
openstaande-zaken
```

De prompt laadt de gedeelde contracten, bevraagt de beschikbare gekoppelde bronnen die relevant zijn, voegt overlappende informatie samen en geeft één compact overzicht terug.

## Wijzigingsbeleid

Versie `0.1.1` is analysis-first. Lezen en samenvatten mag vrij. Wijzig Todoist, Gmail, Calendar, GitHub of een andere gekoppelde dienst nooit zonder expliciete opdracht van de gebruiker en alleen wanneer de wijziging veilig wordt ondersteund.
