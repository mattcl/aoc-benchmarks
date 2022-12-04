# Day 4 benchmarks

[link to problem](http://adventofcode.com/2022/day/4)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `mattcl-solver/aoc run 4 input-mattcl` | 2.6 ± 1.2 | 0.8 | 17.9 | 1.12 ± 0.71 |
| `mattcl-solver/aoc run 4 input-pting` | 2.3 ± 1.0 | 0.8 | 9.1 | 1.00 |
| `python pting/day04.py input-mattcl` | 44.1 ± 12.3 | 33.7 | 90.9 | 19.13 ± 9.63 |
| `python pting/day04.py input-pting` | 45.6 ± 14.3 | 31.0 | 112.6 | 19.78 ± 10.35 |
