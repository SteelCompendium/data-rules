---
action_type: Main action
class: conduit
distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: Choose yourself or one ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance). That character can impose a [bane](scc:mcdm.heroes.v1/rule.dice/bane) on one [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll) made against them before the end of their next [turn](scc:mcdm.heroes.v1/rule.combat/turn).
feature_type: ability
file_basename: sacrificial-offer
file_dpath: feature/ability/conduit/level-1
flavor: Divine magic tears at your foe and defends a nearby friend.
item_id: sacrificial-offer
item_name: Sacrificial Offer
keywords:
    - Magic
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Sacrificial Offer
power_roll_characteristic: '[Intuition](scc:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/sacrificial-offer
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 2 + I corruption damage
tier2: 4 + I corruption damage
tier3: 6 + I corruption damage
type: ability
---

```ds-feature
distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: Choose yourself or one ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance). That character can impose a [bane](scc:mcdm.heroes.v1/rule.dice/bane) on one [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll) made against them before the end of their next [turn](scc:mcdm.heroes.v1/rule.combat/turn).
    - roll: Power Roll + [Intuition](scc:mcdm.heroes.v1/rule.character/intuition)
      tier1: 2 + I corruption damage
      tier2: 4 + I corruption damage
      tier3: 6 + I corruption damage
feature_type: ability
flavor: Divine magic tears at your foe and defends a nearby friend.
keywords:
    - Magic
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: conduit
    distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: Choose yourself or one ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance). That character can impose a [bane](scc:mcdm.heroes.v1/rule.dice/bane) on one [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll) made against them before the end of their next [turn](scc:mcdm.heroes.v1/rule.combat/turn).
    flavor: Divine magic tears at your foe and defends a nearby friend.
    keywords:
        - Magic
        - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Sacrificial Offer
    power_roll_characteristic: '[Intuition](scc:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/sacrificial-offer
    subtype: signature
    target: One creature
    tier1: 2 + I corruption damage
    tier2: 4 + I corruption damage
    tier3: 6 + I corruption damage
    type: ability
name: Sacrificial Offer
target: One creature
type: feature
usage: Main action
```
