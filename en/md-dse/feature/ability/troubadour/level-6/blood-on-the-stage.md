---
action_type: Main action
class: troubadour
cost: 9 Drama
cost_amount: "9"
cost_resource: Drama
distance: Melee 1
feature_type: ability
file_basename: blood-on-the-stage
file_dpath: feature/ability/troubadour/level-6
flavor: It's love and blood or drama and blood. Either way, there's always blood.
item_id: blood-on-the-stage
item_name: Blood on the Stage
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "6"
name: Blood on the Stage
scc: mcdm.heroes.v1/feature.ability.troubadour.level-6/blood-on-the-stage
source: mcdm.heroes.v1
target: One creature or object
type: ability
---

```ds-feature
cost: 9 Drama
distance: Melee 1
effects:
    - effect: "\n*It's love and blood or drama and blood. Either way, there's always blood.*\n\n| **Melee, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |\n|---------------------------|------------------------------:|\n| **\U0001F4CF Melee 1**            | **\U0001F3AF One creature or object** |\n\n**Power Roll + [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 12 + A damage; M < WEAK, [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)\n- **12-16:** 18 + A damage; M < AVERAGE, [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)\n- **17+:** 24 + A damage; [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (EoT), or if M < STRONG, [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)"
feature_type: ability
flavor: It's love and blood or drama and blood. Either way, there's always blood.
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: troubadour
    cost: 9 Drama
    distance: Melee 1
    flavor: It's love and blood or drama and blood. Either way, there's always blood.
    keywords:
        - Melee
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "6"
    name: Blood on the Stage
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-6/blood-on-the-stage
    target: One creature or object
    type: ability
name: Blood on the Stage
target: One creature or object
type: feature
usage: Main action
```
