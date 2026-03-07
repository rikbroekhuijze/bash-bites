# bash-bites 🍪

Kleine, leesbare Bash-snippets die het leven makkelijker maken. 
Geen cryptische one-liners, maar begrijpelijke tools voor normale mensen.

> Vervang teksten in strings OF bestanden met één simpel commando.
> `cat bestand.txt | REPLACE zoekwoord vervanging`

## Waarom bash-bites?

- **Leesbaar** - Geen regex-rage, gewoon functies die doen wat ze beloven
- **Leerzaam** - Snap je code, word een betere bash-schrijver
- **Gratis & Open** - MIT gelicenseerd, altijd

## Voorbeelden

```bash
# Vervang "wereld" door "iedereen" in een string
REPLACE "Hallo wereld" wereld iedereen

# Vervang "oud" door "nieuw" in een bestand (via pipe)
cat document.txt | REPLACE oud nieuw

# Meerdere regels tegelijk vervangen
cat mijn_levensverhaal.txt | REPLACE 'Deze hier is punk
en anarchist' 'Deze hier heeft een baantje
en hij vist'

# Nog meer snippets volgen snel...
