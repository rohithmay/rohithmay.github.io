---
title: 🤖 Multipartite States and Quantum Teleportation
author: Rohith Krishna
date: 8 August 2020
layout: post
permalink: /2020-08-08-teleportation
tags: [quantum teleportation, quantum computing, qiskit, physics]
katex: true
---

[WIP]

# Introduction

In this article, I shall be summarising my learning of mulipartite states such as Bell States and the implementation of teleportation protocol on a quantum computer using IBM's Qiskit. The manner of presentation is as was taught by Elisa Baumer and Abe Asfaw at the Qiskit Global Summer School 2020. 

## From bits and qubits

In classical computation one uses binary states, designated by 0 and 1. Quantum mechanics teaches us that objects can be under superposition states (i.e, simultaneously in 0 and 1 states) and the act of observation/measurement forces the object to collapse to one of these states. The idea is that superpositions allow us to perform calculations on many states at the same time, making quantum algorithms exponentially faster.  

The catch, however, is that once we measure the superposition state, it collapses to one of its original states. Therefore a computational problem can only result in one *answer* and not all answers to all states in superposition. In designing quantum algorithms, one uses interference effects so that the *wrong answers* cancel, leaving out the *right answers.*

## Linear Algebra in Dirac Notation

The conventional Dirac notation employed by physicists is used here to represent state vectors in the Hilbert space. Let $$a,b \in \mathbb{C^2}$$.  We define the following:

$$ \bra{a} = \ket{b} $$
There









