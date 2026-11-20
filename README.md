# Tetris Baselines

The prior systems that the Tetris paper compares against, each pinned as a git submodule at the code we ran.
Every submodule keeps the authors' own `README.md` and adds a `TETRIS.md` that lists what we changed and how to reproduce our runs.

| System | Paper | Used in |
| --- | --- | --- |
| [`otif/`](otif) | OTIF (Bastani and Madden, SIGMOD 2022) | Tracking accuracy and throughput (§7.1), preparation cost (§7.2), query accuracy (§7.3) |
| [`leap/`](leap) | LEAP (Xu et al., SIGMOD 2024) | Tracking accuracy and throughput (§7.1), preparation cost (§7.2), query accuracy (§7.3) |
| [`noscope/`](noscope) | NoScope (Kang et al., PVLDB 2017) | Frame-selection query accuracy (§7.3) |
| [`seiden/`](seiden) | Seiden (Bang et al., PVLDB 2023) | Query accuracy (§7.3) |

All baselines use the same reference detector as Tetris, either run inside the baseline or replayed from its saved outputs.

```sh
git clone --recurse-submodules https://github.com/chanwutk/tetris-baselines.git
```
