---
action_type: Main action
class: censor
cost: 5 Wrath
cost_amount: "5"
cost_resource: Wrath
distance: Melee 1
effect: If the target makes a strike against a creature while [grabbed](../../../../condition/grabbed.md) this way, you can spend 3 wrath to deal holy damage to them equal to your Presence score, then change the target of the strike to another target within the strike's distance.
feature_type: ability
file_basename: arrest
file_dpath: feature/ability/censor/level-1
flavor: '"I got you, you son of a bitch."'
item_id: arrest
item_name: Arrest
keywords:
    - Magic
    - Melee
    - Strike
    - Weapon
level: "1"
name: Arrest
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.censor.level-1/arrest
source: mcdm.heroes.v1
target: One creature
tier1: 6 + M holy damage; [grabbed](../../../../condition/grabbed.md)
tier2: 9 + M holy damage; [grabbed](../../../../condition/grabbed.md)
tier3: 13 + M holy damage; [grabbed](../../../../condition/grabbed.md)
type: ability
---

```ds-feature
cost: 5 Wrath
distance: Melee 1
effects:
    - effect: If the target makes a strike against a creature while [grabbed](../../../../condition/grabbed.md) this way, you can spend 3 wrath to deal holy damage to them equal to your Presence score, then change the target of the strike to another target within the strike's distance.
    - roll: Power Roll + Might
      tier1: 6 + M holy damage; [grabbed](../../../../condition/grabbed.md)
      tier2: 9 + M holy damage; [grabbed](../../../../condition/grabbed.md)
      tier3: 13 + M holy damage; [grabbed](../../../../condition/grabbed.md)
feature_type: ability
flavor: '"I got you, you son of a bitch."'
keywords:
    - Magic
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: censor
    cost: 5 Wrath
    distance: Melee 1
    effect: If the target makes a strike against a creature while [grabbed](../../../../condition/grabbed.md) this way, you can spend 3 wrath to deal holy damage to them equal to your Presence score, then change the target of the strike to another target within the strike's distance.
    flavor: '"I got you, you son of a bitch."'
    keywords:
        - Magic
        - Melee
        - Strike
        - Weapon
    level: "1"
    name: Arrest
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/arrest
    target: One creature
    tier1: 6 + M holy damage; [grabbed](../../../../condition/grabbed.md)
    tier2: 9 + M holy damage; [grabbed](../../../../condition/grabbed.md)
    tier3: 13 + M holy damage; [grabbed](../../../../condition/grabbed.md)
    type: ability
name: Arrest
target: One creature
type: feature
usage: Main action
```
