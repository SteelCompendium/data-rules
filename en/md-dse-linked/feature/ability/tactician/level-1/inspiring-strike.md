---
action_type: Main action
class: tactician
cost: 3 Focus
cost_amount: "3"
cost_resource: Focus
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
feature_type: ability
file_basename: inspiring-strike
file_dpath: feature/ability/tactician/level-1
flavor: Your attack gives an ally hope.
item_id: inspiring-strike
item_name: Inspiring Strike
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
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
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - effect: "\n*Your attack gives an ally hope.*\n\n| **[Melee](../../../../rule/combat/melee.md), [Ranged](../../../../rule/combat/ranged.md), [Strike](../../../../rule/combat/strike.md), Weapon** |               **Main action** |\n|-----------------------------------|------------------------------:|\n| **\U0001F4CF [Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5**        | **\U0001F3AF One creature or object** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Might](../../../../rule/character/might.md):**\n\n- **≤11:** 3 + M damage; you or one ally within 10 squares of you can spend a [Recovery](../../../../rule/health/recoveries.md)\n- **12-16:** 5 + M damage; you or one ally within 10 squares of you can spend a [Recovery](../../../../rule/health/recoveries.md)\n- **17+:** 8 + M damage; you and one ally within 10 squares of you can spend a [Recovery](../../../../rule/health/recoveries.md), and each of you gains an [edge](../../../../rule/dice/edge.md) on the next [ability roll](../../../../rule/dice/ability-roll.md) you make during the encounter"
feature_type: ability
flavor: Your attack gives an ally hope.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: tactician
    cost: 3 Focus
    distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
    flavor: Your attack gives an ally hope.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
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
