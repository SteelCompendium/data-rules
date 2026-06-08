---
action_type: Main action
class: censor
cost: 3 Wrath
cost_amount: "3"
cost_resource: Wrath
distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: repent
file_dpath: feature/ability/censor/level-1
flavor: You conjure memories of their sins to harry your foes.
item_id: repent
item_name: Repent!
keywords:
    - Magic
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Repent!
scc: mcdm.heroes.v1/feature.ability.censor.level-1/repent
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 3 Wrath
distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: "\n*You conjure memories of their sins to harry your foes.*\n\n| **Magic, [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc:mcdm.heroes.v1/rule.combat/strike)**  |    **Main action**  |\n|----------------------------|--------------------:|\n| **\U0001F4CF [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10**           | **\U0001F3AF One creature** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Presence](scc:mcdm.heroes.v1/rule.character/presence):**\n\n- **≤11:** 5 + P holy damage; I < WEAK, [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)\n- **12-16:** 8 + P holy damage; I < AVERAGE, [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)\n- **17+:** 11 + P holy damage; I < STRONG, [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)"
feature_type: ability
flavor: You conjure memories of their sins to harry your foes.
keywords:
    - Magic
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: censor
    cost: 3 Wrath
    distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: You conjure memories of their sins to harry your foes.
    keywords:
        - Magic
        - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Repent!
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/repent
    target: One creature
    type: ability
name: Repent!
target: One creature
type: feature
usage: Main action
```
