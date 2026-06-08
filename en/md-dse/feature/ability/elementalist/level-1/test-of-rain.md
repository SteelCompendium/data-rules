---
action_type: Main action
class: elementalist
cost: 5 Essence
cost_amount: "5"
cost_resource: Essence
distance: 3 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10
effect: You can end one effect on yourself that is ended by a [saving throw](scc:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of your [turn](scc:mcdm.heroes.v1/rule.combat/turn). Each ally in the area also gains this benefit.
feature_type: ability
file_basename: test-of-rain
file_dpath: feature/ability/elementalist/level-1
flavor: You call down a rain that burns your enemies and restores your allies.
item_id: test-of-rain
item_name: Test of Rain
keywords:
    - Area
    - Green
    - Magic
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Test of Rain
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/test-of-rain
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 5 Essence
distance: 3 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - effect: You can end one effect on yourself that is ended by a [saving throw](scc:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of your [turn](scc:mcdm.heroes.v1/rule.combat/turn). Each ally in the area also gains this benefit.
feature_type: ability
flavor: You call down a rain that burns your enemies and restores your allies.
keywords:
    - Area
    - Green
    - Magic
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Main action
    class: elementalist
    cost: 5 Essence
    distance: 3 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 10
    effect: You can end one effect on yourself that is ended by a [saving throw](scc:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of your [turn](scc:mcdm.heroes.v1/rule.combat/turn). Each ally in the area also gains this benefit.
    flavor: You call down a rain that burns your enemies and restores your allies.
    keywords:
        - Area
        - Green
        - Magic
        - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Test of Rain
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/test-of-rain
    target: Each enemy in the area
    type: ability
name: Test of Rain
target: Each enemy in the area
type: feature
usage: Main action
```
