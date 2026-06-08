---
action_type: Main action
class: elementalist
cost: 3 Essence
cost_amount: "3"
cost_resource: Essence
distance: Ranged 10
feature_type: ability
file_basename: the-flesh-a-crucible
file_dpath: feature/ability/elementalist/level-1
flavor: Fire engulfs your target and continues to churn.
item_id: the-flesh-a-crucible
item_name: The Flesh, a Crucible
keywords:
    - Fire
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: The Flesh, a Crucible
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/the-flesh-a-crucible
source: mcdm.heroes.v1
target: One creature or object
type: ability
---

```ds-feature
cost: 3 Essence
distance: Ranged 10
effects:
    - effect: "\n*Fire engulfs your target and continues to churn.*\n\n| **Fire, Magic, Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike)** |               **Main action** |\n|---------------------------------|------------------------------:|\n| **\U0001F4CF Ranged 10**                | **\U0001F3AF One creature or object** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Reason](scc:mcdm.heroes.v1/rule.character/reason):**\n\n- **≤11:** 5 + R fire damage\n- **12-16:** 8 + R fire damage\n- **17+:** 11 + R fire damage\n\n**Persistent 1:** If the target is within [distance](scc:mcdm.heroes.v1/rule.combat/distance) at the start of your turn, you can make the [power roll](scc:mcdm.heroes.v1/rule.dice/power-roll) again without spending essence (no action required)."
feature_type: ability
flavor: Fire engulfs your target and continues to churn.
keywords:
    - Fire
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: elementalist
    cost: 3 Essence
    distance: Ranged 10
    flavor: Fire engulfs your target and continues to churn.
    keywords:
        - Fire
        - Magic
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: The Flesh, a Crucible
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/the-flesh-a-crucible
    target: One creature or object
    type: ability
name: The Flesh, a Crucible
target: One creature or object
type: feature
usage: Main action
```
