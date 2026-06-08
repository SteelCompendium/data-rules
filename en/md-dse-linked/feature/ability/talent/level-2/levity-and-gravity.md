---
action_type: Main action
class: talent
cost: 5 Clarity
cost_amount: "5"
cost_resource: Clarity
distance: Ranged 10
feature_type: ability
file_basename: levity-and-gravity
file_dpath: feature/ability/talent/level-2
flavor: You raise the target slightly into the air, then smother them against the ground.
item_id: levity-and-gravity
item_name: Levity and Gravity
keywords:
    - Psionic
    - Ranged
    - '[Strike](../../../../rule/combat/strike.md)'
    - Telekinesis
level: "2"
name: Levity and Gravity
scc: mcdm.heroes.v1/feature.ability.talent.level-2/levity-and-gravity
source: mcdm.heroes.v1
target: One creature or object
type: ability
---

```ds-feature
cost: 5 Clarity
distance: Ranged 10
effects:
    - effect: "\n*You raise the target slightly into the air, then smother them against the ground.*\n\n| **Psionic, Ranged, [Strike](../../../../rule/combat/strike.md), Telekinesis** |               **Main action** |\n|------------------------------------------|------------------------------:|\n| **\U0001F4CF Ranged 10**                         | **\U0001F3AF One creature or object** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Reason](../../../../rule/character/reason.md):**\n\n- **≤11:** 6 + R damage; M < WEAK[, prone](../../../../condition/prone.md)\n- **12-16:** 10 + R damage; M < AVERAGE[, prone](../../../../condition/prone.md)\n- **17+:** 14 + R damage; M < STRONG, [prone and](../../../../condition/prone.md) can't stand (save ends)\n\n**Strained:** You take half the damage the target takes."
feature_type: ability
flavor: You raise the target slightly into the air, then smother them against the ground.
keywords:
    - Psionic
    - Ranged
    - '[Strike](../../../../rule/combat/strike.md)'
    - Telekinesis
metadata:
    action_type: Main action
    class: talent
    cost: 5 Clarity
    distance: Ranged 10
    flavor: You raise the target slightly into the air, then smother them against the ground.
    keywords:
        - Psionic
        - Ranged
        - '[Strike](../../../../rule/combat/strike.md)'
        - Telekinesis
    level: "2"
    name: Levity and Gravity
    scc: mcdm.heroes.v1/feature.ability.talent.level-2/levity-and-gravity
    target: One creature or object
    type: ability
name: Levity and Gravity
target: One creature or object
type: feature
usage: Main action
```
