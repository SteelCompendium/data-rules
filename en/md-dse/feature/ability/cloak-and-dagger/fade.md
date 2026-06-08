---
action_type: Main action
distance: Melee 1 or ranged 10
feature_type: ability
file_basename: fade
file_dpath: feature/ability/cloak-and-dagger
flavor: A stab, and a few quick, careful steps back.
item_id: fade
item_name: Fade
keywords:
    - Melee
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: cloak-and-dagger
name: Fade
scc: mcdm.heroes.v1/feature.ability.cloak-and-dagger/fade
source: mcdm.heroes.v1
subtype: signature
target: One creature
type: ability
---

```ds-feature
distance: Melee 1 or ranged 10
effects:
    - effect: "*A stab, and a few quick, careful steps back.*\n\n| **Melee, Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |\n|-----------------------------------|--------------------:|\n| **\U0001F4CF Melee 1 or ranged 10**       | **\U0001F3AF One creature** |\n\n**Power Roll + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 3 + M or A damage; you can [shift](scc:mcdm.heroes.v1/movement/shifting) 1 square\n- **12-16:** 6 + M or A damage; you can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 2 squares\n- **17+:** 8 + M or A damage; you can [shift](scc:mcdm.heroes.v1/movement/shifting) up to 3 squares"
feature_type: ability
flavor: A stab, and a few quick, careful steps back.
keywords:
    - Melee
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 1 or ranged 10
    flavor: A stab, and a few quick, careful steps back.
    keywords:
        - Melee
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: cloak-and-dagger
    name: Fade
    scc: mcdm.heroes.v1/feature.ability.cloak-and-dagger/fade
    subtype: signature
    target: One creature
    type: ability
name: Fade
target: One creature
type: feature
usage: Main action
```
