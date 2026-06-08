---
action_type: Main action
class: conduit
distance: Ranged 10
effect: One ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance) gains a number of [surges](scc:mcdm.heroes.v1/rule.resource/surge) equal to the [tier outcome](scc:mcdm.heroes.v1/rule.dice/tier-outcome) of your [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll).
feature_type: ability
file_basename: blessed-light
file_dpath: feature/ability/conduit/level-1
flavor: Burning radiance falls upon your foe, transferring some of their energy to a nearby ally.
item_id: blessed-light
item_name: Blessed Light
keywords:
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Blessed Light
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/blessed-light
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: One ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance) gains a number of [surges](scc:mcdm.heroes.v1/rule.resource/surge) equal to the [tier outcome](scc:mcdm.heroes.v1/rule.dice/tier-outcome) of your [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll).
feature_type: ability
flavor: Burning radiance falls upon your foe, transferring some of their energy to a nearby ally.
keywords:
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: conduit
    distance: Ranged 10
    effect: One ally within [distance](scc:mcdm.heroes.v1/rule.combat/distance) gains a number of [surges](scc:mcdm.heroes.v1/rule.resource/surge) equal to the [tier outcome](scc:mcdm.heroes.v1/rule.dice/tier-outcome) of your [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll).
    flavor: Burning radiance falls upon your foe, transferring some of their energy to a nearby ally.
    keywords:
        - Magic
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Blessed Light
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/blessed-light
    subtype: signature
    target: One creature or object
    type: ability
name: Blessed Light
target: One creature or object
type: feature
usage: Main action
```
