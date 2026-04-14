---
action_type: Triggered
class: tactician
distance: Melee 2
effect: You can shift 1 square. If the target is you, or if you end this shift adjacent to the target, the target takes half the damage. If the damage has any potency effect associated with it, the potency is decreased by 1.
feature_type: ability
file_basename: parry
file_dpath: feature/ability/tactician/level-1
flavor: Your quick reflexes cost an enemy the precision they seek.
item_id: parry
item_name: Parry
keywords:
    - Melee
    - Weapon
level: "1"
name: Parry
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/parry
source: mcdm.heroes.v1
spend: '1 Focus: This ability''s distance becomes Melee 1 + your Reason score, and you can shift up to a number of squares equal to your Reason score instead of 1 square.'
subtype: triggered
target: Self or one ally
trigger: A creature deals damage to the target.
type: ability
---

```ds-feature
distance: Melee 2
effects:
    - effect: You can shift 1 square. If the target is you, or if you end this shift adjacent to the target, the target takes half the damage. If the damage has any potency effect associated with it, the potency is decreased by 1.
    - effect: '1 Focus: This ability''s distance becomes Melee 1 + your Reason score, and you can shift up to a number of squares equal to your Reason score instead of 1 square.'
      name: Spend
feature_type: ability
flavor: Your quick reflexes cost an enemy the precision they seek.
keywords:
    - Melee
    - Weapon
metadata:
    action_type: Triggered
    class: tactician
    distance: Melee 2
    effect: You can shift 1 square. If the target is you, or if you end this shift adjacent to the target, the target takes half the damage. If the damage has any potency effect associated with it, the potency is decreased by 1.
    flavor: Your quick reflexes cost an enemy the precision they seek.
    keywords:
        - Melee
        - Weapon
    level: "1"
    name: Parry
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/parry
    spend: '1 Focus: This ability''s distance becomes Melee 1 + your Reason score, and you can shift up to a number of squares equal to your Reason score instead of 1 square.'
    subtype: triggered
    target: Self or one ally
    trigger: A creature deals damage to the target.
    type: ability
name: Parry
target: Self or one ally
trigger: A creature deals damage to the target.
type: feature
usage: Triggered
```
