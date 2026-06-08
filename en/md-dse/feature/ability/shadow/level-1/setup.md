---
action_type: Main action
class: shadow
cost: 5 Insight
cost_amount: "5"
cost_resource: Insight
distance: Ranged 5
feature_type: ability
file_basename: setup
file_dpath: feature/ability/shadow/level-1
flavor: Your friends will thank you.
item_id: setup
item_name: Setup
keywords:
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Setup
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/setup
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 5 Insight
distance: Ranged 5
effects:
    - effect: "\n*Your friends will thank you.*\n\n| **Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |\n|----------------------------|--------------------:|\n| **\U0001F4CF Ranged 5**            | **\U0001F3AF One creature** |\n\n**Power Roll + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 6 + A damage; R < WEAK, the target has [damage weakness](scc:mcdm.heroes.v1/rule.damage/damage-weakness) 5 (save ends)\n- **12-16:** 9 + A damage; R < AVERAGE, the target has [damage weakness](scc:mcdm.heroes.v1/rule.damage/damage-weakness) 5 (save ends)\n- **17+:** 13 + A damage; R < STRONG, the target has [damage weakness](scc:mcdm.heroes.v1/rule.damage/damage-weakness) 5 (save ends)"
feature_type: ability
flavor: Your friends will thank you.
keywords:
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 5 Insight
    distance: Ranged 5
    flavor: Your friends will thank you.
    keywords:
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Setup
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/setup
    target: One creature
    type: ability
name: Setup
target: One creature
type: feature
usage: Main action
```
