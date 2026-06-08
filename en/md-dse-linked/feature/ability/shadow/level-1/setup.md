---
action_type: Main action
class: shadow
cost: 5 Insight
cost_amount: "5"
cost_resource: Insight
distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
feature_type: ability
file_basename: setup
file_dpath: feature/ability/shadow/level-1
flavor: Your friends will thank you.
item_id: setup
item_name: Setup
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
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
distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - effect: "\n*Your friends will thank you.*\n\n| **[Ranged](../../../../rule/combat/ranged.md), [Strike](../../../../rule/combat/strike.md), Weapon** |     **Main action** |\n|----------------------------|--------------------:|\n| **\U0001F4CF [Ranged](../../../../rule/combat/ranged.md) 5**            | **\U0001F3AF One creature** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Agility](../../../../rule/character/agility.md):**\n\n- **≤11:** 6 + A damage; R < WEAK, the target has [damage weakness](../../../../rule/damage/damage-weakness.md) 5 (save ends)\n- **12-16:** 9 + A damage; R < AVERAGE, the target has [damage weakness](../../../../rule/damage/damage-weakness.md) 5 (save ends)\n- **17+:** 13 + A damage; R < STRONG, the target has [damage weakness](../../../../rule/damage/damage-weakness.md) 5 (save ends)"
feature_type: ability
flavor: Your friends will thank you.
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 5 Insight
    distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
    flavor: Your friends will thank you.
    keywords:
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
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
