# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_01` | 2.9 ± 1.2 | 0.9 | 9.7 | 1.38 ± 1.04 | input-pting
| `lanjian/day_01` | 3.0 ± 1.8 | 0.6 | 18.9 | 1.41 ± 1.23 | input-lanjian
| `lanjian/day_01` | 3.3 ± 1.9 | 0.4 | 18.9 | 1.58 ± 1.36 | input-aspidites
| `lanjian/day_01` | 4.6 ± 4.4 | 0.4 | 46.1 | 2.17 ± 2.50 | input-mattcl
| `mattcl-solver/aoc run 1 input-aspidites` | 2.6 ± 1.4 | 0.0 | 12.3 | 1.21 ± 1.02 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.4 ± 1.2 | 0.3 | 11.4 | 1.12 ± 0.93 |
| `mattcl-solver/aoc run 1 input-mattcl` | 2.1 ± 1.3 | 0.2 | 12.5 | 1.00 |
| `mattcl-solver/aoc run 1 input-pting` | 2.7 ± 1.6 | 0.5 | 12.6 | 1.28 ± 1.10 |
| `python pting/day01.py` | 34.2 ± 6.0 | 25.1 | 47.1 | 16.26 ± 10.74 | input-aspidites
| `python pting/day01.py` | 35.8 ± 6.7 | 24.6 | 55.8 | 17.00 ± 11.29 | input-pting
| `python pting/day01.py` | 36.5 ± 9.1 | 18.5 | 88.6 | 17.35 ± 11.87 | input-lanjian
| `python pting/day01.py` | 36.6 ± 5.8 | 25.2 | 53.4 | 17.41 ± 11.42 | input-mattcl
