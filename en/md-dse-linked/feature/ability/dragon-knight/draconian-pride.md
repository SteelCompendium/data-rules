---
action_type: Main action
ancestry: dragon-knight
distance: 1 [burst](../../../rule/combat/burst.md)
feature_type: ability
file_basename: draconian-pride
file_dpath: feature/ability/dragon-knight
flavor: You let loose a mighty roar to shake your foes' spirits.
item_id: draconian-pride
item_name: Draconian Pride
keywords:
    - Area
    - Magic
name: Draconian Pride
scc: mcdm.heroes.v1/feature.ability.dragon-knight/draconian-pride
source: mcdm.heroes.v1
subtype: signature
target: Each enemy in the area
type: ability
---

```ds-feature
distance: 1 [burst](../../../rule/combat/burst.md)
effects:
    - effect: "*You let loose a mighty roar to shake your foes' spirits.*\n\n| **Area, Magic** |               **Main action** |\n|-----------------|------------------------------:|\n| **\U0001F4CF 1 [burst](../../../rule/combat/burst.md)**  | **\U0001F3AF Each enemy in the area** |\n\n**[Power Roll](../../../rule/dice/power-roll.md) + [Might](../../../rule/character/might.md) or [Presence](../../../rule/character/presence.md):**\n\n- **≤11:** 2 damage\n- **12-16:** 5 damage; push 1\n- **17+:** 7 damage; push 2"
feature_type: ability
flavor: You let loose a mighty roar to shake your foes' spirits.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    ancestry: dragon-knight
    distance: 1 [burst](../../../rule/combat/burst.md)
    flavor: You let loose a mighty roar to shake your foes' spirits.
    keywords:
        - Area
        - Magic
    name: Draconian Pride
    scc: mcdm.heroes.v1/feature.ability.dragon-knight/draconian-pride
    subtype: signature
    target: Each enemy in the area
    type: ability
name: Draconian Pride
target: Each enemy in the area
type: feature
usage: Main action
```
