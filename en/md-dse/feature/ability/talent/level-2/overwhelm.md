---
action_type: Main action
class: talent
cost: 5 Clarity
cost_amount: "5"
cost_resource: Clarity
distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: overwhelm
file_dpath: feature/ability/talent/level-2
flavor: You overload their senses, turning all their subconscious thoughts into conscious ones.
item_id: overwhelm
item_name: Overwhelm
keywords:
    - Psionic
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
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
distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: "\n*You overload their senses, turning all their subconscious thoughts into conscious ones.*\n\n| **Psionic, [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Telepathy** |     **Main action** |\n|----------------------------------------|--------------------:|\n| **\U0001F4CF [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10**                       | **\U0001F3AF One creature** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Reason](scc:mcdm.heroes.v1/rule.character/reason):**\n\n- **≤11:** 6 + R psychic damage; I < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)\n- **12-16:** 10 + R psychic damage; I < AVERAGE, [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)\n- **17+:** 14 + R psychic damage; I < STRONG, [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)\n\n**Strained:** You start crying, and you can't use [triggered actions](scc:mcdm.heroes.v1/rule.combat/triggered-action) or make [free strikes](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) until the end of the target's next [turn](scc:mcdm.heroes.v1/rule.combat/turn)."
feature_type: ability
flavor: You overload their senses, turning all their subconscious thoughts into conscious ones.
keywords:
    - Psionic
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Telepathy
metadata:
    action_type: Main action
    class: talent
    cost: 5 Clarity
    distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: You overload their senses, turning all their subconscious thoughts into conscious ones.
    keywords:
        - Psionic
        - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
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
