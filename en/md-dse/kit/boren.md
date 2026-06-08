---
file_basename: boren
file_dpath: kit
flavor: With this stormwight kit, you channel your primordial ferocity into the form of a bear, becoming large, durable, and imposing. Boren are tied to the craggy, rocky north, and this aspect is associated with the blizzard's bitter cold.
item_id: boren
item_name: Boren
name: Boren
scc: mcdm.heroes.v1/kit/boren
source: mcdm.heroes.v1
type: kit
---

With this stormwight kit, you channel your [primordial ferocity](scc:mcdm.heroes.v1/feature.fury.level-10/primordial-ferocity) into the form of a bear, becoming large, durable, and imposing. [Boren](scc:mcdm.heroes.v1/kit/boren) are tied to the craggy, rocky north, and this aspect is associated with the blizzard's bitter cold.

##### Signature Ability

###### Bear Claws

*Attacks with your sharp and deadly claws grab the weak.*

| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |
|---------------------------|------------------------------:|
| **📏 [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature or object** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 2 + M damage; M < WEAK, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
- **12-16:** 5 + M damage; M < AVERAGE, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)
- **17+:** 11 + M damage; M < STRONG, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: "*Attacks with your sharp and deadly claws grab the weak.*\n\n| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |\n|---------------------------|------------------------------:|\n| **\U0001F4CF [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1**            | **\U0001F3AF One creature or object** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might):**\n\n- **≤11:** 2 + M damage; M < WEAK, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)\n- **12-16:** 5 + M damage; M < AVERAGE, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)\n- **17+:** 11 + M damage; M < STRONG, [grabbed](scc:mcdm.heroes.v1/condition/grabbed)"
feature_type: ability
flavor: Attacks with your sharp and deadly claws grab the weak.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
    flavor: Attacks with your sharp and deadly claws grab the weak.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Bear Claws
    subtype: signature
    target: One creature or object
    type: ability
name: Bear Claws
target: One creature or object
type: feature
usage: Main action
```
