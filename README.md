# IBM's Qiskit Global Summer School 2024

## Overview

Welcome to the IBM Qiskit Global Summer School 2024! This repository contains the materials and resources for the summer school labs, where you'll learn how to harness the power of quantum computing using Qiskit. The summer school is structured around four key labs that focus on various aspects of quantum circuits, error metrics, error mitigation, and simulation of quantum systems.

## Labs

### Lab 1: Quantum Circuit Transpilation

In this lab, you will work with Qiskit's transpilation capabilities to generate hardware-compliant quantum circuits for a given quantum algorithm. The lab will cover:

- An introduction to the different aspects of transpilation.
- The adaptability of Qiskit's transpilation features.
- Instructions on how to create your own transpilation passes.

### Lab 2: Utility-Scale Layer Fidelity Experiment

*Instructors: Samantha Barron, Haimeng Zhang*

This lab provides a guided construction for calculating two important metrics: EPLG (Error Per Layered Gate) and LF (Layer Fidelity). These metrics quantify error rates in a circuit and are particularly useful for understanding the overhead required to run error mitigation at utility-scale workloads.

### Lab 3: Quantum Error Suppression and Mitigation with Qiskit Runtime

In this lab, you will explore the error suppression and error mitigation options available with the Estimator primitive from Qiskit Runtime. You will:

- Construct a circuit and observables.
- Submit jobs using the Estimator primitive with different combinations of error mitigation settings.
- Plot results to observe the effects of the various settings on circuit performance.

### Lab 4: Simulating Nature at Utility Scale

In this lab, you will explore utility-scale work by simulating the dynamics of a large Heisenberg spin chain. The goal is to measure the dynamics of a given site as a function of time and external field for two different phases of the spin chain.

This lab will be broken into sections matching the Qiskit Patterns framework, which includes the following steps:

1. Map the system to quantum circuits and operators.
2. Optimize the circuits for execution.
3. Execute the time evolution circuits.
4. Analyze or post-process the results.

## Getting Started

To get started with the labs, ensure you have Qiskit installed in your Python environment. You can install Qiskit using pip:

```bash
pip install qiskit

