---
action_type: Main action
distance: Ranged 10
feature_type: ability
file_basename: hamstring-shot
file_dpath: feature/ability/ranger
flavor: A well-placed shot leaves your enemy struggling to move.
item_id: hamstring-shot
item_name: Hamstring Shot
keywords:
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: ranger
name: Hamstring Shot
scc: mcdm.heroes.v1/feature.ability.ranger/hamstring-shot
source: mcdm.heroes.v1
subtype: signature
target: One creature
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: "*A well-placed shot leaves your enemy struggling to move.*\n\n| **Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |\n|----------------------------|--------------------:|\n| **\U0001F4CF Ranged 10**           | **\U0001F3AF One creature** |\n\n**Power Roll + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 3 + M or A damage; A < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)\n- **12-16:** 5 + M or A damage; A < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)\n- **17+:** 7 + M or A damage; A < STRONG, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)"
feature_type: ability
flavor: A well-placed shot leaves your enemy struggling to move.
keywords:
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: Ranged 10
    flavor: A well-placed shot leaves your enemy struggling to move.
    keywords:
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: ranger
    name: Hamstring Shot
    scc: mcdm.heroes.v1/feature.ability.ranger/hamstring-shot
    subtype: signature
    target: One creature
    type: ability
name: Hamstring Shot
target: One creature
type: feature
usage: Main action
```
