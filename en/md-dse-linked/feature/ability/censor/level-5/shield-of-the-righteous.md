---
action_type: Main action
class: censor
cost: 9 Wrath
cost_amount: "9"
cost_resource: Wrath
distance: '[Melee](../../../../rule/combat/melee.md) 1'
feature_type: ability
file_basename: shield-of-the-righteous
file_dpath: feature/ability/censor/level-5
flavor: You strike a foe and create a fleet of divine shields that protect your allies.
item_id: shield-of-the-righteous
item_name: Shield of the Righteous
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "5"
name: Shield of the Righteous
scc: mcdm.heroes.v1/feature.ability.censor.level-5/shield-of-the-righteous
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 9 Wrath
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: "\n*You strike a foe and create a fleet of divine shields that protect your allies.*\n\n| **[Melee](../../../../rule/combat/melee.md), [Strike](../../../../rule/combat/strike.md), Weapon** |          **Main action** |\n|---------------------------|-------------------------:|\n| **\U0001F4CF [Melee](../../../../rule/combat/melee.md) 1**            |      **\U0001F3AF One creature** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Might](../../../../rule/character/might.md):**\n\n- **≤11:** 10 + M damage; you and each ally [adjacent](../../../../rule/combat/adjacent.md) to you gain 10 [temporary Stamina](../../../../rule/health/temporary-stamina.md)\n- **12-16:** 14 + M damage; you and each ally [adjacent](../../../../rule/combat/adjacent.md) to you gain 15 [temporary Stamina](../../../../rule/health/temporary-stamina.md)\n- **17+:** 20 + M damage; you and each ally [adjacent](../../../../rule/combat/adjacent.md) to you gain 20 [temporary Stamina](../../../../rule/health/temporary-stamina.md)"
feature_type: ability
flavor: You strike a foe and create a fleet of divine shields that protect your allies.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: censor
    cost: 9 Wrath
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    flavor: You strike a foe and create a fleet of divine shields that protect your allies.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "5"
    name: Shield of the Righteous
    scc: mcdm.heroes.v1/feature.ability.censor.level-5/shield-of-the-righteous
    target: One creature
    type: ability
name: Shield of the Righteous
target: One creature
type: feature
usage: Main action
```
