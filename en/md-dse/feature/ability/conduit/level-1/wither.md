---
action_type: Main action
class: conduit
distance: Ranged 10
feature_type: ability
file_basename: wither
file_dpath: feature/ability/conduit/level-1
flavor: A bolt of holy energy saps the life from a foe.
item_id: wither
item_name: Wither
keywords:
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Wither
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/wither
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: "\n*A bolt of holy energy saps the life from a foe.*\n\n| **Magic, Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike)**  |               **Main action** |\n|----------------------------|------------------------------:|\n| **\U0001F4CF Ranged 10**           | **\U0001F3AF One creature or object** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Intuition](scc:mcdm.heroes.v1/rule.character/intuition):**\n\n- **≤11:** 3 + I corruption damage; P < WEAK, the target takes a [bane](scc:mcdm.heroes.v1/rule.dice/bane) on their next [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll)\n- **12-16:** 5 + I corruption damage; P < AVERAGE, the target takes a [bane](scc:mcdm.heroes.v1/rule.dice/bane) on their next [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll)\n- **17+:** 8 + I corruption damage; P < STRONG, the target takes a [bane](scc:mcdm.heroes.v1/rule.dice/bane) on their next [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll)"
feature_type: ability
flavor: A bolt of holy energy saps the life from a foe.
keywords:
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: conduit
    distance: Ranged 10
    flavor: A bolt of holy energy saps the life from a foe.
    keywords:
        - Magic
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Wither
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/wither
    subtype: signature
    target: One creature or object
    type: ability
name: Wither
target: One creature or object
type: feature
usage: Main action
```
