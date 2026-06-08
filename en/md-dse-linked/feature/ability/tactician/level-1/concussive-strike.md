---
action_type: Main action
class: tactician
cost: 3 Focus
cost_amount: "3"
cost_resource: Focus
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
feature_type: ability
file_basename: concussive-strike
file_dpath: feature/ability/tactician/level-1
flavor: Your precise strike leaves your foe struggling to respond.
item_id: concussive-strike
item_name: Concussive Strike
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Concussive Strike
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/concussive-strike
source: mcdm.heroes.v1
target: One creature or object
type: ability
---

```ds-feature
cost: 3 Focus
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - effect: "\n*Your precise strike leaves your foe struggling to respond.*\n\n| **[Melee](../../../../rule/combat/melee.md), [Ranged](../../../../rule/combat/ranged.md), [Strike](../../../../rule/combat/strike.md), Weapon** |               **Main action** |\n|-----------------------------------|------------------------------:|\n| **\U0001F4CF [Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5**        | **\U0001F3AF One creature or object** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Might](../../../../rule/character/might.md):**\n\n- **≤11:** 3 + M damage; M < WEAK, [dazed](../../../../condition/dazed.md) (save ends)\n- **12-16:** 5 + M damage; M < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)\n- **17+:** 8 + M damage; M < STRONG, [dazed](../../../../condition/dazed.md) (save ends)"
feature_type: ability
flavor: Your precise strike leaves your foe struggling to respond.
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
    flavor: Your precise strike leaves your foe struggling to respond.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Concussive Strike
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/concussive-strike
    target: One creature or object
    type: ability
name: Concussive Strike
target: One creature or object
type: feature
usage: Main action
```
