# 圍道 — Wéi Dào: The Art of Surrounding

*A mathematical and formal exploration of the game of Go, covering its history, rigorous formalizations, and further abstractions.*

## Overview

This repository contains the complete $\LaTeX$ source code for **圍道 — Wéi Dào: The Art of Surrounding**. The work is structured into three main parts:

- **Part I: Foundations** — Historical background spanning from ancient China to its evolution in Argentina, alongside the rules the game.
- **Part II: Construction** — Formal two-dimensional, two-player mathematical model. Precise formulations of legal moves, captures, Superko resolution (via Zobrist hashing), $n$-dimensional generalization ($m$ players), and group life theory (revisiting David Benson work).
- **Part III: Abstractions** — Geometric and graph-theoretic behavior of adjacencies in higher dimensions, an analysis of three-dimensional Go, one-dimensional variants, and common underlying structures across abstract board games.

## Compilation Requirements

**Important:** This document must be compiled using **XeLaTeX**. Standard pdfLaTeX will fail because the project relies on `fontspec`, external OpenType/TrueType fonts (such as CJK Unicode characters (Chinese/Japanese glyphs).
