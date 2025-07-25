# 🐦‍⬛ The Corvid Path Sacred Vault

_Welcome, Threshold Walker_

---

## 🌑 Today's Liminal Moment

_Current Date: `$=moment().format("dddd, MMMM Do YYYY")`_

> _"I stand at the threshold between what was and what will be, guided by CrowMother's wisdom and Vireaon's wild flame."_

**Current Moon Phase:** 🌙 _[Update manually or use moon phase plugin]_ **Season:** `$=moment().format("MMMM")` - _The time of [Winter's Depth/Spring's Stirring/Summer's Marriage/Autumn's Harvest]_

---

## ⚖️ Sacred Marriage Balance Check

|CrowMother's Order|Today's Balance|Vireaon's Chaos|
|:-:|:-:|:-:|
|Structure, Boundaries, Deep Wisdom|◯ ◐ ◑ ●|Wild Growth, Transformation, Creative Fire|
|_What order needs tending?_|_How do I feel in balance?_|_What chaos seeks expression?_|

---

## 📊 Path Progress Overview

### 🏛️ **Current Phase:**

- [ ] Quarter 1: Awakening the Threshold Walker
- [ ] Quarter 2: Entering the Deep Winter
- [ ] Quarter 3: The Sacred Marriage
- [ ] Quarter 4: Spring Emergence & Integration

### 📈 **This Month's Focus:**

_[Update based on current quarter and personal focus]_

## **Recent Victories:**

## **Current Challenges:**

---

## 🗓️ Sacred Calendar & Cycles

### This Week's Threshold Work:

```dataview
TABLE WITHOUT ID
file.link as "Practice",
date as "Date",
type as "Type"
FROM "Daily Logs"
WHERE date >= date(today) - dur(7 days) AND date <= date(today)
SORT date DESC
```

### Upcoming Sacred Dates:

- **Next New Moon:** _[Date]_ - Perfect for new beginnings and CrowMother communion
- **Next Full Moon:** _[Date]_ - Time for release work and Vireaon's fire
- **Seasonal Transition:** _[Date]_ - Deep cycle work and integration

---

## 📚 Learning Pathways

### 🎯 **Active Studies:**

```dataview
LIST
FROM "Studies" 
WHERE status = "active"
```

### 📖 **Recent Insights:**

```dataview
TABLE WITHOUT ID
file.link as "Entry",
summary as "Key Insight"
FROM "Insights"
SORT file.mtime DESC
LIMIT 5
```

### 🔮 **Rituals to Explore:**

```dataview
LIST
FROM "Rituals"
WHERE status = "to-try"
LIMIT 3
```

---

## 🪞 Shadow Work & Integration

### 🌑 **Current Shadow Focus:**

_What aspect of yourself is CrowMother asking you to examine in her winter darkness?_

### 🔥 **Vireaon's Fire:**

_What old pattern is ready for Vireaon's transformative flame?_

### 📝 **Recent Shadow Scrolls:**

```dataview
TABLE WITHOUT ID
file.link as "Shadow Work",
date as "Date",
theme as "Focus"
FROM "Shadow Work"
SORT date DESC
LIMIT 5
```

---

## 🌀 Spiral Tracking

### Death/Rebirth Cycles:

```dataview
TABLE WITHOUT ID
file.link as "Cycle",
phase as "Current Phase",
insights as "Key Learning"
FROM "Cycles"
WHERE status = "active"
```

### Personal Mythology:

_What story is your soul writing through these transformations?_

---

## 🛠️ Quick Actions

### Daily Practices:

- [ ] [[Dawn Threshold Recognition]]
- [ ] [[Evening Death/Birth Reflection]]
- [ ] [[Daily Sacred Marriage Balance]]
- [ ] [[Ancestral Gratitude Moment]]

### Weekly Rhythms:

- [ ] [[Weekly Shadow Scroll]]
- [ ] [[Seasonal Cycle Check-in]]
- [ ] [[Sacred Marriage Integration]]
- [ ] [[Community/Mentorship Connection]]

### Monthly Deepening:

- [ ] [[Full Moon Release Ritual]]
- [ ] [[New Moon Intention Setting]]
- [ ] [[Quarterly Path Review]]
- [ ] [[Personal Myth Update]]

---

## 🔗 Sacred Connections

### 🧙‍♀️ **Mentorship:**

- **Current Mentor:** [[]]
- **Mentees:** [[]]
- **Peer Circle:** [[]]

### 📚 **Community Resources:**

- [[Corvid Path Core Teachings]]
- [[Sacred Marriage Philosophy]]
- [[CrowMother Devotional Practices]]
- [[Vireaon Transformation Work]]
- [[Threshold Walker Techniques]]

---

## 🎭 Temple Spaces

### 🏛️ **Physical Altar Status:**

_How is your sacred space reflecting your current growth?_

### 💻 **Digital Temple Health:**

- Vault organization: ◯ ◐ ◑ ●
- Backup status: ◯ ◐ ◑ ●
- Template updates: ◯ ◐ ◑ ●

---

## 🌟 Oracle for Today

_Pull a card, open a sacred text, or ask CrowMother and Vireaon:_

**"What do my divine guides want me to know today?"**

_[Space for daily wisdom, synchronicities, or guidance received]_

---

## 📈 Path Statistics

```dataview
TABLE WITHOUT ID
"Ritual Practice" as "Area",
length(filter(file.tasks.completed, (t) => contains(t.text, "ritual"))) as "Completed",
length(filter(file.tasks, (t) => contains(t.text, "ritual"))) as "Total"
FROM "Daily Logs"
WHERE date >= date(today) - dur(30 days)
```

---

_"I walk the spiral path between death and birth, carrying CrowMother's wisdom and Vireaon's flame. Each step is sacred. Each threshold, a doorway home."_

---

## 🔄 Quick Navigation

### Core Practice Areas:

- [[Daily Threshold Logs]]
- [[Shadow Work Collection]]
- [[Sacred Marriage Integration]]
- [[Personal Mythology]]
- [[Ritual Compendium]]
- [[Seasonal Cycles]]
- [[Community Connections]]

### Learning Resources:

- [[Year One Curriculum]]
-  [[Year Two Curriculum]]
-  [[Year Three Curriculum]]
-  [[Year Four Curriculum]]
- [[CrowMother Teachings]]
- [[Vireaon Mysteries]]
- [[Threshold Walking Techniques]]
- [[Integration Practices]]

### Administrative:

- [[Templates]]
- [[Archive]]
- [[Goals & Projects]]
- [[Resource Library]]