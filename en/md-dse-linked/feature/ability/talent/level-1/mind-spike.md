---
action_type: Main action
class: talent
distance: Ranged 10
feature_type: ability
file_basename: mind-spike
file_dpath: feature/ability/talent/level-1
flavor: A telepathic bolt instantly zaps a creature's brain.
item_id: mind-spike
item_name: Mind Spike
keywords:
    - Psionic
    - Ranged
    - Strike
    - Telepathy
level: "1"
name: Mind Spike
scc: mcdm.heroes.v1/feature.ability.talent.level-1/mind-spike
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: "\n*A telepathic bolt instantly zaps a creature's brain.*\n\n| **Psionic, Ranged**, **Strike, Telepathy** |     **Main action** |\n|--------------------------------------------|--------------------:|\n| **\U0001F4CF Ranged 10**                           | **\U0001F3AF One creature** |\n\n**[Power Roll](../../../../rule/dice/power-roll.md) + [Reason](../../../../rule/character/reason.md):**\n\n- **≤11:** 2 + R psychic damage\n- **12-16:** 4 + R psychic damage\n- **17+:** 6 + R psychic damage\n\n**Strained:** The target takes an extra 2 psychic damage. You also take 2 psychic damage that can't be reduced in any way."
feature_type: ability
flavor: A telepathic bolt instantly zaps a creature's brain.
keywords:
    - Psionic
    - Ranged
    - Strike
    - Telepathy
metadata:
    action_type: Main action
    class: talent
    distance: Ranged 10
    flavor: A telepathic bolt instantly zaps a creature's brain.
    keywords:
        - Psionic
        - Ranged
        - Strike
        - Telepathy
    level: "1"
    name: Mind Spike
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/mind-spike
    target: One creature
    type: ability
name: Mind Spike
target: One creature
type: feature
usage: Main action
```
