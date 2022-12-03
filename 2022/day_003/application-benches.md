# Day 3 benchmarks

[link to problem](http://adventofcode.com/2022/day/3)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_03 input-lanjian` | 2.4 ± 0.7 | 1.5 | 6.4 | 1.26 ± 0.57 |
| `lanjian/day_03 input-mattcl` | 3.1 ± 1.1 | 1.5 | 8.9 | 1.61 ± 0.78 |
| `lanjian/day_03 input-pting` | 2.4 ± 0.7 | 1.5 | 10.3 | 1.24 ± 0.56 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.9 ± 0.7 | 1.3 | 6.2 | 1.00 |
| `mattcl-solver/aoc run 3 input-mattcl` | 2.6 ± 0.9 | 1.4 | 16.5 | 1.37 ± 0.67 |
| `mattcl-solver/aoc run 3 input-pting` | 2.1 ± 1.0 | 1.4 | 21.4 | 1.11 ± 0.66 |
| `python pting/day03.py input-lanjian` | 38.8 ± 5.2 | 31.3 | 52.7 | 20.26 ± 7.44 |
| `python pting/day03.py input-mattcl` | 34.4 ± 2.6 | 30.3 | 43.0 | 18.00 ± 6.29 |
| `python pting/day03.py input-pting` | 37.1 ± 4.2 | 30.1 | 49.7 | 19.39 ± 6.98 |
