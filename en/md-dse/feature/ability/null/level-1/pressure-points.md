---
action_type: Main action
class: "null"
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
feature_type: ability
file_basename: pressure-points
file_dpath: feature/ability/null/level-1
flavor: You strike at key nerve clusters to leave your foe staggered.
item_id: pressure-points
item_name: Pressure Points
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Pressure Points
scc: mcdm.heroes.v1/feature.ability.null.level-1/pressure-points
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
type: ability
---

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: "\n*You strike at key nerve clusters to leave your foe staggered.*\n\n| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), Psionic, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |\n|------------------------------------|------------------------------:|\n| **\U0001F4CF [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1**                     | **\U0001F3AF One creature or object** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 4 + A damage; A < WEAK, [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)\n- **12-16:** 7 + A damage; A < AVERAGE, [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)\n- **17+:** 9 + A damage; A < STRONG, [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)"
feature_type: ability
flavor: You strike at key nerve clusters to leave your foe staggered.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
    flavor: You strike at key nerve clusters to leave your foe staggered.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Pressure Points
    scc: mcdm.heroes.v1/feature.ability.null.level-1/pressure-points
    subtype: signature
    target: One creature or object
    type: ability
name: Pressure Points
target: One creature or object
type: feature
usage: Main action
```
