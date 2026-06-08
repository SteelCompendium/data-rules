---
equipment_text: You wear medium armor and wield a bow and a medium weapon.
file_basename: ranger
file_dpath: kit
item_id: ranger
item_name: Ranger
name: Ranger
scc: mcdm.heroes.v1/kit/ranger
source: mcdm.heroes.v1
type: kit
---

The [Ranger](scc:mcdm.heroes.v1/kit/ranger) kit outfits you with medium armor and weapons for every challenge, letting you easily switch between [melee](scc:mcdm.heroes.v1/rule.combat/melee) and [ranged](scc:mcdm.heroes.v1/rule.combat/ranged) combat. This kit provides a good balance of [bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties)es to defense and offense to create a hero who is a jack-of-all-trades.

##### Equipment

You wear medium armor and wield a bow and a medium weapon.

##### Kit Bonuses

**[Stamina](scc:mcdm.heroes.v1/rule.health/stamina) [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +6 per [echelon](scc:mcdm.heroes.v1/rule.general/echelon)

**[Speed](scc:mcdm.heroes.v1/rule.character/speed) [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

**[Melee](scc:mcdm.heroes.v1/rule.combat/melee) Damage [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1/+1/+1

**[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) Damage [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1/+1/+1

**[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) [Distance](scc:mcdm.heroes.v1/rule.combat/distance) [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +5

**Disengage [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

##### Signature Ability

###### Hamstring Shot

*A well-placed shot leaves your enemy struggling to move.*

| **[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|----------------------------|--------------------:|
| **📏 [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10**           | **🎯 One creature** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 3 + M or A damage; A < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
- **12-16:** 5 + M or A damage; A < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
- **17+:** 7 + M or A damage; A < STRONG, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)

```ds-feature
distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: "*A well-placed shot leaves your enemy struggling to move.*\n\n| **[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |\n|----------------------------|--------------------:|\n| **\U0001F4CF [Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10**           | **\U0001F3AF One creature** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 3 + M or A damage; A < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)\n- **12-16:** 5 + M or A damage; A < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)\n- **17+:** 7 + M or A damage; A < STRONG, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)"
feature_type: ability
flavor: A well-placed shot leaves your enemy struggling to move.
keywords:
    - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: A well-placed shot leaves your enemy struggling to move.
    keywords:
        - '[Ranged](scc:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Hamstring Shot
    subtype: signature
    target: One creature
    type: ability
name: Hamstring Shot
target: One creature
type: feature
usage: Main action
```
