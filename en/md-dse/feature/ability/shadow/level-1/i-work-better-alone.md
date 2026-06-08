---
action_type: Main action
class: shadow
distance: Melee 1 or ranged 5
effect: If the target has none of your allies adjacent to them, you gain 1 [surge](scc:mcdm.heroes.v1/rule.resource/surge) before making the power roll.
feature_type: ability
file_basename: i-work-better-alone
file_dpath: feature/ability/shadow/level-1
flavor: '"It''s better, just you and me. Isn''t it?"'
item_id: i-work-better-alone
item_name: I Work Better Alone
keywords:
    - Melee
    - Ranged
    - Strike
    - Weapon
level: "1"
name: I Work Better Alone
power_roll_characteristic: Agility
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/i-work-better-alone
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 3 + A damage
tier2: 6 + A damage
tier3: 9 + A damage
type: ability
---

```ds-feature
distance: Melee 1 or ranged 5
effects:
    - effect: If the target has none of your allies adjacent to them, you gain 1 [surge](scc:mcdm.heroes.v1/rule.resource/surge) before making the power roll.
    - roll: Power Roll + Agility
      tier1: 3 + A damage
      tier2: 6 + A damage
      tier3: 9 + A damage
feature_type: ability
flavor: '"It''s better, just you and me. Isn''t it?"'
keywords:
    - Melee
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    distance: Melee 1 or ranged 5
    effect: If the target has none of your allies adjacent to them, you gain 1 [surge](scc:mcdm.heroes.v1/rule.resource/surge) before making the power roll.
    flavor: '"It''s better, just you and me. Isn''t it?"'
    keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
    level: "1"
    name: I Work Better Alone
    power_roll_characteristic: Agility
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/i-work-better-alone
    subtype: signature
    target: One creature
    tier1: 3 + A damage
    tier2: 6 + A damage
    tier3: 9 + A damage
    type: ability
name: I Work Better Alone
target: One creature
type: feature
usage: Main action
```
