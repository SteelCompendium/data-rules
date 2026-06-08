---
action_type: Main action
class: talent
cost: 5 Clarity
cost_amount: "5"
cost_resource: Clarity
distance: 1 [burst](../../../../rule/combat/burst.md)
feature_type: ability
file_basename: gravitic-burst
file_dpath: feature/ability/talent/level-2
flavor: Everyone get away from me!
item_id: gravitic-burst
item_name: Gravitic Burst
keywords:
    - Area
    - Psionic
    - Telekinesis
level: "2"
name: Gravitic Burst
scc: mcdm.heroes.v1/feature.ability.talent.level-2/gravitic-burst
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 5 Clarity
distance: 1 [burst](../../../../rule/combat/burst.md)
effects:
    - effect: "\n*Everyone get away from me!*\n\n| **Area, Psionic, Telekinesis** |               **Main action** |\n|--------------------------------|------------------------------:|\n| **\U0001F4CF 1 [burst](../../../../rule/combat/burst.md)**                 | **\U0001F3AF Each enemy in the area** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Reason](../../../../rule/character/reason.md):**\n\n- **≤11:** 3 damage; vertical push 2\n- **12-16:** 6 damage; vertical push 4\n- **17+:** 9 damage; vertical push 6\n\n**Strained:** The size of the [burst](../../../../rule/combat/burst.md) increases by 1, and you are [weakened](../../../../condition/weakened.md) until the end of your turn."
feature_type: ability
flavor: Everyone get away from me!
keywords:
    - Area
    - Psionic
    - Telekinesis
metadata:
    action_type: Main action
    class: talent
    cost: 5 Clarity
    distance: 1 [burst](../../../../rule/combat/burst.md)
    flavor: Everyone get away from me!
    keywords:
        - Area
        - Psionic
        - Telekinesis
    level: "2"
    name: Gravitic Burst
    scc: mcdm.heroes.v1/feature.ability.talent.level-2/gravitic-burst
    target: Each enemy in the area
    type: ability
name: Gravitic Burst
target: Each enemy in the area
type: feature
usage: Main action
```
