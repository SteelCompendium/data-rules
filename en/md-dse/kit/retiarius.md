---
equipment_text: You wear light armor and wield several ensnaring weapons and a polearm.
file_basename: retiarius
file_dpath: kit
flavor: The retiarius is often depicted as a lightly armored warrior with a net in one hand and a trident in the other, and this kit gives you the equipment and fighting technique to make that happen. Tie up your foe with a net and then poke them to death!
item_id: retiarius
item_name: Retiarius
name: Retiarius
scc: mcdm.heroes.v1/kit/retiarius
source: mcdm.heroes.v1
type: kit
---

The [retiarius](scc:mcdm.heroes.v1/kit/retiarius) is often depicted as a lightly armored warrior with a net in one hand and a trident in the other, and this kit gives you the equipment and fighting technique to make that happen. Tie up your foe with a net and then poke them to death!

##### Equipment

You wear light armor and wield several ensnaring weapons and a polearm.

##### Kit Bonuses

**[Stamina](scc:mcdm.heroes.v1/rule.health/stamina) [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +3 per [echelon](scc:mcdm.heroes.v1/rule.general/echelon)

**[Speed](scc:mcdm.heroes.v1/rule.character/speed) [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

**[Melee](scc:mcdm.heroes.v1/rule.combat/melee) Damage [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +2/+2/+2

**[Melee](scc:mcdm.heroes.v1/rule.combat/melee) [Distance](scc:mcdm.heroes.v1/rule.combat/distance) [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

**Disengage [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

##### Signature Ability

###### Net and Stab

*The well-thrown net that follows your main attack leaves your foes right where you want them.*

| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|---------------------------|--------------------:|
| **📏 [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2**            | **🎯 One creature** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 4 + M or A damage; A < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
- **12-16:** 6 + M or A damage; A < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
- **17+:** 8 + M or A damage; A < STRONG, [restrained](scc:mcdm.heroes.v1/condition/restrained) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2'
effects:
    - roll: Power Roll + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + M or A damage; A < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
      tier2: 6 + M or A damage; A < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
      tier3: 8 + M or A damage; A < STRONG, [restrained](scc:mcdm.heroes.v1/condition/restrained) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
feature_type: ability
flavor: The well-thrown net that follows your main attack leaves your foes right where you want them.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2'
    flavor: The well-thrown net that follows your main attack leaves your foes right where you want them.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Net and Stab
    power_roll_characteristic: '[Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility)'
    subtype: signature
    target: One creature
    tier1: 4 + M or A damage; A < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
    tier2: 6 + M or A damage; A < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
    tier3: 8 + M or A damage; A < STRONG, [restrained](scc:mcdm.heroes.v1/condition/restrained) ([EoT](scc:mcdm.heroes.v1/rule.combat/end-of-turn))
    type: ability
name: Net and Stab
target: One creature
type: feature
usage: Main action
```
