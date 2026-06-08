---
action_type: Main action
class: censor
distance: 2 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 1
feature_type: ability
file_basename: back-blasphemer
file_dpath: feature/ability/censor/level-1
flavor: You channel power through your weapon to repel foes.
item_id: back-blasphemer
item_name: Back Blasphemer!
keywords:
    - Area
    - Magic
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
level: "1"
name: Back Blasphemer!
scc: mcdm.heroes.v1/feature.ability.censor.level-1/back-blasphemer
source: mcdm.heroes.v1
subtype: signature
target: Each enemy in the area
type: ability
---

```ds-feature
distance: 2 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 1
effects:
    - effect: "\n*You channel power through your weapon to repel foes.*\n\n| **Area, Magic, [Melee](scc:mcdm.heroes.v1/rule.combat/melee), Weapon** |               **Main action** |\n|--------------------------------|------------------------------:|\n| **\U0001F4CF 2 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 1**         | **\U0001F3AF Each enemy in the area** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Presence](scc:mcdm.heroes.v1/rule.character/presence):**\n\n- **≤11:** 2 holy damage; push 1\n- **12-16:** 4 holy damage; push 2\n- **17+:** 6 holy damage; push 3"
feature_type: ability
flavor: You channel power through your weapon to repel foes.
keywords:
    - Area
    - Magic
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
metadata:
    action_type: Main action
    class: censor
    distance: 2 [cube](scc:mcdm.heroes.v1/rule.combat/cube) within 1
    flavor: You channel power through your weapon to repel foes.
    keywords:
        - Area
        - Magic
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - Weapon
    level: "1"
    name: Back Blasphemer!
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/back-blasphemer
    subtype: signature
    target: Each enemy in the area
    type: ability
name: Back Blasphemer!
target: Each enemy in the area
type: feature
usage: Main action
```
