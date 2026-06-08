---
action_type: Main action
class: elementalist
cost: 5 Essence
cost_amount: "5"
cost_resource: Essence
distance: Ranged 10
feature_type: ability
file_basename: volcanos-embrace
file_dpath: feature/ability/elementalist/level-2
flavor: Wrap them up in fire and melting stone.
item_id: volcanos-embrace
item_name: Volcano's Embrace
keywords:
    - Earth
    - Fire
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
level: "2"
name: Volcano's Embrace
scc: mcdm.heroes.v1/feature.ability.elementalist.level-2/volcanos-embrace
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 5 Essence
distance: Ranged 10
effects:
    - effect: "\n*Wrap them up in fire and melting stone.*\n\n| **Earth, Fire, Magic, Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike)** |     **Main action** |\n|----------------------------------------|--------------------:|\n| **\U0001F4CF Ranged 10**                       | **\U0001F3AF One creature** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Reason](scc:mcdm.heroes.v1/rule.character/reason):**\n\n- **≤11:** 5 + R fire damage; A < WEAK, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)\n- **12-16:** 9 + R fire damage; A < AVERAGE, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)\n- **17+:** 12 + R fire damage; A < STRONG, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)"
feature_type: ability
flavor: Wrap them up in fire and melting stone.
keywords:
    - Earth
    - Fire
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: elementalist
    cost: 5 Essence
    distance: Ranged 10
    flavor: Wrap them up in fire and melting stone.
    keywords:
        - Earth
        - Fire
        - Magic
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    level: "2"
    name: Volcano's Embrace
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-2/volcanos-embrace
    target: One creature
    type: ability
name: Volcano's Embrace
target: One creature
type: feature
usage: Main action
```
