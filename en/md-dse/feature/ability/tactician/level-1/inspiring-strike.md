---
action_type: Main action
class: tactician
cost: 3 Focus
cost_amount: "3"
cost_resource: Focus
distance: Melee 1 or ranged 5
feature_type: ability
file_basename: inspiring-strike
file_dpath: feature/ability/tactician/level-1
flavor: Your attack gives an ally hope.
item_id: inspiring-strike
item_name: Inspiring Strike
keywords:
    - Melee
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Inspiring Strike
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/inspiring-strike
source: mcdm.heroes.v1
target: One creature or object
type: ability
---

```ds-feature
cost: 3 Focus
distance: Melee 1 or ranged 5
effects:
    - effect: "\n*Your attack gives an ally hope.*\n\n| **Melee, Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |\n|-----------------------------------|------------------------------:|\n| **\U0001F4CF Melee 1 or ranged 5**        | **\U0001F3AF One creature or object** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might):**\n\n- **≤11:** 3 + M damage; you or one ally within 10 squares of you can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries)\n- **12-16:** 5 + M damage; you or one ally within 10 squares of you can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries)\n- **17+:** 8 + M damage; you and one ally within 10 squares of you can spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries), and each of you gains an [edge](scc:mcdm.heroes.v1/rule.dice/edge) on the next [ability roll](scc:mcdm.heroes.v1/rule.dice/ability-roll) you make during the encounter"
feature_type: ability
flavor: Your attack gives an ally hope.
keywords:
    - Melee
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: tactician
    cost: 3 Focus
    distance: Melee 1 or ranged 5
    flavor: Your attack gives an ally hope.
    keywords:
        - Melee
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Inspiring Strike
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/inspiring-strike
    target: One creature or object
    type: ability
name: Inspiring Strike
target: One creature or object
type: feature
usage: Main action
```
