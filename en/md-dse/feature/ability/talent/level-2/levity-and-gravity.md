---
action_type: Main action
class: talent
cost: 5 Clarity
cost_amount: "5"
cost_resource: Clarity
distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: levity-and-gravity
file_dpath: feature/ability/talent/level-2
flavor: You raise the target slightly into the air, then smother them against the ground.
item_id: levity-and-gravity
item_name: Levity and Gravity
keywords:
    - Psionic
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
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
distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: "\n*You raise the target slightly into the air, then smother them against the ground.*\n\n| **Psionic, [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Telekinesis** |               **Main action** |\n|------------------------------------------|------------------------------:|\n| **\U0001F4CF [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10**                         | **\U0001F3AF One creature or object** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Reason](scc:mcdm.heroes.v1/rule.character/reason):**\n\n- **≤11:** 6 + R damage; M < WEAK[, prone](scc:mcdm.heroes.v1/condition/prone)\n- **12-16:** 10 + R damage; M < AVERAGE[, prone](scc:mcdm.heroes.v1/condition/prone)\n- **17+:** 14 + R damage; M < STRONG, [prone and](scc:mcdm.heroes.v1/condition/prone) can't stand (save ends)\n\n**Strained:** You take half the damage the target takes."
feature_type: ability
flavor: You raise the target slightly into the air, then smother them against the ground.
keywords:
    - Psionic
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Telekinesis
metadata:
    action_type: Main action
    class: talent
    cost: 5 Clarity
    distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: You raise the target slightly into the air, then smother them against the ground.
    keywords:
        - Psionic
        - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
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
