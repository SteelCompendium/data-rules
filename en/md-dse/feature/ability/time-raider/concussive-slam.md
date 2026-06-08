---
action_type: Main action
ancestry: time-raider
distance: Ranged 10
feature_type: ability
file_basename: concussive-slam
file_dpath: feature/ability/time-raider
flavor: You slam an invisible force down upon the target.
item_id: concussive-slam
item_name: Concussive Slam
keywords:
    - Psionic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
name: Concussive Slam
scc: mcdm.heroes.v1/feature.ability.time-raider/concussive-slam
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: "*You slam an invisible force down upon the target.*\n\n| **Psionic, Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike)**  | Main action                   |\n|------------------------------|-------------------------------|\n| **\U0001F4CF Ranged 10**             | **\U0001F3AF One creature or object** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Reason](scc:mcdm.heroes.v1/rule.character/reason), [Intuition](scc:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc:mcdm.heroes.v1/rule.character/presence):**\n\n- **≤11:** 2 + R, I, or P damage;\n- **12-16:** 5 + R, I, or P damage; push 1\n- **17+:** 7 + R, I, or P damage; push 2; M < STRONG, [prone](scc:mcdm.heroes.v1/condition/prone)"
feature_type: ability
flavor: You slam an invisible force down upon the target.
keywords:
    - Psionic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    ancestry: time-raider
    distance: Ranged 10
    flavor: You slam an invisible force down upon the target.
    keywords:
        - Psionic
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    name: Concussive Slam
    scc: mcdm.heroes.v1/feature.ability.time-raider/concussive-slam
    subtype: signature
    target: One creature or object
    type: ability
name: Concussive Slam
target: One creature or object
type: feature
usage: Main action
```
