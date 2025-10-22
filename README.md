# Lights Out Non-Solvable Sizes

This repository lists the integers `n` for which the `n × n` Lights Out puzzle is **not guaranteed to have a solution**.

Equivalently, these are the values of `n` for which the matrix that maps a **click vector** (a vector with a `1` at the clicked position and `0`s elsewhere) to a **change vector** (indicating which lights toggle) is **non-invertible**.

If the matrix were invertible, every Lights Out configuration of that size would be solvable.

**OEIS Entry:**  
[https://oeis.org/A117870](https://oeis.org/A117870)
