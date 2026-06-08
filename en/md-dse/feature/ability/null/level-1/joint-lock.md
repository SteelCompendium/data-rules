---
action_type: Main action
class: "null"
distance: Melee 1
feature_type: ability
file_basename: joint-lock
file_dpath: feature/ability/null/level-1
flavor: You contort your enemy's body into a stance they struggle to escape from.
item_id: joint-lock
item_name: Joint Lock
keywords:
    - Melee
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Joint Lock
scc: mcdm.heroes.v1/feature.ability.null.level-1/joint-lock
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: "\n*You contort your enemy's body into a stance they struggle to escape from.*\n\n| **Melee, Psionic, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |\n|------------------------------------|------------------------------:|\n| **\U0001F4CF Melee 1**                     | **\U0001F3AF One creature or object** |\n\n**Power Roll + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 4 + A damage; A < WEAK, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)\n- **12-16:** 7 + A damage; A < AVERAGE, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)\n- **17+:** 9 + A damage; A < STRONG, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)"
feature_type: ability
flavor: You contort your enemy's body into a stance they struggle to escape from.
keywords:
    - Melee
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    distance: Melee 1
    flavor: You contort your enemy's body into a stance they struggle to escape from.
    keywords:
        - Melee
        - Psionic
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Joint Lock
    scc: mcdm.heroes.v1/feature.ability.null.level-1/joint-lock
    subtype: signature
    target: One creature or object
    type: ability
name: Joint Lock
target: One creature or object
type: feature
usage: Main action
```
