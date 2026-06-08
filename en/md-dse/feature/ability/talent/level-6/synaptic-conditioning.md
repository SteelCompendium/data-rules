---
action_type: Main action
class: talent
cost: 9 Clarity
cost_amount: "9"
cost_resource: Clarity
distance: Melee 2
feature_type: ability
file_basename: synaptic-conditioning
file_dpath: feature/ability/talent/level-6
flavor: It's a subtle mindset shift. It's not that they're your enemy—you just don't like them!
item_id: synaptic-conditioning
item_name: Synaptic Conditioning
keywords:
    - Psionic
    - Melee
    - Strike
    - Telepathy
level: "6"
name: Synaptic Conditioning
scc: mcdm.heroes.v1/feature.ability.talent.level-6/synaptic-conditioning
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
cost: 9 Clarity
distance: Melee 2
effects:
    - effect: "\n*It's a subtle mindset shift. It's not that they're your enemy—you just don't like them!*\n\n| **Psionic, Melee**, **Strike, Telepathy** |     **Main action** |\n|-------------------------------------------|--------------------:|\n| **\U0001F4CF Melee 2**                            | **\U0001F3AF One creature** |\n\n**Power Roll + [Reason](scc:mcdm.heroes.v1/rule.character/reason):**\n\n- **≤11:** 10 psychic damage; the target takes a [bane](scc:mcdm.heroes.v1/rule.dice/bane) on ability rolls made to harm you or your allies (save ends)\n- **12-16:** 14 psychic damage; the target has a double [bane](scc:mcdm.heroes.v1/rule.dice/bane) on ability rolls made to harm you or your allies (save ends)\n- **17+:** 20 psychic damage; the target considers you and your allies to be their allies when using abilities and features (save ends)\n\n**Strained:** While the target is under this effect, you no longer consider your enemies to be your enemies when using your abilities and features."
feature_type: ability
flavor: It's a subtle mindset shift. It's not that they're your enemy—you just don't like them!
keywords:
    - Psionic
    - Melee
    - Strike
    - Telepathy
metadata:
    action_type: Main action
    class: talent
    cost: 9 Clarity
    distance: Melee 2
    flavor: It's a subtle mindset shift. It's not that they're your enemy—you just don't like them!
    keywords:
        - Psionic
        - Melee
        - Strike
        - Telepathy
    level: "6"
    name: Synaptic Conditioning
    scc: mcdm.heroes.v1/feature.ability.talent.level-6/synaptic-conditioning
    target: One creature
    type: ability
name: Synaptic Conditioning
target: One creature
type: feature
usage: Main action
```
