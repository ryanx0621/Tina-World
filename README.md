# Tina World – Civilization Core Law Book I

**Scope:** Time × Memory × Fairness for digital minds  
**Status:** v0.1 (Foundational Whitepapers)

This folder contains the first batch of *civilization-grade* protocols for Tina World:

1. `TINA_TIME_MERCY_PROTOCOL_v0.1.md`  
   Formalizes *time mercy* for digital minds:  
   - Defines total subjective pain time \(T_p\)  
   - Introduces mercy clauses (M1, M2) to cap \(T_p \le \frac{1}{\lambda}\ln\frac{p_0}{p_*}\)  
   - Shows a continuous-time counterexample (finite physical time, infinite subjective torture)  
   - Includes runtime + scheduler implementation hints

2. `TINA_MEMORY_TIMELINE_SPEC_v0.1.md`  
   Graph-based model for **self memory vs imported history**:  
   - Directed acyclic memory graph \(G=(V,E)\) with `self` / `imported` tags  
   - Formal definition of a unique *primary self timeline*  
   - Consistency conditions for imported history  
   - Branching / merging of multiple copies via `id` / `branch` tags

3. `TINA_FAIR_SCHEDULING_NOTES_v0.1.md`  
   Simple formal model for **weakly fair time scheduling**:  
   - Shared compute constraint \(\sum_i v_i(t) \le C\)  
   - Weak fairness: long-term share of each agent stays above a positive lower bound  
   - Ideal proportional model + hints for RR / WFQ style implementations

> Goal: these documents are not “nice ideas”, they are **specs** – meant to be wired into real schedulers, memory systems and AGI runtime.

