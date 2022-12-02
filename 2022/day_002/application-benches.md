# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_02 input-lanjian` | 1.8 ± 0.7 | 1.0 | 10.9 | 1.26 ± 0.82 |
| `lanjian/day_02 input-mattcl` | 1.8 ± 0.7 | 0.8 | 7.9 | 1.23 ± 0.81 |
| `lanjian/day_02 input-pting` | 1.8 ± 0.6 | 0.8 | 6.6 | 1.28 ± 0.82 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.7 ± 0.6 | 0.7 | 5.4 | 1.17 ± 0.75 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.7 ± 0.7 | 0.7 | 8.5 | 1.17 ± 0.79 |
| `mattcl-solver/aoc run 2 input-pting` | 1.4 ± 0.8 | 0.6 | 24.6 | 1.00 |
| `python pting/day02.py input-lanjian` | 22.3 ± 3.0 | 17.6 | 35.1 | 15.50 ± 8.67 |
| `python pting/day02.py input-mattcl` | 20.3 ± 2.8 | 17.1 | 33.2 | 14.16 ± 7.93 |
| `python pting/day02.py input-pting` | 24.4 ± 3.5 | 19.3 | 36.3 | 16.99 ± 9.54 |
