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
    - '[Strike](../../../../rule/combat/strike.md)'
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
    - effect: "\n*A bolt of holy energy saps the life from a foe.*\n\n| **Magic, Ranged, [Strike](../../../../rule/combat/strike.md)**  |               **Main action** |\n|----------------------------|------------------------------:|\n| **\U0001F4CF Ranged 10**           | **\U0001F3AF One creature or object** |\n\n**Power Roll + [Intuition](../../../../rule/character/intuition.md):**\n\n- **≤11:** 3 + I corruption damage; P < WEAK, the target takes a [bane](../../../../rule/dice/bane.md) on their next power roll\n- **12-16:** 5 + I corruption damage; P < AVERAGE, the target takes a [bane](../../../../rule/dice/bane.md) on their next power roll\n- **17+:** 8 + I corruption damage; P < STRONG, the target takes a [bane](../../../../rule/dice/bane.md) on their next power roll"
feature_type: ability
flavor: A bolt of holy energy saps the life from a foe.
keywords:
    - Magic
    - Ranged
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: Main action
    class: conduit
    distance: Ranged 10
    flavor: A bolt of holy energy saps the life from a foe.
    keywords:
        - Magic
        - Ranged
        - '[Strike](../../../../rule/combat/strike.md)'
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
