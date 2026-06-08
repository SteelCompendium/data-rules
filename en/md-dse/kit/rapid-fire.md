---
disengage_bonus: "+1"
equipment_text: You wear light armor and wield a bow.
file_basename: rapid-fire
file_dpath: kit
item_id: rapid-fire
item_name: Rapid-Fire
name: Rapid-Fire
ranged_damage_bonus: +2/+2/+2
scc: mcdm.heroes.v1/kit/rapid-fire
source: mcdm.heroes.v1
speed_bonus: "+1"
type: kit
---

The Rapid-Fire kit is for archers who want to deal maximum damage by shooting as many arrows as possible into nearby enemies. With this kit, your fighting technique focuses on peppering foes before they can get close enough to counterattack.

##### Equipment

You wear light armor and wield a bow.

##### Kit Bonuses

**[Stamina](scc:mcdm.heroes.v1/rule.health/stamina) Bonus:** +3 per echelon

**Speed Bonus:** +1

**Ranged Damage Bonus:** +2/+2/+2

**Ranged [Distance](scc:mcdm.heroes.v1/rule.combat/distance) Bonus:** +7

**Disengage Bonus:** +1

##### Signature Ability

###### Two Shot

*When you fire two arrows back-to-back, both hit their mark.*

| **Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |                 **Main action** |
|----------------------------|--------------------------------:|
| **📏 Ranged 12**           | **🎯 Two creatures or objects** |

**Power Roll + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 4 damage
- **12-16:** 6 damage
- **17+:** 8 damage

```ds-feature
distance: Ranged 12
effects:
    - effect: "*When you fire two arrows back-to-back, both hit their mark.*\n\n| **Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |                 **Main action** |\n|----------------------------|--------------------------------:|\n| **\U0001F4CF Ranged 12**           | **\U0001F3AF Two creatures or objects** |\n\n**Power Roll + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 4 damage\n- **12-16:** 6 damage\n- **17+:** 8 damage"
feature_type: ability
flavor: When you fire two arrows back-to-back, both hit their mark.
keywords:
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: Ranged 12
    flavor: When you fire two arrows back-to-back, both hit their mark.
    keywords:
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Two Shot
    subtype: signature
    target: Two creatures or objects
    type: ability
name: Two Shot
target: Two creatures or objects
type: feature
usage: Main action
```
