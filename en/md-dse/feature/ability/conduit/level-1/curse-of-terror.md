---
action_type: Main action
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: Ranged 10
feature_type: ability
file_basename: curse-of-terror
file_dpath: feature/ability/conduit/level-1
flavor: Fear of divine judgment overwhelms your foe.
item_id: curse-of-terror
item_name: Curse of Terror
keywords:
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Curse of Terror
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/curse-of-terror
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 5 Piety
distance: Ranged 10
effects:
    - effect: "\n*Fear of divine judgment overwhelms your foe.*\n\n| **Magic, Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike)**  |                      **Main action** |\n|----------------------------|-------------------------------------:|\n| **\U0001F4CF Ranged 10**           |                  **\U0001F3AF One creature** |\n\n**Power Roll + [Intuition](scc:mcdm.heroes.v1/rule.character/intuition):**\n\n- **≤11:** 6 + I holy damage; I < WEAK, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)\n- **12-16:** 9 + I holy damage; I < AVERAGE, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)\n- **17+:** 13 + I holy damage; I < STRONG, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)"
feature_type: ability
flavor: Fear of divine judgment overwhelms your foe.
keywords:
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: conduit
    cost: 5 Piety
    distance: Ranged 10
    flavor: Fear of divine judgment overwhelms your foe.
    keywords:
        - Magic
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Curse of Terror
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/curse-of-terror
    target: One creature
    type: ability
name: Curse of Terror
target: One creature
type: feature
usage: Main action
```
