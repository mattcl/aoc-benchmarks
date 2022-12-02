# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_02 input-lanjian` | 2.1 ± 0.8 | 1.0 | 7.6 | 1.18 ± 0.65 |
| `lanjian/day_02 input-mattcl` | 2.4 ± 1.0 | 0.6 | 6.8 | 1.32 ± 0.78 |
| `lanjian/day_02 input-pting` | 2.5 ± 1.1 | 1.1 | 9.3 | 1.39 ± 0.83 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.8 ± 0.7 | 0.7 | 7.4 | 1.00 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.1 ± 0.9 | 0.7 | 10.6 | 1.15 ± 0.68 |
| `mattcl-solver/aoc run 2 input-pting` | 2.3 ± 0.7 | 0.7 | 5.7 | 1.28 ± 0.67 |
| `python pting/day02.py input-lanjian` | 24.6 ± 6.5 | 18.3 | 52.8 | 13.69 ± 6.70 |
| `python pting/day02.py input-mattcl` | 24.0 ± 6.5 | 18.3 | 46.1 | 13.35 ± 6.58 |
| `python pting/day02.py input-pting` | 27.0 ± 9.5 | 18.0 | 100.2 | 15.00 ± 8.12 |
