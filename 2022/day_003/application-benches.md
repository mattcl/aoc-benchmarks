# Day 3 benchmarks

[link to problem](http://adventofcode.com/2022/day/3)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.4 ± 1.5 | 11.6 | 24.0 | 12.80 ± 4.52 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 12.9 ± 2.1 | 11.6 | 25.4 | 13.31 ± 4.91 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.5 ± 2.2 | 11.3 | 25.7 | 12.87 ± 4.87 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 13.5 ± 3.5 | 11.5 | 28.6 | 13.87 ± 5.86 |
| `aspidites-solver/aoc -i input-pting -d 3` | 12.5 ± 0.5 | 11.8 | 15.3 | 12.85 ± 4.31 |
| `kcen/2022/03/solve input-aspidites` | 231.1 ± 10.3 | 217.3 | 250.6 | 238.01 ± 79.96 |
| `kcen/2022/03/solve input-kcen` | 252.9 ± 20.5 | 229.0 | 296.2 | 260.41 ± 89.23 |
| `kcen/2022/03/solve input-lanjian` | 232.8 ± 13.4 | 215.7 | 263.0 | 239.73 ± 81.00 |
| `kcen/2022/03/solve input-mattcl` | 245.8 ± 19.1 | 213.3 | 285.9 | 253.11 ± 86.54 |
| `kcen/2022/03/solve input-pting` | 250.3 ± 23.4 | 223.5 | 318.2 | 257.79 ± 89.14 |
| `lanjian/day_03 input-aspidites` | 1.3 ± 0.5 | 0.5 | 6.2 | 1.33 ± 0.66 |
| `lanjian/day_03 input-kcen` | 1.5 ± 0.5 | 0.7 | 5.3 | 1.55 ± 0.71 |
| `lanjian/day_03 input-lanjian` | 1.4 ± 0.8 | 0.5 | 10.7 | 1.48 ± 0.94 |
| `lanjian/day_03 input-mattcl` | 1.0 ± 0.3 | 0.5 | 3.4 | 1.00 |
| `lanjian/day_03 input-pting` | 1.1 ± 0.6 | 0.5 | 6.6 | 1.14 ± 0.69 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.3 ± 0.4 | 0.7 | 4.6 | 1.36 ± 0.63 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.6 ± 0.6 | 0.7 | 6.9 | 1.62 ± 0.79 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.2 ± 0.4 | 0.7 | 4.2 | 1.27 ± 0.61 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.2 ± 0.5 | 0.6 | 5.6 | 1.20 ± 0.66 |
| `mattcl-solver/aoc run 3 input-pting` | 1.4 ± 0.4 | 0.7 | 4.8 | 1.49 ± 0.67 |
| `python pting/day03.py input-aspidites` | 35.7 ± 4.5 | 29.4 | 52.1 | 36.72 ± 13.06 |
| `python pting/day03.py input-kcen` | 36.2 ± 3.1 | 30.1 | 45.3 | 37.23 ± 12.81 |
| `python pting/day03.py input-lanjian` | 35.7 ± 4.1 | 30.2 | 48.9 | 36.78 ± 12.96 |
| `python pting/day03.py input-mattcl` | 32.2 ± 3.5 | 28.9 | 48.5 | 33.13 ± 11.60 |
| `python pting/day03.py input-pting` | 34.6 ± 3.1 | 30.4 | 46.2 | 35.64 ± 12.30 |
