---
action_type: Triggered
class: conduit
distance: Ranged 10
effect: The power roll gains an [edge](../../../../rule/dice/edge.md).
feature_type: ability
file_basename: word-of-guidance
file_dpath: feature/ability/conduit/level-1
flavor: You invigorate an attacking ally with divine energy.
item_id: word-of-guidance
item_name: Word of Guidance
keywords:
    - Magic
    - Ranged
level: "1"
name: Word of Guidance
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/word-of-guidance
source: mcdm.heroes.v1
spend: '1 Piety: The power roll has a double [edge](../../../../rule/dice/edge.md).'
subtype: triggered
target: One ally
trigger: The target makes an ability roll for a damage-dealing ability.
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: The power roll gains an [edge](../../../../rule/dice/edge.md).
    - effect: '1 Piety: The power roll has a double [edge](../../../../rule/dice/edge.md).'
      name: Spend
feature_type: ability
flavor: You invigorate an attacking ally with divine energy.
keywords:
    - Magic
    - Ranged
metadata:
    action_type: Triggered
    class: conduit
    distance: Ranged 10
    effect: The power roll gains an [edge](../../../../rule/dice/edge.md).
    flavor: You invigorate an attacking ally with divine energy.
    keywords:
        - Magic
        - Ranged
    level: "1"
    name: Word of Guidance
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/word-of-guidance
    spend: '1 Piety: The power roll has a double [edge](../../../../rule/dice/edge.md).'
    subtype: triggered
    target: One ally
    trigger: The target makes an ability roll for a damage-dealing ability.
    type: ability
name: Word of Guidance
target: One ally
trigger: The target makes an ability roll for a damage-dealing ability.
type: feature
usage: Triggered
```
