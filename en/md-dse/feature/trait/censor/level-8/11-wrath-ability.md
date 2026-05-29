---
action_type: feature
class: censor
feature_type: trait
file_basename: 11-wrath-ability
file_dpath: feature/trait/censor/level-8
item_id: 11-wrath-ability
item_name: 11-Wrath Ability
level: "8"
name: 11-Wrath Ability
scc: mcdm.heroes.v1/feature.trait.censor.level-8/11-wrath-ability
source: mcdm.heroes.v1
type: trait
---

```ds-feature
effects:
    - effect: "Choose one heroic ability from the following options, each of which costs 11 wrath to use.\n\n##### Excommunication (11 Wrath)\n\n> \n> *You curse your foe to become a bane to their allies.*\n> \n> | **Melee, Strike, Weapon** |     **Main action** |\n> |---------------------------|--------------------:|\n> | **\U0001F4CF Melee 1**            | **\U0001F3AF One creature** |\n> \n> **Power Roll + Might:**\n> \n> - **≤11:** 9 + M damage; I < WEAK, [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)\n> - **12-16:** 13 + M damage; I < AVERAGE, [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)\n> - **17+:** 18 + M damage; I < STRONG, [weakened](scc:mcdm.heroes.v1/condition/weakened) (save ends)\n> \n> **Effect:** At the end of each of your turns, a target [weakened](scc:mcdm.heroes.v1/condition/weakened) this way deals holy damage equal to twice your Presence score to each enemy within 2 squares of them. Additionally, a target [weakened](scc:mcdm.heroes.v1/condition/weakened) this way can't be targeted by their allies' abilities."
feature_type: trait
metadata:
    class: censor
    level: "8"
    name: 11-Wrath Ability
    scc: mcdm.heroes.v1/feature.trait.censor.level-8/11-wrath-ability
    type: trait
name: 11-Wrath Ability
type: feature
```
