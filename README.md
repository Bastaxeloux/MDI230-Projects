# MDI 230 

These two projects have been done in french.

## Project 1 — Epidemiological Modelling

This project deals with mathematical modelling of disease spread in a population.

### Topics
- **SIR and SEIR models** (deterministic & stochastic); simulation of birth-death processes and Markov chains.  
- Study the **impact of public-health policies** on epidemic evolution.  
- Compare **discrete** and **continuous** approaches (differential equations vs. random simulation).

---

## Project 2 — 5G Slicing Modelling (URLLC & eMBB)

This part tackles the **5G network-slicing** problem: running several virtual services on a single physical infrastructure.

### Slices studied
- **URLLC** (Ultra-Reliable Low-Latency Communication) – traffic that is extremely delay-sensitive and cannot wait in a buffer.  
- **eMBB** (enhanced Mobile Broadband) – high-throughput traffic that tolerates some latency.

### Objectives
1. Analyse theoretical models using **M/M/S/S queues** and **Erlang-B formulas**.  
2. Simulate a two-class queue where **URLLC has priority**, including **pre-emption** of eMBB customers.  
3. Derive **stability conditions** and compute **stationary probabilities** with matrix-analytic methods.  
4. Compare with a more realistic **guard-channel model** in which URLLC cannot pre-empt but enjoys reserved servers.