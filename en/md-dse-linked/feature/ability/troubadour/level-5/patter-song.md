---
action_type: Maneuver
class: troubadour
cost: 9 Drama
cost_amount: "9"
cost_resource: Drama
distance: Ranged 10
feature_type: ability
file_basename: patter-song
file_dpath: feature/ability/troubadour/level-5
flavor: Dazzle them with your fancy patter and they forget where they were.
item_id: patter-song
item_name: Patter Song
keywords:
    - Magic
    - Ranged
level: "5"
name: Patter Song
scc: mcdm.heroes.v1/feature.ability.troubadour.level-5/patter-song
source: mcdm.heroes.v1
target: Special
type: ability
---

```ds-feature
cost: 9 Drama
distance: Ranged 10
effects:
    - effect: "\n*Dazzle them with your fancy patter and they forget where they were.*\n\n| **Magic, Ranged** |   **Maneuver** |\n|-------------------|---------------:|\n| **\U0001F4CF Ranged 10**  | **\U0001F3AF Special** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Presence](../../../../rule/character/presence.md):**\n\n- **≤11:** One ally within [distance](../../../../rule/combat/distance.md) can take their turn immediately after yours.\n- **12-16:** Two allies within [distance](../../../../rule/combat/distance.md) can take their turns immediately after yours in any order.\n- **17+:** Three allies within [distance](../../../../rule/combat/distance.md) can take their turns immediately after yours in any order. One of those allies can have already taken a turn this combat round."
feature_type: ability
flavor: Dazzle them with your fancy patter and they forget where they were.
keywords:
    - Magic
    - Ranged
metadata:
    action_type: Maneuver
    class: troubadour
    cost: 9 Drama
    distance: Ranged 10
    flavor: Dazzle them with your fancy patter and they forget where they were.
    keywords:
        - Magic
        - Ranged
    level: "5"
    name: Patter Song
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-5/patter-song
    target: Special
    type: ability
name: Patter Song
target: Special
type: feature
usage: Maneuver
```
