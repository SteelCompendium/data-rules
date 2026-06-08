---
action_type: Main action
class: shadow
cost: 7 Insight
cost_amount: "7"
cost_resource: Insight
distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 5'
feature_type: ability
file_basename: pinning-shot
file_dpath: feature/ability/shadow/level-3
flavor: One missile—placed well and placed hard.
item_id: pinning-shot
item_name: Pinning Shot
keywords:
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "3"
name: Pinning Shot
scc: mcdm.heroes.v1/feature.ability.shadow.level-3/pinning-shot
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 7 Insight
distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - effect: "\n*One missile—placed well and placed hard.*\n\n| **[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |\n|----------------------------|--------------------:|\n| **\U0001F4CF [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 5**            | **\U0001F3AF One creature** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 8 + A damage; A < WEAK, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)\n- **12-16:** 12 + A damage; A < AVERAGE, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)\n- **17+:** 16 + A damage; A < STRONG, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)"
feature_type: ability
flavor: One missile—placed well and placed hard.
keywords:
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 7 Insight
    distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 5'
    flavor: One missile—placed well and placed hard.
    keywords:
        - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "3"
    name: Pinning Shot
    scc: mcdm.heroes.v1/feature.ability.shadow.level-3/pinning-shot
    target: One creature
    type: ability
name: Pinning Shot
target: One creature
type: feature
usage: Main action
```
