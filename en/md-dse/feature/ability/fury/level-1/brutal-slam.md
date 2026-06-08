---
action_type: Main action
class: fury
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
feature_type: ability
file_basename: brutal-slam
file_dpath: feature/ability/fury/level-1
flavor: The heavy impact of your weapon attacks drives your foes ever back.
item_id: brutal-slam
item_name: Brutal Slam
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Brutal Slam
scc: mcdm.heroes.v1/feature.ability.fury.level-1/brutal-slam
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
type: ability
---

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: "\n*The heavy impact of your weapon attacks drives your foes ever back.*\n\n| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |                **Main action** |\n|---------------------------|-------------------------------:|\n| **\U0001F4CF [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1**            |  **\U0001F3AF One creature or object** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might):**\n\n- **≤11:** 3 + M damage; push 1\n- **12-16:** 6 + M damage; push 2\n- **17+:** 9 + M damage; push 4"
feature_type: ability
flavor: The heavy impact of your weapon attacks drives your foes ever back.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: fury
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
    flavor: The heavy impact of your weapon attacks drives your foes ever back.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Brutal Slam
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/brutal-slam
    subtype: signature
    target: One creature or object
    type: ability
name: Brutal Slam
target: One creature or object
type: feature
usage: Main action
```
