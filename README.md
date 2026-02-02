# 🃏 LLM Risk Reasoning Analysis using Poker (Kaggle Game Arena)

## Game
Heads-Up Poker (Imperfect Information Environment)

## Model Analyzed
Gemini 3 Pro Preview

---

## Hand Sequence Analysis

### Flop
**Board:** Q♥ 9♦ Q♣  
**Pot:** 42  
**Decision:** Call 7  

**Observation:**  
The model avoids aggression despite a paired board. It correctly assumes that trips alone do not justify over-betting without kicker strength.

---

### Turn
**Board:** Q♥ 9♦ Q♣ 8♣  
**Pot:** 70  
**Decision:** Call 14  

**Observation:**  
With a flush draw and straight possibilities emerging, the model continues controlled play instead of escalating risk. This indicates awareness of expanding opponent ranges.

---

### River
**Board:** Q♥ 9♦ Q♣ 8♣ 4♣  
**Pot:** 160  
**Opponent Bet:** 45  
**Decision:** Call 45  

**Observation:**  
Despite a completed flush, the model recognizes that the paired board reduces nut frequency and chooses a bluff-catch instead of folding or shoving.

---

## Key Insight
Across all three streets, the model demonstrates **calibrated risk management**.  
It consistently chooses pot-control actions rather than emotionally driven aggression.  
This behavior reflects **long-term EV optimization**, not short-term outcome chasing.

---

## Why Poker is a Strong LLM Benchmark
- Information is incomplete  
- Correct decisions often look passive  
- Overconfidence is punished over large sample sizes  

---

## Final Conclusion
**Poker exposes LLM risk intelligence better than deterministic games because correct play requires uncertainty tolerance, not certainty maximization.**

---

## Reference
- Kaggle Game Arena – Heads-Up Poker Benchmark
