# AGENTS.md

## Project

Productivity Prompts is een zelfstandige promptrepository voor het orkestreren van persoonlijke productiviteitsdata uit gekoppelde diensten.

## Versie

Huidige basis: `0.1.1`.

## Repositoryprincipes

1. Houd prompts klein, combineerbaar en bronbewust.
2. Geef voorkeur aan één gecombineerd antwoord boven rapporten per app.
3. Behandel bronapplicaties als leidend voor hun eigen gegevens.
4. Verzin nooit niet-beschikbare taak-, e-mail-, kalender- of GitHub-data.
5. Benoem bronbeschikbaarheid of onzekerheid wanneer die het resultaat materieel beïnvloedt.
6. Voeg dezelfde verplichting samen wanneer die in meerdere bronnen voorkomt.
7. Scheid lees-/analysegedrag van wijzigingen.
8. Wijzig externe systemen niet zonder expliciete intentie van de gebruiker.
9. Houd gebruikersgerichte prompts, commando's en documentatie standaard in het Nederlands.
10. Behoud achterwaartse compatibiliteit via `prompts.json` wanneer workflows worden hernoemd.
11. Gebruik Todoist als databron en presenteer opgehaalde taken als tekst/Markdown; gebruik geen embedded of inline Todoist-interface als uitvoer.

## Promptontwerp

Iedere canonieke workflow moet:

- via `prompts.json` worden opgelost;
- alle vereiste gedeelde contracten laden;
- alleen bronnen opvragen die relevant zijn voor het doel;
- informatie eerst tussen bronnen synthetiseren en daarna presenteren;
- actiegerichte informatie boven volledigheid prioriteren;
- de standaarduitvoer compact en scanbaar houden;
- blokkades, deadlines, wachtstatussen en planningsconflicten benoemen wanneer relevant;
- voorkomen dat ideeën met lage waarde of backlog als urgent werk worden gepresenteerd.

## Gekoppelde diensten

De initiële bronnen zijn Todoist, Google Calendar, Gmail, GitHub en relevante ChatGPT-gesprekscontext. Later kunnen aanvullende bronnen via gedeelde contracten en resolvermetadata worden toegevoegd.

## Veiligheid en privacy

Persoonlijke productiviteitsdata kan privé- of gevoelige informatie bevatten. Haal alleen de minimaal relevante gegevens op, reproduceer berichtinhoud niet onnodig en geef voorkeur aan samenvattingen boven ruwe dumps. Wijzigingen moeten `contracts/ACTION-SAFETY.md` volgen.

## Versiebeheer

Gebruik semantic versioning. Werk `CHANGELOG.md` bij wanneer gedrag of commandocontracten materieel veranderen.
