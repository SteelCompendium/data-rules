---
action_type: Triggered
class: censor
distance: Ranged 10
effect: You spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries) and the target regains [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) equal to your [recovery value](scc:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
file_basename: my-life-for-yours
file_dpath: feature/ability/censor/level-1
flavor: You channel some of your vitality into more resilience for you or an ally.
item_id: my-life-for-yours
item_name: My Life for Yours
keywords:
    - Magic
    - Ranged
level: "1"
name: My Life for Yours
scc: mcdm.heroes.v1/feature.ability.censor.level-1/my-life-for-yours
source: mcdm.heroes.v1
spend: '1 Wrath: You can end one effect on the target that is ended by a saving throw or that ends at the end of their turn, or a [prone](scc:mcdm.heroes.v1/condition/prone) target can stand up.'
subtype: triggered
target: Self or one ally
trigger: The target starts their turn or takes damage.
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: You spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries) and the target regains [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) equal to your [recovery value](scc:mcdm.heroes.v1/rule.health/recoveries).
    - effect: '1 Wrath: You can end one effect on the target that is ended by a saving throw or that ends at the end of their turn, or a [prone](scc:mcdm.heroes.v1/condition/prone) target can stand up.'
      name: Spend
feature_type: ability
flavor: You channel some of your vitality into more resilience for you or an ally.
keywords:
    - Magic
    - Ranged
metadata:
    action_type: Triggered
    class: censor
    distance: Ranged 10
    effect: You spend a [Recovery](scc:mcdm.heroes.v1/rule.health/recoveries) and the target regains [Stamina](scc:mcdm.heroes.v1/rule.health/stamina) equal to your [recovery value](scc:mcdm.heroes.v1/rule.health/recoveries).
    flavor: You channel some of your vitality into more resilience for you or an ally.
    keywords:
        - Magic
        - Ranged
    level: "1"
    name: My Life for Yours
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/my-life-for-yours
    spend: '1 Wrath: You can end one effect on the target that is ended by a saving throw or that ends at the end of their turn, or a [prone](scc:mcdm.heroes.v1/condition/prone) target can stand up.'
    subtype: triggered
    target: Self or one ally
    trigger: The target starts their turn or takes damage.
    type: ability
name: My Life for Yours
target: Self or one ally
trigger: The target starts their turn or takes damage.
type: feature
usage: Triggered
```
