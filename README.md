# Computational Modeling of Gene Expression Dynamics

A comprehensive exploration of mathematical models describing gene regulatory networks, from basic activation/repression mechanisms to complex oscillatory systems like the Repressilator.

## 📋 Project Overview

This project implements and analyzes four fundamental models of gene expression:
1. **Activation Model** (Hill Function)
2. **Repression Model** (Inverse Hill Function) 
3. **Oscillator Model** (Negative Feedback with Delay)
4. **Three-Gene Repressilator** (Synthetic Genetic Oscillator)

The implementation includes both conceptual demonstrations and detailed numerical simulations with biological parameter sensitivity analysis.

## 🧬 Models Implemented

### 1. Activation Model (Positive Regulation)
- **Biological Mechanism:** Transcription factor binding with cooperative dynamics
- **Mathematics:** Hill Equation \( y = \frac{x^n}{K^n + x^n} \)
- **Features:** Sigmoidal response, switch-like behavior, parameter exploration

### 2. Repression Model (Negative Regulation)  
- **Biological Mechanism:** Repressor protein blocking transcription
- **Mathematics:** Inverse Hill Function \( y = \frac{1}{1 + \left(\frac{x}{K}\right)^n} \)
- **Features:** Dose-response analysis, biological interpretation plots

### 3. Oscillator Model (Negative Feedback)
- **Biological Mechanism:** Delayed self-inhibition creating rhythms
- **Mathematics:** Delay Differential Equations (DDEs)
- **Features:** Circadian rhythm simulation, synthetic biology applications

### 4. Three-Gene Repressilator
- **Biological Mechanism:** Cyclic repression network (A→B→C→A)
- **Mathematics:** System of coupled ODEs
- **Features:** 
  - Network topology visualization
  - Phase space analysis (2D & 3D)
  - Parameter sensitivity studies
  - Stochastic vs deterministic simulations
  - Quantitative oscillation analysis (period, amplitude)

## 🛠️ Technical Implementation

### Core Dependencies
```python
numpy, matplotlib, scipy, pandas
