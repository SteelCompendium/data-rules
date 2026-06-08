---
action_type: Main action
class: talent
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
feature_type: ability
file_basename: hoarfrost
file_dpath: feature/ability/talent/level-1
flavor: You blast a foe with a pulse of cold energy.
item_id: hoarfrost
item_name: Hoarfrost
keywords:
    - Cryokinesis
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Strike
level: "1"
name: Hoarfrost
scc: mcdm.heroes.v1/feature.ability.talent.level-1/hoarfrost
source: mcdm.heroes.v1
subtype: signature
target: One creature
type: ability
---

```ds-feature
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: "\n*You blast a foe with a pulse of cold energy.*\n\n| **Cryokinesis, Psionic, [Ranged](../../../../rule/combat/ranged.md)**, **Strike** |     **Main action** |\n|----------------------------------------------|--------------------:|\n| **\U0001F4CF [Ranged](../../../../rule/combat/ranged.md) 10**                             | **\U0001F3AF One creature** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Reason](../../../../rule/character/reason.md):**\n\n- **≤11:** 2 + R cold damage; M < WEAK, [slowed](../../../../condition/slowed.md) ([EoT](../../../../rule/combat/end-of-turn.md))\n- **12-16:** 4 + R cold damage; M < AVERAGE, [slowed](../../../../condition/slowed.md) ([EoT](../../../../rule/combat/end-of-turn.md))\n- **17+:** 6 + R cold damage; M < STRONG, [slowed](../../../../condition/slowed.md) ([EoT](../../../../rule/combat/end-of-turn.md))\n\n**Strained:** You are [slowed](../../../../condition/slowed.md) until the end of your next [turn](../../../../rule/combat/turn.md). Additionally, a target [slowed](../../../../condition/slowed.md) by this ability is [restrained](../../../../condition/restrained.md) instead."
feature_type: ability
flavor: You blast a foe with a pulse of cold energy.
keywords:
    - Cryokinesis
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Strike
metadata:
    action_type: Main action
    class: talent
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    flavor: You blast a foe with a pulse of cold energy.
    keywords:
        - Cryokinesis
        - Psionic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - Strike
    level: "1"
    name: Hoarfrost
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/hoarfrost
    subtype: signature
    target: One creature
    type: ability
name: Hoarfrost
target: One creature
type: feature
usage: Main action
```
