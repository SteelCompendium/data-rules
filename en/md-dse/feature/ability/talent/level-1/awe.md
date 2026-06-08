---
action_type: Main action
class: talent
cost: 3 Clarity
cost_amount: "3"
cost_resource: Clarity
distance: Ranged 10
effect: If you target an ally, they gain [temporary Stamina](scc:mcdm.heroes.v1/rule.health/temporary-stamina) equal to three times your Presence score, and they can end one effect on them that is ended by a saving throw or that ends at the end of their turn. If you target an enemy, you make a power roll.
feature_type: ability
file_basename: awe
file_dpath: feature/ability/talent/level-1
flavor: You project psionic energy out to a creature and take on a new visage in their mind.
item_id: awe
item_name: Awe
keywords:
    - Psionic
    - Ranged
    - Strike
    - Telepathy
level: "1"
name: Awe
power_roll_characteristic: Presence
scc: mcdm.heroes.v1/feature.ability.talent.level-1/awe
source: mcdm.heroes.v1
target: One creature
tier1: 3 + P psychic damage; I < WEAK, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
tier2: 6 + P psychic damage; I < AVERAGE, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
tier3: 9 + P psychic damage; I < STRONG, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
type: ability
---

```ds-feature
cost: 3 Clarity
distance: Ranged 10
effects:
    - effect: If you target an ally, they gain [temporary Stamina](scc:mcdm.heroes.v1/rule.health/temporary-stamina) equal to three times your Presence score, and they can end one effect on them that is ended by a saving throw or that ends at the end of their turn. If you target an enemy, you make a power roll.
    - roll: Power Roll + Presence
      tier1: 3 + P psychic damage; I < WEAK, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
      tier2: 6 + P psychic damage; I < AVERAGE, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
      tier3: 9 + P psychic damage; I < STRONG, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
feature_type: ability
flavor: You project psionic energy out to a creature and take on a new visage in their mind.
keywords:
    - Psionic
    - Ranged
    - Strike
    - Telepathy
metadata:
    action_type: Main action
    class: talent
    cost: 3 Clarity
    distance: Ranged 10
    effect: If you target an ally, they gain [temporary Stamina](scc:mcdm.heroes.v1/rule.health/temporary-stamina) equal to three times your Presence score, and they can end one effect on them that is ended by a saving throw or that ends at the end of their turn. If you target an enemy, you make a power roll.
    flavor: You project psionic energy out to a creature and take on a new visage in their mind.
    keywords:
        - Psionic
        - Ranged
        - Strike
        - Telepathy
    level: "1"
    name: Awe
    power_roll_characteristic: Presence
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/awe
    target: One creature
    tier1: 3 + P psychic damage; I < WEAK, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
    tier2: 6 + P psychic damage; I < AVERAGE, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
    tier3: 9 + P psychic damage; I < STRONG, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
    type: ability
name: Awe
target: One creature
type: feature
usage: Main action
```
