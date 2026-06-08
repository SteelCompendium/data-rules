---
action_type: Free maneuver
class: shadow
distance: 2 cube within 10
effect: Each target takes acid, fire, or poison damage (your choice) equal to your [Agility](scc:mcdm.heroes.v1/rule.character/agility) score.
feature_type: ability
file_basename: time-bomb
file_dpath: feature/ability/shadow/level-8
flavor: The longer it cooks, the bigger the boom.
item_id: time-bomb
item_name: Time Bomb
keywords:
    - Area
    - Ranged
level: "8"
name: Time Bomb
scc: mcdm.heroes.v1/feature.ability.shadow.level-8/time-bomb
source: mcdm.heroes.v1
spend: '2+ Insight: For every 2 insight spent, you increase the cube''s [size](scc:mcdm.heroes.v1/rule.character/size) by 1 and gain 1 [surge](scc:mcdm.heroes.v1/rule.resource/surge) that can be used only with this ability.'
target: Each enemy in the area
type: ability
---

```ds-feature
distance: 2 cube within 10
effects:
    - effect: Each target takes acid, fire, or poison damage (your choice) equal to your [Agility](scc:mcdm.heroes.v1/rule.character/agility) score.
    - effect: '2+ Insight: For every 2 insight spent, you increase the cube''s [size](scc:mcdm.heroes.v1/rule.character/size) by 1 and gain 1 [surge](scc:mcdm.heroes.v1/rule.resource/surge) that can be used only with this ability.'
      name: Spend
feature_type: ability
flavor: The longer it cooks, the bigger the boom.
keywords:
    - Area
    - Ranged
metadata:
    action_type: Free maneuver
    class: shadow
    distance: 2 cube within 10
    effect: Each target takes acid, fire, or poison damage (your choice) equal to your [Agility](scc:mcdm.heroes.v1/rule.character/agility) score.
    flavor: The longer it cooks, the bigger the boom.
    keywords:
        - Area
        - Ranged
    level: "8"
    name: Time Bomb
    scc: mcdm.heroes.v1/feature.ability.shadow.level-8/time-bomb
    spend: '2+ Insight: For every 2 insight spent, you increase the cube''s [size](scc:mcdm.heroes.v1/rule.character/size) by 1 and gain 1 [surge](scc:mcdm.heroes.v1/rule.resource/surge) that can be used only with this ability.'
    target: Each enemy in the area
    type: ability
name: Time Bomb
target: Each enemy in the area
type: feature
usage: Free maneuver
```
