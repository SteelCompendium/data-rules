---
action_type: Main action
distance: Melee 3
feature_type: ability
file_basename: extension-of-my-arm
file_dpath: feature/ability/whirlwind
flavor: When you draw your whip back after an attack, your enemy is drawn ever closer.
item_id: extension-of-my-arm
item_name: Extension of My Arm
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: whirlwind
name: Extension of My Arm
scc: mcdm.heroes.v1/feature.ability.whirlwind/extension-of-my-arm
source: mcdm.heroes.v1
subtype: signature
target: One creature
type: ability
---

```ds-feature
distance: Melee 3
effects:
    - effect: "*When you draw your whip back after an attack, your enemy is drawn ever closer.*\n\n| **Melee, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |\n|---------------------------|--------------------:|\n| **\U0001F4CF Melee 3**            | **\U0001F3AF One creature** |\n\n**Power Roll + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 4 + M or A damage; vertical pull 1\n- **12-16:** 7 + M or A damage; vertical pull 2\n- **17+:** 10 + M or A damage; vertical pull 3"
feature_type: ability
flavor: When you draw your whip back after an attack, your enemy is drawn ever closer.
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 3
    flavor: When you draw your whip back after an attack, your enemy is drawn ever closer.
    keywords:
        - Melee
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: whirlwind
    name: Extension of My Arm
    scc: mcdm.heroes.v1/feature.ability.whirlwind/extension-of-my-arm
    subtype: signature
    target: One creature
    type: ability
name: Extension of My Arm
target: One creature
type: feature
usage: Main action
```
