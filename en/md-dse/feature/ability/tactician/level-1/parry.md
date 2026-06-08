---
action_type: Triggered
class: tactician
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2'
effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) 1 square. If the target is you, or if you end this [shift](scc:mcdm.heroes.v1/movement/shifting) [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to the target, the target takes half the damage. If the damage has any [potency](scc:mcdm.heroes.v1/rule.character/potency) effect associated with it, the [potency](scc:mcdm.heroes.v1/rule.character/potency) is decreased by 1.
feature_type: ability
file_basename: parry
file_dpath: feature/ability/tactician/level-1
flavor: Your quick reflexes cost an enemy the precision they seek.
item_id: parry
item_name: Parry
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
level: "1"
name: Parry
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/parry
source: mcdm.heroes.v1
spend: '1 Focus: This ability''s [distance](scc:mcdm.heroes.v1/rule.combat/distance) becomes [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1 + your [Reason](scc:mcdm.heroes.v1/rule.character/reason) score, and you can [shift](scc:mcdm.heroes.v1/movement/shifting) up to a number of squares equal to your [Reason](scc:mcdm.heroes.v1/rule.character/reason) score instead of 1 square.'
subtype: triggered
target: Self or one ally
trigger: A creature deals damage to the target.
type: ability
---

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2'
effects:
    - effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) 1 square. If the target is you, or if you end this [shift](scc:mcdm.heroes.v1/movement/shifting) [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to the target, the target takes half the damage. If the damage has any [potency](scc:mcdm.heroes.v1/rule.character/potency) effect associated with it, the [potency](scc:mcdm.heroes.v1/rule.character/potency) is decreased by 1.
    - effect: '1 Focus: This ability''s [distance](scc:mcdm.heroes.v1/rule.combat/distance) becomes [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1 + your [Reason](scc:mcdm.heroes.v1/rule.character/reason) score, and you can [shift](scc:mcdm.heroes.v1/movement/shifting) up to a number of squares equal to your [Reason](scc:mcdm.heroes.v1/rule.character/reason) score instead of 1 square.'
      name: Spend
feature_type: ability
flavor: Your quick reflexes cost an enemy the precision they seek.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
metadata:
    action_type: Triggered
    class: tactician
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2'
    effect: You can [shift](scc:mcdm.heroes.v1/movement/shifting) 1 square. If the target is you, or if you end this [shift](scc:mcdm.heroes.v1/movement/shifting) [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to the target, the target takes half the damage. If the damage has any [potency](scc:mcdm.heroes.v1/rule.character/potency) effect associated with it, the [potency](scc:mcdm.heroes.v1/rule.character/potency) is decreased by 1.
    flavor: Your quick reflexes cost an enemy the precision they seek.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - Weapon
    level: "1"
    name: Parry
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/parry
    spend: '1 Focus: This ability''s [distance](scc:mcdm.heroes.v1/rule.combat/distance) becomes [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1 + your [Reason](scc:mcdm.heroes.v1/rule.character/reason) score, and you can [shift](scc:mcdm.heroes.v1/movement/shifting) up to a number of squares equal to your [Reason](scc:mcdm.heroes.v1/rule.character/reason) score instead of 1 square.'
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
