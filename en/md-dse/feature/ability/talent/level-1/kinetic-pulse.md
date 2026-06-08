---
action_type: Main action
class: talent
distance: 1 [burst](scc:mcdm.heroes.v1/rule.combat/burst)
feature_type: ability
file_basename: kinetic-pulse
file_dpath: feature/ability/talent/level-1
flavor: The force of your mind hurls enemies backward.
item_id: kinetic-pulse
item_name: Kinetic Pulse
keywords:
    - Area
    - Psionic
    - Telepathy
level: "1"
name: Kinetic Pulse
scc: mcdm.heroes.v1/feature.ability.talent.level-1/kinetic-pulse
source: mcdm.heroes.v1
subtype: signature
target: Each enemy in the area
type: ability
---

```ds-feature
distance: 1 [burst](scc:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: "\n*The force of your mind hurls enemies backward.*\n\n| **Area, Psionic, Telepathy** |               **Main action** |\n|------------------------------|------------------------------:|\n| **\U0001F4CF 1 [burst](scc:mcdm.heroes.v1/rule.combat/burst)**               | **\U0001F3AF Each enemy in the area** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Reason](scc:mcdm.heroes.v1/rule.character/reason):**\n\n- **≤11:** 2 psychic damage\n- **12-16:** 5 psychic damage; push 1\n- **17+:** 7 psychic damage; push 2\n\n**Strained:** The size of the [burst](scc:mcdm.heroes.v1/rule.combat/burst) increases by 2, and you are [bleeding](scc:mcdm.heroes.v1/condition/bleeding) until the start of your next turn."
feature_type: ability
flavor: The force of your mind hurls enemies backward.
keywords:
    - Area
    - Psionic
    - Telepathy
metadata:
    action_type: Main action
    class: talent
    distance: 1 [burst](scc:mcdm.heroes.v1/rule.combat/burst)
    flavor: The force of your mind hurls enemies backward.
    keywords:
        - Area
        - Psionic
        - Telepathy
    level: "1"
    name: Kinetic Pulse
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/kinetic-pulse
    subtype: signature
    target: Each enemy in the area
    type: ability
name: Kinetic Pulse
target: Each enemy in the area
type: feature
usage: Main action
```
