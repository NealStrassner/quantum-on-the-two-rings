# Quantum Computing on the Two Rings: the calculator and the tutorial (v1.0)

## Overview

Two interactive browser pages accompanying the 2026 quantum series of papers by Neal Strassner. Every tool of quantum computing is one of three moves on two sliding rings marked with the sixty last digits of the Fibonacci numbers: a setting, a fold and a turn. The calculator computes all forty tools of the standard method as those three moves, beside the textbook value, with the instrument itself under a slider. The tutorial teaches the three moves from the beginning, with no physics assumed.

## The two pages

- **The calculator** (`index.html`, also `quantum-on-the-two-rings-calculator-v1.0.html`): the live gate instrument, the forty tools of *Quantum Computing on the Sixty-Ring* computed one by one, and the 2025 W-state entangled measurement read as a turn on the triangle. Every ring reading stands beside the standard value with the difference.
- **The tutorial** (`tutorials/quantum-in-three-moves.html`): *Quantum Computing in Three Moves*, a plain-language primer, the three moves as live animations, and the forty tools as a decoder.

## Technical Details

Both pages are single readable HTML files that run offline, with no data transmission. The only outside request is the page font. Every sine and cosine in the calculator is computed from the ring's own anchors by the ring's laws, not the browser's Math.sin and Math.cos, and is checked against them on the page.

## Attribution & Access

**Creator:** Neal Strassner
**Code:** Implemented by Claude (Anthropic) under Neal Strassner's direction
**License:** CC BY 4.0
**Live:** https://nealstrassner.github.io/quantum-on-the-two-rings/ (calculator) and https://nealstrassner.github.io/quantum-on-the-two-rings/tutorials/quantum-in-three-moves.html (tutorial)
**Repository:** https://github.com/NealStrassner/quantum-on-the-two-rings

## The papers (Zenodo)

Prerequisites: Two Sliding Rings, https://doi.org/10.5281/zenodo.22833894, with its calculator https://nealstrassner.github.io/one-setting-trig-rings/; Neal's Net, Version 3, https://doi.org/10.5281/zenodo.20754147, with its calculator https://nealstrassner.github.io/neals-net-calculator/.

The quantum series, in reading order:

1. The Qubit on the Two Rings, https://doi.org/10.5281/zenodo.23265465
2. The Harmonic Oscillator on the Two Rings, https://doi.org/10.5281/zenodo.23265479
3. Quantum Dynamics and Entanglement on the Two Rings, https://doi.org/10.5281/zenodo.23265481
4. Quantum Computing on the Sixty-Ring, https://doi.org/10.5281/zenodo.23265483
5. Where the Rings Stop, https://doi.org/10.5281/zenodo.23265502

The instrument and its method, and applications such as detecting and repairing errors in computing, are the subject of the author's pending U.S. provisional patent applications.
