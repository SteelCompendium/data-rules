---
equipment_text: You wear medium armor and wield a polearm.
file_basename: guisarmier
file_dpath: kit
flavor: The Guisarmier kit is for those who want to use a polearm for extended reach while remaining protected by sturdy armor. This is the kit that allows you to become the ultimate halberd, longspear, or glaive fighter.
item_id: guisarmier
item_name: Guisarmier
name: Guisarmier
scc: mcdm.heroes.v1/kit/guisarmier
source: mcdm.heroes.v1
type: kit
---

The [Guisarmier](scc:mcdm.heroes.v1/kit/guisarmier) kit is for those who want to use a polearm for extended reach while remaining protected by sturdy armor. This is the kit that allows you to become the ultimate halberd, longspear, or glaive fighter.

##### Equipment

You wear medium armor and wield a polearm.

##### Kit Bonuses

**[Stamina](scc:mcdm.heroes.v1/rule.health/stamina) [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +6 per [echelon](scc:mcdm.heroes.v1/rule.general/echelon)

**[Stability](scc:mcdm.heroes.v1/rule.character/stability) [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

**[Melee](scc:mcdm.heroes.v1/rule.combat/melee) Damage [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +2/+2/+2

**[Melee](scc:mcdm.heroes.v1/rule.combat/melee) [Distance](scc:mcdm.heroes.v1/rule.combat/distance) [Bonus](scc:mcdm.heroes.v1/rule.dice/bonuses-and-penalties):** +1

##### Signature Ability

###### Forward Thrust, Backward Smash

*In your hands, the haft is as good as the head.*

| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |                 **Main action** |
|---------------------------|--------------------------------:|
| **📏 [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2**            | **🎯 Two creatures or objects** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 4 damage
- **12-16:** 7 damage
- **17+:** 9 damage

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2'
effects:
    - effect: "*In your hands, the haft is as good as the head.*\n\n| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |                 **Main action** |\n|---------------------------|--------------------------------:|\n| **\U0001F4CF [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2**            | **\U0001F3AF Two creatures or objects** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might) or [Agility](scc:mcdm.heroes.v1/rule.character/agility):**\n\n- **≤11:** 4 damage\n- **12-16:** 7 damage\n- **17+:** 9 damage"
feature_type: ability
flavor: In your hands, the haft is as good as the head.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 2'
    flavor: In your hands, the haft is as good as the head.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Forward Thrust, Backward Smash
    subtype: signature
    target: Two creatures or objects
    type: ability
name: Forward Thrust, Backward Smash
target: Two creatures or objects
type: feature
usage: Main action
```
