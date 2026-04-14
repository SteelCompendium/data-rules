---
action_type: Triggered
class: elementalist
distance: Ranged 10
effect: The forced movement distance gains a bonus equal to your Reason score.
feature_type: ability
file_basename: explosive-assistance
file_dpath: feature/ability/elementalist/level-1
flavor: You add a little magic to an ally's aggression at just the right time.
item_id: explosive-assistance
item_name: Explosive Assistance
keywords:
    - Fire
    - Magic
    - Ranged
level: "1"
name: Explosive Assistance
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/explosive-assistance
source: mcdm.heroes.v1
spend: '1 Essence: The forced movement distance gains a bonus equal to twice your Reason score instead.'
subtype: triggered
target: Self or one ally
trigger: The target force moves a creature or object.
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: The forced movement distance gains a bonus equal to your Reason score.
    - effect: '1 Essence: The forced movement distance gains a bonus equal to twice your Reason score instead.'
      name: Spend
feature_type: ability
flavor: You add a little magic to an ally's aggression at just the right time.
keywords:
    - Fire
    - Magic
    - Ranged
metadata:
    action_type: Triggered
    class: elementalist
    distance: Ranged 10
    effect: The forced movement distance gains a bonus equal to your Reason score.
    flavor: You add a little magic to an ally's aggression at just the right time.
    keywords:
        - Fire
        - Magic
        - Ranged
    level: "1"
    name: Explosive Assistance
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/explosive-assistance
    spend: '1 Essence: The forced movement distance gains a bonus equal to twice your Reason score instead.'
    subtype: triggered
    target: Self or one ally
    trigger: The target force moves a creature or object.
    type: ability
name: Explosive Assistance
target: Self or one ally
trigger: The target force moves a creature or object.
type: feature
usage: Triggered
```
