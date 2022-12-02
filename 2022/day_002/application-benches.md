# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_02 input-lanjian` | 5.1 ± 4.3 | 0.6 | 27.0 | 1.55 ± 1.71 |
| `lanjian/day_02 input-mattcl` | 3.3 ± 2.3 | 0.4 | 19.8 | 1.00 |
| `lanjian/day_02 input-pting` | 4.8 ± 2.9 | 0.8 | 25.1 | 1.45 ± 1.37 |
| `mattcl-solver/aoc run 2 input-lanjian` | 3.3 ± 4.0 | 0.0 | 38.6 | 1.02 ± 1.41 |
| `mattcl-solver/aoc run 2 input-mattcl` | 3.6 ± 2.5 | 0.3 | 14.1 | 1.11 ± 1.11 |
| `mattcl-solver/aoc run 2 input-pting` | 3.8 ± 4.2 | 0.6 | 61.5 | 1.14 ± 1.51 |
| `python pting/day02.py input-lanjian` | 43.1 ± 16.4 | 28.8 | 125.6 | 13.15 ± 10.62 |
| `python pting/day02.py input-mattcl` | 48.2 ± 20.4 | 27.7 | 124.2 | 14.69 ± 12.17 |
| `python pting/day02.py input-pting` | 41.9 ± 13.9 | 26.2 | 109.5 | 12.77 ± 10.03 |
