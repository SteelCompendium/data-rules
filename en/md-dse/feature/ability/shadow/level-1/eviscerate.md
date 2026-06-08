---
action_type: Main action
class: shadow
cost: 3 Insight
cost_amount: "3"
cost_resource: Insight
distance: Melee 1 or ranged 5
feature_type: ability
file_basename: eviscerate
file_dpath: feature/ability/shadow/level-1
flavor: You leave your foe bleeding out after a devastating attack.
item_id: eviscerate
item_name: Eviscerate
keywords:
    - Melee
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Eviscerate
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/eviscerate
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 3 Insight
distance: Melee 1 or ranged 5
effects:
    - effect: "\n*You leave your foe bleeding out after a devastating attack.*\n\n| **Melee, Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |\n|-----------------------------------|--------------------:|\n| **\U0001F4CF Melee 1 or ranged 5**        | **\U0001F3AF One creature** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 4 + A damage; A < WEAK, [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)\n- **12-16:** 6 + A damage; A < AVERAGE, [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)\n- **17+:** 10 + A damage; A < STRONG, [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)"
feature_type: ability
flavor: You leave your foe bleeding out after a devastating attack.
keywords:
    - Melee
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 3 Insight
    distance: Melee 1 or ranged 5
    flavor: You leave your foe bleeding out after a devastating attack.
    keywords:
        - Melee
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Eviscerate
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/eviscerate
    target: One creature
    type: ability
name: Eviscerate
target: One creature
type: feature
usage: Main action
```
