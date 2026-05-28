---
action_type: feature
class: censor
feature_type: trait
file_basename: implement-of-wrath
file_dpath: feature/trait/censor/level-6
item_id: implement-of-wrath
item_name: Implement of Wrath
level: "6"
name: Implement of Wrath
scc: mcdm.heroes.v1/feature.trait.censor.level-6/implement-of-wrath
source: mcdm.heroes.v1
type: trait
---

```ds-feature
effects:
    - effect: |-
        Each time you finish a respite, you can choose one hero's weapon, including your own, to channel supernatural power as an implement of your god's wrath. The weapon becomes magic and gains the following benefits until your next respite:

        - Strikes with the weapon deal extra holy damage equal to the wielder's highest characteristic score.
        - Any creature struck by the weapon who has holy weakness and has P < STRONG is [frightened](../../../../condition/frightened.md) and [weakened](../../../../condition/weakened.md) (save ends).
        - Any minion targeted by a strike using the weapon dies. That minion's Stamina maximum is removed from the minion Stamina pool before any damage is applied to the rest of the squad.
        - The weapon's wielder can't be made [frightened](../../../../condition/frightened.md).
feature_type: trait
metadata:
    class: censor
    level: "6"
    name: Implement of Wrath
    scc: mcdm.heroes.v1/feature.trait.censor.level-6/implement-of-wrath
    type: trait
name: Implement of Wrath
type: feature
```
