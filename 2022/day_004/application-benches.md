# Day 4 benchmarks

[link to problem](http://adventofcode.com/2022/day/4)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `kcen/2022/04/solve.sh input-kcen` | 132.9 ± 19.7 | 105.2 | 193.4 | 282.70 ± 338.83 |
| `kcen/2022/04/solve.sh input-mattcl` | 124.2 ± 18.4 | 100.4 | 182.0 | 264.17 ± 316.63 |
| `kcen/2022/04/solve.sh input-pting` | 122.8 ± 10.0 | 105.2 | 143.8 | 261.13 ± 311.31 |
| `mattcl-solver/aoc run 4 input-kcen` | 0.5 ± 0.6 | 0.0 | 9.6 | 1.00 |
| `mattcl-solver/aoc run 4 input-mattcl` | 1.2 ± 0.8 | 0.0 | 5.2 | 2.60 ± 3.51 |
| `mattcl-solver/aoc run 4 input-pting` | 1.2 ± 0.9 | 0.0 | 9.0 | 2.55 ± 3.62 |
| `python pting/day04.py input-kcen` | 41.8 ± 8.6 | 32.3 | 73.9 | 88.94 ± 107.35 |
| `python pting/day04.py input-mattcl` | 43.8 ± 8.3 | 33.0 | 66.1 | 93.17 ± 112.20 |
| `python pting/day04.py input-pting` | 40.5 ± 12.7 | 28.4 | 91.3 | 86.19 ± 106.00 |
