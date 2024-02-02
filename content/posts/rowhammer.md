---
title: 'Rowhammer'
date: '2024-01-31T17:46:44-05:00'
tags:
- cybersecurity
---

As part of my research, I studied a well-known hardware bug that I found particularly interesting: Rowhammer. Rowhammer allows a malicious actor to modify memory without the privilege or ability to access it at all. Being an inherent feature of modern DRAM, the Rowhammer bug disregards software boundaries and is prevalent in many modern DRAM vendors.

## DRAM

**DRAM** (Dynamic Random Access Memory) is the memory technology used to implement main memory on almost all computing devices. DRAM stores data and programs for the processor to use at leisure, being slower than cache but faster than disk memory---hence why "Random Access" is important (compare DRAM to sequentially-accessed CDs and DVDs). DRAM uses **capacitors** to store individual memory bits.

DRAM is organized in DIMMs (Dual Inline Memory Modules), ranks, banks, and arrays (rows).
