---
action_type: Main action
class: "null"
cost: 3 Discipline
cost_amount: "3"
cost_resource: Discipline
distance: Melee 1
feature_type: ability
file_basename: stunning-blow
file_dpath: feature/ability/null/level-1
flavor: You focus your psionic technique into a concussive punch.
item_id: stunning-blow
item_name: Stunning Blow
keywords:
    - Melee
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Stunning Blow
scc: mcdm.heroes.v1/feature.ability.null.level-1/stunning-blow
source: mcdm.heroes.v1
target: One creature or object
type: ability
---

```ds-feature
cost: 3 Discipline
distance: Melee 1
effects:
    - effect: "\n*You focus your psionic technique into a concussive punch.*\n\n| **Melee, Psionic, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |\n|------------------------------------|------------------------------:|\n| **\U0001F4CF Melee 1**                     | **\U0001F3AF One creature or object** |\n\n**Power Roll + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 4 + A damage; I < WEAK, [dazed](scc:mcdm.heroes.v1/condition/dazed) and [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)\n- **12-16:** 5 + A damage; I < AVERAGE, [dazed](scc:mcdm.heroes.v1/condition/dazed) and [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)\n- **17+:** 7 + A damage; I < STRONG, [dazed](scc:mcdm.heroes.v1/condition/dazed) and [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)"
feature_type: ability
flavor: You focus your psionic technique into a concussive punch.
keywords:
    - Melee
    - Psionic
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    cost: 3 Discipline
    distance: Melee 1
    flavor: You focus your psionic technique into a concussive punch.
    keywords:
        - Melee
        - Psionic
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Stunning Blow
    scc: mcdm.heroes.v1/feature.ability.null.level-1/stunning-blow
    target: One creature or object
    type: ability
name: Stunning Blow
target: One creature or object
type: feature
usage: Main action
```
