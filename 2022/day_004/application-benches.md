# Day 4 benchmarks

[link to problem](http://adventofcode.com/2022/day/4)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/04/solve.sh input-mattcl` | 133.0 ± 19.0 | 104.2 | 165.9 | 81.14 ± 38.13 |
| `kcen/2022/04/solve.sh input-pting` | 127.9 ± 15.9 | 107.5 | 175.2 | 78.08 ± 36.27 |
| `mattcl-solver/aoc run 4 input-mattcl` | 1.6 ± 0.7 | 0.5 | 5.1 | 1.00 |
| `mattcl-solver/aoc run 4 input-pting` | 2.0 ± 0.9 | 0.6 | 14.0 | 1.20 ± 0.79 |
| `python pting/day04.py input-mattcl` | 43.1 ± 10.1 | 31.3 | 72.5 | 26.30 ± 13.28 |
| `python pting/day04.py input-pting` | 45.3 ± 11.1 | 34.6 | 81.9 | 27.67 ± 14.11 |
