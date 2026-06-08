---
action_type: Main action
distance: Melee 1
feature_type: ability
file_basename: bear-claws
file_dpath: feature/ability/boren
flavor: Attacks with your sharp and deadly claws grab the weak.
item_id: bear-claws
item_name: Bear Claws
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: boren
name: Bear Claws
scc: mcdm.heroes.v1/feature.ability.boren/bear-claws
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: "*Attacks with your sharp and deadly claws grab the weak.*\n\n| **Melee, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |\n|---------------------------|------------------------------:|\n| **\U0001F4CF Melee 1**            | **\U0001F3AF One creature or object** |\n\n**Power Roll + [Might](scc:mcdm.heroes.v1/rule.character/might):**\n\n- **≤11:** 2 + M damage; M < WEAK, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)\n- **12-16:** 5 + M damage; M < AVERAGE, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)\n- **17+:** 11 + M damage; M < STRONG, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)"
feature_type: ability
flavor: Attacks with your sharp and deadly claws grab the weak.
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: Melee 1
    flavor: Attacks with your sharp and deadly claws grab the weak.
    keywords:
        - Melee
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: boren
    name: Bear Claws
    scc: mcdm.heroes.v1/feature.ability.boren/bear-claws
    subtype: signature
    target: One creature or object
    type: ability
name: Bear Claws
target: One creature or object
type: feature
usage: Main action
```
