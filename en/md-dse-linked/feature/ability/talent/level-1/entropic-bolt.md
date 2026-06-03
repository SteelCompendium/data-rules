---
action_type: Main action
class: talent
distance: Ranged 10
effect: The target takes an extra 1 corruption damage for each additional time they are targeted by this ability during the encounter.
feature_type: ability
file_basename: entropic-bolt
file_dpath: feature/ability/talent/level-1
flavor: You advance an enemy's age for a moment.
item_id: entropic-bolt
item_name: Entropic Bolt
keywords:
    - Chronopathy
    - Psionic
    - Ranged
    - Strike
level: "1"
name: Entropic Bolt
power_roll_characteristic: Presence
scc: mcdm.heroes.v1/feature.ability.talent.level-1/entropic-bolt
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 2 + P corruption damage; P < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
tier2: 3 + P corruption damage; P < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
tier3: 5 + P corruption damage; P < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: The target takes an extra 1 corruption damage for each additional time they are targeted by this ability during the encounter.
    - roll: Power Roll + Presence
      tier1: 2 + P corruption damage; P < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
      tier2: 3 + P corruption damage; P < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
      tier3: 5 + P corruption damage; P < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
feature_type: ability
flavor: You advance an enemy's age for a moment.
keywords:
    - Chronopathy
    - Psionic
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: talent
    distance: Ranged 10
    effect: The target takes an extra 1 corruption damage for each additional time they are targeted by this ability during the encounter.
    flavor: You advance an enemy's age for a moment.
    keywords:
        - Chronopathy
        - Psionic
        - Ranged
        - Strike
    level: "1"
    name: Entropic Bolt
    power_roll_characteristic: Presence
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/entropic-bolt
    subtype: signature
    target: One creature or object
    tier1: 2 + P corruption damage; P < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
    tier2: 3 + P corruption damage; P < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
    tier3: 5 + P corruption damage; P < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
    type: ability
name: Entropic Bolt
target: One creature or object
type: feature
usage: Main action
```
