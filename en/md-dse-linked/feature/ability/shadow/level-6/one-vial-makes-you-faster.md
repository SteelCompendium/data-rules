---
action_type: Main action
class: shadow
cost: 9 Insight
cost_amount: "9"
cost_resource: Insight
distance: Ranged 10
effect: You ready, hand, or lob a potion to each target, who can immediately quaff the potion (no action required). If they don't drink the potion right away, they must use the Use Consumable maneuver to consume it later. The potion loses its potency at the end of the encounter.
feature_type: ability
file_basename: one-vial-makes-you-faster
file_dpath: feature/ability/shadow/level-6
flavor: Each ally who catches a potion you throw can take the battle to the next level.
item_id: one-vial-makes-you-faster
item_name: One Vial Makes You Faster
keywords:
    - Ranged
level: "6"
name: One Vial Makes You Faster
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.shadow.level-6/one-vial-makes-you-faster
source: mcdm.heroes.v1
target: Three creatures
tier1: The creature's speed is increased by 2 until the end of the encounter.
tier2: The creature can [fly](scc:mcdm.heroes.v1/movement/fly) until the end of the encounter.
tier3: The creature turns invisible until the end of their next turn.
type: ability
---

```ds-feature
cost: 9 Insight
distance: Ranged 10
effects:
    - effect: You ready, hand, or lob a potion to each target, who can immediately quaff the potion (no action required). If they don't drink the potion right away, they must use the Use Consumable maneuver to consume it later. The potion loses its potency at the end of the encounter.
    - roll: Power Roll + Agility
      tier1: The creature's speed is increased by 2 until the end of the encounter.
      tier2: The creature can [fly](scc:mcdm.heroes.v1/movement/fly) until the end of the encounter.
      tier3: The creature turns invisible until the end of their next turn.
feature_type: ability
flavor: Each ally who catches a potion you throw can take the battle to the next level.
keywords:
    - Ranged
metadata:
    action_type: Main action
    class: shadow
    cost: 9 Insight
    distance: Ranged 10
    effect: You ready, hand, or lob a potion to each target, who can immediately quaff the potion (no action required). If they don't drink the potion right away, they must use the Use Consumable maneuver to consume it later. The potion loses its potency at the end of the encounter.
    flavor: Each ally who catches a potion you throw can take the battle to the next level.
    keywords:
        - Ranged
    level: "6"
    name: One Vial Makes You Faster
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.shadow.level-6/one-vial-makes-you-faster
    target: Three creatures
    tier1: The creature's speed is increased by 2 until the end of the encounter.
    tier2: The creature can [fly](scc:mcdm.heroes.v1/movement/fly) until the end of the encounter.
    tier3: The creature turns invisible until the end of their next turn.
    type: ability
name: One Vial Makes You Faster
target: Three creatures
type: feature
usage: Main action
```
