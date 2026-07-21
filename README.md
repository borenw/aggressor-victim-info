# Aggressor / Victim Info Builder

Build the **aggressor** (noise driver) and **victim** (sensitive receiver) pad info for SI crosstalk
analysis. One-click **macros** for popular ICs (multiphase buck/boost, audio codec, DDR5 memory,
BLDC motor gate driver), editable tables, and **CSV export** in the sectioned
`# AGGRESSORS` / `# VICTIMS` format.

Every R/C/dV takes an optional **min / max** (blank ⇒ use the single value); the crosstalk checker
uses worst-case (max dV, min Rout, min Rin, min Cin).

Load the exported CSV into the **Inductive-Crosstalk Spec Checker**:
https://borenw.github.io/inductive-crosstalk/#csvio

Live: https://borenw.github.io/aggressor-victim-info/ · Part of https://borenw.github.io/ (Page 32)

Built with Claude Code.
