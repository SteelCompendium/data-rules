---
action_type: Main action
class: talent
cost: 5 Clarity
cost_amount: "5"
cost_resource: Clarity
distance: Ranged 10
feature_type: ability
file_basename: overwhelm
file_dpath: feature/ability/talent/level-2
flavor: You overload their senses, turning all their subconscious thoughts into conscious ones.
item_id: overwhelm
item_name: Overwhelm
keywords:
    - Psionic
    - Ranged
    - '[Strike](../../../../rule/combat/strike.md)'
    - Telepathy
level: "2"
name: Overwhelm
scc: mcdm.heroes.v1/feature.ability.talent.level-2/overwhelm
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 5 Clarity
distance: Ranged 10
effects:
    - effect: "\n*You overload their senses, turning all their subconscious thoughts into conscious ones.*\n\n| **Psionic, Ranged, [Strike](../../../../rule/combat/strike.md), Telepathy** |     **Main action** |\n|----------------------------------------|--------------------:|\n| **\U0001F4CF Ranged 10**                       | **\U0001F3AF One creature** |\n\n**Power Roll + [Reason](../../../../rule/character/reason.md):**\n\n- **≤11:** 6 + R psychic damage; I < WEAK, [slowed](../../../../condition/slowed.md) (save ends)\n- **12-16:** 10 + R psychic damage; I < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)\n- **17+:** 14 + R psychic damage; I < STRONG, [dazed](../../../../condition/dazed.md) (save ends)\n\n**Strained:** You start crying, and you can't use triggered actions or make [free strikes](../../../common/main-actions/free-strike.md) until the end of the target's next turn."
feature_type: ability
flavor: You overload their senses, turning all their subconscious thoughts into conscious ones.
keywords:
    - Psionic
    - Ranged
    - '[Strike](../../../../rule/combat/strike.md)'
    - Telepathy
metadata:
    action_type: Main action
    class: talent
    cost: 5 Clarity
    distance: Ranged 10
    flavor: You overload their senses, turning all their subconscious thoughts into conscious ones.
    keywords:
        - Psionic
        - Ranged
        - '[Strike](../../../../rule/combat/strike.md)'
        - Telepathy
    level: "2"
    name: Overwhelm
    scc: mcdm.heroes.v1/feature.ability.talent.level-2/overwhelm
    target: One creature
    type: ability
name: Overwhelm
target: One creature
type: feature
usage: Main action
```
