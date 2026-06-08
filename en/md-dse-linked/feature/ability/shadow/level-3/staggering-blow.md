---
action_type: Main action
class: shadow
cost: 7 Insight
cost_amount: "7"
cost_resource: Insight
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
feature_type: ability
file_basename: staggering-blow
file_dpath: feature/ability/shadow/level-3
flavor: There's no recovering from this.
item_id: staggering-blow
item_name: Staggering Blow
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "3"
name: Staggering Blow
scc: mcdm.heroes.v1/feature.ability.shadow.level-3/staggering-blow
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 7 Insight
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - effect: "\n*There's no recovering from this.*\n\n| **[Melee](../../../../rule/combat/melee.md), [Ranged](../../../../rule/combat/ranged.md), [Strike](../../../../rule/combat/strike.md), Weapon** |     **Main action** |\n|-----------------------------------|--------------------:|\n| **\U0001F4CF [Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5**        | **\U0001F3AF One creature** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Agility](../../../../rule/character/agility.md):**\n\n- **≤11:** 7 + A damage; M < WEAK, [slowed](../../../../condition/slowed.md) (save ends)\n- **12-16:** 11 + A damage; M < AVERAGE, [prone and](../../../../condition/prone.md) can't stand (save ends)\n- **17+:** 16 + A damage; M < STRONG, [prone and](../../../../condition/prone.md) can't stand (save ends)"
feature_type: ability
flavor: There's no recovering from this.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 7 Insight
    distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
    flavor: There's no recovering from this.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "3"
    name: Staggering Blow
    scc: mcdm.heroes.v1/feature.ability.shadow.level-3/staggering-blow
    target: One creature
    type: ability
name: Staggering Blow
target: One creature
type: feature
usage: Main action
```
