---
action_type: Maneuver
class: troubadour
distance: 2 burst
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
distance: 2 burst
effects:
    - effect: "\n*Your instrument rings true and your music blows everyone away.*\n\n| **Area, Magic** |                  **Maneuver** |\n|-----------------|------------------------------:|\n| **\U0001F4CF 2 burst**  | **\U0001F3AF Each enemy in the area** |\n\n**Power Roll + [Presence](scc:mcdm.heroes.v1/rule.character/presence):**\n\n- **≤11:** Push 1\n- **12-16:** Push 2\n- **17+:** Push 3"
feature_type: ability
flavor: Your instrument rings true and your music blows everyone away.
keywords:
    - Area
    - Magic
metadata:
    action_type: Maneuver
    class: troubadour
    distance: 2 burst
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
