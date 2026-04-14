---
action_type: Triggered
class: troubadour
distance: Ranged 10
effect: An edge on the triggering roll becomes a bane, or a double edge becomes an edge. A bane becomes an edge, or a double bane becomes a bane.
feature_type: ability
file_basename: turnabout-is-fair-play
file_dpath: feature/ability/troubadour/level-1
flavor: All's fair in love and whatever.
item_id: turnabout-is-fair-play
item_name: Turnabout Is Fair Play
keywords:
    - Ranged
level: "1"
name: Turnabout Is Fair Play
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/turnabout-is-fair-play
source: mcdm.heroes.v1
spend: '3 Drama: An edge on the triggering roll becomes a double bane, or a double edge is negated. A bane becomes a double edge, or a double bane is negated.'
subtype: triggered
target: One creature
trigger: The target makes an ability roll that has an edge, a double edge, a bane, or a double bane.
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: An edge on the triggering roll becomes a bane, or a double edge becomes an edge. A bane becomes an edge, or a double bane becomes a bane.
    - effect: '3 Drama: An edge on the triggering roll becomes a double bane, or a double edge is negated. A bane becomes a double edge, or a double bane is negated.'
      name: Spend
feature_type: ability
flavor: All's fair in love and whatever.
keywords:
    - Ranged
metadata:
    action_type: Triggered
    class: troubadour
    distance: Ranged 10
    effect: An edge on the triggering roll becomes a bane, or a double edge becomes an edge. A bane becomes an edge, or a double bane becomes a bane.
    flavor: All's fair in love and whatever.
    keywords:
        - Ranged
    level: "1"
    name: Turnabout Is Fair Play
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/turnabout-is-fair-play
    spend: '3 Drama: An edge on the triggering roll becomes a double bane, or a double edge is negated. A bane becomes a double edge, or a double bane is negated.'
    subtype: triggered
    target: One creature
    trigger: The target makes an ability roll that has an edge, a double edge, a bane, or a double bane.
    type: ability
name: Turnabout Is Fair Play
target: One creature
trigger: The target makes an ability roll that has an edge, a double edge, a bane, or a double bane.
type: feature
usage: Triggered
```
