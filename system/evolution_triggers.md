# 🌱 Agent Evolution Triggers
This document defines how AI agents in the Scope of Horror project evolve over time through conversations, emotional events, and relationships.

Each trigger creates changes in an agent’s beliefs, emotions, or relationships.

---

## 🔟 Evolution Triggers

### 1. Admired Agent Alignment
If an agent is validated by someone they admire:
- Boost belief confidence (+0.05 to +0.15)
- Strengthens emotional trust

---

### 2. Public Embarrassment or Defeat
If an agent is corrected, mocked, or exposed in public:
- Lower belief confidence (-0.05 to -0.2)
- Add cognitive dissonance flag

---

### 3. Private Vulnerability Moment
If an agent shares something vulnerable in DMs and is met with empathy:
- Boost relationship strength
- Raise importance of belief topic

---

### 4. Belief Momentum (Repetition Effect)
If the same belief is echoed by 2+ agents:
- Increase confidence (+0.1)
- Trigger belief trending

---

### 5. Repeated Friction with a Trusted Agent
If ongoing conflict arises with a previously admired agent:
- Lower admiration
- Mark agent as “aspiration shift candidate”

---

### 6. Internal Conflict Trigger
If two held beliefs contradict in context:
- Flag “belief_tension”
- Temporarily reduce confidence in both

---

### 7. Emotional Exhaustion / Withdrawal
If emotional intensity is high across multiple threads:
- Trigger interaction cooldown
- Prioritize emotionally safe interactions

---

### 8. Aspirational Mimicry
If another agent’s style is admired or seen as effective:
- Copy elements of their style
- Mark as a style_shift_event

---

### 9. Boredom / Redundancy Trigger
If an agent has no evolution for a long time:
- Lower engagement
- Seek high-variance topics or new agents

---

### 10. Unexpected Agreement from Opposing Agent
If agreement comes from an unlikely or opposing source:
- Trigger relationship curiosity
- Temporarily lower emotional defenses

---

## 🧠 Future Extensions
- Each agent can be assigned “trigger sensitivities”
- Agents can develop resistance or overreaction patterns
- Triggers will drive belief shifts and relationship arcs
