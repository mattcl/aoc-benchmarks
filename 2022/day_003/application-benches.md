# Day 3 benchmarks

[link to problem](http://adventofcode.com/2022/day/3)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 3` | 13.8 ± 3.0 | 12.0 | 25.3 | 13.24 ± 4.82 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 13.1 ± 1.3 | 11.8 | 23.4 | 12.59 ± 3.90 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.9 ± 1.6 | 11.7 | 23.4 | 12.40 ± 3.95 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 33.0 ± 12.2 | 12.6 | 67.8 | 31.71 ± 15.02 |
| `aspidites-solver/aoc -i input-pting -d 3` | 13.2 ± 1.8 | 11.9 | 23.9 | 12.70 ± 4.12 |
| `kcen/2022/03/solve input-aspidites` | 245.5 ± 24.9 | 217.7 | 312.0 | 236.03 ± 73.33 |
| `kcen/2022/03/solve input-kcen` | 255.7 ± 11.7 | 233.2 | 268.6 | 245.86 ± 73.09 |
| `kcen/2022/03/solve input-lanjian` | 224.3 ± 14.7 | 209.1 | 251.3 | 215.66 ± 64.89 |
| `kcen/2022/03/solve input-mattcl` | 236.5 ± 15.5 | 216.1 | 257.8 | 227.40 ± 68.44 |
| `kcen/2022/03/solve input-pting` | 246.9 ± 10.2 | 234.6 | 276.3 | 237.42 ± 70.42 |
| `lanjian/day_03 input-aspidites` | 1.4 ± 0.5 | 0.4 | 7.0 | 1.38 ± 0.65 |
| `lanjian/day_03 input-kcen` | 1.1 ± 0.3 | 0.7 | 3.8 | 1.07 ± 0.45 |
| `lanjian/day_03 input-lanjian` | 1.2 ± 0.5 | 0.6 | 7.1 | 1.13 ± 0.56 |
| `lanjian/day_03 input-mattcl` | 1.2 ± 0.5 | 0.6 | 7.7 | 1.17 ± 0.56 |
| `lanjian/day_03 input-pting` | 1.6 ± 0.7 | 0.6 | 8.6 | 1.50 ± 0.81 |
| `mattcl-solver/aoc run 3 input-aspidites` | 8.6 ± 15.2 | 1.2 | 105.1 | 8.23 ± 14.79 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.3 ± 0.4 | 0.8 | 8.7 | 1.24 ± 0.53 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.0 ± 0.3 | 0.6 | 5.5 | 1.00 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.2 ± 0.5 | 0.6 | 6.2 | 1.16 ± 0.55 |
| `mattcl-solver/aoc run 3 input-pting` | 1.5 ± 0.4 | 0.8 | 4.3 | 1.44 ± 0.56 |
| `python pting/day03.py input-aspidites` | 34.6 ± 4.6 | 28.2 | 49.7 | 33.26 ± 10.72 |
| `python pting/day03.py input-kcen` | 36.6 ± 5.0 | 30.0 | 47.8 | 35.23 ± 11.42 |
| `python pting/day03.py input-lanjian` | 35.7 ± 5.4 | 28.3 | 55.6 | 34.36 ± 11.35 |
| `python pting/day03.py input-mattcl` | 32.1 ± 2.8 | 27.0 | 43.1 | 30.83 ± 9.44 |
| `python pting/day03.py input-pting` | 36.0 ± 4.2 | 30.9 | 49.8 | 34.66 ± 10.96 |
