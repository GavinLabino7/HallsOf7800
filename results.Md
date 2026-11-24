## Initial Baseline 

## index.html
instructions - 30%
Branhes - 20%
Lines - 30%
Methods - 37%
Classes - 66%

## Coverage by subsystem
world: Line - 74% Branch - 54%
util: Line - 83% Branch - 63%
effect: Line - 60% Branch - 38%
progression: Line - 48% Branch - 18%
gen: Line - 50% Branch - 40%
entity: Line - 41% Branch - 8%
combat: Line - 35% Branch - 14%
engine: Line - 30% Branch - 16%
persist: Line - 23% Branch - 14%
quest: Line - 21% Branch - 7%
ui: Line - 0% Branch - 0%
app: Line - 0% Branch - 0%
ui.audio: Line - 0% Branch - 0%

## Risks and weaknesses
- Core commands throwCommand, dropCommand, pickupCommand, stairsCommand, closerdoorCommand, wandzapper, and examiner have zero test coverage
- Continue can restore an incorrect position
- 5 bugs listed in bugs.md are present
- overall low branch coverage
- no enforced coverage threshold in pom.xml
