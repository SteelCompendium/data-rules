---
action_type: Main action
class: censor
cost: 5 Wrath
cost_amount: "5"
cost_resource: Wrath
distance: Melee 1 or ranged 5
effect: Each enemy [frightened](scc:mcdm.heroes.v1/condition/frightened) this way is pushed up to 2 squares away from the target and takes psychic damage equal to your [Presence](scc:mcdm.heroes.v1/rule.character/presence) score.
feature_type: ability
file_basename: behold-the-face-of-justice
file_dpath: feature/ability/censor/level-1
flavor: You attack a foe and your enemies behold a vision of the true nature of your resolve.
item_id: behold-the-face-of-justice
item_name: Behold the Face of Justice!
keywords:
    - Magic
    - Melee
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Behold the Face of Justice!
scc: mcdm.heroes.v1/feature.ability.censor.level-1/behold-the-face-of-justice
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 5 Wrath
distance: Melee 1 or ranged 5
effects:
    - effect: Each enemy [frightened](scc:mcdm.heroes.v1/condition/frightened) this way is pushed up to 2 squares away from the target and takes psychic damage equal to your [Presence](scc:mcdm.heroes.v1/rule.character/presence) score.
feature_type: ability
flavor: You attack a foe and your enemies behold a vision of the true nature of your resolve.
keywords:
    - Magic
    - Melee
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: censor
    cost: 5 Wrath
    distance: Melee 1 or ranged 5
    effect: Each enemy [frightened](scc:mcdm.heroes.v1/condition/frightened) this way is pushed up to 2 squares away from the target and takes psychic damage equal to your [Presence](scc:mcdm.heroes.v1/rule.character/presence) score.
    flavor: You attack a foe and your enemies behold a vision of the true nature of your resolve.
    keywords:
        - Magic
        - Melee
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Behold the Face of Justice!
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/behold-the-face-of-justice
    target: One creature
    type: ability
name: Behold the Face of Justice!
target: One creature
type: feature
usage: Main action
```
