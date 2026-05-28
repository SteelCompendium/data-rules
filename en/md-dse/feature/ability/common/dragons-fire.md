---
action_type: Main action
distance: 5 x 1 line within 1
feature_type: ability
file_basename: dragons-fire
file_dpath: feature/ability/common
flavor: You open your maw and unleash hell.
item_id: dragons-fire
item_name: Dragon's Fire
keywords:
    - Area
    - Magic
name: Dragon's Fire
scc: mcdm.heroes.v1/feature.ability.common/dragons-fire
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
distance: 5 x 1 line within 1
effects:
    - effect: "*You open your maw and unleash hell.*\n\n| **Area, Magic**            |               **Main action** |\n|----------------------------|------------------------------:|\n| **\U0001F4CF 5 x 1 line within 1** | **\U0001F3AF Each enemy in the area** |\n\n**Power Roll + Your Highest Characteristic Score:**\n\n- **≤11:** 5 fire damage\n- **12-16:** 8 fire damage\n- **17+:** 11 fire damage\n\n**Invulnerable:** When an ability roll made against you obtains a tier 1 outcome, you can ignore its damage and effects.\n\n**Leyline Walker:** Once per turn as a move action, you can spend any amount of your movement to instead [teleport](scc:mcdm.heroes.v1/movement/teleport) that distance.\n\n**Life:** Whenever you would die, you can spend a Recovery to regain Stamina instead. If you have no Recoveries to spend, you die.\n\n**Magic Resistance III:** The benefit of the armor's Magic Resistance II enhancement extends to each ally within 3 squares of you.\n\n**Phasing III:** Your movement doesn't provoke opportunity attacks, and you can move through the space of any enemy as if they were an ally. You can't end your turn in an enemy's space.\n\n**Psionic Resistance III:** The benefit of the armor's Psionic Resistance II enhancement extends to each ally within 3 squares of you.\n\n**Temporal Flux:** Whenever you move out of a square, you can choose to leave an imprint behind that lasts until the end of the encounter, until your imprint takes 20 or more damage, or until you create a new imprint. The square is occupied by your imprint, and you can share that space with it.\n\nOn your turn, you can [teleport](scc:mcdm.heroes.v1/movement/teleport) to the imprint's space as a free maneuver. When you are targeted by an ability, you can use a free triggered action to [teleport](scc:mcdm.heroes.v1/movement/teleport) to your imprint, and the power roll for the ability is an automatic tier 1 result.\n\n**Unbending:** You can't be subjected to [forced movement](scc:mcdm.heroes.v1/movement/forced-movement) unless you choose to be. Effects that ignore Stability also ignore this enhancement."
feature_type: ability
flavor: You open your maw and unleash hell.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    distance: 5 x 1 line within 1
    flavor: You open your maw and unleash hell.
    keywords:
        - Area
        - Magic
    name: Dragon's Fire
    scc: mcdm.heroes.v1/feature.ability.common/dragons-fire
    target: Each enemy in the area
    type: ability
name: Dragon's Fire
target: Each enemy in the area
type: feature
usage: Main action
```
