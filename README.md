# CSP Modelling, Simulation & Verification in FDR4

**Purpose**  
To explore and learn process modelling and verification using CSP (Communicating Sequential Processes) with FDR4. Surprisingly approachable – and pretty fun too! 😄

---

## Project Overview

This project involves modelling two classic problems using CSP in the FDR4 model checker:

1. **The Dining Philosophers Problem** – a concurrency classic.
2. **The Needham-Schroeder Authentication Protocol** – a lesson in security flaws and how to fix them.

Each problem includes simulations, analysis, and formal verification.

---

## 1. Dining Philosophers Problem  
Based on Edsger Dijkstra's classic synchronization challenge (1971).  
👉 [Read more](https://en.wikipedia.org/wiki/Dining_philosophers_problem)

### Objectives:
- Model and analyze the dining philosopher scenario using CSP.
- Implement a *butler* to avoid deadlock.
- Monitor and control the number of philosophers eating at once.

---

## 2. Needham-Schroeder Protocol  
A study in secure communications – and what can go wrong.  
👉 [More on the theory](https://en.wikipedia.org/wiki/Needham%E2%80%93Schroeder_protocol)

### Objectives:
- Model the protocol assuming honest participants.
- Introduce an *intruder* and simulate a man-in-the-middle (MitM) attack.
- Apply Lowe's amendment to fix the flaw, resulting in the **Needham-Schroeder-Lowe Protocol**.

---

## Tools Used

- **FDR4** – Model checker for CSP.
- **CSP Language** – Used to define process behavior and interactions.

---

