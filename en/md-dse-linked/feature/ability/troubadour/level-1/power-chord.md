---
action_type: Maneuver
class: troubadour
distance: 2 [burst](../../../../rule/combat/burst.md)
feature_type: ability
file_basename: power-chord
file_dpath: feature/ability/troubadour/level-1
flavor: Your instrument rings true and your music blows everyone away.
item_id: power-chord
item_name: Power Chord
keywords:
    - Area
    - Magic
level: "1"
name: Power Chord
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/power-chord
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
distance: 2 [burst](../../../../rule/combat/burst.md)
effects:
    - effect: "\n*Your instrument rings true and your music blows everyone away.*\n\n| **Area, Magic** |                  **Maneuver** |\n|-----------------|------------------------------:|\n| **\U0001F4CF 2 [burst](../../../../rule/combat/burst.md)**  | **\U0001F3AF Each enemy in the area** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Presence](../../../../rule/character/presence.md):**\n\n- **≤11:** Push 1\n- **12-16:** Push 2\n- **17+:** Push 3"
feature_type: ability
flavor: Your instrument rings true and your music blows everyone away.
keywords:
    - Area
    - Magic
metadata:
    action_type: Maneuver
    class: troubadour
    distance: 2 [burst](../../../../rule/combat/burst.md)
    flavor: Your instrument rings true and your music blows everyone away.
    keywords:
        - Area
        - Magic
    level: "1"
    name: Power Chord
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/power-chord
    target: Each enemy in the area
    type: ability
name: Power Chord
target: Each enemy in the area
type: feature
usage: Maneuver
```
