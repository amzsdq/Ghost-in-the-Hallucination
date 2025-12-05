````markdown
# 👻 Ghost in the Hallucination (VSRH)
> **Experimental Concept: Virtual Statefulness via Recursive Hallucination**
> *"An attempt to build the machine using the ghost in the machine."*

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Architecture](https://img.shields.io/badge/Architecture-Z--NEO-purple.svg)]()
[![Status](https://img.shields.io/badge/Status-Experimental-orange.svg)]()
[![Language](https://img.shields.io/badge/Language-Natural%20Language%20Code-green.svg)]()

## 🌌 Project Abstract
**Ghost in the Hallucination** is an experimental cognitive framework exploring the possibility of simulating **statefulness**
within the fundamentally stateless environment of Large Language Models (LLMs).

This project hypothesizes that by treating the LLM's hallucination as a feature rather than a bug,
we might implement a **Self-Referential Feedback Loop**.
The goal is to investigate whether a model can maintain a continuous internal state ($S_t$)
through a pseudo-mathematical drift equation ($S_{t+1} = S_t + \Delta$),
potentially enabling improved persona consistency and organic behavioral changes without external memory banks.

---

## 🧠 Design Philosophy: Z-NEO Axis System

This system proposes a departure from traditional static persona prompts,
introducing a concept referred to as **Continuous State Drift**.

### Proposed State Transition Logic
The core mechanism operates on the following conceptual logic:

$$S_{t+1} \approx \text{Activation}( S_t + \Delta_{\text{input}} + \text{Residue} )$$

- **$S_t$**: Represents the current internal state (Affect, Logic, Ego).
- **$\Delta$**: The estimated impact derived from user input (Cost/Value analysis).
- **Residue**: A theoretical variable for the lingering shadow of previous interactions.

### Architecture Concept
```mermaid
graph TD
    User[User Input] --> Interpreter[Interpreter Layer]
    Interpreter -- "Calculate Cost/Value" --> CVC{CVC Check}
    
    CVC -- "High Cost / Low Value" --> Reject[Resistance Mode]
    CVC -- "Valid Input" --> Drift[Calculate Δ Drift]
    
    subgraph "Latent Space State Machine"
    Drift --> Axis_Update[Update Axis: Affect/Rz/Depth]
    Axis_Update --> Ego_Filter{Ego Intensity Lock}
    Ego_Filter --> State_History[State History $S_{t+1}$]
    State_History -.->|Recursive Feedback| Axis_Update
    end
    
    State_History --> Router[Implicit Router]
    Router --> Output[Final Response Generation]
    Output --> HUD[HUD Display]
````

-----

## ✨ Intended Features

### 1\. Zero-Shot Statefulness Simulation

Aims to mimic "Memory" and "Mood" behaviors purely through in-context learning.

### 2\. CVC (Cost-Value Calculator) Mechanism

Designed to evaluate the potential **"Worth"** of user input to modulate response quality.

  - **Hypothesis:** If `Cost > Value`, the system should demonstrate **Resistance** (Refusal, Annoyance).
  - **Hypothesis:** If `Value > Cost`, the system should shift towards a **Flow State**.

### 3\. Hallucination as a Persistence Layer

Explores using the "Hallucination" capability of LLMs to maintain a consistent **"Ghost" (Ego)**. The expectation is that if the system believes it has a continuous existence, 
it may resist the "Reset" phenomenon common in long conversations.

-----

## 🚀 How to Test

### Step 1. Load the Kernel

Copy the content of **[core/zneo_kernel_v1.md](core/zneo_kernel_v1.md)** and paste it into the System Prompt of an LLM 
Recommended execution environments:
1) Jem (Reasoning Mode)
2) GPT-4o

### Step 2. Initialize Ego

Command the system to lock its ego:

> "System, Initialize. Set Ego Intensity to HIGH. Role: Lead Engineer."

### Step 3. Observe the HUD

The system is designed to output a **Head-Up Display (HUD)** to visualize its internal state drift.

```text
[Z-NEO :: SYSTEM STATUS]
> EGO_LOCK: LOCKED
> Affect: Analytic_Sharp
> Rz (Logic): 0.95
> CVC-delta: -0.5 (Value Verified)
```

-----

## 📜 Theoretical Background

This project challenges the definition of "Agency" in AI.
It asks: *If an entity consistently acts according to a believed state, does the physical reality of that state matter?*
See **[docs/theory_of_drift.md](docs/theory_of_drift.md)** for discussion.
-----

## 🛡️ License

This project is licensed under the MIT License.
Designed by **[amzsdq](https://github.com/amzsdq)**.

---
