---
action_type: Main action
class: censor
distance: Melee 1
feature_type: ability
file_basename: halt-miscreant
file_dpath: feature/ability/censor/level-1
flavor: You infuse your weapon with holy magic that makes it difficult for your foe to get away.
item_id: halt-miscreant
item_name: Halt Miscreant!
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Halt Miscreant!
scc: mcdm.heroes.v1/feature.ability.censor.level-1/halt-miscreant
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: "\n*You infuse your weapon with holy magic that makes it difficult for your foe to get away.*\n\n| **Melee, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon**  |               **Main action** |\n|----------------------------|------------------------------:|\n| **\U0001F4CF Melee 1**             | **\U0001F3AF One creature or object** |\n\n**Power Roll + [Might](scc:mcdm.heroes.v1/rule.character/might):**\n\n- **≤11:** 2 + M holy damage; P < WEAK, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)\n- **12-16:** 5 + M holy damage; P < AVERAGE, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)\n- **17+:** 7 + M holy damage; P < STRONG, [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)"
feature_type: ability
flavor: You infuse your weapon with holy magic that makes it difficult for your foe to get away.
keywords:
    - Melee
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: censor
    distance: Melee 1
    flavor: You infuse your weapon with holy magic that makes it difficult for your foe to get away.
    keywords:
        - Melee
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Halt Miscreant!
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/halt-miscreant
    subtype: signature
    target: One creature or object
    type: ability
name: Halt Miscreant!
target: One creature or object
type: feature
usage: Main action
```
