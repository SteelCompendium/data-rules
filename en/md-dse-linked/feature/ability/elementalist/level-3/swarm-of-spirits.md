---
action_type: Main action
class: elementalist
cost: 7 Essence
cost_amount: "7"
cost_resource: Essence
distance: 3 aura
effect: Until the end of your next turn, each ally in the area has each of their characteristic scores treated as 1 higher for the purpose of resisting potencies, and has a +1 bonus to saving throws.
feature_type: ability
file_basename: swarm-of-spirits
file_dpath: feature/ability/elementalist/level-3
flavor: Guardian animal spirits surround you to harry your foes and bolster your allies.
item_id: swarm-of-spirits
item_name: Swarm of Spirits
keywords:
    - Area
    - Green
    - Magic
level: "3"
name: Swarm of Spirits
power_roll_characteristic: Reason
scc: mcdm.heroes.v1/feature.ability.elementalist.level-3/swarm-of-spirits
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 3 damage
tier2: 6 damage
tier3: 9 damage
type: ability
---

```ds-feature
cost: 7 Essence
distance: 3 aura
effects:
    - effect: Until the end of your next turn, each ally in the area has each of their characteristic scores treated as 1 higher for the purpose of resisting potencies, and has a +1 bonus to saving throws.
    - roll: Power Roll + Reason
      tier1: 3 damage
      tier2: 6 damage
      tier3: 9 damage
feature_type: ability
flavor: Guardian animal spirits surround you to harry your foes and bolster your allies.
keywords:
    - Area
    - Green
    - Magic
metadata:
    action_type: Main action
    class: elementalist
    cost: 7 Essence
    distance: 3 aura
    effect: Until the end of your next turn, each ally in the area has each of their characteristic scores treated as 1 higher for the purpose of resisting potencies, and has a +1 bonus to saving throws.
    flavor: Guardian animal spirits surround you to harry your foes and bolster your allies.
    keywords:
        - Area
        - Green
        - Magic
    level: "3"
    name: Swarm of Spirits
    power_roll_characteristic: Reason
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-3/swarm-of-spirits
    target: Each enemy in the area
    tier1: 3 damage
    tier2: 6 damage
    tier3: 9 damage
    type: ability
name: Swarm of Spirits
target: Each enemy in the area
type: feature
usage: Main action
```
