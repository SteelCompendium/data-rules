---
action_type: Main action
class: conduit
cost: 3 Piety
cost_amount: "3"
cost_resource: Piety
distance: Ranged 10
feature_type: ability
file_basename: judgments-hammer
file_dpath: feature/ability/conduit/level-1
flavor: Your divine [fury](scc:mcdm.heroes.v1/class/fury) is a hammer that crashes down upon the unrighteous.
item_id: judgments-hammer
item_name: Judgment's Hammer
keywords:
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Judgment's Hammer
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/judgments-hammer
source: mcdm.heroes.v1
target: One creature or object
type: ability
---

```ds-feature
cost: 3 Piety
distance: Ranged 10
effects:
    - effect: "\n*Your divine [fury](scc:mcdm.heroes.v1/class/fury) is a hammer that crashes down upon the unrighteous.*\n\n| **Magic, Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike)**  |               **Main action** |\n|----------------------------|------------------------------:|\n| **\U0001F4CF Ranged 10**           | **\U0001F3AF One creature or object** |\n\n**Power Roll + [Intuition](scc:mcdm.heroes.v1/rule.character/intuition):**\n\n- **≤11:** 3 + I holy damage; A < WEAK[, prone](scc:mcdm.heroes.v1/condition/prone)\n- **12-16:** 6 + I holy damage; A < AVERAGE[, prone](scc:mcdm.heroes.v1/condition/prone)\n- **17+:** 9 + I holy damage; A < STRONG, [prone and](scc:mcdm.heroes.v1/condition/prone) can't stand (save ends)"
feature_type: ability
flavor: Your divine [fury](scc:mcdm.heroes.v1/class/fury) is a hammer that crashes down upon the unrighteous.
keywords:
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: conduit
    cost: 3 Piety
    distance: Ranged 10
    flavor: Your divine [fury](scc:mcdm.heroes.v1/class/fury) is a hammer that crashes down upon the unrighteous.
    keywords:
        - Magic
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Judgment's Hammer
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/judgments-hammer
    target: One creature or object
    type: ability
name: Judgment's Hammer
target: One creature or object
type: feature
usage: Main action
```
