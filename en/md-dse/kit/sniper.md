---
disengage_bonus: "+1"
equipment_text: You wear no armor and wield a bow.
file_basename: sniper
file_dpath: kit
item_id: sniper
item_name: Sniper
name: Sniper
ranged_damage_bonus: +0/+0/+4
scc: mcdm.heroes.v1/kit/sniper
source: mcdm.heroes.v1
speed_bonus: "+1"
type: kit
---

The [Sniper](scc:mcdm.heroes.v1/kit/sniper) kit gives you the tools and techniques to take down enemies from afar. This kit can help you become the archer who lurks behind trees or down tunnels, picking off enemies with a bow or crossbow as they approach.

##### Equipment

You wear no armor and wield a bow.

##### Kit Bonuses

**Speed Bonus:** +1

**Ranged Damage Bonus:** +0/+0/+4

**Ranged [Distance](scc:mcdm.heroes.v1/rule.combat/distance) Bonus:** +10

**Disengage Bonus:** +1

##### Signature Ability

###### Patient Shot

*Breathe... aim... wait... then strike!*

| **Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|----------------------------|--------------------:|
| **📏 Ranged 15**           | **🎯 One creature** |

**Power Roll + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 3 + M or A damage
- **12-16:** 6 + M or A damage
- **17+:** 13 + M or A damage

**Effect:** If you don't take a move action this turn, this [strike](scc:mcdm.heroes.v1/rule.combat/strike) deals extra damage equal to your [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility) score (your choice).

```ds-feature
distance: Ranged 15
effects:
    - effect: If you don't take a move action this turn, this [strike](scc:mcdm.heroes.v1/rule.combat/strike) deals extra damage equal to your [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility) score (your choice).
feature_type: ability
flavor: Breathe... aim... wait... then strike!
keywords:
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: Ranged 15
    effect: If you don't take a move action this turn, this [strike](scc:mcdm.heroes.v1/rule.combat/strike) deals extra damage equal to your [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility) score (your choice).
    flavor: Breathe... aim... wait... then strike!
    keywords:
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Patient Shot
    subtype: signature
    target: One creature
    type: ability
name: Patient Shot
target: One creature
type: feature
usage: Main action
```
