---
action_type: Main action
class: troubadour
cost: 11 Drama
cost_amount: "11"
cost_resource: Drama
distance: Melee 1
effect: Add your current [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) to your target's current [Stamina](scc:mcdm.heroes.v1/rule.health/stamina), then you have half that total [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) and the target has the remainder. If either of you would gain more [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) this way than their [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) maximum, the difference in [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) between what that creature would gain and their maximum is gained by the other creature. Neither of you can gain more [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) than your maximum this way. You then make a [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll).
feature_type: ability
file_basename: renegotiated-contract
file_dpath: feature/ability/troubadour/level-9
flavor: No, no. You don't die until the sequel.
item_id: renegotiated-contract
item_name: Renegotiated Contract
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "9"
name: Renegotiated Contract
scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/renegotiated-contract
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 11 Drama
distance: Melee 1
effects:
    - effect: Add your current [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) to your target's current [Stamina](scc:mcdm.heroes.v1/rule.health/stamina), then you have half that total [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) and the target has the remainder. If either of you would gain more [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) this way than their [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) maximum, the difference in [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) between what that creature would gain and their maximum is gained by the other creature. Neither of you can gain more [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) than your maximum this way. You then make a [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll).
feature_type: ability
flavor: No, no. You don't die until the sequel.
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: troubadour
    cost: 11 Drama
    distance: Melee 1
    effect: Add your current [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) to your target's current [Stamina](scc:mcdm.heroes.v1/rule.health/stamina), then you have half that total [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) and the target has the remainder. If either of you would gain more [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) this way than their [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) maximum, the difference in [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) between what that creature would gain and their maximum is gained by the other creature. Neither of you can gain more [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) than your maximum this way. You then make a [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll).
    flavor: No, no. You don't die until the sequel.
    keywords:
        - Melee
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "9"
    name: Renegotiated Contract
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/renegotiated-contract
    target: One creature
    type: ability
name: Renegotiated Contract
target: One creature
type: feature
usage: Main action
```
