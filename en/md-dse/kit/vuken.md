---
file_basename: vuken
file_dpath: kit
flavor: With this stormwight kit, you channel your primordial ferocity into the form of a wolf, becoming a fleet-footed hunter. Vuken are tied to forests and open steppes, and this aspect is associated with the thunderstorm.
item_id: vuken
item_name: Vuken
name: Vuken
scc: mcdm.heroes.v1/kit/vuken
source: mcdm.heroes.v1
type: kit
---

With this stormwight kit, you channel your [primordial ferocity](scc:mcdm.heroes.v1/feature.fury.level-10/primordial-ferocity) into the form of a wolf, becoming a fleet-footed hunter. [Vuken](scc:mcdm.heroes.v1/kit/vuken) are tied to forests and open steppes, and this aspect is associated with the thunderstorm.

##### Signature Ability

###### Unbalancing Attack

*A wild assault forces your foe onto their back.*

| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |
|---------------------------|------------------------------:|
| **📏 [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature or object** |

**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 4 + M damage; A < WEAK[, prone](scc:mcdm.heroes.v1/condition/prone)
- **12-16:** 7 + M damage; A < AVERAGE[, prone](scc:mcdm.heroes.v1/condition/prone)
- **17+:** 9 + M damage; A < STRONG[, prone](scc:mcdm.heroes.v1/condition/prone)

```ds-feature
distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: "*A wild assault forces your foe onto their back.*\n\n| **[Melee](scc:mcdm.heroes.v1/rule.combat/melee), [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |\n|---------------------------|------------------------------:|\n| **\U0001F4CF [Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1**            | **\U0001F3AF One creature or object** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc:mcdm.heroes.v1/rule.character/might):**\n\n- **≤11:** 4 + M damage; A < WEAK[, prone](scc:mcdm.heroes.v1/condition/prone)\n- **12-16:** 7 + M damage; A < AVERAGE[, prone](scc:mcdm.heroes.v1/condition/prone)\n- **17+:** 9 + M damage; A < STRONG[, prone](scc:mcdm.heroes.v1/condition/prone)"
feature_type: ability
flavor: A wild assault forces your foe onto their back.
keywords:
    - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc:mcdm.heroes.v1/rule.combat/melee) 1'
    flavor: A wild assault forces your foe onto their back.
    keywords:
        - '[Melee](scc:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Unbalancing Attack
    subtype: signature
    target: One creature or object
    type: ability
name: Unbalancing Attack
target: One creature or object
type: feature
usage: Main action
```
