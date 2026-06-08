---
action_type: Main action
class: shadow
cost: 5 Insight
cost_amount: "5"
cost_resource: Insight
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 5'
feature_type: ability
file_basename: in-a-puff-of-ash
file_dpath: feature/ability/shadow/level-2
flavor: You enchant a [strike](scc:mcdm.heroes.v1/rule.combat/strike) with your [teleport](scc:mcdm.heroes.v1/movement/teleport)ation magic.
item_id: in-a-puff-of-ash
item_name: In a Puff of Ash
keywords:
    - Magic
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "2"
name: In a Puff of Ash
scc: mcdm.heroes.v1/feature.ability.shadow.level-2/in-a-puff-of-ash
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 5 Insight
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - effect: "\n*You enchant a [strike](scc:mcdm.heroes.v1/rule.combat/strike) with your [teleport](scc:mcdm.heroes.v1/movement/teleport)ation magic.*\n\n| **Magic, [Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |\n|------------------------------------------|--------------------:|\n| **\U0001F4CF [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 5**               | **\U0001F3AF One creature** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 6 + A damage; you can [teleport](scc:mcdm.heroes.v1/movement/teleport) the target 1 square\n- **12-16:** 10 + A damage; you can [teleport](scc:mcdm.heroes.v1/movement/teleport) the target up to 3 squares\n- **17+:** 14 + A damage; you can [teleport](scc:mcdm.heroes.v1/movement/teleport) the target up to 5 squares"
feature_type: ability
flavor: You enchant a [strike](scc:mcdm.heroes.v1/rule.combat/strike) with your [teleport](scc:mcdm.heroes.v1/movement/teleport)ation magic.
keywords:
    - Magic
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 5 Insight
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 5'
    flavor: You enchant a [strike](scc:mcdm.heroes.v1/rule.combat/strike) with your [teleport](scc:mcdm.heroes.v1/movement/teleport)ation magic.
    keywords:
        - Magic
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "2"
    name: In a Puff of Ash
    scc: mcdm.heroes.v1/feature.ability.shadow.level-2/in-a-puff-of-ash
    target: One creature
    type: ability
name: In a Puff of Ash
target: One creature
type: feature
usage: Main action
```
