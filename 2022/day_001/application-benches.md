# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.0 ± 0.5 | 11.3 | 14.0 | 12.30 ± 3.64 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.6 ± 0.5 | 11.7 | 14.5 | 12.89 ± 3.82 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.8 ± 0.9 | 11.6 | 17.1 | 13.13 ± 3.95 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.7 ± 1.4 | 11.5 | 23.7 | 12.97 ± 4.07 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.0 ± 0.4 | 11.4 | 14.2 | 12.28 ± 3.63 |
| `kcen/2022/01/solve input-aspidites` | 110.7 ± 10.0 | 92.7 | 142.0 | 113.42 ± 34.81 |
| `kcen/2022/01/solve input-kcen` | 105.6 ± 10.3 | 88.9 | 136.1 | 108.17 ± 33.45 |
| `kcen/2022/01/solve input-lanjian` | 105.2 ± 12.6 | 89.5 | 141.2 | 107.75 ± 34.15 |
| `kcen/2022/01/solve input-mattcl` | 107.3 ± 8.2 | 93.4 | 124.8 | 109.95 ± 33.32 |
| `kcen/2022/01/solve input-pting` | 108.5 ± 8.7 | 94.5 | 133.2 | 111.18 ± 33.80 |
| `lanjian/day_01 input-aspidites` | 1.8 ± 0.9 | 0.9 | 12.6 | 1.88 ± 1.04 |
| `lanjian/day_01 input-kcen` | 1.4 ± 0.5 | 0.8 | 5.3 | 1.40 ± 0.62 |
| `lanjian/day_01 input-lanjian` | 1.4 ± 0.7 | 0.7 | 5.2 | 1.43 ± 0.79 |
| `lanjian/day_01 input-mattcl` | 1.3 ± 0.4 | 0.7 | 6.1 | 1.29 ± 0.55 |
| `lanjian/day_01 input-pting` | 1.5 ± 0.7 | 0.8 | 14.3 | 1.58 ± 0.85 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.7 ± 1.0 | 0.7 | 9.8 | 1.75 ± 1.15 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.4 ± 0.6 | 0.6 | 12.7 | 1.42 ± 0.76 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.3 ± 0.4 | 0.7 | 4.3 | 1.34 ± 0.59 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.4 ± 0.6 | 0.6 | 6.0 | 1.46 ± 0.75 |
| `mattcl-solver/aoc run 1 input-pting` | 1.0 ± 0.3 | 0.5 | 2.9 | 1.00 |
| `python pting/day01.py input-aspidites` | 36.0 ± 4.2 | 29.8 | 47.0 | 36.93 ± 11.66 |
| `python pting/day01.py input-kcen` | 33.4 ± 4.4 | 27.5 | 52.5 | 34.21 ± 11.00 |
| `python pting/day01.py input-lanjian` | 31.8 ± 4.1 | 27.3 | 54.1 | 32.59 ± 10.45 |
| `python pting/day01.py input-mattcl` | 32.0 ± 3.2 | 27.4 | 45.2 | 32.77 ± 10.14 |
| `python pting/day01.py input-pting` | 33.9 ± 4.5 | 28.4 | 52.5 | 34.70 ± 11.19 |
