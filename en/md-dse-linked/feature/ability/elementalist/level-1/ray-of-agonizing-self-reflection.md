---
action_type: Main action
class: elementalist
distance: Ranged 10
feature_type: ability
file_basename: ray-of-agonizing-self-reflection
file_dpath: feature/ability/elementalist/level-1
flavor: You inflict pain and doubt in equal measure.
item_id: ray-of-agonizing-self-reflection
item_name: Ray of Agonizing Self-Reflection
keywords:
    - Magic
    - Ranged
    - '[Strike](../../../../rule/combat/strike.md)'
    - Void
level: "1"
name: Ray of Agonizing Self-Reflection
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/ray-of-agonizing-self-reflection
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: "\n*You inflict pain and doubt in equal measure.*\n\n| **Magic, Ranged, [Strike](../../../../rule/combat/strike.md), Void** |               **Main action** | \n|---------------------------------|------------------------------:|\n| **\U0001F4CF Ranged 10**                | **\U0001F3AF One creature or object** |\n\n**Power Roll + [Reason](../../../../rule/character/reason.md):**\n\n- **≤11:** 2 + R corruption damage; R < WEAK, [slowed](../../../../condition/slowed.md) (save ends)\n- **12-16:** 4 + R corruption damage; R < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)\n- **17+:** 6 + R corruption damage; R < STRONG, [slowed](../../../../condition/slowed.md) (save ends)"
feature_type: ability
flavor: You inflict pain and doubt in equal measure.
keywords:
    - Magic
    - Ranged
    - '[Strike](../../../../rule/combat/strike.md)'
    - Void
metadata:
    action_type: Main action
    class: elementalist
    distance: Ranged 10
    flavor: You inflict pain and doubt in equal measure.
    keywords:
        - Magic
        - Ranged
        - '[Strike](../../../../rule/combat/strike.md)'
        - Void
    level: "1"
    name: Ray of Agonizing Self-Reflection
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/ray-of-agonizing-self-reflection
    subtype: signature
    target: One creature or object
    type: ability
name: Ray of Agonizing Self-Reflection
target: One creature or object
type: feature
usage: Main action
```
