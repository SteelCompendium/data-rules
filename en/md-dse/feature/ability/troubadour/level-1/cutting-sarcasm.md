---
action_type: Main action
class: troubadour
distance: Ranged 10
feature_type: ability
file_basename: cutting-sarcasm
file_dpath: feature/ability/troubadour/level-1
flavor: There you are, radiating your usual charisma.
item_id: cutting-sarcasm
item_name: Cutting Sarcasm
keywords:
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Cutting Sarcasm
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/cutting-sarcasm
source: mcdm.heroes.v1
subtype: signature
target: One creature
type: ability
---

```ds-feature
distance: Ranged 10
effects:
    - effect: "\n*There you are, radiating your usual charisma.*\n\n| **Magic, Ranged, [Strike](scc:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |\n|-----------------------------------|--------------------:|\n| **\U0001F4CF Ranged 10**                  | **\U0001F3AF One creature** |\n\n**[Power Roll](scc:mcdm.heroes.v1/rule.dice/power-roll) + [Presence](scc:mcdm.heroes.v1/rule.character/presence):**\n\n- **≤11:** 2 + P psychic damage; P < WEAK, [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)\n- **12-16:** 5 + P psychic damage; P < AVERAGE, [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)\n- **17+:** 7 + P psychic damage; P < STRONG, [bleeding](scc:mcdm.heroes.v1/condition/bleeding) (save ends)"
feature_type: ability
flavor: There you are, radiating your usual charisma.
keywords:
    - Magic
    - Ranged
    - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: troubadour
    distance: Ranged 10
    flavor: There you are, radiating your usual charisma.
    keywords:
        - Magic
        - Ranged
        - '[Strike](scc:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Cutting Sarcasm
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/cutting-sarcasm
    subtype: signature
    target: One creature
    type: ability
name: Cutting Sarcasm
target: One creature
type: feature
usage: Main action
```
