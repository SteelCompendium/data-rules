---
action_type: Main action
class: shadow
cost: 5 Insight
cost_amount: "5"
cost_resource: Insight
distance: Melee 1 or ranged 5
feature_type: ability
file_basename: coup-de-grace
file_dpath: feature/ability/shadow/level-1
flavor: Your blade might be the last thing they see.
item_id: coup-de-grace
item_name: Coup de Grace
keywords:
    - Melee
    - Ranged
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Coup de Grace
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/coup-de-grace
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 5 Insight
distance: Melee 1 or ranged 5
effects:
    - effect: "\n*Your blade might be the last thing they see.*\n\n| **Melee, Ranged, [Strike](../../../../rule/combat/strike.md), Weapon** |     **Main action** |\n|-----------------------------------|--------------------:|\n| **\U0001F4CF Melee 1 or ranged 5**        | **\U0001F3AF One creature** |\n\n**Power Roll + [Agility](../../../../rule/character/agility.md):**\n\n- **≤11:** 2d6 + 7 + A damage\n- **12-16:** 2d6 + 11 + A damage\n- **17+:** 2d6 + 16 + A damage"
feature_type: ability
flavor: Your blade might be the last thing they see.
keywords:
    - Melee
    - Ranged
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 5 Insight
    distance: Melee 1 or ranged 5
    flavor: Your blade might be the last thing they see.
    keywords:
        - Melee
        - Ranged
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Coup de Grace
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/coup-de-grace
    target: One creature
    type: ability
name: Coup de Grace
target: One creature
type: feature
usage: Main action
```
