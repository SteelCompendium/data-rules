---
action_type: Main action
class: talent
cost: 9 Clarity
cost_amount: "9"
cost_resource: Clarity
distance: Ranged 10
feature_type: ability
file_basename: greater-kinetic-grip
file_dpath: feature/ability/talent/level-6
flavor: You raise the target into the air without breaking a sweat.
item_id: greater-kinetic-grip
item_name: Greater Kinetic Grip
keywords:
    - Psionic
    - Ranged
    - Strike
    - Telekinesis
level: "6"
name: Greater Kinetic Grip
scc: mcdm.heroes.v1/feature.ability.talent.level-6/greater-kinetic-grip
source: mcdm.heroes.v1
target: One creature or object
type: ability
---

```ds-feature
cost: 9 Clarity
distance: Ranged 10
effects:
    - effect: "\n*You raise the target into the air without breaking a sweat.*\n\n| **Psionic, Ranged**, **Strike, Telekinesis** |               **Main action** |\n|----------------------------------------------|------------------------------:|\n| **\U0001F4CF Ranged 10**                             | **\U0001F3AF One creature or object** |\n\n**Power Roll + [Reason](scc:mcdm.heroes.v1/rule.character/reason):**\n\n- **≤11:** Slide 4 + R; M < WEAK, the [forced movement](scc:mcdm.heroes.v1/movement/forced-movement) is vertical\n- **12-16:** Slide 8 + R; M < AVERAGE, the [forced movement](scc:mcdm.heroes.v1/movement/forced-movement) is vertical\n- **17+:** Slide 12 + R; [prone](scc:mcdm.heroes.v1/condition/prone); M < STRONG, the [forced movement](scc:mcdm.heroes.v1/movement/forced-movement) is vertical\n\n**Strained:** The [forced movement](scc:mcdm.heroes.v1/movement/forced-movement) ignores stability. You take 2d6 damage and are [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)."
feature_type: ability
flavor: You raise the target into the air without breaking a sweat.
keywords:
    - Psionic
    - Ranged
    - Strike
    - Telekinesis
metadata:
    action_type: Main action
    class: talent
    cost: 9 Clarity
    distance: Ranged 10
    flavor: You raise the target into the air without breaking a sweat.
    keywords:
        - Psionic
        - Ranged
        - Strike
        - Telekinesis
    level: "6"
    name: Greater Kinetic Grip
    scc: mcdm.heroes.v1/feature.ability.talent.level-6/greater-kinetic-grip
    target: One creature or object
    type: ability
name: Greater Kinetic Grip
target: One creature or object
type: feature
usage: Main action
```
