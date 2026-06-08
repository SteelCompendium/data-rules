---
action_type: Main action
ancestry: wode-elf
distance: Ranged 10
feature_type: ability
file_basename: the-wode-defends
file_dpath: feature/ability/wode-elf
flavor: Thorny vines erupt from every surface and attempt to bind your foe.
item_id: the-wode-defends
item_name: The Wode Defends
keywords:
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
name: The Wode Defends
scc: mcdm.heroes.v1/feature.ability.wode-elf/the-wode-defends
source: mcdm.heroes.v1
subtype: signature
target: One creature
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: "*Thorny vines erupt from every surface and attempt to bind your foe.*\n\n| **Magic, Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike)** |               **Main action** |\n|---------------------------|------------------------------:|\n| **\U0001F4CF Ranged 10**          |           **\U0001F3AF One creature** |\n\n**Power Roll + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 2 + M or A damage; A < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)\n- **12-16:** 3 + M or A damage; A < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)\n- **17+:** 5 + M or A damage; A < STRONG, [restrained](scc:mcdm.heroes.v1/condition/restrained) (save ends)"
feature_type: ability
flavor: Thorny vines erupt from every surface and attempt to bind your foe.
keywords:
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    ancestry: wode-elf
    distance: Ranged 10
    flavor: Thorny vines erupt from every surface and attempt to bind your foe.
    keywords:
        - Magic
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    name: The Wode Defends
    scc: mcdm.heroes.v1/feature.ability.wode-elf/the-wode-defends
    subtype: signature
    target: One creature
    type: ability
name: The Wode Defends
target: One creature
type: feature
usage: Main action
```
