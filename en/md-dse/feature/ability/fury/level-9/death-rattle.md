---
action_type: Main action
class: fury
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: 3 burst
feature_type: ability
file_basename: death-rattle
file_dpath: feature/ability/fury/level-9
flavor: You unleash an otherworldly cry that rips through your enemies, killing the weakest of them.
item_id: death-rattle
item_name: Death Rattle
keywords:
    - Area
    - Magic
level: "9"
name: Death Rattle
scc: mcdm.heroes.v1/feature.ability.fury.level-9/death-rattle
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: 3 burst
effects:
    - effect: "\n*You unleash an otherworldly cry that rips through your enemies, killing the weakest of them.*\n\n| **Area, Magic** |               **Main action** |\n|-----------------|------------------------------:|\n| **\U0001F4CF 3 burst**  | **\U0001F3AF Each enemy in the area** |\n\n**Power Roll + [Might](scc:mcdm.heroes.v1/rule.character/might):**\n\n- **≤11:** 4 psychic damage; any target who is a minion is reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina)\n- **12-16:** 6 psychic damage; any target who is a minion is reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina), as does one [winded](scc:mcdm.heroes.v1/rule.health/winded) target who is not a leader or solo creature\n- **17+:** 10 psychic damage; each target who is not a leader or solo creature is [winded](scc:mcdm.heroes.v1/rule.health/winded); any target who is a minion is reduced to 0 [Stamina](scc:mcdm.heroes.v1/rule.health/stamina), as does one [winded](scc:mcdm.heroes.v1/rule.health/winded) target who is not a leader or solo creature"
feature_type: ability
flavor: You unleash an otherworldly cry that rips through your enemies, killing the weakest of them.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: fury
    cost: 11 Ferocity
    distance: 3 burst
    flavor: You unleash an otherworldly cry that rips through your enemies, killing the weakest of them.
    keywords:
        - Area
        - Magic
    level: "9"
    name: Death Rattle
    scc: mcdm.heroes.v1/feature.ability.fury.level-9/death-rattle
    target: Each enemy in the area
    type: ability
name: Death Rattle
target: Each enemy in the area
type: feature
usage: Main action
```
