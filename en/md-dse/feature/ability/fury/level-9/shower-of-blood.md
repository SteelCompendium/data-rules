---
action_type: Main action
class: fury
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: Melee 1
effect: Each enemy within 5 squares of you is distracted until the end of the round. While a creature is distracted this way, they can't take triggered actions or free triggered actions, ability rolls made against them gain an edge, and their characteristic scores are considered 1 lower for the purpose of resisting potencies.
feature_type: ability
file_basename: shower-of-blood
file_dpath: feature/ability/fury/level-9
flavor: You shock your foes with the brutality of your strike, resetting the balance of combat.
item_id: shower-of-blood
item_name: Shower of Blood
keywords:
    - Melee
    - Strike
    - Weapon
level: "9"
name: Shower of Blood
power_roll_characteristic: Might
scc: mcdm.heroes.v1/feature.ability.fury.level-9/shower-of-blood
source: mcdm.heroes.v1
target: One creature
tier1: 12 + M damage
tier2: 18 + M damage
tier3: 24 + M damage
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: Melee 1
effects:
    - effect: Each enemy within 5 squares of you is distracted until the end of the round. While a creature is distracted this way, they can't take triggered actions or free triggered actions, ability rolls made against them gain an edge, and their characteristic scores are considered 1 lower for the purpose of resisting potencies.
    - roll: Power Roll + Might
      tier1: 12 + M damage
      tier2: 18 + M damage
      tier3: 24 + M damage
feature_type: ability
flavor: You shock your foes with the brutality of your strike, resetting the balance of combat.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 11 Ferocity
    distance: Melee 1
    effect: Each enemy within 5 squares of you is distracted until the end of the round. While a creature is distracted this way, they can't take triggered actions or free triggered actions, ability rolls made against them gain an edge, and their characteristic scores are considered 1 lower for the purpose of resisting potencies.
    flavor: You shock your foes with the brutality of your strike, resetting the balance of combat.
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "9"
    name: Shower of Blood
    power_roll_characteristic: Might
    scc: mcdm.heroes.v1/feature.ability.fury.level-9/shower-of-blood
    target: One creature
    tier1: 12 + M damage
    tier2: 18 + M damage
    tier3: 24 + M damage
    type: ability
name: Shower of Blood
target: One creature
type: feature
usage: Main action
```
