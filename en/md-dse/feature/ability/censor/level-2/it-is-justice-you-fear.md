---
action_type: Main action
class: censor
cost: 5 Wrath
cost_amount: "5"
cost_resource: Wrath
distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: If the target is already [frightened](scc:mcdm.heroes.v1/condition/frightened) of you or another creature and this ability would frighten them again, they instead take psychic damage equal to twice your [Presence](scc:mcdm.heroes.v1/rule.character/presence) score.
feature_type: ability
file_basename: it-is-justice-you-fear
file_dpath: feature/ability/censor/level-2
flavor: I am but a vessel. Your own deeds weigh upon you.
item_id: it-is-justice-you-fear
item_name: It Is Justice You Fear
keywords:
    - Magic
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
level: "2"
name: It Is Justice You Fear
power_roll_characteristic: '[Might](scc:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.censor.level-2/it-is-justice-you-fear
source: mcdm.heroes.v1
target: One creature
tier1: 8 + M holy damage; P < WEAK, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
tier2: 12 + M holy damage; P < AVERAGE, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
tier3: 15 + M holy damage; P < STRONG, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
type: ability
---

```ds-feature
cost: 5 Wrath
distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: If the target is already [frightened](scc:mcdm.heroes.v1/condition/frightened) of you or another creature and this ability would frighten them again, they instead take psychic damage equal to twice your [Presence](scc:mcdm.heroes.v1/rule.character/presence) score.
    - roll: Power Roll + [Might](scc:mcdm.heroes.v1/rule.character/might)
      tier1: 8 + M holy damage; P < WEAK, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
      tier2: 12 + M holy damage; P < AVERAGE, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
      tier3: 15 + M holy damage; P < STRONG, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
feature_type: ability
flavor: I am but a vessel. Your own deeds weigh upon you.
keywords:
    - Magic
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: censor
    cost: 5 Wrath
    distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: If the target is already [frightened](scc:mcdm.heroes.v1/condition/frightened) of you or another creature and this ability would frighten them again, they instead take psychic damage equal to twice your [Presence](scc:mcdm.heroes.v1/rule.character/presence) score.
    flavor: I am but a vessel. Your own deeds weigh upon you.
    keywords:
        - Magic
        - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    level: "2"
    name: It Is Justice You Fear
    power_roll_characteristic: '[Might](scc:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-2/it-is-justice-you-fear
    target: One creature
    tier1: 8 + M holy damage; P < WEAK, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
    tier2: 12 + M holy damage; P < AVERAGE, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
    tier3: 15 + M holy damage; P < STRONG, [frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
    type: ability
name: It Is Justice You Fear
target: One creature
type: feature
usage: Main action
```
