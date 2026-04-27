---
action_type: Main action
class: rapid-fire
distance: Ranged 12
feature_type: ability
file_basename: two-shot
file_dpath: feature/ability/rapid-fire
flavor: When you fire two arrows back-to-back, both hit their mark.
item_id: two-shot
item_name: Two Shot
keywords:
    - Ranged
    - Strike
    - Weapon
name: Two Shot
scc: mcdm.heroes.v1/feature.ability.rapid-fire/two-shot
source: mcdm.heroes.v1
subtype: signature
target: Two creatures or objects
type: ability
---

```ds-feature
distance: Ranged 12
effects:
    - effect: "*When you fire two arrows back-to-back, both hit their mark.*\n\n| **Ranged, Strike, Weapon** |                 **Main action** |\n|----------------------------|--------------------------------:|\n| **\U0001F4CF Ranged 12**           | **\U0001F3AF Two creatures or objects** |\n\n**Power Roll + Might or Agility:**\n\n- **≤11:** 4 damage\n- **12-16:** 6 damage\n- **17+:** 8 damage"
feature_type: ability
flavor: When you fire two arrows back-to-back, both hit their mark.
keywords:
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: rapid-fire
    distance: Ranged 12
    flavor: When you fire two arrows back-to-back, both hit their mark.
    keywords:
        - Ranged
        - Strike
        - Weapon
    name: Two Shot
    scc: mcdm.heroes.v1/feature.ability.rapid-fire/two-shot
    subtype: signature
    target: Two creatures or objects
    type: ability
name: Two Shot
target: Two creatures or objects
type: feature
usage: Main action
```
