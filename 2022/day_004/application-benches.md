# Day 4 benchmarks

[link to problem](http://adventofcode.com/2022/day/4)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `mattcl-solver/aoc run 4 input-mattcl` | 1.7 ± 0.7 | 0.8 | 11.7 | 1.01 ± 0.52 |
| `mattcl-solver/aoc run 4 input-pting` | 1.7 ± 0.6 | 0.9 | 7.2 | 1.00 |
| `python pting/day04.py input-mattcl` | 37.5 ± 4.4 | 31.2 | 53.6 | 21.67 ± 8.24 |
| `python pting/day04.py input-pting` | 33.6 ± 3.9 | 29.6 | 55.8 | 19.39 ± 7.37 |
