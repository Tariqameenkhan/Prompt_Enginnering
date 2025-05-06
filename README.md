# Prompt_Enginnering

# Chain of Thought Prompting

## One-shot Chain of Thought Prompting

**Q**: In a football match, 11 players in each team. One team has 11 players: one goalkeeper and 10 outfield players. 
In 10 outfield players, 2 players take an injury and one has not come. How many outfield players are required?

**A**: 11 players consist of one goalkeeper and 10 outfield players. Since two outfield players are injured, and one has not come, 3 outfield players are required.

---

**Q**: How many players play football in both teams without including goalkeepers?

**A**:

---

## Zero-shot Chain of Thought Prompting

**Q**: How much time is consumed to cover 100 km, if a car covers 10 km distance in 25 minutes?  
**A**: Let's think step by step:  

---

# Generated Knowledge

## Example1. Economic Problems

**Q**: Write four economic problems facing a nation.  
**A**: AI response
**Q**: Write a blog on these problems.  
**A**: 

---

## Example2. AI Agent Framework

**Q**: Give me a framework of Python to build AI agents.  
**A**:  

**Q**: Give  me a roadmap of these frameworks and learning resources.  
**A**:   

---

# Least-to-Most Prompting

**Definition**: Least-to-most (LTM) prompting breaks down a problem into sub-problems and solves them sequentially. 
The output of previous sub-problems is used as input for the next.
