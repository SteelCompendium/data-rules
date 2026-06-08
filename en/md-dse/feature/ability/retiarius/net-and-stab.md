---
action_type: Main action
distance: Melee 2
feature_type: ability
file_basename: net-and-stab
file_dpath: feature/ability/retiarius
flavor: The well-thrown net that follows your main attack leaves your foes right where you want them.
item_id: net-and-stab
item_name: Net and Stab
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: retiarius
name: Net and Stab
scc: mcdm.heroes.v1/feature.ability.retiarius/net-and-stab
source: mcdm.heroes.v1
subtype: signature
target: One creature
type: ability
---

```ds-feature
distance: Melee 2
effects:
    - effect: "*The well-thrown net that follows your main attack leaves your foes right where you want them.*\n\n| **Melee, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |\n|---------------------------|--------------------:|\n| **\U0001F4CF Melee 2**            | **\U0001F3AF One creature** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 4 + M or A damage; A < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))\n- **12-16:** 6 + M or A damage; A < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))\n- **17+:** 8 + M or A damage; A < STRONG, [restrained](scc:mcdm.heroes.v1/condition/restrained) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))"
feature_type: ability
flavor: The well-thrown net that follows your main attack leaves your foes right where you want them.
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 2
    flavor: The well-thrown net that follows your main attack leaves your foes right where you want them.
    keywords:
        - Melee
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: retiarius
    name: Net and Stab
    scc: mcdm.heroes.v1/feature.ability.retiarius/net-and-stab
    subtype: signature
    target: One creature
    type: ability
name: Net and Stab
target: One creature
type: feature
usage: Main action
```
