---
action_type: Main action
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: Ranged 5
feature_type: ability
file_basename: blade-of-the-heavens
file_dpath: feature/ability/conduit/level-6
flavor: A greatsword streams down from the sky, threatening to pin your foe.
item_id: blade-of-the-heavens
item_name: Blade of the Heavens
keywords:
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
level: "6"
name: Blade of the Heavens
scc: mcdm.heroes.v1/feature.ability.conduit.level-6/blade-of-the-heavens
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 9 Piety
distance: Ranged 5
effects:
    - effect: "\n*A greatsword streams down from the sky, threatening to pin your foe.*\n\n| **Magic, Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike)**  |     **Main action** |\n|----------------------------|--------------------:|\n| **\U0001F4CF Ranged 5**            | **\U0001F3AF One creature** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Intuition](scc:mcdm.heroes.v1/rule.character/intuition):**\n\n- **≤11:** 8 + I damage; A < WEAK, [prone and](scc:mcdm.heroes.v1/condition/prone) [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)\n- **12-16:** 12 + I damage; A < AVERAGE, [prone and](scc:mcdm.heroes.v1/condition/prone) [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)\n- **17+:** 16 + I damage; A < STRONG, [prone and](scc:mcdm.heroes.v1/condition/prone) [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)"
feature_type: ability
flavor: A greatsword streams down from the sky, threatening to pin your foe.
keywords:
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: conduit
    cost: 9 Piety
    distance: Ranged 5
    flavor: A greatsword streams down from the sky, threatening to pin your foe.
    keywords:
        - Magic
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    level: "6"
    name: Blade of the Heavens
    scc: mcdm.heroes.v1/feature.ability.conduit.level-6/blade-of-the-heavens
    target: One creature
    type: ability
name: Blade of the Heavens
target: One creature
type: feature
usage: Main action
```
