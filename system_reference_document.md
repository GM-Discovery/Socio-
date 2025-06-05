# 🎲 Socio-: System Reference Document (SRD)

> *A simplified, modular reference for designing your own games, modules, and forks using the open-source engine of* **Socio-: Stories of Us**. Licensed under CC BY. Redistribution encouraged. Attribution required.*

---

## ⚙️ Core Engine Philosophy

> 🧠 **Attributes define capacity**, not power. 
> 🎲 **Dice resolve actions** against Target Values (TV).
> 🤝 **Helpers matter** — cooperation increases success.
> 🕰️ **Actions have scale** — timing defines risk.
> 🚫 **No defense rolls** — narrative counters and helper reactions take their place.

---

## 🎲 Dice & Resolution Mechanics

- `Skill Dice`: d4 to d20+ depending on proficiency
- `Exploding Dice`: Roll max, roll again and add
- `Advantage`: Roll twice, keep best
- `Disadvantage`: Roll twice, keep worst

🧮 **Check =** `Roll ≥ Target Value`

---

## 🧠 Attributes & Skill Capacity

Each attribute allows a character to learn up to `10` related skills by default.

| 🧩 Attribute | 📖 Concept |
|-------------|------------|
| **Might** | Strength, endurance, labor |
| **Grace** | Agility, finesse, charm |
| **Intellect** | Logic, analysis, system mastery |
| **Awareness** | Perception, vigilance, reflexes |
| **Presence** | Social impact, charisma, performance |
| **Spirit** | Inner force, spiritual connection |
| **Empathy** | Emotional resonance, care, mimicry |
| **Resolve** | Grit, recovery, inner fire |
| **Craft** | Technical skill, creation, repair |
| **Lore** | Knowledge, scholarship, cultural literacy |

> 💡 *Forks may expand skill limits for attributes like Lore or Craft. Specialization can also be modeled through improved dice instead of wider skill lists.*

---

## 🧩 Core Action Economy

⏱️ Actions are resolved in **four phases**:
1. **Declaration** — What you’re attempting
2. **Reaction** — Others intercept, assist, or redirect
3. **Resolution** — Dice are rolled
4. **Narration** — Story reflects the outcomes

🌀 Actions occur across scales:

| ⏳ Type | ⏰ Time | 🧪 Examples |
|--------|--------|--------------|
| Instant | Seconds | Dodge, Strike, Speak Out |
| Short | Minutes | Persuade, Lockpick, Treat Wound |
| Long | Hours–Days | Craft Item, Ritual, Train |
| Extended | Weeks+ | Build Institution, Launch Movement |

> 🔒 Long/Extended = You’re committed. Vulnerable to interruption. Cannot dodge/react.

---

## 🤝 Helper Actions & Coordination

Helpers act in the **Reaction Phase**.

| 🪢 Type | 🎁 Effect | 📈 Complexity |
|--------|-----------|----------------|
| Advantage | Target rolls twice | +1 TV |
| Flat Bonus | +1 to +3 added to roll | +1 to +2 TV |
| Reroll | Target may reroll 1+ dice | +1 TV |
| Target Reduction | Lowers difficulty | +1 to +3 TV |

- Helpers must **succeed** on their own skill check
- All helpers must act at same time scale
- Too many helpers = coordination penalty

---

## 🎭 Social Stances & Emotional Conflict

Every participant in a social scene chooses a **stance**.

| 🎭 Stance | 🟢 Strong vs | 🔴 Weak vs |
|-----------|-------------|--------------|
| **Convince** | Command | Sympathy |
| **Command** | Follow | Insight |
| **Insight** | Convince | Follow |
| **Sympathy** | Insight | Command |
| **Follow** | Sympathy | Convince |

- 🧠 Stances resolve via rolls
- 💔 Results affect **Presence, Empathy, Spirit, or Lore HP**
- 🔄 Players may shift stance between rounds

---

## ❤️ Health, Damage & Exhaustion

Every attribute has a matching **HP Pool**. Damage types target specific pools.

| 💥 Damage Type | 🎯 HP Targeted |
|----------------|---------------|
| Physical | Might |
| Mental | Intellect |
| Emotional | Empathy, Presence |
| Spiritual | Spirit |
| Exhaustion | Resolve |
| Knowledge | Lore |
| Awareness | Awareness |
| Tool Depletion | Craft |

> 🛠️ Recovery: Rest, Helper actions, Narrative events, or Skills.

---

## 🏷️ Tags & Status Effects

- **Tags** = Narrative properties with mechanical consequences
- **Status Effects** = Conditions until cleared (e.g., `Winded`, `Cursed`)
- **Requirement Tags** = Needed to unlock some helpers, stances, or abilities

| Tag Type | Meaning |
|----------|---------|
| Descriptive | Identity, role, memory |
| Functional | Adds bonuses, effects, risk |
| Requirement | Gate for content/tools/traits |

> 🧼 Tags/Statuses are cleared through narrative resolution, skill use, or helper support.

---

## 💀 Threats & Encounter Design

Threats follow PC structure. Use short stat blocks.

| 🔢 TV (Threat Value) | 💣 Power Tier |
|---------------------|----------------|
| 1–10 | Street Level |
| 11–20 | City/Institutional |
| 21–30+ | Mythic/Regional+ |

🧮 TV = HP Pools × Tier Scale + Helper-Like Abilities + Tags

- 🐝 Swarms = 1 stat block until broken
- ⚔️ Threats act in player initiative order

---

## 🧾 Templates

### 🎴 Helper Card
```markdown
**Name**: [Helper Name]  
**Triggering Skill**: [Skill Name]  
**Action Type**: Minor / Major / Reaction  
**Effect**: [Benefit]  
**Coordination Complexity**: +[Value]  
**Prerequisites**: [Tags, Status, or Scenario]  
```

### 💀 Threat Block
```markdown
**Name**: [Threat Name]  
**Tier**: [Street, City, Regional, etc.]  
**TV**: [#]  
**HP Pools**: Might [#], Resolve [#], etc.  
**Skills**: [Skill (dice)], [Skill (dice)]  
**Tags**: [Tag1], [Tag2]  
**Abilities**:  
- [Ability Name]: [Trigger and effect]  
```

### 🧠 Status/Tag Creator
```markdown
**Tag Name**: [Name]  
**Type**: Descriptive / Functional / Requirement  
**Acquired By**: [Action/Event]  
**Cleared By**: [Action/Event or Skill]  
**Effect**: [Mechanical Impact or Narrative Cue]  
```

---

## 🧭 The Forker's Code

> *This system was not built to be sacred—it was built to be shared.*

Fork this system if you:

- 🎴 Create meaningfully — remix, reframe, reimagine
- 🤝 Attribute openly — credit strengthens communities
- 🛡️ Respect consent — safety and trust above all


❤️ Honor Love — care is design
🧠 Promote Truth — clarity builds good systems
⚖️ Embrace Accountability — especially across power
🌱 Prioritize Well-being — content has impact
🕸️ Build Community — don't gatekeep
🔍 Innovate — Tell your own stories
🕊️ Protect Freedom — of imagination and design

**The fork is not betrayal.**  
**It is the continuation of the story.**

---

## 📜 License

**Creative Commons Attribution (CC BY)**

You may remix, adapt, and build upon this system for any purpose, even commercially, so long as attribution is given to:

> Grant A. Murray (2025), aka GM Discovery — *Socio-: Stories of Us (An Open-Source Collaborative Tabletop Roleplaying Game)*

Redistribution of this SRD (unaltered or modified) is encouraged.
