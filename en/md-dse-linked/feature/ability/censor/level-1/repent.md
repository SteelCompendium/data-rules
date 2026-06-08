---
action_type: Main action
class: censor
cost: 3 Wrath
cost_amount: "3"
cost_resource: Wrath
distance: Ranged 10
feature_type: ability
file_basename: repent
file_dpath: feature/ability/censor/level-1
flavor: You conjure memories of their sins to harry your foes.
item_id: repent
item_name: Repent!
keywords:
    - Magic
    - Ranged
    - '[Strike](../../../../rule/combat/strike.md)'
level: "1"
name: Repent!
scc: mcdm.heroes.v1/feature.ability.censor.level-1/repent
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 3 Wrath
distance: Ranged 10
effects:
    - effect: "\n*You conjure memories of their sins to harry your foes.*\n\n| **Magic, Ranged, [Strike](../../../../rule/combat/strike.md)**  |    **Main action**  |\n|----------------------------|--------------------:|\n| **\U0001F4CF Ranged 10**           | **\U0001F3AF One creature** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Presence](../../../../rule/character/presence.md):**\n\n- **≤11:** 5 + P holy damage; I < WEAK, [dazed](../../../../condition/dazed.md) (save ends)\n- **12-16:** 8 + P holy damage; I < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)\n- **17+:** 11 + P holy damage; I < STRONG, [dazed](../../../../condition/dazed.md) (save ends)"
feature_type: ability
flavor: You conjure memories of their sins to harry your foes.
keywords:
    - Magic
    - Ranged
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: Main action
    class: censor
    cost: 3 Wrath
    distance: Ranged 10
    flavor: You conjure memories of their sins to harry your foes.
    keywords:
        - Magic
        - Ranged
        - '[Strike](../../../../rule/combat/strike.md)'
    level: "1"
    name: Repent!
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/repent
    target: One creature
    type: ability
name: Repent!
target: One creature
type: feature
usage: Main action
```
