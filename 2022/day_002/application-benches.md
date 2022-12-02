# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_02 input-lanjian` | 0.4 ± 1.7 | 0.0 | 26.8 | 1.47 ± 6.96 |
| `lanjian/day_02 input-mattcl` | 0.8 ± 1.6 | 0.0 | 13.1 | 2.62 ± 9.04 |
| `lanjian/day_02 input-pting` | 0.5 ± 1.0 | 0.0 | 8.9 | 1.80 ± 5.93 |
| `mattcl-solver/aoc run 2 input-lanjian` | 0.8 ± 3.1 | 0.0 | 43.6 | 2.49 ± 12.29 |
| `mattcl-solver/aoc run 2 input-mattcl` | 0.3 ± 0.8 | 0.0 | 9.7 | 1.00 |
| `mattcl-solver/aoc run 2 input-pting` | 0.6 ± 1.3 | 0.0 | 11.0 | 1.96 ± 6.88 |
| `python pting/day02.py input-lanjian` | 33.1 ± 7.3 | 23.6 | 53.9 | 108.86 ± 305.15 |
| `python pting/day02.py input-mattcl` | 41.2 ± 8.4 | 23.3 | 69.0 | 135.39 ± 379.33 |
| `python pting/day02.py input-pting` | 42.6 ± 7.9 | 29.8 | 64.1 | 140.20 ± 392.63 |
