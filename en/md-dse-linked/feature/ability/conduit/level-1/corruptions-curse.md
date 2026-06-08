---
action_type: Main action
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
feature_type: ability
file_basename: corruptions-curse
file_dpath: feature/ability/conduit/level-1
flavor: Cursed by you, your enemy takes more damage from your allies.
item_id: corruptions-curse
item_name: Corruption's Curse
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
level: "1"
name: Corruption's Curse
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/corruptions-curse
source: mcdm.heroes.v1
target: One creature or object
type: ability
---

```ds-feature
cost: 5 Piety
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: "\n*Cursed by you, your enemy takes more damage from your allies.*\n\n| **Magic, [Ranged](../../../../rule/combat/ranged.md), [Strike](../../../../rule/combat/strike.md)**  |               **Main action** |\n|----------------------------|------------------------------:|\n| **\U0001F4CF [Ranged](../../../../rule/combat/ranged.md) 10**           | **\U0001F3AF One creature or object** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Intuition](../../../../rule/character/intuition.md):**\n\n- **≤11:** 3 + I corruption damage; M < WEAK, [damage weakness](../../../../rule/damage/damage-weakness.md) 5 (save ends)\n- **12-16:** 6 + I corruption damage; M < AVERAGE, [damage weakness](../../../../rule/damage/damage-weakness.md) 5 (save ends)\n- **17+:** 9 + I corruption damage; M < STRONG, [damage weakness](../../../../rule/damage/damage-weakness.md) 5 (save ends)"
feature_type: ability
flavor: Cursed by you, your enemy takes more damage from your allies.
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: Main action
    class: conduit
    cost: 5 Piety
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    flavor: Cursed by you, your enemy takes more damage from your allies.
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
    level: "1"
    name: Corruption's Curse
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/corruptions-curse
    target: One creature or object
    type: ability
name: Corruption's Curse
target: One creature or object
type: feature
usage: Main action
```
