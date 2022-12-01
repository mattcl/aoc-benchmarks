# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `AOC_INPUT=input-aspidites lanjian/day_01` | 1.7 ± 1.5 | 0.8 | 46.0 | 1.28 ± 1.99 |
| `AOC_INPUT=input-aspidites python pting/day01.py` | 20.8 ± 2.9 | 16.8 | 32.0 | 15.39 ± 20.07 |
| `AOC_INPUT=input-lanjian lanjian/day_01` | 1.4 ± 0.5 | 0.8 | 4.2 | 1.07 ± 1.43 |
| `AOC_INPUT=input-lanjian python pting/day01.py` | 20.8 ± 3.0 | 15.6 | 29.5 | 15.44 ± 20.14 |
| `AOC_INPUT=input-mattcl lanjian/day_01` | 1.7 ± 1.1 | 0.8 | 19.9 | 1.26 ± 1.84 |
| `AOC_INPUT=input-mattcl python pting/day01.py` | 20.1 ± 3.1 | 16.6 | 35.8 | 14.90 ± 19.46 |
| `AOC_INPUT=input-pting lanjian/day_01` | 1.3 ± 1.7 | 0.7 | 21.3 | 1.00 |
| `AOC_INPUT=input-pting python pting/day01.py` | 19.9 ± 2.8 | 16.4 | 30.7 | 14.78 ± 19.28 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.8 ± 11.1 | 0.6 | 441.1 | 1.31 ± 8.43 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.4 ± 0.8 | 0.6 | 8.3 | 1.07 ± 1.51 |
| `mattcl-solver/aoc run 1 input-mattcl` | 2.0 ± 1.7 | 0.7 | 26.4 | 1.47 ± 2.28 |
| `mattcl-solver/aoc run 1 input-pting` | 1.5 ± 0.5 | 0.7 | 7.5 | 1.09 ± 1.47 |
